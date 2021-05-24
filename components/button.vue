<template>
  <button
    :class="[
      bg,
      'border-none',
      color,
      'text-body',
      'font-semibold',
      'py-3.5',
      'px-8',
      'rounded-md',
    ]"
  >
    {{ text }}
  </button>
</template>

<script>
export default {
  props: ["text", "bg", "color"],
};
</script>