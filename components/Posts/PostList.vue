<template>
  <section class="post-list">
    <PostPreview
      id="1"
      title="My First Post"
      previewText="Here is some preview text about my first blog post!!!"
      thumbnail="https://res-3.cloudinary.com/fieldfisher/image/upload/c_lfill,g_auto/f_auto,q_auto/v1/sectors/technology/tech_neoncircuitboard_857021704_medium_lc5h05"
    />
    <PostPreview
      id="2"
      title="Coding is fun"
      previewText="Lorem ipsum dolor sit amet, consectetur adipiscing elit"
      thumbnail="https://images.unsplash.com/photo-1488590528505-98d2b5aba04b?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mnx8dGVjaG5vbG9neXxlbnwwfHwwfHw%3D&w=1000&q=80"
    />
  </section>
</template>

<script>
import PostPreview from './PostPreview.vue';

export default {
  components: {
    PostPreview
  }
}
</script>

<style scoped>
.post-list {
  display: flex;
  padding: 20px;
  box-sizing: border-box;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}
</style>
