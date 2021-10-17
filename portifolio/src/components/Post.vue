<template>
  <div class="cotainer">
      <img width="100%" :src="foto" alt="">
  </div>
</template>

<script>
export default {
name: "Post",
props:{
    foto: String
},
}
</script>

<style src="./Post.scss" lang="scss" scoped />