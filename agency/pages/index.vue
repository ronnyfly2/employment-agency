<template lang="pug">
	section.container
		div
			logo
			h1.title agency
			h2.subtitle agency hecho en nuxt
			.links
				a(href="https://nuxtjs.org/" target="_blank" class="button--green") Documentation
				a(href="https://github.com/nuxt/nuxt.js" target="_blank" class="button--grey") GitHub
</template>

<script>
import Logo from '~/components/Logo.vue'
export default {
  components: {
    Logo
  }
}
</script>

<style lang="stylus">
.container
	min-height 100vh
	display flex
	justify-content center
	align-items center
	text-align center
.title
	display block
	font-weight 300
	font-size 100px
	color #35495e
	letter-spacing 1px
.subtitle
	font-weight 300
	font-size 42px
	color #526488
	word-spacing 5px
	padding-bottom 15px
.links
	padding-top 15px
</style>
