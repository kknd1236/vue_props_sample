<!-- TabContainer.vue -->
<template>
	<div>
		<button-tab>
			<!-- slot 영역 -->
			<h1 slot="header">First Header</h1>
			<div slot="content" class="content">Tab Contents #1</div>
		</button-tab>
		<button-tab>
			<!-- slot 영역 -->
			<h1 slot="header">Second Header</h1>
			<div slot="content" class="content">Tab Contents #2</div>
		</button-tab>
		<button-tab>
			<!-- slot 영역 -->
			<h1 slot="header">Third Header</h1>
			<div slot="content" class="content">Tab Contents #3</div>
		</button-tab>
	</div>
</template>

<script>
import ButtonTab from './ButtonTab';
export default {
	components: {
		ButtonTab,
	},
};
</script>
