<template>
  <view class="flex-col page">
    <view class="flex-col group">
      <text class="self-center text">个人信息</text>
      <view class="flex-row justify-between items-end self-stretch group_2">
        <view class="flex-col items-center">
          <text class="font text_2">头像</text>
          <text class="font text_3 mt-39">姓名</text>
        </view>
        <view class="flex-col items-center group_3">
          <image
            class="image"
            src="/static/2ca2bb24e2dd1e00d24456678c1d28bd.png"
          />
          <text class="mt-12 font_2 text_4">上上签</text>
        </view>
      </view>
      <view class="flex-row justify-between items-center self-stretch group_4">
        <text class="font text_5">ID</text>
        <text class="font_3 text_6">2024XXXX</text>
      </view>
      <view class="flex-row justify-between items-baseline self-stretch group_5 view">
        <text class="font text_7">已加入社区</text>
        <text class="font_2 text_8">湖北大学</text>
      </view>
      <view class="flex-row justify-between items-baseline self-stretch group_5">
        <text class="font text_9">实名状态</text>
        <text class="font_2 text_10">已实名</text>
      </view>
      <view class="flex-row justify-between items-baseline self-stretch group_6">
        <text class="font">手机号</text>
        <text class="font_3">130xxxxx979</text>
      </view>
      <view class="flex-row justify-between items-baseline self-stretch group_5">
        <text class="font text_11">邮箱</text>
        <text class="font_3 text_12">9541...</text>
      </view>
      <view class="flex-row justify-between items-baseline self-stretch group_7">
        <text class="font text_13">微信</text>
        <text class="font_2 text_14">文和</text>
      </view>
      <view class="flex-row justify-between items-baseline self-stretch group_8">
        <text class="font">支付宝</text>
        <text class="font_2 text_15">未绑定</text>
      </view>
      <view class="flex-row justify-between self-stretch group_9">
        <text class="font text_16">QQ</text>
        <text class="self-start font_2 text_17">未绑定</text>
      </view>
    </view>
    <view class="flex-col justify-start section mt-25">
      <view class="flex-row equal-division">
        <view class="flex-col items-center group_10 equal-division-item">
          <image
            class="shrink-0 image_2"
            src="/static/b81115432643f33c3a7fc5837f01be47.png"
          />
          <text class="font_4 text_18">主页</text>
        </view>
        <view class="flex-col items-center group_10 equal-division-item">
          <image
            class="shrink-0 image_2"
            src="/static/a0d2925376f3a6fa664905443fecccaf.png"
          />
          <text class="font_4 text_18">消息</text>
        </view>
        <view class="flex-col items-center group_10 equal-division-item">
          <image
            class="shrink-0 image_2"
            src="/static/b5c5b240dc45624d009ac0260b9834c1.png"
          />
          <text class="font_4 text_18">我的</text>
        </view>
      </view>
    </view>
  </view>
</template>

<script>
  export default {
    components: {},
    props: {},
    data() {
      return {};
    },

    methods: {},
  };
</script>

<style scoped lang="css">
  .mt-39 {
    margin-top: 74.43rpx;
  }
  .mt-25 {
    margin-top: 47.71rpx;
  }
  .page {
    padding-top: 133.59rpx;
    background-color: #ffffff;
    width: 100%;
    overflow-y: auto;
    overflow-x: hidden;
    height: 100%;
  }
  .group {
    padding-left: 122.14rpx;
    padding-right: 91.6rpx;
  }
  .text {
    color: #000000;
    font-size: 61.07rpx;
    font-family: STIX Two Text;
    font-weight: 700;
    line-height: 58.02rpx;
  }
  .group_2 {
    margin-top: 34.35rpx;
  }
  .font {
    font-size: 45.8rpx;
    font-family: STIX Two Text;
    line-height: 43.09rpx;
    font-weight: 600;
    color: #000000;
  }
  .text_2 {
    line-height: 43.05rpx;
  }
  .text_3 {
    line-height: 43.32rpx;
  }
  .group_3 {
    margin-bottom: 7.63rpx;
  }
  .image {
    width: 183.21rpx;
    height: 183.21rpx;
  }
  .font_2 {
    font-size: 30.53rpx;
    font-family: STIX Two Text;
    line-height: 29.26rpx;
    font-weight: 600;
    color: #000000;
  }
  .text_4 {
    line-height: 28.15rpx;
  }
  .group_4 {
    margin-top: 83.97rpx;
  }
  .text_5 {
    line-height: 30.1rpx;
  }
  .font_3 {
    font-size: 30.53rpx;
    font-family: STIX Two Text;
    line-height: 20.27rpx;
    font-weight: 600;
    color: #000000;
  }
  .text_6 {
    margin-right: 15.27rpx;
    line-height: 20.4rpx;
  }
  .group_5 {
    margin-top: 76.34rpx;
    padding: 0 3.82rpx;
  }
  .view {
    margin-top: 80.15rpx;
  }
  .text_7 {
    line-height: 43.02rpx;
  }
  .text_8 {
    margin-right: 26.72rpx;
    line-height: 28.97rpx;
  }
  .text_9 {
    line-height: 43.65rpx;
  }
  .text_10 {
    margin-right: 41.98rpx;
    line-height: 29.1rpx;
  }
  .group_6 {
    margin-top: 76.34rpx;
  }
  .text_11 {
    line-height: 43.38rpx;
  }
  .text_12 {
    margin-right: 45.8rpx;
    line-height: 20.19rpx;
  }
  .group_7 {
    margin-top: 76.34rpx;
  }
  .text_13 {
    line-height: 43.05rpx;
  }
  .text_14 {
    margin-right: 61.07rpx;
    line-height: 28.76rpx;
  }
  .group_8 {
    margin-top: 76.34rpx;
  }
  .text_15 {
    margin-right: 45.8rpx;
    line-height: 28.89rpx;
  }
  .group_9 {
    margin-top: 83.97rpx;
  }
  .text_16 {
    line-height: 38.61rpx;
  }
  .text_17 {
    margin-right: 45.8rpx;
    line-height: 28.89rpx;
  }
  .section {
    padding: 15.27rpx 0 26.72rpx;
    background-image: url('/static/9ef58bfca3448fc325d82a62ab2ca15f.png');
    background-size: 100% 100%;
    background-repeat: no-repeat;
  }
  .equal-division {
    padding: 0 22.9rpx;
  }
  .group_10 {
    flex: 1 1 234.73rpx;
  }
  .equal-division-item {
    padding: 3.82rpx 0 11.45rpx;
  }
  .image_2 {
    width: 80rpx;
    height: 80rpx;
  }
  .font_4 {
    font-size: 30.53rpx;
    font-family: Microsoft YaHei;
    line-height: 29.26rpx;
    color: #000000;
  }
  .text_18 {
    margin-top: -7.63rpx;
  }
</style>