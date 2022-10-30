<script setup>
import Top from "./components/Top.vue";
import Category from "./components/Category.vue";
import ChannelsAndStreamers from "./components/ChannelsAndStreamers.vue";
import SocialMedia from "./components/SocialMedia.vue";
components: {
  Top, Category, ChannelsAndStreamers, SocialMedia;
}
</script>

<template>
  <Top />
  <main>
    <Category />
    <ChannelsAndStreamers />
    <SocialMedia />
  </main>
</template>
