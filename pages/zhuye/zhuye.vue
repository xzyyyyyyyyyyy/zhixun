<template>
  <view class="flex-col page">
    <view class="flex-col flex-1 group_8">
      <view class="flex-col self-stretch group">
        <view class="flex-row">
          <view class="flex-col items-center shrink-0 section">
            <text class="text">地区</text>
            <image
              class="image_2 mt-3"
              src="/static/bc5fa6324bfbc36c7bc4ee93aa523c97.png"
            />
          </view>
          <view class="flex-col justify-start items-end flex-1 image-wrapper ml-6" @click="onClick">
            <image
              class="image"
              src="/static/8bd421df2e210c668375325e341ceebb.png"
            />
          </view>
        </view>
        <view class="flex-row equal-division">
          <view class="flex-col justify-start equal-division-item section_2">
            <view class="flex-col items-center section_3" @click="onClick_1">
              <text class="font">我要</text>
              <text class="font mt-41">寻物</text>
            </view>
          </view>
          <view class="flex-col justify-start equal-division-item section_5 ml-23">
            <view class="flex-col items-center section_4" @click="onClick_2">
              <text class="font">我要</text>
              <text class="font mt-42">找人</text>
            </view>
          </view>
        </view>
        <view class="flex-col section_6">
          <view class="flex-col">
            <view class="flex-row items-center self-stretch">
              <image
                class="equal-division-item_2"
                src="/static/5d399264c4026b0933524a2f96ec7f66.png"
              />
              <view class="flex-col items-start ml-11">
                <text class="font_2">Pluto</text>
                <text class="font_2">36 分钟前</text>
              </view>
            </view>
            <text class="self-start font_3 text_2 mt-10">风华园，蔡明伟，手机都不要啦</text>
            <image
              class="self-start image_4 mt-10"
              src="/static/3ce89ff2c18e4d14d52cfa8d8d17bcf0.png"
            />
          </view>
          <view class="flex-col mt-23">
            <view class="flex-row justify-evenly self-stretch">
              <view class="flex-col justify-start items-center text-wrapper">
                <text class="font_2 text_3">IPhone 15 Pro</text>
              </view>
              <view class="flex-col justify-start text-wrapper_2">
                <text class="font_4 text_4">16:30左右找到</text>
              </view>
              <view class="flex-col justify-start items-center text-wrapper_3"><text class="font_4">风华园</text></view>
            </view>
            <view class="flex-row justify-between equal-division_2 group_2 mt-3">
              <image
                class="equal-division-item_2"
                src="/static/5834664a37997d9f4abbdcd208a21e19.png"
              />
              <image
                class="equal-division-item_2"
                src="/static/a49d75a836b0d71e382a665b45170830.png"
              />
              <image
                class="equal-division-item_1"
                src="/static/619670036979a7ead647827166f4f3d6.png"
              />
            </view>
          </view>
        </view>
      </view>
      <view class="flex-col justify-start self-center group_3 mt-12">
        <view class="flex-col section_7">
          <view class="flex-row items-center">
            <image
              class="equal-division-item_2"
              src="/static/75f8d7b10dab26de4855ff7bdbf05ad3.png"
            />
            <view class="flex-col items-start ml-9">
              <text class="font_2">CT橙</text>
              <text class="font_2">45 分钟前</text>
            </view>
          </view>
          <text class="font_3 text_5 mt-7">
            有没有宝子的车是凤凰牌，蓝色，里面有根古茗吸管纸的，停在一期。就是非常非常对不起，我们的车一模一样锁也一样，我今天晚上去教室的时候没注意看，用钥匙一下就打开了，然后准备骑回来的时候发现打不开没办法把车骑回来就以为是锁坏了，在教学楼试了一个小时，结果回来之后发现自己的车还停在一期，才知道骑错，现在车停在教三门口，宝子看到联系我一下，看看要怎么处理?真的对不起
          </text>
        </view>
      </view>
    </view>
    <view class="flex-col justify-start section_8">
      <view class="flex-row equal-division_3">
        <view class="flex-col items-center group_4 group_1">
          <image
            class="shrink-0 image_5"
            src="/static/1c20b0ccd01f4f01e6801f0a84caa4be.png"
          />
          <text class="font_3 text_6">主页</text>
        </view>
        <view class="flex-col items-center group_4 group_5" @click="onClick_3">
          <image
            class="shrink-0 image_5"
            src="/static/a0d2925376f3a6fa664905443fecccaf.png"
          />
          <text class="font_3 text_7">消息</text>
        </view>
        <view class="flex-col items-center group_4 group_6" @click="onClick_4">
          <image
            class="shrink-0 image_5"
            src="/static/d04fb7b19dcdfe8635c03290118348c2.png"
          />
          <text class="font_3 text_8">我的</text>
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
        uni.navigateTo({ url: '/pages/sousuo/sousuo' });
      },
      onClick_1() {
        uni.navigateTo({ url: '/pages/woyaoxunwu/woyaoxunwu' });
      },
      onClick_2() {
        uni.navigateTo({ url: '/pages/zhinengxunren/zhinengxunren' });
      },
      onClick_3() {
        uni.navigateTo({ url: '/pages/xiaoxi/xiaoxi' });
      },
      onClick_4() {
        uni.navigateTo({ url: '/pages/wode/wode' });
      },
    },
  };
