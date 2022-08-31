<template>
  <button class="a-button">
    <slot></slot>
  </button>
</template>

<style lang="postcss">
.a-button {
  @apply rounded py-2 px-6 cursor-pointer;
  @apply transition duration-300;
  @apply bg-blue border border-blue text-white;

  &:hover,
  &:focus {
    @apply bg-blue-light border-blue-light;
  }

  &:focus {
    @apply ring-blue-dark ring-2;
  }

  &:active {
    @apply bg-blue-dark;
  }

  /* You can also use tailwind variants/modifiers instead of nesting pseudo class selectors.
  Although, sometimes nesting can produce a bit more readable result.

  @apply hover:bg-blue-light hover:border-blue-light;
  @apply focus:bg-blue-light focus:border-blue-light focus:ring-blue-dark focus:ring-2;
  @apply active:bg-blue-dark; */
}
</style>
