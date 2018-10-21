<template>
  <section class="posts-list">
    <PostPreview
      id="1"
      title="Hello there"
      previewText="sample blog 1"
      thumbnail="https://static.pexels.com/photos/270348/pexels-photo-270348.jpeg"
    />
  </section>
</template>
<script>
import PostPreview from '@/components/Posts/PostPreview'

export default {
  components: {
    PostPreview
  }
}

</script>
<style>
  .posts-list {
    display: flex;
    padding: 20px;
    box-sizing: border-box;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center;
  }
</style>
