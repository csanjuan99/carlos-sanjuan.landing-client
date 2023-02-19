<template>
  <div class="h-screen w-screen bg-[#0E9577] relative overflow-hidden z-0">
    <div
      class="app-texture z-5 opacity-20 w-full h-full absolute top-0 left-0 cover"
    />
    <div class="absolute blur-[250px] bg-opacity-80 app-1" />
    <div class="absolute blur-[250px] bg-opacity-80 app-3" />
    <div class="absolute blur-[250px] bg-opacity-80 app-4" />
    <div class="absolute blur-[250px] bg-opacity-80 app-5" />
  </div>
</template>

<script>
export default {
  name: "AppBackgroundComponent",
};
</script>

<style scoped lang="scss">
@keyframes fly {
  100% {
    transform: rotate(1turn) translate(100px) rotate(-1turn);
  }
}

@keyframes flyPlus {
  100% {
    transform: rotate(1turn) translate(150px) rotate(-1turn);
  }
}

.app-1 {
  border-radius: 100%;
  width: 900px;
  height: 400px;
  background-color: rgba(4, 222, 173, 0.80);
  left: -10px;
  top: -300px;
  z-index: 3;
  animation: fly 12s linear infinite;
  transform: rotate(0) translate(150px) rotate(0);
}


.app-3 {
  border-radius: 100%;
  width: 450px;
  height: 450px;
  bottom: -80px;
  right: -100px;
  background-color: rgba(4, 222, 173, 0.7);
  animation: flyPlus 8s linear infinite;
  transform: rotate(0) translate(100px) rotate(0);
}

.app-4 {
  background-color: rgba(14, 149, 119, 1);
  top: -30px;
  right: -80px;
  width: 900px;
  height: 800px;
  animation: flyPlus 2s linear infinite;
  transform: rotate(0) translate(100px) rotate(0);
}

.app-5 {
  border-radius: 100%;
  top: 0;
  right: 400px;
  width: 900px;
  height: 1000px;
  background-color: rgba(241, 239, 185, 0.85);
  transform: rotate(0) translate(250px) rotate(0);
  animation: flyPlus 7s linear infinite;
}

.app-texture {
  background-image: url("@/assets/images/bg-texture.png");
}
</style>
