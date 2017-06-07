<template lang="pug">

	nav(class="sidebar")
		sidebar-title
		sidebar-navegation

</template>

<script>

	import Navegation from './Sidebar_navegation.vue'
	import Title from './Sidebar_title.vue'

	export default {
		data () {
			return {
				msg: ''
			}
		},
		components: {
			"sidebar-navegation": Navegation,
			"sidebar-title": Title
		}
	}

</script>

<style lang="sass">

	.sidebar
		width: 250px
		position: absolute
		top: 0
		bottom: 0
		left: 0
		background-color: #34495e

</style>
