<template>
  <view class="flex-col page">
    <view class="flex-col items-start">
      <image
        class="image"
        src="/static/a5424564109f254ec41206c1aad87b61.png"
      />
      <text class="mt-20 text">键入内容...</text>
    </view>
    <image
      class="image_2 mt-79"
      src="/static/e7544a676c8b76f68c6a7f2ef95c8780.png"
    />
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
  .mt-79 {
    margin-top: 150.76rpx;
  }
  .page {
    padding: 125.95rpx 40.08rpx 984.73rpx;
    background-color: #ffffff;
    width: 100%;
    overflow-y: auto;
    overflow-x: hidden;
    height: 100%;
  }
  .image {
    border-radius: 50%;
    width: 93.66rpx;
    height: 91.53rpx;
  }
  .text {
    margin-left: 53.44rpx;
    color: #d9d9d9;
    font-size: 30.53rpx;
    font-family: STIX Two Text;
    font-weight: 600;
    line-height: 29.12rpx;
  }
  .image_2 {
    margin: 0 15.27rpx;
    width: 637.4rpx;
    height: 206.11rpx;
  }
</style>