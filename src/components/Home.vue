<template>
	<div class="Home">
		<AceEditor :theme="github" :options="editorOptions" :lang="javascript" style="font-size: 16px"/>
	</div>
</template>

<script>
import AceEditor from 'vue2-ace'
import 'brace/mode/javascript'
import 'brace/theme/github'

export default {
	name: 'Home',
	components: {
		AceEditor
	},
	data () {
		return {
			editorOptions: {
				fontSize: '16px'
			}
		}
	}
}
</script>

<style>

</style>
