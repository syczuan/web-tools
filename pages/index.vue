<template>
  <div class="home">
    <div class="content">
      <nuxt-link :to="{ name: 'video-frames' }">视频帧提取</nuxt-link>
      <nuxt-link :to="{ name: 'video-transcode' }">视频转码</nuxt-link>
      <nuxt-child />
    </div>
  </div>
</template>

<script>
export default {
  name: "index",
  data() {
    return {};
  },
  methods: {},
  beforeDestroy() {},
  computed: {},
};
</script>
<style lang="scss" scoped>
.home {
  width: 100%;
  .content {
    margin: 100px auto;
    width: 100%;
    min-height: 500px;
    border-radius: 8px;
    box-shadow: 0px 2px 4px 1px rgba(128, 128, 128, 0.2);
    box-sizing: border-box;
    padding: 20px;
    background: #ffffff;
  }
}
</style>
