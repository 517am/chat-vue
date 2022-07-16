<template>
  <div class="registration">
    <h1 class="logo">Chat</h1>

  <form action="">
    <input type="text" placeholder="Имя" />
    <input type="text" placeholder="Фамилия" />
    <input type="text" placeholder="E-mail" />
    <input type="password" placeholder="Пароль" />

    <button>Зарегистрироваться</button>
  </form>

  <a class="toBack">Назад</a>
  </div>
</template>

<style scoped>
form {
  padding: 20px;
}

.registration{
    display: flex;
    flex-direction: column;
    align-items: center;
}

input {
  display: block;
  width: 500px;
  height: 40px;
  margin: 30px 0;
  text-indent: 10px;
}

button {
  background-color: #a90000;
  color: #fff;
  width: 200px;
  height: 30px;
  border: 0;
  transition: 0.4s;
  cursor: pointer;
}

button:hover {
  background-color: #6d0404;
}

.toBack {
  background-color: #a90000;
  width: 60px;
  height: 60px;
  border-radius: 50%;
  text-align: center;
  line-height: 60px;
  transition: 0.4s;
  cursor: pointer;

  position: absolute;
  top: 10px;
  left: 10px;
}

.toBack:hover {
  background-color: #6d0404;
}
</style>
