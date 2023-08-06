<template>
	<nav>
		<ul>
			<li>
				<NuxtLink to="/">Home</NuxtLink>
			</li>
			<li>
				<NuxtLink to="/projects">Projects</NuxtLink>
			</li>
			<li>
				<NuxtLink to="/map">Map</NuxtLink>
			</li>
			<li>
				<NuxtLink to="/about">About</NuxtLink>
			</li>
		</ul>
	</nav>
</template>

<script setup lang="ts">

</script>

<style scoped>
nav {}

li {
	list-style-type: none;
}
</style>