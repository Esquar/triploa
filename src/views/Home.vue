<template>
	<v-app class="grey lighten-3">
		<cabecalho />
		<banner />
		<listaimovel />
		<buscaimovel />
		<rodape />
	</v-app>
</template>

<script>
import cabecalho	from '../components/cabecalho'
import banner		from '../components/banner'
import listaimovel	from '../components/listaimovel'
import buscaimovel	from '../components/buscaimovel'
import rodape		from '../components/rodape'

export default {
	name: 'Home',

	components: {
		cabecalho,
		banner,
		listaimovel,
		buscaimovel,
		rodape
	},
}
</script>
