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
}
</style>
