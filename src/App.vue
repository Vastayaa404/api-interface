<script setup>
import Layout from './components/layout.vue'
</script>

<template>
  <div class="wrapper">
    <span class="ico">&#x2764;</span>
    <div class="el1">routes</div>
    <div class="el2">systemstatus</div>
    <div class="el3"><Layout /></div>
    <div class="el4">{{`interface\nsettings\nbuttons\ncontrol panel`}}</div>
    <div class="el5">something</div>
    <div class="el6">{{`backend\ncomponents, \nversions`}}</div>
  </div>
</template>

<style>
body {
  margin: 0;
  overflow-x: hidden;
  user-select: none;
}

*,
*:before,
*:after {
  box-sizing: border-box;
}

.wrapper {
  width: 100vw;
  height: 100vh;
}

.ico {
  position: absolute;
  font-size: 2vh;
  top: .5%;
  left: .5%;
}

.el1 {
  position: absolute;
  width: 20%;
  height: 80%;
  top: 10%;
  left: 1%;

  background-color: rgb(231, 231, 231);
  border-radius: 1vw;

  filter: drop-shadow(0 2px 8px rgba(0, 0, 0, 0.1))
}

.el2 {
  position: absolute;
  width: 77%;
  height: 5%;
  top: 10%;
  left: 22%;

  background-color: rgb(231, 231, 231);
  border-radius: 1vw;

  filter: drop-shadow(0 2px 8px rgba(0, 0, 0, 0.1))
}

.el3 {
  position: absolute;
  width: 66%;
  height: 20%;
  top: 16%;
  left: 22%;

  background-color: rgb(231, 231, 231);
  border-radius: 1vw;

  filter: drop-shadow(0 2px 8px rgba(0, 0, 0, 0.1))
}

.el4 {
  position: absolute;
  width: 10%;
  height: 20%;
  top: 16%;
  left: 89%;

  background-color: rgb(231, 231, 231);
  border-radius: 1vw;

  filter: drop-shadow(0 2px 8px rgba(0, 0, 0, 0.1))
}

.el5 {
  position: absolute;
  width: 66%;
  height: 53%;
  top: 37%;
  left: 22%;

  background-color: rgb(231, 231, 231);
  border-radius: 1vw;

  filter: drop-shadow(0 2px 8px rgba(0, 0, 0, 0.1))
}

.el6 {
  position: absolute;
  width: 10%;
  height: 20%;
  top: 37%;
  left: 89%;

  background-color: rgb(231, 231, 231);
  border-radius: 1vw;

  filter: drop-shadow(0 2px 8px rgba(0, 0, 0, 0.1))
}
</style>
