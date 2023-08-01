<script setup>
import 'swiper/css';
import 'swiper/css/navigation';
import 'swiper/css/pagination';
import 'swiper/css/scrollbar';
import { Swiper, SwiperSlide } from 'swiper/vue';
import BrandBlock from './brandBlock.vue';
</script>

<template>
	<div class="slider-container">
		<swiper
			:pagination="true"
			:modules="modules"
			class="mySwiper">
			<swiper-slide>
				<div class="slide">
					<brand-block
						><span>Trusted by</span>
						<span class="big-text">16</span>
						<span>dealers</span>
					</brand-block>
					<brand-block
						><img
							src="../../assets/brands/KennyRoss.svg"
							alt=""
					/></brand-block>
					<brand-block
						><img
							src="../../assets/brands/kia.svg"
							alt=""
					/></brand-block>
					<brand-block
						><img
							src="../../assets/brands/1Coch.svg"
							alt=""
					/></brand-block>
					<brand-block
						><img
							src="../../assets/brands/Honda.svg"
							alt=""
					/></brand-block>
					<brand-block
						><img
							src="../../assets/brands/Mid.svg"
							alt=""
					/></brand-block>
				</div>
			</swiper-slide>
			<swiper-slide>
				<div class="slide">
					<brand-block
						><span>Trusted by</span>
						<span class="big-text">16</span>
						<span>dealers</span>
					</brand-block>
					<brand-block
						><img
							src="../../assets/brands/KennyRoss.svg"
							alt=""
					/></brand-block>
					<brand-block
						><img
							src="../../assets/brands/kia.svg"
							alt=""
					/></brand-block>
					<brand-block
						><img
							src="../../assets/brands/1Coch.svg"
							alt=""
					/></brand-block>
					<brand-block
						><img
							src="../../assets/brands/Honda.svg"
							alt=""
					/></brand-block>
					<brand-block
						><img
							src="../../assets/brands/Mid.svg"
							alt=""
					/></brand-block>
				</div>
			</swiper-slide>
			<swiper-slide>
				<div class="slide">
					<brand-block
						><span>Trusted by</span>
						<span class="big-text">16</span>
						<span>dealers</span>
					</brand-block>
					<brand-block
						><img
							src="../../assets/brands/KennyRoss.svg"
							alt=""
					/></brand-block>
					<brand-block
						><img
							src="../../assets/brands/kia.svg"
							alt=""
					/></brand-block>
					<brand-block
						><img
							src="../../assets/brands/1Coch.svg"
							alt=""
					/></brand-block>
					<brand-block
						><img
							src="../../assets/brands/Honda.svg"
							alt=""
					/></brand-block>
					<brand-block
						><img
							src="../../assets/brands/Mid.svg"
							alt=""
					/></brand-block>
				</div>
			</swiper-slide>
		</swiper>
	</div>
</template>

<style lang="scss" scoped>
.slider-container {
	width: 100%;
	max-width: 959px;
}
.slide {
	display: flex;
	flex-wrap: wrap;
	justify-content: center;
	gap: 16px;
	max-width: 959px;
}
</style>
