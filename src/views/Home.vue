<template>
  <div class="home">
    <div class="left">
      <div>
        <span>1</span>
        <span>2</span>
        <span>3</span>
      </div>
    </div>
    <!-- 右边 -->
    <div class="right">
      <div>
        <span>one</span>
        <span>two</span>
        <span>three</span>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  components: {},
};
</script>
<style lang="scss">
.home {
  display: flex;
  .left {
  }
  width: 3.125rem;
  .right {
    width: 3.125rem;
    margin-left: 18.75rem;
  }
}

.wrap_flex {
  display: flex;
}
span {
  display: block;
  width: 6.25rem;
  height: 100px;
  text-align: center;
  background-color: burlywood;

  margin-top: 30px;
}
</style>