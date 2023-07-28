<script setup lang="ts">

const data = [
  {
    'userId': 1,
    'tweetText': '1つめのツイートです。1つめのツイートです。1つめのツイートです。1つめのツイートです。1つめのツイートです。1つめのツイートです。1つめのツイートです。1つめのツイートです。1つめのツイートです。1つめのツイートです。'
  },
  {
    'userId': 2,
    'tweetText': '2つめのツイートです。2つめのツイートです。2つめのツイートです。2つめのツイートです。2つめのツイートです。2つめのツイートです。2つめのツイートです。2つめのツイートです。2つめのツイートです。2つめのツイートです。'
  }
]

</script>

<template>
  <ul class="timeLine">
    <li
      v-for="item in data"
      v-bind:key="data + item.userId"
      class="tweet"
    >
      {{item.tweetText}}
    </li>
  </ul>

</template>

<style scoped>
.timeLine {
  width: 100%;
  padding: 0;
}
.tweet {
  list-style: none;
  font-size: 14px;
  color: #181818;
  border-bottom: 1px solid #e8e8e8;
  padding: 10px;
}

</style>