</script>

<style scoped lang="css">
  .mt-41 {
    margin-top: 78.24rpx;
  }
  .ml-23 {
    margin-left: 43.89rpx;
  }
  .ml-11 {
    margin-left: 20.99rpx;
  }
  .mt-23 {
    margin-top: 43.89rpx;
  }
  .mt-3 {
    margin-top: 5.73rpx;
  }
  .ml-9 {
    margin-left: 17.18rpx;
  }
  .mt-7 {
    margin-top: 13.36rpx;
  }
  .page {
    background-color: #ffffff;
    width: 100%;
    overflow-y: auto;
    overflow-x: hidden;
    height: 100%;
  }
  .group_8 {
    padding-top: 127.86rpx;
    overflow-y: auto;
  }
  .group {
    padding-left: 45.8rpx;
    padding-right: 43.89rpx;
  }
  .section {
    padding: 27.54rpx 0 7.63rpx;
    filter: drop-shadow(0rpx 7.63rpx 3.82rpx #00000040);
    background-color: #cbe8e3;
    border-radius: 28.63rpx;
    width: 164.12rpx;
    height: 95.42rpx;
  }
  .text {
    color: #000000;
    font-size: 38.17rpx;
    font-family: Microsoft YaHei;
    line-height: 35.27rpx;
  }
  .image_2 {
    width: 38.17rpx;
    height: 19.08rpx;
  }
  .image-wrapper {
    margin-right: 3.82rpx;
    padding: 24.81rpx 0;
    background-color: #ecf5f2;
    border-radius: 38.17rpx;
    box-shadow: 0rpx 7.63rpx 7.63rpx #00000040;
    height: 95.42rpx;
  }
  .image {
    margin-right: 30.53rpx;
    width: 49.62rpx;
    height: 45.8rpx;
  }
  .equal-division {
    margin-left: 5.73rpx;
    margin-top: 15.27rpx;
  }
  .equal-division-item {
    flex: 1 1 305.34rpx;
  }
  .section_2 {
    background-image: url('/static/0a3c5c68cbcbf5740bac8197fe67c9ed.png');
    background-size: 100% 100%;
    background-repeat: no-repeat;
    height: 303.44rpx;
  }
  .section_3 {
    padding: 79.81rpx 0 65.94rpx;
    background-image: linear-gradient(270deg, #ecf5f299 0%, #b5d2ec99 37.5%);
    border-radius: 28.63rpx;
    box-shadow: 0rpx 7.63rpx 7.63rpx #00000040;
  }
  .font {
    font-size: 91.6rpx;
    font-family: Microsoft YaHei;
    line-height: 40.08rpx;
    color: #000000;
  }
  .section_5 {
    background-image: url('/static/0ceab1555510c7259560e652286885b6.png');
    background-size: 100% 100%;
    background-repeat: no-repeat;
    height: 303.44rpx;
  }
  .section_4 {
    margin-right: 3.82rpx;
    padding: 74.08rpx 0 70.95rpx;
    background-image: linear-gradient(270deg, #ecf5f299 0%, #ee874199 77%);
    border-radius: 28.63rpx;
    box-shadow: 0rpx 7.63rpx 7.63rpx #00000040;
  }
  .section_6 {
    margin: 24.81rpx 3.82rpx 0 5.73rpx;
    padding: 17.77rpx 24.81rpx 11.45rpx 24.81rpx;
    background-color: #ecf5f2;
    border-radius: 28.63rpx;
  }
  .equal-division-item_2 {
    width: 68.7rpx;
    height: 68.7rpx;
  }
  .font_2 {
    font-size: 26.72rpx;
    font-family: Microsoft YaHei;
    line-height: 40.08rpx;
    color: #000000;
  }
  .font_3 {
    font-size: 30.53rpx;
    font-family: Microsoft YaHei;
    line-height: 29.37rpx;
    color: #000000;
  }
  .text_2 {
    margin-left: 10.06rpx;
    line-height: 29.75rpx;
  }
  .image_4 {
    margin-left: 9.54rpx;
    width: 179.39rpx;
    height: 246.18rpx;
  }
  .text-wrapper {
    padding: 18.72rpx 0 16.81rpx;
    background-color: #d9d9d9;
    border-radius: 28.63rpx;
    width: 229.01rpx;
    height: 57.25rpx;
  }
  .text_3 {
    line-height: 21.72rpx;
  }
  .text-wrapper_2 {
    margin-top: 3.82rpx;
    padding: 13.97rpx 0 13.82rpx;
    background-color: #d9d9d9;
    border-radius: 28.63rpx;
    height: 53.44rpx;
  }
  .font_4 {
    font-size: 26.72rpx;
    font-family: Microsoft YaHei;
    line-height: 25.94rpx;
    color: #000000;
  }
  .text_4 {
    margin-left: 18.34rpx;
    margin-right: 17.92rpx;
    line-height: 25.65rpx;
  }
  .text-wrapper_3 {
    padding: 15.84rpx 0 13.57rpx;
    background-color: #d9d9d9;
    border-radius: 28.63rpx;
    width: 108.78rpx;
    height: 55.34rpx;
  }
  .equal-division_2 {
    align-self: center;
  }
  .group_2 {
    width: 458.02rpx;
  }
  .equal-division-item_1 {
    width: 68.7rpx;
    height: 66.79rpx;
  }
  .group_3 {
    margin-bottom: -235.19rpx;
    width: 650.76rpx;
  }
  .section_7 {
    padding: 15.15rpx 20.69rpx 0 30.53rpx;
    background-color: #ecf5f2;
    border-radius: 28.63rpx 28.63rpx 0 0;
    width: 650.76rpx;
  }
  .text_5 {
    line-height: 40.08rpx;
  }
  .section_8 {
    padding: 16.72rpx 0 25.8rpx;
    background-image: url('/static/9ef58bfca3448fc325d82a62ab2ca15f.png');
    background-size: 100% 100%;
    background-repeat: no-repeat;
  }
  .equal-division_3 {
    padding: 0 21.91rpx;
  }
  .group_4 {
    flex: 1 1 234.73rpx;
  }
  .group_1 {
    padding: 4.35rpx 0 10rpx;
  }
  .image_5 {
    width: 80rpx;
    height: 80rpx;
  }
  .text_6 {
    margin-top: -6.35rpx;
    line-height: 29.79rpx;
  }
  .group_5 {
    padding: 4.35rpx 0 10.44rpx;
  }
  .text_7 {
    margin-top: -6.37rpx;
  }
  .group_6 {
    padding: 4.35rpx 0 10.42rpx;
  }
  .text_8 {
    margin-top: -6.24rpx;
    line-height: 29.26rpx;
  }
</style>