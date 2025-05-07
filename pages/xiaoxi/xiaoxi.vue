<template>
  <view class="flex-col page">
    <view class="flex-col flex-1 group_1">
      <view class="flex-row justify-between items-center group">
        <text class="text">消息</text>
        <view class="flex-row group_2">
          <image
            class="image"
            src="/static/5bb2c6cda18bdbc651ab1d1ddce0f47d.png"
          />
          <image
            class="image_2 image_3"
            src="/static/6d88a0565d2f0e52421a5b461b7f6233.png"
          />
          <image
            class="image_2"
            src="/static/b2358b27e79e145bfa8292821b3a5c64.png"
          />
        </view>
      </view>
      <view class="flex-row group_3 mt-35">
        <view class="flex-col shrink-0 group_4">
          <view class="flex-col">
            <view class="flex-col justify-start items-center image-wrapper" @click="onClick">
              <image
                class="image_2"
                src="/static/eac4e244dc5457afdadcbf52d32a4a45.png"
              />
            </view>
            <view class="flex-col group_6">
              <view class="flex-col justify-start items-center image-wrapper_2" @click="onClick_1">
                <image
                  class="image_2"
                  src="/static/7386d321c350fdd2c9edf9280da6e65c.png"
                />
              </view>
              <view class="flex-col justify-start items-center image-wrapper_3 mt-20">
                <image
                  class="image_2"
                  src="/static/3689efc0e07c1c298f4322517905aa69.png"
                />
              </view>
              <view class="flex-col justify-start items-center image-wrapper_4 mt-20">
                <image
                  class="image_2"
                  src="/static/d60cb8859f2d9d673c2e3d5d0d1a9fb6.png"
                />
              </view>
            </view>
          </view>
          <image
            class="image_4 mt-24"
            src="/static/f4d829143ddfb1a832e096065e21adbb.png"
          />
        </view>
        <view class="flex-col flex-1 self-start group_5 ml-18">
          <text class="self-start font text_2" @click="onClick_2">系统消息</text>
          <text class="self-start font text_3" @click="onClick_3">我的客服</text>
          <text class="self-start font text_4">提到了我</text>
          <text class="self-start font text_5">我收到的赞</text>
          <view class="flex-col items-start self-stretch group_7">
            <text class="font text_6">Lifetime（江翔）</text>
            <text class="text_7 mt-20">你好，请问是你捡到了我的身份证吗</text>
          </view>
        </view>
      </view>
    </view>
    <view class="flex-col justify-start section">
      <view class="flex-row equal-division">
        <view class="flex-col items-center group_8 group_9" @click="onClick_4">
          <image
            class="shrink-0 image_5"
            src="/static/b81115432643f33c3a7fc5837f01be47.png"
          />
          <text class="font_2 text_8">主页</text>
        </view>
        <view class="flex-col items-center group_8 group_10">
          <image
            class="shrink-0 image_5"
            src="/static/a0d2925376f3a6fa664905443fecccaf.png"
          />
          <text class="font_2 text_9">消息</text>
        </view>
        <view class="flex-col items-center group_8 group_11" @click="onClick_5">
          <image
            class="shrink-0 image_5"
            src="/static/d04fb7b19dcdfe8635c03290118348c2.png"
          />
          <text class="font_2 text_10">我的</text>
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

    methods: {
      onClick() {
        uni.navigateTo({ url: '/pages/xitongtongzhi/xitongtongzhi' });
      },
      onClick_1() {
        uni.navigateTo({ url: '/pages/wodekefu/wodekefu' });
      },
      onClick_2() {
        uni.navigateTo({ url: '/pages/xitongtongzhi/xitongtongzhi' });
      },
      onClick_3() {
        uni.navigateTo({ url: '/pages/wodekefu/wodekefu' });
      },
      onClick_4() {
        uni.navigateTo({ url: '/pages/zhuye/zhuye' });
      },
      onClick_5() {
        uni.navigateTo({ url: '/pages/wode/wode' });
      },
    },
  };
</script>

