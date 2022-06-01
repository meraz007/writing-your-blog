<template>
  <Nav />
  <div class="flex justify-center mt-36">
      <div class="w-7/12">
        <h1 class="text-5xl font-bold">A better, 10x faster way to write</h1>
        <h2 class="text-center">Rytr is an AI writing assistant that helps you create high-quality content, in just a few seconds, at a fraction of the cost!</h2>
        <ButtonSimple class="bg-orange-600 place-self-center">Create You Text</ButtonSimple>
      </div>
  </div>
</template>

<script>
import Nav from '@/components/Nav.vue'
import ButtonSimple from '@/components/ButtonSimple.vue'
export default {
    components:{
        Nav,
        ButtonSimple
    }
}
</script>

<style>

</style>