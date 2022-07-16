<script></script>

<template>
  <div class="list-item-friends">
    <ul>
      
      <li class="active">
        <div class="item">
          <a href="#"><img class="q1" src="../assets/image/icon-user.png" alt="" /></a>
          <h2>Name Surname</h2>
          <button>x</button>
        </div>
      </li>
      <li>
        <div class="item">
          <a href="#"><img class="q1" src="../assets/image/icon-user.png" alt="" /></a>
          <h2>Name Surname</h2>
          <button>x</button>
        </div>
      </li>
      <li>
        <div class="item">
          <a href="#"><img class="q1" src="../assets/image/icon-user.png" alt="" /></a>
          <h2>Name Surname</h2>
          <button>x</button>
        </div>
      </li>
      <li>
        <div class="item">
          <a href="#"><img class="q1" src="../assets/image/icon-user.png" alt="" /></a>
          <h2>Name Surname</h2>
          <button>x</button>
        </div>
      </li>

      <button class="users-prev">a</button>
      <button class="users-next">></button>
    </ul>
  </div>
</template>

<style scoped>
ul {
  display: flex;
  background-color: #333;
  list-style: none;
  border-radius: 50px;
  -webkit-border-radius: 50px;
  -moz-border-radius: 50px;
  -ms-border-radius: 50px;
  -o-border-radius: 50px;
  overflow: hidden;
  max-width: 1170px;
  justify-content: center;
  position: relative;
  margin: 20px 0;
  padding: 0;
}

.active {
  background-color: #8f0000;
}

ul li {
  width: 23%;
  height: 50px;
  transform: skew(-40deg);
  -webkit-transform: skew(-40deg);
  -moz-transform: skew(-40deg);
  -ms-transform: skew(-40deg);
  -o-transform: skew(-40deg);
  border: 1px solid #fff;
  background-color: #333;
  z-index: 2;
}

ul li a {
  transform: skew(40deg);
  -webkit-transform: skew(40deg);
  -moz-transform: skew(40deg);
  -ms-transform: skew(40deg);
  -o-transform: skew(40deg);
}

.item {
  display: flex;
  position: relative;
  align-items: center;
}

.item a {
  width: 40px;
  height: 40px;
  border-radius: 50%;
  margin: 5px 0 10px 20px;
  background-color: #fff;
  -webkit-border-radius: 50%;
  -moz-border-radius: 50%;
  -ms-border-radius: 50%;
  -o-border-radius: 50%;
}

.item img {
  width: 40px;
}

.item a {
  width: 40px;
  height: 40px;
  border-radius: 50%;
  margin: 5px 20px 10px 20px;
  background-color: #fff;
  -webkit-border-radius: 50%;
  -moz-border-radius: 50%;
  -ms-border-radius: 50%;
  -o-border-radius: 50%;
}

.item h2 {
  color: #fff;
  transform: skew(40deg);
  font-size: 20px;
}

.item button {
  position: absolute;
  right: 15px;
  top: 5px;
  background: none;
  border: none;
  color: #fff;
  transform: skew(40deg);
  cursor: pointer;
}

.users-next {
  background: none;
  border: none;
  color: #fff;
  position: absolute;
  top: 0;
  right: 0;
  width: 100px;
  height: 50px;
}

.users-prev {
  background: none;
  border: none;
  color: #fff;
  position: absolute;
  top: 0;
  left: 0;
  width: 100px;
  height: 50px;
}

.users-next:hover,
.users-prev:hover {
  background-color: rgb(77, 0, 107);
}
</style>
