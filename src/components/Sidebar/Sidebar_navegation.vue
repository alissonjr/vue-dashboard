<template lang="pug">

	-
		const menu_items = [
			{
				name: "Item 1",
				link: "#route_link1",
				icon: "file-o"
			},
			{
				name: "Item 2",
				link: "#route_link2",
				icon: "file-o"
			},
			{
				name: "Item 3",
				link: "#route_link3",
				icon: "file-o"
			}
		];


	ul(class="navegation")
		each item in menu_items
			a(href=item.link)
				li(class="navegation__item")
					i(class=`fa fa-${item.icon} icon`)
					=item.name

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

	.navegation
		list-style: none
		padding: 0
		&__item
			color: #95a5a6
			font-weight: 700
			font-size: 0.8em
			padding: 15px 0 15px 25px
			height: 25px
			line-height: 25px
			letter-spacing: 1px
			text-transform: uppercase
			.icon
				height: 25px
				width: 25px
				margin-right: 5px
			&:hover
				background-color: rgba(255, 255, 255, 0.08)
				color: rgba(255, 255, 255, 0.8)
				.icon
					color: #2ecc71

</style>
