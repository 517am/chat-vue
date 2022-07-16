<script></script>

<template>
  <div class="wrapperSearch">
    <div class="search-user">
      <span>?</span>
    </div>
    <div class="listForChoose">
      <ul>
        <li class="show1"><img src="../assets/image/icon-user.png" alt="" /></li>
        <li class="show2"><img src="../assets/image/icon-user.png" alt="" /></li>
        <li class="show3"><img src="../assets/image/icon-user.png" alt="" /></li>
      </ul>
     
        <a href="" class="prev">-</a>
        <a href="" class="next">+</a>

    </div>
  </div>
</template>

<style>
.wrapperSearch {
  position: absolute;
  top: -150px;
  left: -150px;
  background: #f5f5f5;
  width: 315px;
  height: 315px;
  border-radius: 50%;
}

.search-user {
  width: 200px;
  height: 200px;
  background-color: black;
  position: absolute;
  top: 50px;
  right: 70px;
  border-radius: 50%;
}

.search-user span {
  position: absolute;
  right: 50px;
  top: 110px;
  font-size: 50px;
}

.listForChoose {
  width: 200px;
  position: absolute;
  right: 0;
  bottom: 0;
}

ul {
    margin: 0;
    padding: 0;
} 

.show1{
    position: absolute;
    bottom: 80px;
    left: 120px;
    transform: rotate(289deg);
}

.show2{
    position: absolute;
    bottom: 35px;
    left: 93px;
    transform: rotate(312deg);
}

.show3{
    position: absolute;
    bottom: 0px;
    left: 49px;
    transform: rotate(340deg);
}

a.prev{
    position: absolute;
    background-color: #8f0000;
    width: 25px;
    height: 25px;
    border-radius: 50%;
    text-align: center;
    line-height: 22px;
    bottom: 20px;
    left: 40px;
}

a.next{
    position: absolute;
    background-color: #8f0000;
    width: 25px;
    height: 25px;
    border-radius: 50%;
    text-align: center;
    line-height: 25px;
    bottom: 135px;
    left: 152px;
}

img {
  width: 70px;
}
</style>
