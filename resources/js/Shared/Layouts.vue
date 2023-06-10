<template>
    <main>
      <header>
        <Link href="/home">Home</Link>
        <Link href="/about">About</Link>
      </header>
      <article>
        <slot />
      </article>
    </main>
  </template>
  
  <script>
  import { Link } from '@inertiajs/vue3'
  
  export default {
    components: {
      Link,
    }
  }
  </script>