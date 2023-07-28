<script setup lang="ts">
import Tabs from "./Tabs.vue";
import TweetSpace from "@/components/organisms/TweetSpace.vue";
import TimeLine from "@/components/organisms/TimeLine.vue";
</script>

<template>
  <div class="tweetTimelineWrapper">
    <h2>Home</h2>
    <Tabs />
    <TweetSpace />
    <TimeLine />
  </div>
</template>

<style scoped>
.tweetTimelineWrapper {
  width: 600px;
  height: 1280px;
  border: 1px solid #e8e8e8;
}

.tweetTimelineWrapper h2 {
  margin: 6px 20px;
  font-weight: bold;
  font-size: 22px;
  color: #222222;
  padding-top: 6px;
  height: 41px;
  vertical-align: middle;
}
</style>
