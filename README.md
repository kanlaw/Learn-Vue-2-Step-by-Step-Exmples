* Learning Vue 2
	https://laracasts.com/series/learn-vue-2-step-by-step

* Install Vue.js syntax highlighter in sublime
	https://medium.com/@kentaguilar/install-vue-syntax-highlighting-via-package-control-on-sublime-text-2-bfb977f444e7

* Vue Directives
	v-model
	v-for
	v-text
	v-on:click | @click
	v-on:click="addName" | @click="addName"
	v-on:keyup.enter | @keyup.enter
	v-bind:title | :title
	v-bind:class | :class
	v-bind:class="className" | :class="className"
	v-bind:class="{'color-red' : isColorRed}" | :class="{'color-red' : isColorRed}"
	v-bind:disabled="isDisabled" | :disabled="isDisabled"

* Vue Structure

	var app = new Vue({
		el: '#root',
		data: {
			names: ['Ram', 'Kans', 'Selva']
		},

		methods: {
			addName: function() {

			}
		}
	
		mounted() {
			// executed earlier
		}

	})