<template>
  <div class="p-4 m-auto border-2 rounded-lg bg-slate-800 text-white">
    <h1 class="text-3xl font-bold">Hello world!</h1>
    <p class="mt-5">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam qui
      minima autem nobis animi perspiciatis deleniti quaerat, recusandae
      officiis ea totam quisquam repellat quidem perferendis ad! Vel officia
      voluptatibus ipsam.
    </p>
    <button
      class="bg-indigo-600 hover:bg-indigo-800 mt-4 font-bold py-2 px-4 rounded"
    >
      Click Me
    </button>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
