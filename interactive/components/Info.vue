<template>
  <div px5 py12 gap4 c-gray5 h-full of-auto>
    <svg w-25 h-25 mxa mb4 mt8 flex-none viewBox="0 0 220 220" xmlns="http://www.w3.org/2000/svg">
      <path
        d="M117.722 167.444C117.722 139.83 140.108 117.444 167.722 117.444V117.444C195.336 117.444 217.722 139.83 217.722 167.444V167.444C217.722 195.058 195.336 217.444 167.722 217.444V217.444C140.108 217.444 117.722 195.058 117.722 167.444V167.444Z"
        fill="#666" fill-opacity="60"
      />
      <path
        d="M117.722 52.5561C117.722 24.9419 140.108 2.55614 167.722 2.55614V2.55614C195.336 2.55614 217.722 24.9419 217.722 52.5561V97.5561C217.722 100.318 215.483 102.556 212.722 102.556H122.722C119.961 102.556 117.722 100.318 117.722 97.5561V52.5561Z"
        fill="#666" fill-opacity="30"
      />
      <path
        d="M102.278 167.444C102.278 195.058 79.8922 217.444 52.278 217.444V217.444C24.6637 217.444 2.27796 195.058 2.27796 167.444L2.27796 122.444C2.27796 119.682 4.51654 117.444 7.27796 117.444L97.278 117.444C100.039 117.444 102.278 119.682 102.278 122.444L102.278 167.444Z"
        fill="#666"
      />
    </svg>
    <p>
      Welcome to UnoCSS <b c-black dark:c-white>Interactive</b> docs! <sup>Beta</sup>
    </p>
    <p>
      Type anything to search for atomic utils, CSS properties, guides, or evaluate the expressions!
    </p>

    <div divider w-30 ma mb3 mt10 />
    <p>
      Or try start with the following utils:
    </p>
    <div row flex-wrap gap-2 justify-center>
      <RouterLink :to="{ query: { s: 'border' } }" badge-lg-orange>
        border
      </RouterLink>
      <RouterLink :to="{ query: { s: 'margin' } }" badge-lg-amber>
        margin
      </RouterLink>
      <RouterLink :to="{ query: { s: 'c-yellow' } }" badge-lg-yellow>
        c-yellow
      </RouterLink>
      <RouterLink :to="{ query: { s: 'colors' } }" badge-lg-lime>
        colors
      </RouterLink>
      <RouterLink :to="{ query: { s: 'guide:' } }" badge-lg-green>
        guide:
      </RouterLink>
      <RouterLink :to="{ query: { s: 'i-carbon-car' } }" badge-lg-emerald>
        i-carbon-car
      </RouterLink>
      <RouterLink :to="{ query: { s: 'random:' } }" badge-lg-teal>
        random:
      </RouterLink>
    </div>
    <div divider w-30 ma my5 />

    <div flex-auto />
    <div text-opacity-50 text-gray text-sm>
      <div row gap1 justify-center>
        Built with <a href="https://v3.nuxtjs.org/" target="_blank" text-gray text-opacity-100>Nuxt 3</a> ·
        Deploys on <a href="https://www.netlify.com/" target="_blank" text-gray text-opacity-100>Netlify</a>
      </div>
      <div>
        MIT Licensed | Copyright © 2021-PRESENT Anthony Fu and UnoCSS contributors
      </div>
    </div>
  </div>
</template>
