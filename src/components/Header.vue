<template>
  <div>
    <ul>
      <router-link to="/" tag="li" active-class="current" exact>
        <a>Home</a>
      </router-link>
      <router-link to="/user" tag="li" active-class="current">
        <a>User</a>
      </router-link>
    </ul>
  </div>
</template>

<script>
export default {

};
</script>

<style scoped>
a {
    color: #ffffff;
    text-decoration: none;
}
ul {
    text-align: center;
}

li {
  display: inline-block;
  padding: 10px;
  background: rgb(53, 73, 94);
  color: white;
  cursor: pointer;
  transition: 0.2s;
}
li:hover {
  transform: scale(1.2);
  box-shadow: 1px 1px 3px rgba(0, 0, 0, 0.5);
  transition: all 0s, background 0.2s;
  z-index: 10;
}
.current {
  background: rgb(56, 184, 131);
}
div {
  padding: 10px;
  background: white;
}
</style>