<script setup lang="ts">
defineProps<{
  //
}>();
</script>

<template>
  <div class="leftSideBarWrapper">
    <img src="../../assets/icon.webp" alt="icon" />
    <ul>
      <li><img src="../../assets/home.png" alt="home" class="home"><span class="home">Home</span></li>
      <li><img src="../../assets/search.png" alt="search" class="search"><span>Explore</span></li>
      <li><img src="../../assets/notice.png" alt="notice" class="notice"><span>Notification</span></li>
      <li><img src="../../assets/message.png" alt="message" class="message"><span>Messages</span></li>
      <li><img src="../../assets/lists.png" alt="lists" class="lists"><span>Lists</span></li>
      <li><img src="../../assets/bookmark.png" alt="bookmark" class="bookmark"><span>Bookmarks</span></li>
      <li><img src="../../assets/profile.png" alt="profile" class="profile"><span>Profile</span></li>
      <li><img src="../../assets/more.png" alt="more" class="more"><span>More</span></li>
    </ul>
    <button class="tweetStart"><span>Tweet</span></button>
  </div>
</template>

<style scoped>
.leftSideBarWrapper {
  height: 100%;
  width: 260px;
}

.leftSideBarWrapper img {
  width: 28px;
  margin: 15px 5px 15px 12px;
}

.leftSideBarWrapper ul {
  list-style: none;
  padding: 0;
  margin-left: 10px;
}

.leftSideBarWrapper ul li {
  margin-bottom: 22px;
  display: flex;
}

.leftSideBarWrapper ul li span {
  font-weight: 425;
  font-size: 22px;
  margin-left: 10px;
  padding-top: 2px;
}

.leftSideBarWrapper ul li span.home {
  font-weight: bold;
  font-size: 22px;
  margin-left: 10px;
  padding-top: 2px;
}


.leftSideBarWrapper ul li img {
  margin: 0;
  width: 34px;
}

.leftSideBarWrapper ul li img.notice {
  width: 28px;
  height: 28px;
  margin-top: 5px;
  margin-left: 3px;
  margin-right: 4px;
}

.leftSideBarWrapper ul li img.message {
  width: 22px;
  height: 22px;
  margin-top: 9px;
  margin-left: 7px;
  margin-right: 6px;
}

.leftSideBarWrapper ul li img.lists {
  width: 20px;
  height: 20px;
  margin-top: 9px;
  margin-left: 8px;
  margin-right: 8px;
}

.leftSideBarWrapper ul li img.bookmark {
  width: 22px;
  height: 22px;
  margin-top: 9px;
  margin-left: 7px;
  margin-right: 6px;
}

.leftSideBarWrapper ul li img.profile {
  width: 22px;
  height: 22px;
  margin-top: 9px;
  margin-left: 7px;
  margin-right: 6px;
}

.leftSideBarWrapper ul li img.more {
  width: 24px;
  height: 24px;
  margin-top: 9px;
  margin-left: 6px;
  margin-right: 6px;
}

.leftSideBarWrapper button.tweetStart {
  padding: 16px 90px;
  border-style: none;
  background-color: rgb(29, 155, 240);
  border-radius: 30px;
  transition: background-color 0.3s ease;
}

.leftSideBarWrapper button.tweetStart:hover {
  background-color: rgb(33, 127, 194);
}

.leftSideBarWrapper button span {
  font-size: 18px;
  font-weight: bold;
  color: white;
}

h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

@media (min-width: 1024px) {
}
</style>
