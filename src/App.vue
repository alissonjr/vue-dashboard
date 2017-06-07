<template lang="pug">

	div
		// navegation
		sidebar-nav
		// header
		header-nav

</template>

<script>

	import Sidebar from './components/Sidebar/Sidebar.vue';
	import Header from './components/Header/Header.vue';

	export default {
		name: 'app',
		data () {
			return {
				msg: ''
			}
		},
		components: {
			"sidebar-nav": Sidebar,
			"header-nav": Header
		}
	}
</script>

<style lang="sass">

</style>
