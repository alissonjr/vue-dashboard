<template lang="pug">

	ul.header-nav
		li
			a(href="")
				i(class="fa fa-bell-o")
		li
			a(href="")
				i(class="fa fa-user-o")
		li
			a(href="")
				i(class="fa fa-comment-o")

</template>

<script>

	export default {
		data () {
			return {
				msg: ''
			}
		}
	}
</script>

<style lang="sass">

	.header-nav
		> li
			padding: 15px
			float: left
			height: 40px
			line-height: 40px
			// margin-top: 35px
			font-size: 14pt
			a
				padding: 5px 8px
				height: inherit
				border-radius: 150px
				max-width: 30px
				max-height: 30px
				text-align: center
				color: rgba(0, 0, 0, 0.4)
				&:hover
					background-color: rgba(0, 0, 0, 0.1)

</style>
