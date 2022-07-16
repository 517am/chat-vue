<script>
export default {
  data() {
    return {
      isList: false,
    };
  },
  methods: {},
};
</script>

<template>
  <header>
    <span></span>
    <div class="logo"><a href="">CHAT</a></div>
    <div class="profile">
      <a @click.prevent="isList = !isList" href=""
        ><img src="../assets/image/icon-user.png" alt=""
      /></a>

      <transition name="slide-fade"> <ul v-if="isList" :class="{ list: isList }">
        <li>Профиль</li>
        <li>Друзья</li>
        <li>Настройки</li>
      </ul></transition>
     
    </div>
  </header>
</template>

<style scoped>
header {
  text-align: center;
  line-height: 120px;
  height: 120px;
  background-color: #000000;
  position: relative;
}

.logo{
  font-size: 50px;
}

.profile {
  display: flex;
  position: absolute;
  right: 0;
  top: 20px;
}

.profile ul {
  display: none;
}

.profile .list {
  display: flex;
}

.profile ul li {
  margin: 0 10px;
  line-height: 80px;
}

.slide-fade-enter-active {
  transition: all 0.4s ease-out;
}

.slide-fade-leave-active {
  transition: all 0.2s cubic-bezier(1, 0.5, 0.8, 1);
}

.slide-fade-enter-from,
.slide-fade-leave-to {
  transform: translateX(20px);
  opacity: 0;
}
</style>
