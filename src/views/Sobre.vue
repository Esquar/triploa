<template>
	<v-app>
		<cabecalho />
		<sobreempresa />
		<rodape />
	</v-app>
</template>

<script>
import cabecalho	from '../components/cabecalho'
import sobreempresa	from '../components/sobreempresa'
import rodape		from '../components/rodape'

export default {
	name: 'Home',

	components: {
		cabecalho,
		sobreempresa,
		rodape
	},
}
</script>
