<script>
  import "../app.postcss";
</script>

<div class="bg-neutral-300 h-screen w-screen">
  <nav class="p-4">
    <ul class="flex space-x-4">
      <li class="text-neutral-700 hover:text-neutral-900">
        <a href="/">Main</a>
      </li>
      <li class="text-neutral-700 hover:text-neutral-900">
        <a href="/two">Two</a>
      </li>
    </ul>
  </nav>

  <main class="p-4">
    <h1>
      <span class="line-through text-5xl">Portfolio</span>
      <span class="text-5xl">Playground</span>
    </h1>
    <slot />
  </main>
</div>
