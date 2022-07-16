<script setup>
import HeaderApp from "./components/Header-App.vue";
import DialogueList from "./components/Dialogue-List.vue";
import PlaceForMessage from "./components/Place-For-Message.vue";
import SearchUser from "./components/Search-User.vue";
import Registration from "./views/Registration.vue";
</script>

<template>
  <div class="wrapper">
    <SearchUser></SearchUser>
    <div class="container">
      <HeaderApp></HeaderApp>
      <DialogueList></DialogueList>
      <PlaceForMessage></PlaceForMessage>
    </div>
  </div>
</template>

<style>
h1,
h2,
h3,
h4,
h5,
h6,
a,
p,
span,
li {
  color: #fff;
  text-decoration: none;
}

.ul,
li {
  list-style: none;
  margin: 0;
  padding: 0;
}

body {
  margin: 0;
  padding: 0;
  background: #000000;
}

.wrapper {
  width: 100%;
}

.container {
  width: 1170px;
  margin: 0 auto;
}
</style>
