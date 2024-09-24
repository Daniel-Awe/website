<template>
  <div class="background">
    <div class="body">
      <div class="body-banner">
        <div class="image">
          <img src="./assets/pictures/Maranatha.jpg" style="width: 1000px" class="img-responsive" alt="Image" />
        </div>
        <div class="tips">“因为还有一点点时候，那要来的就来，并不迟延...”</div>
        <div class="tips">“We love because he first loved us.”</div>
      </div>
      <div class="body-content">
        <h1>Daniel =></h1>
        <div class="work">
          <div class="img">
            <img style="width: 100%; height: 100%" src="./assets/pictures/PhoneBrand.png" alt="" />
          </div>
          <div class="intro">
            <div class="title">Cool -- 手机品牌网站</div>
            <div class="text">
              HTML5课程期末作品，前后耗时两个月完成。使用Swiper.js、Bootstrap.js、jQuery.js等插件与工具，实现简单的登录、购物车等功能，以及丝滑的页面动画效果。
              <br />
              技术栈：HTML5 + CSS + Javascript + Less + jQuery
            </div>
            <div class="enter">
              <a href="./pages/Iphone/index.html"><div class="button">></div></a>
            </div>
          </div>
        </div>
        <div class="work2">
          <div class="intro">
            <div class="title">Ai - 浙江省多媒体竞赛作品</div>
            <div class="text">
              2023浙江省多媒体设计作品大赛参赛作品，使用Vue3框架完成项目建设，实现了题库做题、题目收藏、做题报告等功能
              <br />
              技术栈：HTML5 + Vue.js + Vue CLI + VueRouter + Vuex + Scss + Node.js + MySQL
            </div>
            <div class="enter">
              <a href="./pages/Ai/index.html"><div class="button">></div></a>
            </div>
          </div>
          <div class="img">
            <img style="width: 100%; height: 100%" src="./assets/pictures/AiProject.png" alt="" />
          </div>
        </div>
        <div class="work">
          <div class="img">
            <img style="width: 100%; height: 100%" src="./assets/pictures/Love.png" alt="" />
          </div>
          <div class="intro">
            <div class="title">Love - 爱心</div>
            <div class="text">
              Love never fails
              <br />
              技术栈：HTML5 + CSS + Javascript
            </div>
            <div class="enter">
              <a href="./pages/Love/love.html"><div class="button">></div></a>
            </div>
          </div>
        </div>
        <div class="work2">
          <div class="intro">
            <div class="title">Echarts - 数据可视化</div>
            <div class="text">
              哈哈哈哈哈哈哈...
              <br />
              技术栈：HTML5 + CSS + Javascript + echarts
            </div>
            <div class="enter">
              <a href="./pages/Echarts/Echarts.html"><div class="button">></div></a>
            </div>
          </div>
          <div class="img">
            <img style="width: 100%; height: 100%" src="./assets/pictures/Echarts.png" alt="" />
          </div>
        </div>
      </div>
      <div class="body-video">
        <h1>Videos =></h1>
        <div class="videoBox">
          <div class="box">
            <div class="v">
              <video src="./assets/videos/美善力量.mp4" style="width: 100%; height: 100%" controls></video>
            </div>
            <div class="content">
              <div class="title">tianfu美善力量</div>
              <div class="text">We love because he first loved us.</div>
            </div>
          </div>
          <div class="box">
            <div class="v">
              <video src="./assets/videos/玉漏沙残时将尽.mp4" style="width: 100%; height: 100%" controls></video>
            </div>
            <div class="content">
              <div class="title">玉漏沙残时将尽</div>
              <div class="text">
                惟愿他快来黑影全飞散 <br />
                见他如朝鹿显在比特山
              </div>
            </div>
          </div>
          <div class="box">
            <div class="v">
              <video src="./assets/videos/瓦器里有宝贝.mp4" style="width: 100%; height: 100%" controls></video>
            </div>
            <div class="content">
              <div class="title">瓦器里有宝贝</div>
              <div class="text">|| Corinthians 4:7</div>
            </div>
          </div>
          <div class="box">
            <div class="v">
              <video src="./assets/videos/佳偶的歌.mp4" style="width: 100%; height: 100%" controls></video>
            </div>
            <div class="content">
              <div class="title">佳偶的歌</div>
              <div class="text">
                你的膏油馨香； 你的名如同倒出来的香膏，<br />
                我们要称赞你的爱情，胜似称赞美酒。
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="bottom">©酷欧 2021-2022 版权所有 | 隐私政策 | 用户协议 | 营业执照 | <a href="https://beian.miit.gov.cn/">浙ICP备2023014283号-1</a></div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
  components: {},
  data() {
    return {
      account: '',
      password: '',
      code: '',
    }
  },
}
</script>

