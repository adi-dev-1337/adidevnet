<script>
  import "../app.scss"
  import '../prism.css'
  import 'focus-visible'
  import MoonIcon from 'heroicons-svelte/solid/MoonIcon.svelte'
  import SunIcon from 'heroicons-svelte/solid/SunIcon.svelte'
  import { browser } from '$app/env'

  let prefersLight = browser ? Boolean(JSON.parse(localStorage.getItem('prefersLight'))) : false
</script>

<div class="flex flex-col min-h-screen">
  <div class="mx-auto flex flex-col flex-grow w-full max-w-4xl">
    <div class="flex h-16 px-4 py-2 justify-between items-center">
      <h2 class="!text-transparent bg-clip-text bg-gradient-to-r from-blue-500 to-teal-500 dark:from-violet-500 dark:to-pink-500">
      
      </h2>
      {#if browser}
        <!-- <button type="button" role="switch" aria-label="Toggle Dark Mode" aria-checked="{!prefersLight}" class="h-4 w-4 sm:h-8 sm:w-8 sm:p-1" on:click="{()}" => {
            prefersLight = !prefersLight
            localStorage.setItem(&apos;prefersLight&apos;, prefersLight.toString())

            if (prefersLight) {
              document.querySelector(&apos;html&apos;).classList.remove(&apos;dark&apos;)
            } else {
              document.querySelector(&apos;html&apos;).classList.add(&apos;dark&apos;)
            }
          }}
        &gt;
          {#if prefersLight}
            <moonicon class="text-slate-500"></moonicon>
          {:else}
            <sunicon class="text-slate-400"></sunicon>
          {/if}
        </button> -->
      {/if}
    </div>
    <main class="prose prose-slate prose-sm sm:prose sm:prose-slate sm:prose-lg sm:max-w-none dark:prose-invert flex flex-col w-full flex-grow py-4 px-4 yt">
      <slot></slot>
    </main>
  </div>
</div>