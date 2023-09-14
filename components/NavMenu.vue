<template>
	<nav>
		<ul>
			<li>
				<NuxtLink class="link" to="/">Home</NuxtLink>
			</li>
			<li>
				<NuxtLink class="link" to="/projects">Projects</NuxtLink>
			</li>
			<li>
				<NuxtLink class="link" to="/map">Map</NuxtLink>
			</li>
			<li>
				<NuxtLink class="link" to="/history">History</NuxtLink>
			</li>
			<li>
				<NuxtLink class="link" to="/contact">Contact</NuxtLink>
			</li>
		</ul>
	</nav>
</template>

<script setup lang="ts">

</script>

<style scoped>
nav {
	max-width: 650px;
	height: 100%;
	margin: auto;
	align-items: center;
}

ul {
	width: 100%;
	display: flex;
	flex-direction: row;
	justify-content: space-around;
	height: 100%;
	padding: 0px;
	margin: 0px;
	align-items: center;
}

li {
	display: inline-block;
	text-align: center;
	list-style-type: none;
}

.link {
	font-size: 24px;
	padding: 10px;
	text-decoration: none;
	border-radius: 10px;
	color: white;
}

.link {
	font-size: 24px;
	padding: 10px;
	text-decoration: none;
	border-radius: 10px;
}

.link:hover {
	text-decoration: underline;
	animation: pop 0.4s ease-in-out;
}

@keyframes pop {
	50% {
		transform: scale(1.25);
	}
}
</style>