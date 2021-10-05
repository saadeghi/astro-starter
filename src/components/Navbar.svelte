<div class="navbar">
  <div class="flex-1 px-2 mx-2">
    <span class="text-lg font-bold">{title}</span>
  </div> 
  <div class="flex-none">
    <slot/>
  </div>
</div>

<script>
export let title = ''
</script>