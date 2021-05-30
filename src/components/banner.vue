<template>
	<v-row class="pt-5 mt-5">
		<v-carousel
			:show-arrows="false"
			class="pl-5 pr-5">

			<v-carousel-item
				v-for="(item,i) in items"
				:key="i"
				:src="item.src"
				reverse-transition="fade-transition"
				transition="fade-transition">
			</v-carousel-item>
		</v-carousel>
	</v-row>
</template>

<script>
export default {
	name: 'banner',

	data: () => ({
		items: [
			{
				src: 'https://i.picsum.photos/id/1029/4887/2759.jpg?hmac=uMSExsgG8_PWwP9he9Y0LQ4bFDLlij7voa9lU9KMXDE',
			},
			{
				src: 'https://i.picsum.photos/id/1040/4496/3000.jpg?hmac=kvZONlBpTcZ16PuE_g2RWxlicQ5JKVq2lqqZndfafBY',
			},
			{
				src: 'https://i.picsum.photos/id/1067/5760/3840.jpg?hmac=gO_V7rUFdM8YddyLysCQet4CS0CzSvUcfAtHI1ismLM',
			},
			{
				src: 'https://i.picsum.photos/id/238/2560/1440.jpg?hmac=wKo4dLHwDntZmO_fdtnKtsnmRcPMACca3m5J5vx2AVc',
			},
		],
	}),
}
</script>
