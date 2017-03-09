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