<style scoped lang="css">
  .mt-35 {
    margin-top: 66.79rpx;
  }
  .page {
    background-color: #ffffff;
    width: 100%;
    overflow-y: auto;
    overflow-x: hidden;
    height: 100%;
  }
  .group_1 {
    padding: 98.47rpx 0 452.29rpx;
    overflow-y: auto;
  }
  .group {
    padding: 0 38.7rpx;
  }
  .text {
    color: #000000;
    font-size: 76.34rpx;
    font-family: STIX Two Text;
    font-weight: 600;
    line-height: 72.44rpx;
  }
  .group_2 {
    margin-right: 5.19rpx;
  }
  .image {
    width: 68.7rpx;
    height: 66.79rpx;
  }
  .image_2 {
    width: 68.7rpx;
    height: 68.7rpx;
  }
  .image_3 {
    margin-left: 17.18rpx;
  }
  .group_3 {
    padding-left: 59.16rpx;
    padding-right: 43.84rpx;
  }
  .group_4 {
    width: 122.14rpx;
  }
  .image-wrapper {
    padding: 26.72rpx 0 26.72rpx;
    background-image: url('/static/7a048ff3fd254e6a604e2f66430e24ff.png');
    background-size: 100% 100%;
    background-repeat: no-repeat;
  }
  .group_6 {
    padding-top: 38.17rpx;
  }
  .image-wrapper_2 {
    padding: 26.72rpx 0 26.72rpx;
    background-image: url('/static/c59818ea7f1a25d5d3f132ab6ccbc718.png');
    background-size: 100% 100%;
    background-repeat: no-repeat;
  }
  .image-wrapper_3 {
    padding: 26.72rpx 0 26.72rpx;
    background-image: url('/static/da5ed90fbc225d210b6920b99373ea7c.png');
    background-size: 100% 100%;
    background-repeat: no-repeat;
  }
  .image-wrapper_4 {
    padding: 26.72rpx 0 26.72rpx;
    background-color: #d9d9d9;
    border-radius: 50%;
  }
  .image_4 {
    width: 122.14rpx;
    height: 122.14rpx;
  }
  .group_5 {
    margin-top: 50.31rpx;
  }
  .font {
    font-size: 45.8rpx;
    font-family: STIX Two Text;
    line-height: 43.32rpx;
    font-weight: 600;
    color: #000000;
  }
  .text_2 {
    margin-left: 30.59rpx;
    line-height: 43.78rpx;
  }
  .text_3 {
    margin-left: 27.04rpx;
    margin-top: 109.35rpx;
    line-height: 43.24rpx;
  }
  .text_4 {
    margin-left: 26.68rpx;
    margin-top: 109.52rpx;
    line-height: 43.15rpx;
  }
  .text_5 {
    margin-left: 4.45rpx;
    margin-top: 109.43rpx;
  }
  .group_7 {
    margin-top: 91.72rpx;
  }
  .text_6 {
    margin-left: 5.42rpx;
    line-height: 44.01rpx;
  }
  .text_7 {
    color: #d9d9d9;
    font-size: 30.53rpx;
    font-family: STIX Two Text;
    font-weight: 600;
    line-height: 30.5rpx;
  }
  .section {
    padding: 16.72rpx 0 25.8rpx;
    background-image: url('/static/9ef58bfca3448fc325d82a62ab2ca15f.png');
    background-size: 100% 100%;
    background-repeat: no-repeat;
  }
  .equal-division {
    padding: 0 21.91rpx;
  }
  .group_8 {
    flex: 1 1 234.73rpx;
  }
  .group_9 {
    padding: 4.35rpx 0 10rpx;
  }
  .image_5 {
    width: 80rpx;
    height: 80rpx;
  }
  .font_2 {
    font-size: 30.53rpx;
    font-family: Microsoft YaHei;
    line-height: 29.79rpx;
    color: #000000;
  }
  .text_8 {
    margin-top: -6.35rpx;
  }
  .group_10 {
    padding: 4.35rpx 0 10.44rpx;
  }
  .text_9 {
    margin-top: -6.37rpx;
    line-height: 29.37rpx;
  }
  .group_11 {
    padding: 4.35rpx 0 10.42rpx;
  }
  .text_10 {
    margin-top: -6.24rpx;
    line-height: 29.26rpx;
  }
</style>