<script setup></script>

<template>
	<input
		type="search"
		placeholder="Search Services"
		class="input-search" />
</template>

<style lang="scss" scoped>
.input-search {
	width: 100%;
	max-width: 960px;
	height: 64px;
	border-radius: 16px;
	border: 2px solid rgba(255, 255, 255, 0.08);
	padding-left: 30px;
	&::placeholder {
	}
	&::-webkit-input-placeholder {
		color: #67829a;
		font-size: 20px;
		font-style: normal;
		font-weight: 400;
		line-height: 24px;
		letter-spacing: -0.2px;
	}
	&::-moz-placeholder {
		color: #67829a;
		font-size: 20px;
		font-style: normal;
		font-weight: 400;
		line-height: 24px;
		letter-spacing: -0.2px;
	}
	&:-moz-placeholder {
		color: #67829a;
		font-size: 20px;
		font-style: normal;
		font-weight: 400;
		line-height: 24px;
		letter-spacing: -0.2px;
	}
	&[type='search'] {
		background-image: url('../assets/input/search.svg');
		background-position: 10px center;
		background-repeat: no-repeat;
		padding-left: 30px;
	}
}
</style>
