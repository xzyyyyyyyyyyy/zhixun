<template>
  <view class="flex-col page">
    <view class="flex-row justify-between items-center group">
      <text class="font text">键入你想要的内容</text>
      <image
        class="image"
        src="/static/8bd421df2e210c668375325e341ceebb.png"
      />
    </view>
    <view class="flex-col mt-25">
      <view class="flex-row items-center group_2">
        <image
          class="image_2"
          src="/static/ab7ac19491866c0ac90c4daf87c05aef.png"
        />
        <text class="ml-6 font_2 text_2">搜索历史</text>
      </view>
      <view class="flex-row group_3">
        <view class="flex-col justify-start items-center text-wrapper"><text class="font text_3">身份证</text></view>
        <view class="flex-col justify-start items-center text-wrapper_2 ml-7">
          <text class="font text_4">手提包</text>
        </view>
        <view class="flex-col justify-start items-center text-wrapper_3 ml-7"><text class="font text_5">伞</text></view>
      </view>
      <view class="flex-row items-center group_2 view">
        <image
          class="image_2"
          src="/static/b9521e697032944ae3c76e9f6f7c4b88.png"
        />
        <text class="ml-12 font_2 text_6">智能推荐</text>
      </view>
      <view class="grid">
        <view class="flex-col justify-start items-center grid-item">
          <text class="font">湖北大学（阳逻校区）</text>
        </view>
        <view class="flex-col justify-start items-center grid-item">
          <text class="font">湖北大学（武昌校区）</text>
        </view>
        <view class="flex-col justify-start items-center grid-item"><text class="font">今天上午八时左右</text></view>
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
  .mt-25 {
    margin-top: 47.71rpx;
  }
  .ml-7 {
    margin-left: 13.36rpx;
  }
  .page {
    padding: 152.67rpx 20.99rpx 910.31rpx 30.53rpx;
    background-color: #ffffff;
    width: 100%;
    overflow-y: auto;
    overflow-x: hidden;
    height: 100%;
  }
  .group {
    padding: 0 38.17rpx;
  }
  .font {
    font-size: 30.53rpx;
    font-family: STIX Two Text;
    line-height: 29.35rpx;
    font-weight: 600;
    color: #000000;
  }
  .text {
    color: #d9d9d9;
    line-height: 29.12rpx;
  }
  .image {
    margin-right: 19.08rpx;
    width: 49.62rpx;
    height: 45.8rpx;
  }
  .group_2 {
    padding: 0 28.63rpx;
  }
  .image_2 {
    width: 68.7rpx;
    height: 68.7rpx;
  }
  .font_2 {
    font-size: 45.8rpx;
    font-family: STIX Two Text;
    line-height: 43.19rpx;
    font-weight: 600;
  }
  .text_2 {
    color: #484550;
  }
  .group_3 {
    margin-top: 11.45rpx;
    padding: 0 26.72rpx;
  }
  .text-wrapper {
    padding: 30.53rpx 0;
    background-color: #ecf5f2;
    border-radius: 28.63rpx;
    width: 124.05rpx;
    height: 87.79rpx;
  }
  .text_3 {
    line-height: 28.8rpx;
  }
  .text-wrapper_2 {
    padding: 30.53rpx 0;
    background-color: #ecf5f2;
    border-radius: 28.63rpx;
    width: 120.23rpx;
    height: 87.79rpx;
  }
  .text_4 {
    line-height: 28.8rpx;
  }
  .text-wrapper_3 {
    padding: 30.53rpx 0;
    background-color: #ecf5f2;
    border-radius: 28.63rpx;
    width: 66.79rpx;
    height: 87.79rpx;
  }
  .text_5 {
    line-height: 29.06rpx;
  }
  .view {
    margin-top: 11.45rpx;
  }
  .text_6 {
    color: #575b66;
    line-height: 43.32rpx;
  }
  .grid {
    margin-top: 22.9rpx;
    height: 194.66rpx;
    display: grid;
    grid-template-rows: repeat(2, minmax(0, 1fr));
    grid-template-columns: repeat(2, minmax(0, 1fr));
    row-gap: 21.09rpx;
    column-gap: 13.45rpx;
  }
  .grid-item {
    padding: 26.72rpx 0 30.53rpx;
    background-color: #ecf5f2;
    border-radius: 28.63rpx;
  }
</style>