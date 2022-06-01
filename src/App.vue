<template>
  <index></index>

  
  <!-- <Card>
    <template #header>
      <h1>A paragraph for the main content</h1>
    </template>
    <template #default>
    <p>Here's some contact info</p>
    <p>And another one.</p>
  </template>
    <template #footer>
    <p>Here's some contact info</p>
  </template>
  </Card>

<BaseInput
  v-model="event"
  label="Title"
  type="text"
/>-->

</template>

<script>
import '@/assets/tailwind.css';
import Card from '@/components/Card.vue'
import BaseInput from '@/components/BaseInput.vue'
import index from '@/views/index.vue'

export default {
  name: 'App',
  components: {
    Card,
    BaseInput,
    index
  }
}

</script>

<style></style>
