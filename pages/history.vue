<template>
	<main>
		<div id="history">
			<h1>History</h1>
			<p></p>
		</div>
		<div id="sponsors">
			<h1>Sponsors</h1>
			<p></p>
		</div>
		<div id="request">
			<h1>Request a Mirror</h1>
			<p></p>
		</div>
	</main>
</template>

<script setup lang="ts">
const pageInfo = {
	title: "Mirror - History",
	description: "A public repository of free and open source software located at Clarkson University in Potsdam, NY, US.",
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
	ogUrl: "https://mirror.clarkson.edu/about",
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