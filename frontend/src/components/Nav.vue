<template>
  <!-- <nav class="navbar navbar-expand navbar-dark bg-dark">
    <a href="/" class="navbar-brand">AppPenilaian</a>
    <div class="navbar-nav mr-auto">
      <li class="nav-item">
        <router-link to="/home" class="nav-link">
          <font-awesome-icon icon="home" /> Home
        </router-link>
      </li>
      <li v-if="showAdmin" class="nav-item">
        <router-link to="/admin" class="nav-link">Admin</router-link>
      </li>
      <li v-if="showGuru" class="nav-item">
        <router-link to="/guru" class="nav-link">Guru</router-link>
      </li>
      <li v-if="showAdmin" class="nav-item">
        <router-link to="/gurulist" class="nav-link">Gurulist</router-link>
      </li>
      <li class="nav-item">
        <router-link v-if="currentUser" to="/walas" class="nav-link"
          >Walas</router-link
        >
      </li>
    </div>

    <div v-if="!currentUser" class="navbar-nav ml-auto">
      <li class="nav-item">
        <router-link to="/register" class="nav-link">
          <font-awesome-icon icon="user-plus" /> Sign Up
        </router-link>
      </li>
      <li class="nav-item">
        <router-link to="/login" class="nav-link">
          <font-awesome-icon icon="sign-in-alt" /> Login
        </router-link>
      </li>
    </div>

    <div v-if="currentUser" class="navbar-nav ml-auto">
      <li class="nav-item">
        <router-link to="/profile" class="nav-link">
          <font-awesome-icon icon="user" />
          {{ currentUser.username }}
        </router-link>
      </li>
      <li class="nav-item">
        <a class="nav-link" @click.prevent="logOut">
          <font-awesome-icon icon="sign-out-alt" /> LogOut
        </a>
      </li>
    </div>
  </nav> -->
  <div></div>
</template>

<script>
// import EventBus from "../common/EventBus";
// export default {
//   computed: {
//     currentUser() {
//       return this.$store.state.auth.user;
//     },
//     showAdmin() {
//       if (this.currentUser && this.currentUser["roles"]) {
//         return this.currentUser["roles"].includes("ROLE_ADMIN");
//       }
//       return false;
//     },
//     showGuru() {
//       if (this.currentUser && this.currentUser["roles"]) {
//         return this.currentUser["roles"].includes("ROLE_GURU");
//       }
//       return false;
//     },
//   },
//   methods: {
//     logOut() {
//       this.$store.dispatch("auth/logout");
//       this.$router.push("/login");
//     },
//   },
//   mounted() {
//     EventBus.on("logout", () => {
//       this.logOut();
//     });
//   },
//   beforeUnmount() {
//     EventBus.remove("logout");
//   },
// };
</script>
