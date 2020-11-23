<template>
  <div id="app">
    <DeviceLists></DeviceLists>
    <DeviceDetail></DeviceDetail>
  </div>
</template>

<script>
import DeviceLists from "./pages/DeviceLists";
import DeviceDetail from "./pages/DeviceDetail";

export default {
  name: "App",
  components: {
    DeviceLists,
    DeviceDetail,
  },
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
