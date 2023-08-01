<script setup>
import LayoutHeader from '@/components/layout/Header.vue';
</script>

<template>
	<div class="container">
		<div class="circle-first"></div>
		<div class="circle-second"></div>
		<div class="circle-third"></div>
		<layout-header />
		<slot></slot>
	</div>
</template>

<style lang="scss" scoped>
.container {
	display: flex;
	flex-direction: column;
	margin: 0 auto;
	align-items: center;
	.circle-first {
		position: fixed;
		top: -56vw;
		left: 0;
		width: 56vw;
		height: 56vw;
		border-radius: 1083px;
		background: #0a72d4;
		filter: blur(480px);
	}
	.circle-second {
		position: fixed;
		top: 1405px;
		left: -915px;
		width: 1083px;
		height: 1083px;
		border-radius: 1083px;
		background: #0a72d4;
		filter: blur(480px);
	}
	.circle-third {
		position: fixed;
		top: 512px;
		right: -85%;
		width: 56vw;
		height: 56vw;
		border-radius: 1083px;
		background: #0a72d4;
		filter: blur(480px);
	}
}
</style>
