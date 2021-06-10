<template lang="pug">
#app
	#nav
		router-link.header-logo( 
		to="/" 
		) Basic settings
	router-view
</template>

<style lang="scss">

@import "./assets/variables.scss";
@import "./assets/reset.scss";
@import "./assets/base.scss";
</style>
