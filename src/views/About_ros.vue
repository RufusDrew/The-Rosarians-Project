<template>
  <div class="man">
    <div class="container">
      <h2>About Us</h2>
      <img :src="blogCoverPhoto" alt="" />
      <!-- <div class="post-content ql-editor" v-html="blogHTML"></div> -->
    </div>
  </div>
</template>

<style lang="scss">
.man {
  min-height: 100%;
  .container {
    max-width: 1000px;
    padding: 60px 25px;
  }
  .ql-editor {
    padding: 0;
  }
  h2 {
    margin-bottom: 16px;
    font-weight: 300;
    font-size: 82px;
    text-align: center;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  }
  img {
    width: 100%;
    margin-bottom: 32px;
  }
}
</style>

