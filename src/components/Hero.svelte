<div class="min-h-screen hero">
  <div class="text-center hero-content">
    <div class="max-w-md">
      <h1 class="mb-5 text-5xl font-bold">{title}</h1>
      <p class="mb-5">{desc}</p>
      <slot/>
    </div>
  </div>
</div>

<script>
export let title = ''
export let desc = ''
</script>