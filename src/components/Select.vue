<template>
  <div>
    <span>{{ name }}</span>
    <v-select :label="name" :items="items" />
  </div>
</template>

<script>

export default {
  name: 'Select',
  props: {
    name: String,
    items: Array,
  },
};
</script>
