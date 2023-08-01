<script setup></script>

<template>
	<div class="brand-block"><slot></slot></div>
</template>

<style lang="scss">
.brand-block {
	width: 309px;
	height: 256px;
	border-radius: 16px;
	background: linear-gradient(
			315deg,
			rgba(51, 123, 190, 0.2) 0%,
			rgba(51, 123, 190, 0) 100%
		),
		rgba(255, 255, 255, 0.08);
	display: flex;
	justify-content: center;
	align-items: center;
	flex-direction: column;
	span {
		font-size: 32px;
		font-weight: 900;
		line-height: 40px;
		text-transform: uppercase;
	}
	.big-text {
		display: flex;
		align-items: center;
		font-size: 108px;
		height: 108px;
		text-align: center;
	}
}
</style>
