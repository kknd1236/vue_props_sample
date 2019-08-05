<template>
	<v-app>
		<v-content>
			<User />
		</v-content>
	</v-app>
</template>

<script>
import User from './components/User';
//import tab from './components/TabContainer';

export default {
	name: 'App',
	components: {
		User,
		//tab,
	},
};
</script>
