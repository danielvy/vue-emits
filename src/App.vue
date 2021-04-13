<template>
	<h1>Vue array type</h1>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

interface MyArray extends Array<number> {};

export default defineComponent({
  name: 'App',
	
	emits: ["test"],
	
	data() {
	},

	mounted() {
		this.$nextTick(() => {

		});
	}

});
</script>


