<template>
	<div id="app">
		<router-view/>
	</div>
</template>

<script>
    export default {
        data() {
            return {}
        }
    }
</script>

<style lang="scss">
	@import "assets/styles/app";

	#app {
		font-family: 'Avenir', Helvetica, Arial, sans-serif;
		-webkit-font-smoothing: antialiased;
		-moz-osx-font-smoothing: grayscale;
		text-align: center;
	}

	#nav {
		padding: 30px;

		a {
			font-weight: bold;

			&.router-link-exact-active {
				color: #42b983;
			}
		}
	}

	hr {
		border-top: 1px solid rgba(255,255,255,0.1);
	}

	a.router-link-active{
		font-size: 32px;
		color: white;
	}

</style>
