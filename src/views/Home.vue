<template>
  <div id="app">
    <div class="navbar navbar-dark bg-dark">
      <a href="#" class="navbar-brand">Doctors</a>
      <ul class="nav">
        <li class="nav-item px-3">
          <router-link class="text-white" to="/">Home</router-link>
        </li>
        <!-- <li class="nav-item px-3">
          <router-link class="text-white" to="#">mon compte</router-link>
        </li> -->
        <li class="nav-item px-3">
          <router-link class="text-white" to="/Dashbord">Dashboard</router-link>
        </li>
        <li class="nav-item px-3">
          <a href="#" @click.prevent="Logout" style="color: white">Logout</a>
        </li>
      </ul>
    </div>
  </div>
</template>
