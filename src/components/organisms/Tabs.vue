<script setup lang="ts">

</script>

<template>
  <div class="TabsWrapper">
    <!--    component化する-->
    <div class="tabWrapper">
      <div class="tab forYou">For You</div>
    </div>
    <div class="tabWrapper">
      <div class="tab following">Following</div>
    </div>
  </div>
</template>

<style scoped>
.TabsWrapper {
  display: flex;
  border-bottom: 1px solid #e8e8e8;
}

.tab {
  padding: 16px 1px;
}

.tabWrapper {
  width: 50%;
  text-align: center;
}

.forYou {
  text-align: center;
  font-weight: bold;
  color: #111111;
  border-bottom: 4px solid rgb(29, 155, 240);
  display: inline-block;
}

.following {
  text-align: center;
  font-weight: bold;
  color: #6c6c6c;
}
</style>
