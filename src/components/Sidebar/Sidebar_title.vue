<template lang="pug">

	div(class="sidebar__title")
		img(src="", alt="")
		p {{ name }}

</template>

<script>

	export default {
		data () {
			return {
				name: 'Alisson Costa'
			}
		}
	}

</script>

<style lang="sass">

	.sidebar
		&__title
			background-color: #2ecc71
			width: 100%
			height: 70px
			display: flex
			justify-content: center
			> img
				height: 50px
				width: 50px
				float: left
				margin-top: 10px
				margin-right: 15px
			> p
				margin: 0
				color: white
				font-size: 13px
				text-transform: uppercase
				letter-spacing: 1px
				height: 70px
				line-height: 70px
				display: block

</style>
