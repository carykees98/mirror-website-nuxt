<template>
	<main>
		<h1>Welcome to Mirror</h1>
	</main>
</template>

<script setup lang="ts">

const pageInfo = {
	title: "Mirror - Home",
	description: "",
	image: "",
}

useServerSeoMeta({
	title: pageInfo.title,
	ogTitle: pageInfo.title,
	twitterTitle: pageInfo.title,
	description: pageInfo.description,
	ogDescription: pageInfo.description,
	twitterDescription: pageInfo.description,
	ogImage: pageInfo.image,
	twitterImage: pageInfo.image,
	ogUrl: "https://mirror.clarkson.edu/",
	twitterCard: 'summary'
})

useHead({
	htmlAttrs: {
		lang: 'en'
	},
	link: [
		{
			rel: 'icon',
			type: 'image/x-icon',
			href: 'favicon.ico'
		}
	]
})
</script>

<style scoped>
main {
	margin-top: 4%;
	text-align: center;
}

h1 {
	font-size: 60px;
}
</style>