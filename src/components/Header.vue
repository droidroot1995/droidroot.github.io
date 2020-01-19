<template>
  <div class="header">
    <div class="nav">
      <router-link class="link" to="/">
        <span class="link_name">Home</span>
      </router-link>
      <router-link class="link" to="/about">
        <span class="link_name">About</span>
      </router-link>
      <router-link class="link" to="/contacts">
        <span class="link_name">Contacts</span>
      </router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header"
};
</script>

<style scoped>
.header {
  width: 100%;
  height: 50px;
  background: #fff;
}

.nav {
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}

.link {
  flex: 1 1 10%;
  background: #098609;
  margin: 5px;
  border-radius: 5px;
  text-decoration: none;
  line-height: 40px;
}

.link_name {
  color: #fff;
  font-weight: 600;
}

.link.router-link-exact-active {
  background: #0ba00b;
}
</style>
