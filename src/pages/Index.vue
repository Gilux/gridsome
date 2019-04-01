<template>
  <Layout>
    <div class="band">
      <div class="item-1">
        <a href="https://design.tutsplus.com/articles/international-artist-feature-malaysia--cms-26852" class="card">
          <div class="thumb" style="background-image: url(https://s3-us-west-2.amazonaws.com/s.cdpn.io/210284/flex-1.jpg);"></div>
          <article>
            <h1>International Artist Feature: Malaysia</h1>
            <span>Mary Winkler</span>
          </article>
        </a>
      </div>
    </div>
  </Layout>
</template>

<script>
import Layout from '~/layouts/Default.vue'
export default {
  metaInfo: {
    title: 'Hello, world!'
  },
  components: {
    Layout
  }
}
</script>

<style>
.home-links a {
  margin-right: 1rem;
}
</style>
