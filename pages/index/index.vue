<template>
	<view class="content">
		<iframe src="./static/index.html"></iframe>
		<svg class="refresh" onclick="location.reload()" t="1706147715254" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="4230" width="200" height="200"><path d="M856.3 550.7c-13.2-1.8-25.3 7.5-27.1 20.6-24.8 184.6-194.5 314.2-379.1 289.4s-314.2-194.4-289.4-379C185.5 297 355.1 167.5 539.8 192.2c97.4 13.1 179 66.9 231 141.5H639.5c-13.3 0-24.1 10.8-24.1 24.1s10.8 24.1 24.1 24.1H808c26.6 0 48.4-21.7 48.4-48.4V165.1c0-13.3-10.8-24.1-24.1-24.1s-24.1 10.8-24.1 24.1l-0.1 138.1c-59.6-83.8-151.8-143.9-261.8-158.7-211-28.3-404.9 119.9-433.2 330.8-28.3 211 119.8 404.9 330.7 433.2 211 28.3 405-119.9 433.3-330.8 1.7-13.2-7.5-25.3-20.8-27z m0 0" fill="#2197EF" p-id="4231"></path></svg>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: 'Hello'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	.content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}

	iframe, body, html, uni-page-body, uni-view {
		width: 100%;
		height: 100%;
		margin: 0;
		padding: 0;
	}
	iframe {
		lef: 0;
		top: 0;
		border: none;
	}
	.refresh {
		position: fixed;
		right: 2%;
		bottom: 2%;
		z-index: 99;
		width: 45px;
		height: 45px;
	}
</style>
