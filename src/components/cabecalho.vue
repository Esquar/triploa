<template>
	<v-card class="grey lighten-3" flat style="border-top-left-radius: 0;border-top-right-radius: 0;">
		<v-toolbar class="top_cabecalho" extended flat >
			<v-app-bar-nav-icon color="grey lighten-5"></v-app-bar-nav-icon>
		</v-toolbar>

		<v-card class="mx-auto" max-width="80%" style="margin-top:-90px; height:120px;">
			<v-toolbar flat style="height: 120px;">
				<v-spacer></v-spacer>
				<v-toolbar-title class="grey--text">
					<img :src="require('@/assets/img/logo_banner.png')" style="max-width:500px;">
				</v-toolbar-title>
				<v-spacer></v-spacer>
			</v-toolbar>
		</v-card>
	</v-card>

</template>

<script>
export default {
	name: 'cabecalho',

	data: () => ({

	}),
}
</script>
