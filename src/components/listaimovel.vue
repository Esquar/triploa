<template>
	<v-container>
		<v-spacer class="mt-5 pt-5"></v-spacer>

		<v-row justify="center" class="mt-5 pt-5">
			<v-col
				v-for="k in 6"
				:key="k"
				md="4">

				<v-card
				class="pa-2"
				outlined
				tile
				>
					<v-img src="https://i.picsum.photos/id/1029/4887/2759.jpg?hmac=uMSExsgG8_PWwP9he9Y0LQ4bFDLlij7voa9lU9KMXDE" />
					<v-row class="pt-2">
						<v-col cols=3 class="text-right font-weight-black colorBase">info</v-col>
						<v-col>aaaaaaaa</v-col>
					</v-row>
					<v-row>
						<v-col cols=3 class="text-right font-weight-black colorBase">info</v-col>
						<v-col>aaaaaaaa</v-col>
					</v-row>
					<v-row>
						<v-col cols=3 class="text-right font-weight-black colorBase">info</v-col>
						<v-col>aaaaaaaa</v-col>
					</v-row>
				</v-card>
			</v-col>
		</v-row>
	</v-container>
</template>

<script>
export default {
	name: 'listaimobel',

	data: () => ({

	}),
}
</script>
