<template>
	<div id="app">
		<!-- 右边的导航栏 -->
		<el-container style="height: 99%; border: 1px solid #eee">
			<el-aside width="250px" style="background-color: darkgrey">
				<div style="margin: 20px 0;">
					<div class="demo-avatar">
						<div class="dmeo-header">
						</div>
						<!-- <Avatar class="demo-radius" /> -->
						<div>
							<el-upload class="avatar-uploader" action="https://jsonplaceholder.typicode.com/posts/">
								<img src="./assets/logo.png" class="avatar">
							</el-upload>


						</div>
						<hr style="padding: 40px 0;" />
						<div class="aside-buttom">
							<div><a href="" style="color: #2C3E50;"><b>首页</b></a></div>

							<div><a href="" style="color: #2C3E50;"><b>个人</b></a></div>

							<div><a href="https://www.cnblogs.com/YouAreABug" style="color: #2C3E50;"><b>博客</b></a></div>

							<div><a href="https://github.com/wgc00" style="color: #2C3E50;"><b>github</b></a></div>
						</div>
					</div>
				</div>
			</el-aside>

			<!-- 右边布局 -->
			<el-container>
				<el-main>
					<!-- <HelloWorld></HelloWorld> -->
					<personalResume></personalResume>
				</el-main>
			</el-container>
		</el-container>
	</div>
</template>

<script>
	import HelloWorld from './components/HelloWorld.vue'
	import personalResume	from './components/personalResume.vue'
	export default {
		name: 'app',
		components: {
			HelloWorld,
			personalResume
		}
	}
</script>

<style>
	#app {
		width: 890px;
		height: 100%;
		font-family: 'Avenir', Helvetica, Arial, sans-serif;
		-webkit-font-smoothing: antialiased;
		-moz-osx-font-smoothing: grayscale;
		text-align: center;
		color: #2c3e50;
		margin: auto;

	}

	.el-header,
	.el-footer {
		/* background-color: #333333; */
		color: #333;
		text-align: center;
		line-height: 60px;
	}

	.el-aside {
		/* background-color: #D3DCE6; */
		color: #333;
		text-align: center;
		/* line-height: 200px; */
	}

	.el-main {
		background-color: #E9EEF3;
		color: #333;
		text-align: center;
		line-height: 1em;
	}


	.el-container:nth-child(5) .el-aside,
	.el-container:nth-child(6) .el-aside {
		line-height: 260px;
	}

	.el-container:nth-child(7) .el-aside {
		line-height: 320px;
	}

	.demo-radius {
		display: inline-block;
		margin-right: 5px;
		border-radius: 50px;
		/* 圆形边缘弧度 */
		width: 100px;
		/* 宽度 */
		height: 100px;
		/* 高度 */
		border: red solid 1px;
	}

	.dmeo-header {
		margin-top: 25%;
	}

	.avatar-uploader .el-upload {
		border: 1px dashed #d9d9d9;
		border-radius: 6px;
		cursor: pointer;
		position: relative;
		overflow: hidden;
	}

	.avatar-uploader .el-upload:hover {
		border-color: #409EFF;
	}

	.avatar-uploader-icon {
		font-size: 28px;
		color: #8c939d;
		width: 178px;
		height: 178px;
		line-height: 178px;
		text-align: center;
	}

	.avatar {
		width: 178px;
		height: 178px;
		display: block;
	}

	.aside-buttom {
		line-height: 2em;
		font-size: 14px;
	}
</style>
