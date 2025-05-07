<template>
  <view class="flex-col page">
    <view class="flex-col flex-1 group_14">
      <view class="flex-row justify-evenly group" @click="onClick">
        <view class="flex-col items-start">
          <text class="font text">我的</text>
          <image
            class="image mt-13"
            src="/static/1f5a9f49764f87f496109f039ea1dc99.png"
          />
        </view>
        <view class="flex-col items-start self-start group_2">
          <text class="font text_2">上上签</text>
          <text class="font_2 text_3 mt-23">ID：2024XXXXX</text>
        </view>
        <image
          class="self-start image_2"
          src="/static/fad689b68edea48b71e2c5f4e5a59220.png"
        />
      </view>
      <view class="flex-col justify-start mt-19">
        <view class="flex-col group_3">
          <view class="flex-col justify-start section">
            <view class="flex-row equal-division">
              <view class="flex-col items-center group_4 group_12">
                <text class="font_3">2</text>
                <text class="font_2 mt-14">我丢失的</text>
              </view>
              <view class="flex-col items-center group_4 group_13">
                <text class="font_3 text_1">4</text>
                <text class="font_2 text_13 mt-14">我捡到的</text>
              </view>
            </view>
          </view>
          <view class="flex-col justify-start group_5 mt-21">
            <view class="flex-col relative section_2">
              <view class="flex-col">
                <view class="flex-row items-center">
                  <image
                    class="image_3"
                    src="/static/d494c31366e24c2b0c8a8ab02ab26980.png"
                  />
                  <text class="font_4 text_4 ml-14">我的图文</text>
                </view>
                <view class="flex-row items-center mt-20">
                  <image
                    class="image_3"
                    src="/static/290f26134aeb48954e88c86e31233844.png"
                  />
                  <text class="font_4 text_5 ml-13">浏览历史</text>
                </view>
                <view class="flex-row items-center mt-20">
                  <image
                    class="image_3"
                    src="/static/d36892f07680642f880ca5691fada540.png"
                  />
                  <text class="font_4 text_6 ml-14">小黑屋</text>
                </view>
              </view>
              <view class="flex-row items-center group_8 mt-26">
                <image
                  class="image_4"
                  src="/static/1fc311498507437fed66b3cbca415404.png"
                />
                <text class="font_4 ml-17">隐私保护</text>
              </view>
              <view class="flex-col mt-26">
                <view class="flex-row items-center">
                  <image
                    class="image_3"
                    src="/static/374c153445dabf5d79e219717aa5f46a.png"
                  />
                  <text class="font_4 ml-13">设置</text>
                </view>
                <view class="flex-row items-center mt-20">
                  <image
                    class="image_3"
                    src="/static/bf10f815776539f42234dc11c95cd64e.png"
                  />
                  <text class="font_4 text_7 ml-13">关于</text>
                </view>
              </view>
            </view>
          </view>
        </view>
      </view>
    </view>
    <view class="flex-col justify-start section_3">
      <view class="flex-row equal-division_2">
        <view class="flex-col items-center group_6 group_9" @click="onClick_1">
          <image
            class="shrink-0 image_5"
            src="/static/b81115432643f33c3a7fc5837f01be47.png"
          />
          <text class="font_5 text_10">主页</text>
        </view>
        <view class="flex-col items-center group_6 group_10" @click="onClick_2">
          <image
            class="shrink-0 image_5"
            src="/static/a0d2925376f3a6fa664905443fecccaf.png"
          />
          <text class="font_5 text_11">消息</text>
        </view>
        <view class="flex-col items-center group_6 group_11">
          <image
            class="shrink-0 image_5"
            src="/static/b5c5b240dc45624d009ac0260b9834c1.png"
          />
          <text class="font_5 text_12">我的</text>
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
        uni.navigateTo({ url: '/pages/gerenxinxi/gerenxinxi' });
      },
      onClick_1() {
        uni.navigateTo({ url: '/pages/zhuye/zhuye' });
      },
      onClick_2() {
        uni.navigateTo({ url: '/pages/xiaoxi/xiaoxi' });
      },
    },
  };
</script>

