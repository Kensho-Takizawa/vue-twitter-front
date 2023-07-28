<script setup lang="ts">
</script>

<template>
  <div class="timelineWrapper">
    <div class="tweetLeftSection">
      <div class="iconSection"></div>
    </div>
    <div class="tweetRightSection">
      <textarea class="tweetText" rows="1" placeholder="What is happening?!"></textarea>
      <div class="attacheIcons"></div>
    </div>
  </div>
</template>

<style scoped>
.timelineWrapper {
  width: 100%;
  height: 110px;
  display: flex;
  padding: 0 16px;
  border-bottom: 1px solid #e8e8e8;
}

.tweetLeftSection {
  width: 7%;
  margin-right: 12px;
}

.tweetLeftSection .iconSection {
  height: 40px;
  width: 40px;
  border-radius: 50%;
  margin-top: 12px;
  background-color: black;
}

.tweetRightSection {
  margin-top: 6px;
  width: 90%;
  max-height: 200px;
}

.tweetRightSection .tweetText {
  font-size: 20px;
  padding: 12px 0;
  width: 100%;
  resize: none;
  overflow: hidden;
  max-height: 100px;
  border-style: none;
}

textarea:focus {
  outline: none;
}

.tweetRightSection .attacheIcons {
  height: 40%;
  font-size: 22px;
  background-color: #ffb3b3;
}
</style>
