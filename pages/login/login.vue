<template>
	<view class="">
		<view >
			<label for="mobile">账号</label>
			<input id="mobile" type="text" value="" placeholder="昵称/手机号"/>
		</view>
		<view>
			<label for="password">密码</label>
			<input password type="text" value="" placeholder="密码" id="password"/>
		</view>
		<button type="primary" style="width: 600rpx;margin-left:auto;">登陆</button>
		<view style="display: flex; justify-content:space-between; margin-top:10px;">
			<button class="mini-btn fs16p" type="default" size="mini" style="font-size: 16px;border: none;">忘记密码</button>
			<button type="primary" size="mini" style="font-size: 16px;">立即注册</button>
		</view>
		
		<view style="">
			<button type="default" plain size="mini" style="margin-left:260rpx ;" class="mini-btn fs16p buttonBorder">快速登陆</button>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		methods: {
			
		}
	}
</script>

<style>
	.fs16p {
		font-size: 16px;
	}
	.styleFlex {
		display: flex;
	}
	.styleInlineFlex {
		display: inline-flex;
	}
	.loginButtonSize {
		font-size: medium !important;
	}
	.buttonBorder {
		border: #007AFF 1px solid !important;
	}
	view {
		margin-top:10px;
	}
</style>
