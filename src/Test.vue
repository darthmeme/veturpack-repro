<template>
  <div></div>
</template>

<script lang="ts">
import Vue from 'vue'
import { foo } from './test'

function test(): string {
	return
}
const x: string = null;
const y = test();

foo()

export default Vue.extend({})
</script>