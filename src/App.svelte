<script>
  import Button from './Button.svelte'

  export let name
</script>

<style lang="postcss">
  @import 'tailwindcss/base';
  @import 'tailwindcss/components';
  @import 'tailwindcss/utilities';

  h1 {
    @apply bg-orange-500 text-white;
  }
</style>

<main>
  <h1 class="text-2xl">Hello {name}!</h1>
  <Button />
</main>
