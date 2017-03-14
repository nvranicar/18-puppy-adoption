<template lang="html">
  <div class="">
    <nav class="nav">
      <div class="nav-left">
        <div class="nav-item">
          <h2>Puppies</h2>
        </div>
      </div>
      <div class="nav-right">
        <div class="nav-item">
          <router-link :to="{ name: 'index' }">All Puppies</router-link>
        </div>
      </div>
    </nav>
    <div class="section">
      <div class="container">
        <div class="sidebar box">
          <div class="sidebar__heading">
            <h2>Adopt a Pupper</h2>
          </div>
            <div class="level">
              <div class="level-left">
                <div class="level-item">
                  <img src="http://placecorgi.com/300/200" alt="" class="pup-pic">
                </div>
                <div class="level-item">
                  <h2>Pup Name</h2>
                  <router-link>read more</router-link>
                </div>
              </div>
            </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
    };
  },

  methods: {

  },
};
</script>
