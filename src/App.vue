<script setup>
import LayoutContainer from './components/Layout/LayoutContainer.vue';
import Slider from './components/ui/slider.vue';
</script>

<template>
	<layout-container>
		<div class="title">
			<span class="title__main"
				>Start connecting your world</span
			>
			<!-- <span class="title__description"
				>Save time and money by making the internet work for
				you! We believe you might like...</span
			>  -->
		</div>
		<div class="slider"><slider></slider></div>
		<div class="title">
			<span class="title__main"
				>Powerful monitor <br />of your dealer
				infestruction</span
			>
		</div>
	</layout-container>
</template>

<style lang="scss">
@import './styles/global.scss';

.title {
	display: flex;
	flex-direction: column;
	color: var(--white);
	text-align: center;
	font-style: normal;
	line-height: 100%;
	margin-top: 107px;
	max-width: 957px;

	&__main {
		font-size: 72px;
		text-transform: uppercase;
		line-height: 100%;
		font-weight: 900;
		word-spacing: 1.5px;
	}

	&__description {
		margin-top: 8px;
		font-size: 16px;
		font-style: normal;
		font-weight: 400;
		line-height: 100%;
	}
}

.slider {
	margin-top: 333px;
}
</style>
