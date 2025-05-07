<template>
  <view class="flex-col page">
    <view class="flex-row justify-between items-end">
      <view class="flex-row">
        <image
          class="shrink-0 image"
          src="/static/a5424564109f254ec41206c1aad87b61.png"
        />
        <image
          class="ml-10 shrink-0 self-start image_2 image_3"
          src="https://codefun-proj-user-res-1256085488.cos.ap-guangzhou.myqcloud.com/670ac317d54496f19f897261/670d410b0a3d780012a63323/ddc134d0880e1deb1e2e5f45a5158cce.png"
        />
        <text class="ml-10 self-start font text">系统通知</text>
      </view>
      <image
        class="image_2 image_4"
        src="/static/9be3096dec7eb8dd01f6d84ab8cb826a.png"
      />
    </view>
    <view class="flex-row group">
      <image
        class="shrink-0 self-start image_5"
        src="https://codefun-proj-user-res-1256085488.cos.ap-guangzhou.myqcloud.com/670ac317d54496f19f897261/670d410b0a3d780012a63323/4ab64cd0e7a27dc86e1fdf873613831f.png"
      />
      <view class="ml-14 flex-col flex-1 section">
        <text class="self-start text_2">发现一个可能的小学同学，以下是相似条目</text>
        <view class="mt-12 flex-row self-stretch">
          <view class="flex-col justify-start items-center text-wrapper"><text class="font">A...</text></view>
          <view class="ml-12 flex-col justify-start items-center text-wrapper_2">
            <text class="font text_3">B...</text>
          </view>
          <view class="ml-12 flex-col justify-start items-center text-wrapper_3">
            <text class="font text_4">C...</text>
          </view>
        </view>
      </view>
    </view>
    <view class="flex-row justify-between section_2">
      <image
        class="image_6"
        src="/static/09ae131aa1c5d8b305c9fdc3d0d758c5.png"
      />
      <view class="flex-col justify-start items-center relative image-wrapper">
        <image
          class="shrink-0 image_7"
          src="/static/122f05e3f43319d15ad23bbffa257203.png"
        />
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
  .page {
    padding: 125.95rpx 40.08rpx 43.89rpx;
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
  .image_2 {
    width: 68.7rpx;
    height: 68.7rpx;
  }
  .image_3 {
    margin-top: 20.99rpx;
  }
  .font {
    font-size: 45.8rpx;
    font-family: STIX Two Text;
    line-height: 30.73rpx;
    font-weight: 600;
    color: #ffffff;
  }
  .text {
    margin-top: 30.53rpx;
    color: #000000;
    line-height: 43.74rpx;
  }
  .image_4 {
    margin-right: 22.9rpx;
  }
  .group {
    margin-top: 34.35rpx;
    padding: 0 9.54rpx;
  }
  .image_5 {
    width: 91.6rpx;
    height: 91.6rpx;
  }
  .section {
    margin-right: 5.73rpx;
    padding: 26.72rpx 15.27rpx 36.26rpx;
    background-color: #cbe8e3;
    border-radius: 28.63rpx;
    height: 261.45rpx;
  }
  .text_2 {
    color: #000000;
    font-size: 38.17rpx;
    font-family: STIX Two Text;
    font-weight: 600;
    line-height: 40.08rpx;
    width: 446.56rpx;
  }
  .text-wrapper {
    padding: 26.72rpx 0 38.17rpx;
    flex: 1 1 148.85rpx;
    background-color: #8faadc;
    border-radius: 28.63rpx;
    height: 95.42rpx;
  }
  .text-wrapper_2 {
    padding: 30.53rpx 0;
    flex: 1 1 148.85rpx;
    background-color: #8faadc;
    border-radius: 28.63rpx;
    height: 95.42rpx;
  }
  .text_3 {
    line-height: 30.5rpx;
  }
  .text-wrapper_3 {
    padding: 34.35rpx 0 30.53rpx;
    flex: 1 1 148.85rpx;
    background-color: #8faadc;
    border-radius: 28.63rpx;
    height: 95.42rpx;
  }
  .text_4 {
    line-height: 31.18rpx;
  }
  .section_2 {
    margin: 990.46rpx 15.27rpx 0 9.54rpx;
    padding: 0 15.27rpx;
    background-color: #ecf5f2;
    border-radius: 82.06rpx;
    height: 78.24rpx;
  }
  .image_6 {
    border-radius: 190.84rpx;
    width: 76.34rpx;
    height: 76.34rpx;
  }
  .image-wrapper {
    margin: -15.27rpx 15.27rpx -15.27rpx 0;
    padding: 30.53rpx 0;
    border-radius: 30.53rpx;
    overflow: hidden;
    background-color: #cbe8e3;
    box-shadow: 0rpx 1.91rpx 5.73rpx #0000004d, 0rpx 7.63rpx 15.27rpx 5.73rpx #00000026;
    width: 106.87rpx;
    height: 106.87rpx;
  }
  .image_7 {
    width: 45.8rpx;
    height: 45.8rpx;
  }
</style>