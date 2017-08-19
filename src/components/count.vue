<template>
	<div class="count">
		{{ count }}
	</div>
</template>
<script>
export default {
  name: 'count',
  computed: {
    count () {
      return this.$store.state.count
    }
  }
  // data () {
  //   return {
  //     msg: 'Welcome to Your Vue.js App'
  //   }
  // }
}
</script>