<template lang="pug">

	div(class="header")
		header-nav
		header-search

</template>

<script>

	import HeaderNav from './Header-navegation.vue'
	import HeaderSearch from './Header-search.vue'

	export default {
		data () {
			return {
				msg: ''
			}
		},
		components: {
			"header-nav": HeaderNav,
			"header-search": HeaderSearch
		}
	}
</script>

<style lang="sass">

	.header
		position: absolute
		left: 250px
		top: 0
		right: 0
		height: 70px
		border-bottom: 1px solid #e5e5e5
		background-color: white

</style>
