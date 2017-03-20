<template lang="html">
  <div class="">
    <nav class="nav">
      <div class="nav-left">
        <div class="nav-item">
          <h1>Puppies</h1>
        </div>
      </div>
      <div class="nav-center">
        <a class="nav-item">
          <router-link :to="{ name: 'index' }">All Puppies</router-link>
        </a>
        <a class="nav-item">
          <router-link :to="{ name: 'new' }">Add Puppy</router-link>
        </a>
      </div>
    </nav>
    <div class="section">
      <div class="container">
        <div class="columns">
          <div class="panel is-brand column">
            <div class="panel-heading">
              <h2>Adopt a Pupper</h2>
            </div>
            <div class="panel-block ">
              <div class="level-item">
                <img src="http://placecorgi.com/200/200" alt="" class="pup-pic image is-64x64">
              </div>
              <div class="sidebar-text">
                <div>
                  <h2>Pup Name</h2>
                  <router-link :to="{ name: 'detail' }">read more</router-link>
                </div>
              </div>
            </div>
            <div class="panel-block ">
              <div class="level-item">
                <img src="http://placecorgi.com/200/200" alt="" class="pup-pic image is-64x64">
              </div>
              <div class="sidebar-text">
                <div>
                  <h2>Pup Name</h2>
                  <router-link :to="{ name: 'detail' }">read more</router-link>
                </div>
              </div>
            </div>
            <div class="panel-block ">
              <div class="level-item">
                <img src="http://placecorgi.com/200/200" alt="" class="pup-pic image is-64x64">
              </div>
              <div class="sidebar-text">
                <div>
                  <h2>Pup Name</h2>
                  <router-link :to="{ name: 'detail' }">read more</router-link>
                </div>
              </div>
            </div>
            <div class="panel-block ">
              <div class="level-item">
                <img src="http://placecorgi.com/200/200" alt="" class="pup-pic image is-64x64">
              </div>
              <div class="sidebar-text">
                <div>
                  <h2>Pup Name</h2>
                  <router-link :to="{ name: 'detail' }">read more</router-link>
                </div>
              </div>
            </div>
            <div class="panel-block ">
              <div class="level-item">
                <img src="http://placecorgi.com/200/200" alt="" class="pup-pic image is-64x64">
              </div>
              <div class="sidebar-text">
                <div>
                  <h2>Pup Name</h2>
                  <router-link :to="{ name: 'detail' }">read more</router-link>
                </div>
              </div>
            </div>
            <div class="panel-block ">
              <div class="level-item">
                <img src="http://placecorgi.com/200/200" alt="" class="pup-pic image is-64x64">
              </div>
              <div class="sidebar-text">
                <div>
                  <h2>Pup Name</h2>
                  <router-link :to="{ name: 'detail' }">read more</router-link>
                </div>
              </div>
            </div>
          </div>
          <div class="column is-two-thirds"></div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  },

  methods: {

  },
};
</script>