<style scoped lang="css">
  .mt-13 {
    margin-top: 24.81rpx;
  }
  .mt-23 {
    margin-top: 43.89rpx;
  }
  .mt-19 {
    margin-top: 36.26rpx;
  }
  .mt-21 {
    margin-top: 40.08rpx;
  }
  .ml-17 {
    margin-left: 32.44rpx;
  }
  .ml-13 {
    margin-left: 24.81rpx;
  }
  .page {
    background-color: #ffffff;
    width: 100%;
    overflow-y: auto;
    overflow-x: hidden;
    height: 100%;
  }
  .group_14 {
    padding-top: 105.76rpx;
    overflow-y: auto;
  }
  .group {
    padding: 0 34.35rpx;
  }
  .font {
    font-size: 61.07rpx;
    font-family: Microsoft YaHei;
    line-height: 58.63rpx;
    font-weight: 700;
    color: #000000;
  }
  .text {
    margin-left: 14.39rpx;
  }
  .image {
    width: 244.27rpx;
    height: 244.27rpx;
  }
  .group_2 {
    margin-top: 150.59rpx;
  }
  .text_2 {
    line-height: 56.83rpx;
  }
  .font_2 {
    font-size: 38.17rpx;
    font-family: Microsoft YaHei;
    line-height: 36.79rpx;
    font-weight: 700;
    color: #000000;
  }
  .text_3 {
    margin-left: 7.25rpx;
    line-height: 29.87rpx;
  }
  .image_2 {
    margin-top: 161.41rpx;
    width: 38.17rpx;
    height: 74.43rpx;
  }
  .group_3 {
    padding: 0 47.71rpx 38.17rpx;
  }
  .section {
    margin-right: 3.82rpx;
    padding: 19.22rpx 0 25rpx;
    background-color: #cbe8e3;
    border-radius: 28.63rpx;
  }
  .equal-division {
    padding: 0 22.86rpx;
  }
  .group_4 {
    flex: 1 1 301.53rpx;
  }
  .group_12 {
    padding: 10rpx 0;
  }
  .font_3 {
    font-size: 68.7rpx;
    font-family: Microsoft YaHei;
    line-height: 52.84rpx;
    font-weight: 700;
    color: #000000;
  }
  .group_13 {
    padding: 10.88rpx 0 10.15rpx;
  }
  .text_1 {
    line-height: 51.97rpx;
  }
  .text_13 {
    line-height: 36.64rpx;
  }
  .group_5 {
    margin-right: 3.82rpx;
    padding-bottom: 24.81rpx;
    overflow: hidden;
  }
  .section_2 {
    margin-top: -7.63rpx;
    padding: 19.08rpx 59.16rpx 20.99rpx 59.16rpx;
    background-color: #cbe8e3;
    border-radius: 28.63rpx;
  }
  .image_3 {
    width: 80.15rpx;
    height: 80.15rpx;
  }
  .font_4 {
    font-size: 45.8rpx;
    font-family: Microsoft YaHei;
    line-height: 44.37rpx;
    font-weight: 700;
    color: #000000;
  }
  .text_4 {
    line-height: 44.33rpx;
  }
  .text_5 {
    line-height: 44.77rpx;
  }
  .text_6 {
    line-height: 44.2rpx;
  }
  .group_8 {
    padding: 0 5.73rpx;
  }
  .image_4 {
    width: 68.7rpx;
    height: 68.7rpx;
  }
  .text_7 {
    line-height: 44.41rpx;
  }
  .section_3 {
    padding: 16.72rpx 0 25.8rpx;
    background-image: url('/static/9ef58bfca3448fc325d82a62ab2ca15f.png');
    background-size: 100% 100%;
    background-repeat: no-repeat;
  }
  .equal-division_2 {
    padding: 0 21.91rpx;
  }
  .group_6 {
    flex: 1 1 234.73rpx;
  }
  .group_9 {
    padding: 4.35rpx 0 10rpx;
  }
  .image_5 {
    width: 80rpx;
    height: 80rpx;
  }
  .font_5 {
    font-size: 30.53rpx;
    font-family: Microsoft YaHei;
    line-height: 29.37rpx;
    color: #000000;
  }
  .text_10 {
    margin-top: -6.35rpx;
    line-height: 29.79rpx;
  }
  .group_10 {
    padding: 4.35rpx 0 10.44rpx;
  }
  .text_11 {
    margin-top: -6.37rpx;
  }
  .group_11 {
    padding: 4.35rpx 0 10.42rpx;
  }
  .text_12 {
    margin-top: -6.24rpx;
    line-height: 29.26rpx;
  }
</style>