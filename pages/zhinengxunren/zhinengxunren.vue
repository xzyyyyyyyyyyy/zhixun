<template>
  <view class="flex-col page">
    <view class="flex-col">
      <view class="flex-row">
        <image
          class="image"
          src="/static/a5424564109f254ec41206c1aad87b61.png"
          @click="onClick"
        />
        <image
          class="self-start image_2 ml-10"
          src="/static/36b2fb14331810b74b19aef1c594179e.png"
        />
        <text class="self-start font text ml-10">智能寻人</text>
      </view>
      <view class="flex-col mt-19">
        <view class="flex-row self-stretch group">
          <image
            class="shrink-0 self-start image_3"
            src="/static/1c2095f1952de3d6d4c7625caae6916a.png"
          />
          <view class="flex-col justify-start flex-1 text-wrapper ml-9">
            <text class="font text_2">
              感谢您对智寻的信任！现在我们要开始寻找您的好友，现需要您提供相关信息以更好寻人。我们承诺，您提供的信息不会泄露，仅用于信息匹配和筛选范围。
            </text>
          </view>
        </view>
        <view class="self-end section"></view>
        <view class="flex-row self-stretch group_2">
          <image
            class="self-start image_3"
            src="/static/1c2095f1952de3d6d4c7625caae6916a.png"
          />
          <view class="self-center section_2 ml-5"></view>
        </view>
      </view>
    </view>
    <view class="flex-row justify-between section_3 mt-265">
      <image
        class="image_4"
        src="/static/09ae131aa1c5d8b305c9fdc3d0d758c5.png"
      />
      <view class="flex-col justify-start items-center relative image-wrapper">
        <image
          class="shrink-0 image_5"
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

    methods: {
      onClick() {
        uni.navigateBack();
      },
    },
  };
</script>

<style scoped lang="css">
  .mt-19 {
    margin-top: 36.26rpx;
  }
  .ml-9 {
    margin-left: 17.18rpx;
  }
  .ml-5 {
    margin-left: 9.54rpx;
  }
  .mt-265 {
    margin-top: 505.73rpx;
  }
  .page {
    padding: 125.95rpx 40.08rpx 43.89rpx 40.08rpx;
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
    margin-top: 20.99rpx;
    width: 68.7rpx;
    height: 68.7rpx;
  }
  .font {
    font-size: 45.8rpx;
    font-family: STIX Two Text;
    color: #000000;
  }
  .text {
    margin-top: 31.45rpx;
    font-weight: 600;
    line-height: 43.24rpx;
  }
  .group {
    padding: 0 3.82rpx;
  }
  .image_3 {
    width: 91.6rpx;
    height: 91.6rpx;
  }
  .text-wrapper {
    margin-right: 40rpx;
    padding: 41.41rpx 0 65.65rpx;
    background-color: #cbe8e3;
    border-radius: 28.63rpx;
    height: 507.63rpx;
  }
  .text_2 {
    margin-left: 28rpx;
    margin-right: 31.16rpx;
    line-height: 57.25rpx;
  }
  .section {
    margin-right: 122.14rpx;
    background-color: #ecf5f2;
    border-radius: 28.63rpx;
    width: 305.34rpx;
    height: 103.05rpx;
  }
  .group_2 {
    padding-top: 30.53rpx;
  }
  .section_2 {
    background-color: #cbe8e3;
    border-radius: 28.63rpx;
    width: 305.34rpx;
    height: 103.05rpx;
  }
  .section_3 {
    margin-left: 9.54rpx;
    margin-right: 15.27rpx;
    padding: 0 15.27rpx;
    background-color: #ecf5f2;
    border-radius: 82.06rpx;
    height: 78.24rpx;
  }
  .image_4 {
    border-radius: 190.84rpx;
    width: 76.34rpx;
    height: 76.34rpx;
  }
  .image-wrapper {
    margin: -13.36rpx 15.27rpx -15.27rpx 0;
    padding: 30.53rpx 0 30.53rpx;
    border-radius: 30.53rpx;
    overflow: hidden;
    background-color: #cbe8e3;
    box-shadow: 0rpx 1.91rpx 5.73rpx #0000004d, 0rpx 7.63rpx 15.27rpx 5.73rpx #00000026;
    width: 106.87rpx;
    height: 106.87rpx;
  }
  .image_5 {
    width: 45.8rpx;
    height: 45.8rpx;
  }
</style>