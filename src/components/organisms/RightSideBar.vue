<script setup lang="ts">
</script>

<template>
  <div class="main-container">
    <div class="rightSideBarWrapper">
      <div class="search-container">
        <div class="icon-container">
          <img src="../../assets/search.png" alt="Search Icon" class="search-icon" />
        </div>
        <div class="input-container">
          <input class="search-input" type="text" placeholder="Search Twitter" />
        </div>
      </div>
    </div>
    <aside class="whatsHappning">
      <div class="header-text">What's happening</div>
      <div class="content">super beaber</div>
    </aside>
  </div>
</template>

<style scoped>
.main-container {
  /* Add styles as per requirement */
}

.rightSideBarWrapper {
  /* Add styles as per requirement */
}

.search-container {
  display: flex;
  align-items: center;
  width: 350px;
  height: 45px;
  border-radius: 30px;
  background-color: rgb(239, 243, 244);
  margin-top: 4px;
}

.icon-container {
  padding: 5px;
}

.search-icon {
  width: 28px;
  height: 28px;
  margin-top: 6px;
  margin-left: 8px;
}

.input-container {
  flex-grow: 1;
  padding-left: 6px;
}

.search-input {
  width: 100%;
  border: none;
  outline: none;
  background-color: transparent;
  font-size: 15px;
}

.whatsHappning {
  background-color: rgb(239, 243, 244);
  margin: 18px 0;
  border-radius: 15px;
  padding: 12px 16px;
}

.header-text {
  font-weight: bold;
  color: black;
  font-size: 22px;
}

.content {
  margin-top: 10px;
  color: black;
  font-size: 18px;
  font-weight: bold;
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
  /* Add media queries as per requirement */
}
</style>
