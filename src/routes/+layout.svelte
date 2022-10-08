<script>
  import '../app.css';
  import { page } from '$app/stores';

  const routes = [
    { href: '/', text: 'Home' },
    { href: '/tables', text: 'Charts & Tables' }
  ];

  $: activePage = $page.url.pathname;
</script>

<header class="mb-4">
  <div class="w-full mb-4">
    <h1 class="font-bold text-2xl w-full text-center"><a href="/">Mordheim Helper</a></h1>
  </div>
  <!-- <nav> -->
  <!-- <ul class="flex items-center justify-center gap-2"> -->
  <!-- {#each routes as route} -->
  <!-- <li> -->
  <!-- <a -->
  <!-- href={route.href} -->
  <!-- class={`${ -->
  <!-- activePage === route.href && 'border-2 border-gray-800' -->
  <!-- } bg-gray-300 rounded py-2 px-4`}>{route.text}</a -->
  <!-- > -->
  <!-- </li> -->
  <!-- {/each} -->
  <!-- </ul> -->
  <!-- </nav> -->
</header>

<slot />

<!-- <footer class="text-center my-10 min-w-full"> -->
<!-- &copy; 2022 &mdash; Mike Bowman &mdash; <a href="https://mikebowman.dev">mikebowman.dev</a> -->
<!-- </footer> -->