<style lang="scss">
a {
  text-decoration: none;
  color: #000;
}
html,
body {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.background {
  position: relative;
  width: 100vw;
  margin: 0;
  padding: 0;
  background: rgba(31, 205, 48, 0.2);
  .mop {
    position: fixed;
    left: 0;
    top: 0;
    width: 100vw;
    height: 100vh;
    // background: rgba(31, 205, 48, 0.2);
    z-index: 0;
  }
  .body {
    width: 1150px;
    margin: 0 auto;
    z-index: 10;
    background: #fff;
    padding: 50px 30px;

    .body-banner {
      margin: 0 auto;
      width: 1000px;

      .image {
        width: 1000px;
        height: 445px;
        border-radius: 20px;
        overflow: hidden;
      }
      image {
        width: 1000px;
      }
      .tips {
        margin-top: 10px;
        font-style: italic;
      }
    }
    h1 {
      font-weight: 500;
      font-size: 56px;
      font-family: 'YuZhou';
    }
    .body-video {
      padding: 50px 80px;
      .box {
        display: flex;
        margin: 40px 0;
        .v {
          border-radius: 20px;
          overflow: hidden;
          width: 500px;
          margin-right: 5%;
        }
        .content {
          .title {
            font-size: 36px;
            font-family: 'HaiSong';
            margin: 20px 0;
          }
          .text {
            font-family: 'YuZhou';
            font-size: 22px;
          }
        }
      }
    }
    .body-content {
      padding: 50px 80px;

      .work {
        display: flex;
        margin: 50px 0;
        .img {
          border-radius: 20px;
          overflow: hidden;
          width: 43%;
          margin-right: 5%;
        }
        .intro {
          width: 52%;
          .title {
            font-size: 36px;
            font-family: 'HaiSong';
            margin-bottom: 20px;
          }
          .text {
            font-family: 'YuZhou';
            line-height: 34px;
          }
          .enter {
            display: flex;
            justify-content: end;
            .button {
              margin: 0.25rem 0.25rem 0 0;
              width: 66px;
              height: 38px;
              text-align: center;
              line-height: 34px;
              font-family: 'YuZhou';
              border-radius: 24px;
              border: 5px solid rgba(31, 205, 48, 0.2);
              background: #fff;
              cursor: pointer;
              font-size: 24px;
              font-weight: 700;
              transform: scale(1);
              transition: transform 0.25s ease-in-out;
            }
            .button:hover {
              transform: scale(1.1);
            }
          }
        }
      }
      .work2 {
        display: flex;
        margin: 50px 0;
        .img {
          border-radius: 20px;
          overflow: hidden;
          width: 43%;
        }
        .intro {
          width: 52%;
          margin-right: 5%;
          .title {
            font-size: 36px;
            font-family: 'HaiSong';
            margin-bottom: 20px;
          }
          .text {
            font-family: 'YuZhou';

            line-height: 34px;
          }
          .enter {
            display: flex;
            justify-content: end;
            .button {
              margin: 0.25rem 0.25rem 0 0;
              width: 66px;
              height: 38px;
              text-align: center;
              line-height: 34px;
              font-family: 'YuZhou';
              border-radius: 24px;
              border: 5px solid rgba(31, 205, 48, 0.2);
              background: #fff;
              cursor: pointer;
              font-size: 24px;
              font-weight: 700;
              transform: scale(1);
              transition: transform 0.25s ease-in-out;
            }
            .button:hover {
              transform: scale(1.1);
            }
          }
        }
      }
    }
  }
  .bottom {
    width: fit-content;
    padding: 30px 0;
    margin: 0 auto;
    font-family: 'HaiSong';
  }
}
</style>
