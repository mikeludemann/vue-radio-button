<template lang="html">

	<div class="radio-button">
	<label>
		<input
			type="radio"
			:value="value"
			:name="name + '[]'"
			:checked="!!isChecked"
			@change="e => isChecked = e.target.checked"
		/>
		
	</label>
	</div>

</template>

<script lang="js">

	export default {
		name: 'RadioButton',
		props: {
			name: {
				type: string,
				required: true
			},
			value: {
				type: string,
				required: true
			},
			text: {
				type: string,
				required: false
			},
			isChecked: {
				type: boolean,
				default: false,
				required: true
			}
		},
		mounted () {

		},
		data () {
			return {

			}
		},
		methods: {

		},
		computed: {

		}
}


</script>

<style scoped lang="scss">
	.radio-button {

	}
</style>
