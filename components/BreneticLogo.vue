<template>
  <div class="BreneticLogo">
    <div class="CircleSmall topleft"></div>
    <div class="CircleSmall topright"></div>
    <div class="CircleLarge bottomleft"></div>
    <div class="CircleLarge bottomright"></div>
  </div>
</template>

<style>
.BreneticLogo {
  display: inline-block;
  position: relative;
  overflow: hidden;
  height: 185px;
  width: 248px;
}

.CircleSmall {
  height: 60px;
  width: 60px;
  background-color: #000;
  margin-bottom: 5px;
}
.CircleLarge {
  height: 120px;
  width: 120px;
  background-color: #000;
}

.topleft {
  float: left;
  margin-left: 60px;
  background-color: #000;
  border-radius: 50%;
  -moz-border-radius: 50%;
  -webkit-border-radius: 50%;
}

.topright {
  margin-left: 128px;
  background-color: #000;
  border-radius: 50%;
  -moz-border-radius: 50%;
  -webkit-border-radius: 50%;
}

.bottomleft {
  float: left;
  background-color: #000;
  border-radius: 50%;
  -moz-border-radius: 50%;
  -webkit-border-radius: 50%;
}

.bottomright {
  margin-left: 128px;
  background-color: #000;
  border-radius: 50%;
  -moz-border-radius: 50%;
  -webkit-border-radius: 50%;
}
</style>

