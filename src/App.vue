<script>
	export default {
		onLaunch: function() {
			console.log('App Launch')
		},
		onShow: function() {
			console.log('App Show')
		},
		onHide: function() {
			console.log('App Hide')
		}
	}
</script>

<style>
	/*每个页面公共css */
	.bottom-line {
  position: fixed;
  bottom: 0;
  left: 0;
  height: 5px;
  width: 100vw;
  box-shadow: 0 -5px 5px rgba(0, 0, 0, 0.05);
  z-index: 999;
}
</style>
