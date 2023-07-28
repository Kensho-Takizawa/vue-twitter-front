<script lang="ts" setup>
// import { RouterView } from "vue-router";
import LeftSideBar from "./components/organisms/LeftSideBar.vue";
import RightSideBar from "@/components/organisms/RightSideBar.vue";
import TweetTimeLine from "@/components/organisms/MainSection.vue";</script>

<template>
  <div class="wrapper">
    <div class="leftNavWrapper">
      <nav>
        <LeftSideBar />
      </nav>
    </div>
    <!--    <RouterView />-->
    <TweetTimeLine />
    <div class="rightNavWrapper">
      <nav>
        <RightSideBar />
      </nav>
    </div>
  </div>

</template>

<style scoped>
header {
  line-height: 1.5;
  height: 10px;
}

.wrapper {
  display: flex;
  justify-content: space-between;
  width: 100%;
}

.leftNavWrapper nav {
  margin: 0;
  padding: 0;
}

.rightNavWrapper nav {
  margin: 0;
  padding: 0;
}

nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
  margin-top: 2rem;
}

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }

  nav {
    text-align: left;
    margin-left: -1rem;
    font-size: 1rem;

    padding: 1rem 0;
  }
}
</style>
