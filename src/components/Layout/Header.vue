<script setup></script>

<template>
	<header class="header">
		<a
			href="/"
			class="header__logo"
			>Uptify</a
		>
		<button>
			<img
				src="@/assets/buttons/login.svg"
				alt="SVG file" />
		</button>
	</header>
</template>

<style lang="scss" scoped>
.header {
	padding: 24px 32px 0;
	width: 100%;
	display: flex;
	align-items: center;
	justify-content: space-between;
	&__logo {
		font-size: 48px;
		font-weight: 900;
	}
}
</style>
