<script>
	export default {
		onLaunch: function() {
			console.log('App Launch')
		},
		onShow: function() {
			console.log('App Show')
		},
		// onHide: function() {
		// 	console.log('App Hide')
		// }
	}
</script>

<style lang="scss">
	/*每个页面公共css */
	/* 注意要写在第一行，同时给style标签加入lang="scss"属性 */
	@import "@/uni_modules/uview-ui/index.scss";
	@import url('//at.alicdn.com/t/font_3350402_bx3bn7qytqp.css');
	//@import "@/common/font/iconfont.css";
	@import url('@/common/css/flex.css');

</style>
