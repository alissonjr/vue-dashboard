<template lang="pug">

	div.search-form
		input(type="text", placeholder="Digite para Pesquisar", class="search-input")
		button(type="submit")
			i(class="fa fa-search")

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

	.search
		&-form
			float: right
			margin-right: 30px
			height: 70px
			line-height: 70px
		&-input
			border: none
	button
		background: transparent
		border: none

</style>
