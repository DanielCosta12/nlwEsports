<script>
export default {
  name: "Top",
  data() {
    return {
      srcImg: "https://github.com/danielcosta12.png",
      atl: "Foto de Daniel Costa",
    };
  },
};
</script>
<template>
  <header>
    <div>
      <img v-bind:src="srcImg" v-bind:alt="alt" />
    </div>
  </header>
</template>

<style scoped>
header {
  padding-top: 32px;
  height: calc(120px + 32px);
}
header div {
  width: 120px;
  margin: auto;
  background-image: linear-gradient(
    90deg,
    #9572fc 0%,
    #43e7ad 50.52%,
    #e2d45c 100%
  );
  border-radius: 50%;
  display: flex;
  padding: 4px;
  transition: transform 0.5s;
}
header img {
  width: 100%;
  border-radius: 50%;
}
header div:hover {
  transform: scale(1.1);
}
</style>
