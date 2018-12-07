<template>
	<div class="resume">
		<div class="resume-title">
			<h1 class="resume-title-h">简历</h1>
		</div>
		<div style="padding: 20px;">
			
		</div>
		<div class="resume-info">
			<div class="resume-info-title">
				<h3>基本信息</h3>
				<div class="resume-info-item">
					<div class="resume-info-context-left">
						<p>姓 名：王国聪 </p>
						<p>民 族：汉 </p>
						<p>电 话：13025777738 </p>
						<p>邮 箱：1605513752@qq.com </p>
						<p>住 址：广东省珠海市南方IT学院</p>
					</div>
					<div class="resume-info-context-left">
						<p>籍 贯：广西 </p>
						<p>出生年月：1998.11.24 </p>
						<p>身 高：170cm </p>
						<p>毕业院校：南方IT学院 </p>
						<p>学 历：专科 </p>
					</div>
				</div>
			</div>
		</div>
		<!-- 教育背景 -->
		<div class="resume-info">
			<div class="resume-info-title">
				<h3>教育背景</h3>
				<div class="resume-info-item">
					<div class="resume-info-context-left">
						<p>2014.09-2017.06</p>
						<p>2017.09-2019.06</p>
					</div>
					<div class="resume-info-context-left">
						<p>育贤中学（广西）</p>
						<p>广东珠海南方职业培训学院</p>
					</div>
					<div class="resume-info-context-left">
						<p>义务教育（高中）</p>
						<p>Java编程（专科）</p>
					</div>
				</div>
			</div>
		</div>

		<div class="resume-info">
			<div class="resume-info-title">
				<h3>专业技能</h3>
				<div class="resume-info-item">
					<div class="resume-info-context-left">
						<p>1、熟练掌握JAVA面向对象语言； </p>
						<p>2、熟练掌握SSM框架核心技术，并能独立Web开发； </p>
						<p>3、熟练Bootstrap、MUI、UNI、Element UI等组件； </p>
						<p>4、熟练Vue框架的使用，并能开发SPA应用。 </p>
						<p>
							<h4>数据库： </h4>
						</p>
						<div>
							<p>1、 掌握SQL语言，能熟练的使用SQL语句创建表、视图、存储过程、触发器、约束；</p>
							<p>2、 掌握SQL server、SQLite、MySQL数据库的使用，并且可以进行应用程序开发；</p>
							<p>3、 熟悉数据库设计规范，掌握数据库的基本理论。</p>
						</div>
					</div>

				</div>
			</div>
		</div>

		<div class="resume-info">
			<div class="resume-info-title">
				<h3>团队项目</h3>
				<div class="resume-info-item">
					<div class="resume-info-context-left">
						后期添加上
					</div>
					
				</div>
			</div>
		</div>
	</div>
</template>

<script>
	export default {
		name: 'personalResume',
		data() {
			return {

			};
		}
	}
</script>

<style>
	.resume-title-h {
		margin-top: 2em;
		text-align: left;

	}

	.resume-info-title {
		text-align: left;
		margin-left: 5em;
		padding-bottom: 1em;
	}

	.resume-info-item {
		display: flex;
	}

	.resume-info-context-left {
		/* border: 1px solid red; */
		width: 240px;
		margin-left: 2em;
		line-height: 3em;
		flex: 1;
	}
</style>
