<script>

</script>

<template>
  <div class="placeForMessage">
    <div class="messageFrom">
      <div class="avatar">
        <img src="../assets/image/icon-user.png" alt="" />
      </div>
      <div class="date">
        <h2>11.06.2021</h2>
        <h2>18:47</h2>
      </div>
      <div class="message">
        <p>hello there! i wrote first message!</p>
      </div>
    </div>

    <div class="messageTo">
      <div class="avatar">
        <img src="../assets/image/icon-user.png" alt="" />
      </div>
      <div class="date">
        <h2>11.06.2021</h2>
        <h2>18:47</h2>
      </div>
      <div class="message">
        <p>hello there! i wrote first message!</p>
      </div>
    </div>

    <div class="formForSendMessage">
      <form action="">
        <input
          type="text"
          placeholder="Напишите ваше сообщение"
          name=""
          id="message"
        />
        <input type="button" id="send" value="Отправить" />
      </form>
    </div>

    <footer>
      <div class="infoDev">
        <p>qwe 2022</p>
      </div>
    </footer>
  </div>
</template>

<style>

.placeForMessage{
    width: 100%;
    background-color: #212121;
}

.messageFrom {
  display: flex;
  flex-wrap: wrap;
  justify-content: left;
  margin: 20px;
}

.messageFrom .avatar {
  width: 100px;
}

.message {
  flex: 1 100%;
}

.messageTo {
  display: flex;
  flex-wrap: wrap;
  justify-content: right;
  margin: 20px;
}

.messageTo .message {
  text-align: right;
}

.formForSendMessage {
  margin: 20px;
  width: 100%;
  padding-bottom: 20px;
}

.formForSendMessage form {
  width: 100%;
  max-width: 1130px;
  display: flex;
}

.formForSendMessage #message {
  width: 80%;
  height: 40px;
  line-height: 40px;
  padding: 0;
  margin: 0;
  border: 0;
  outline: none;
  text-indent: 20px;
}

.formForSendMessage #send {
  width: 20%;
  height: 40px;
  line-height: 40px;
  padding: 0;
  margin: 0;
  border: 0;
  background-color: #8f0000;
  color: #fff;
}

footer {
  text-align: center;
  border-top: 1px solid #fff;
  background-color: #000000;
}

footer .infoDev {
  padding: 20px;
}
</style>