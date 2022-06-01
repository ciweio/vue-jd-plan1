<template>
  <div class="top">
    <div class="tl">
      <el-menu
          default-active="2"
          class="el-menu-vertical-demo">
        <el-menu-item index="1">
          <span slot="title">家用电器</span>
        </el-menu-item>
        <el-menu-item index="2">
          <span slot="title">手机/运营商/数码</span>
        </el-menu-item>
        <el-menu-item index="3">
          <span slot="title">电脑/办公</span>
        </el-menu-item>
        <el-menu-item index="1">
          <span slot="title">家居/家具/家装/厨具</span>
        </el-menu-item>
        <el-menu-item index="5">
          <span slot="title">男装/童装/女装/内衣</span>
        </el-menu-item>
        <el-menu-item index="6">
          <span slot="title">食品/酒类/生鲜/特产</span>
        </el-menu-item>
        <el-menu-item index="7">
          <span slot="title">图书/文娱/教育/电子书</span>
        </el-menu-item>
        <el-menu-item index="8">
          <span slot="title">机票/酒店/旅游/生活</span>
        </el-menu-item>
      </el-menu>
    </div>
    <div class="slide1">
      <slide :pics="item1" height="480px" img="true"></slide>
    </div>
    <div class="slide2">
      <slideMin :slides="item2" :img=true></slideMin>
    </div>
    <div class="tr">
      <div class="tr-top">
        <div class="tr-left">
          <el-avatar src="https://cube.elemecdn.com/0/88/03b0d39583f48206768a7534e55bcpng.png"></el-avatar>
        </div>
        <div class="tr-right">
          <p>Hi~欢迎逛京东！</p>
          <p><a>登陆</a> | <a>注册</a></p>
        </div>
      </div>
      <div class="bt-group">
        <el-button size="mini" round style="color: white;background-color: crimson">新人福利</el-button>
        <el-button size="mini" round style="color: #e5d790;background-color: #363634">PLUS会员</el-button>
      </div>
      <div class="divider"></div>
      <div class="tr-mid">
        <span>京东快报</span>
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        <span>更多></span>
        <span class="HOT">HOT</span><span class="context">&nbsp;假日休闲无事可做，巧用vivo X80享受美好瞬间</span>
        <span class="HOT">推荐</span><span class="context">&nbsp;珠江白啤，不可多得国产精酿啤酒！</span>
        <span class="HOT">HOT</span><span class="context">&nbsp;黑白调J101学习椅，更舒适的学习方式</span>
        <span class="HOT">推荐</span><span class="context">&nbsp;科沃斯T10 OMNI：聪明更全能的扫地机器人</span>
      </div>
      <div class="divider"></div>
      <div class="tr-bott">
        <div class="container">
          <div class="block">
            <el-avatar :size="35"
                       src="//m.360buyimg.com/babel/jfs/t1/30057/19/14881/720/5cbf064aE187b8361/eed6f6cbf1de3aaa.png"></el-avatar>
          </div>
          <span>话费</span>
        </div>
        <div class="container">
          <div class="block">
            <el-avatar :size="35"
                       src="//m.360buyimg.com/babel/jfs/t1/36478/38/5384/2901/5cbf065aEb0c60a12/afb4399323fe3b76.png"></el-avatar>
          </div>
          <span>机票</span>
        </div>
        <div class="container">
          <div class="block">
            <el-avatar :size="35"
                       src="//m.360buyimg.com/babel/jfs/t1/31069/34/14642/979/5cbf0665Ec7dc8223/5fee386254dd2ebc.png"></el-avatar>
          </div>
          <span>酒店</span>
        </div>
        <div class="container">
          <div class="block">
            <el-avatar :size="35"
                       src="//m.360buyimg.com/babel/jfs/t1/32403/22/14829/3699/5cbf0674E04723693/caa83ce9b881cd24.png"></el-avatar>
          </div>
          <span>游戏</span>
        </div>
        <div class="container">
          <div class="block">
            <el-avatar :size="35"
                       src="https://m.360buyimg.com/babel/jfs/t1/71890/14/9897/3048/5d7739ddE93eb94f8/f1f6dc5c207329f9.png"></el-avatar>
          </div>
          <span>加油卡</span>
        </div>
        <div class="container">
          <div class="block">
            <el-avatar :size="35"
                       src="https://m.360buyimg.com/babel/jfs/t1/45761/32/10307/1581/5d7739e2Ece4b6671/0004c1b85fbf7bde.png"></el-avatar>
          </div>
          <span>火车票</span>
        </div>
        <div class="container">
          <div class="block">
            <el-avatar :size="35"
                       src="https://m.360buyimg.com/babel/jfs/t1/51584/31/10221/1685/5d7739e7E1adb25cd/1d0957d7f2ae01a2.png"></el-avatar>
          </div>
          <span>众筹</span>
        </div>
        <div class="container">
          <div class="block">
            <el-avatar :size="35"
                       src="https://m.360buyimg.com/babel/jfs/t1/52683/35/10394/3447/5d7739edE270aa7b3/d4d1151b09b5553b.png"></el-avatar>
          </div>
          <span>理财</span>
        </div>
        <div class="container">
          <div class="block">
            <el-avatar :size="35"
                       src="https://m.360buyimg.com/babel/jfs/t1/56296/3/10260/1443/5d7739f3E233abc53/e6976f3cb30c9a8a.png"></el-avatar>
          </div>
          <span>白条</span>
        </div>
        <div class="container">
          <div class="block">
            <el-avatar :size="35"
                       src="https://m.360buyimg.com/babel/jfs/t1/60778/37/9838/3066/5d7739faEd3b7dbb9/dd4d9ef7ce8fc169.png"></el-avatar>
          </div>
          <span>电影票</span>
        </div>
        <div class="container">
          <div class="block">
            <el-avatar :size="35"
                       src="https://m.360buyimg.com/babel/jfs/t1/40738/20/14562/826/5d773a01E09eb8121/d6f3909618c6307a.png"></el-avatar>
          </div>
          <span>企业购</span>
        </div>
        <div class="container">
          <div class="block">
            <el-avatar :size="35"
                       src="https://m.360buyimg.com/babel/jfs/t1/57014/6/10297/815/5d773a07Ec7a61fc9/97917a2daa34be0f.png"></el-avatar>
          </div>
          <span>礼品卡</span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>

import slide from './slide.vue'
import slideMin from './slideMin.vue'

export default {
  name: "top",
  components: {
    slide,
    slideMin
  },
  data() {
    return {
      img: true,
      methods: {
        handleOpen(key, keyPath) {
          console.log(key, keyPath);
        },
        handleClose(key, keyPath) {
          console.log(key, keyPath);
        }
      },
      item1: [
        {
          url: '//img10.360buyimg.com/babel/s1180x940_jfs/t1/217656/5/19384/73266/628b7d8eE5811134a/b5b0e08882080c15.jpg.webp',
        },
        {
          url: '//imgcps.jd.com/ling4/100026667910/5Lqs6YCJ5aW96LSn/5L2g5YC85b6X5oul5pyJ/p-5bd8253082acdd181d02fa02/54f3f325/cr/s/q.jpg'
        },
        {
          url: '//img13.360buyimg.com/pop/s1180x940_jfs/t1/148185/27/28184/63554/628f812dE9cb870b5/f5069be4b1dfae28.jpg.webp'
        },
        {
          url: '//img20.360buyimg.com/pop/s1180x940_jfs/t1/195525/16/25601/99981/6290886eEffdaef7a/1ef9eaf341a6f4e4.jpg.webp'
        }
      ],
      item2: [
        [
          {
            url: "//img14.360buyimg.com/da/s380x300_jfs/t1/69777/36/4877/40615/5d308fcaEb0c3772b/679f92d55f5adb40.png.webp",
          },
          {
            url: "//img11.360buyimg.com/babel/s380x300_jfs/t1/156373/29/12285/68780/603f2b75E4fd09458/a6aa23f1163ff561.jpg.webp",
          }
        ],
        [
          {
            url: "//img12.360buyimg.com/babel/s380x300_jfs/t1/152314/13/19839/57522/603e118dE941f0ce9/fdff58457adbef3e.jpg.webp"
          },
          {
            url: "//img12.360buyimg.com/babel/s380x300_jfs/t1/126827/13/19259/67342/60a8abe5E986230da/ef6c1e67fddb54c8.jpg.webp"
          }
        ],
        [
          {
            url: "//img10.360buyimg.com/babel/s380x300_jfs/t1/179822/25/5393/75049/60a86e86Edafc14d5/5e9eb0f22d1f6b77.jpg.webp"
          },
          {
            url: "//img11.360buyimg.com/da/s380x300_jfs/t1/91680/39/19130/41707/5e9d3e20Eb165a936/f9149db4a98dd9a9.png.webp"
          },
        ],
      ]
    }
  }
}

</script>

<style lang="less">
.top {
  background-color: var(--gray-bg);
  height: 480px;
  position: relative;
  display: flex;
}

.tl {
  margin-right: 10px;
  width: 17%;
  height: 100%;
  background-color: #fff;
}

.slide1 {
  margin-right: 10px;
  width: 49%;
  height: 100%;
}

.slide2 {
  margin-right: 10px;
  width: 15%;
  height: 100%;
}

.tr {
  height: 100%;
  background-color: white;

  .bt-group {
    height: 20px;
    width: 200px;
    margin: 0 0 20px 25px;
  }

  .tr-top {
    height: 50px;
    margin: 5px 0 0 20px;

    .tr-left {
      float: left;
      margin-left: 10px;
    }

    .tr-right {
      float: right;
      margin: 5px 30px 0 0;
    }
  }

  .divider {
    width: 100%;
    height: 2px;
    background-color: #f0f0f0;
    margin: 10px;
  }

  .tr-mid {
    margin-left: 15px;

    .HOT {
      color: #e1251b;
      background-color: rgba(225, 37, 27, .08);
      display: block;
      width: 30px;
      text-align: center;
      float: left;
      margin-top: 5px;
    }

    .context {
      display: block;
      width: 160px;
      color: #363634;
      white-space: nowrap;
      text-overflow: ellipsis;
      overflow: hidden;
      margin-top: 5px;
    }
  }

  .tr-bott {
    margin-left: 10px;
    width: 210px;
    height: 220px;

    .container {
      width: 70px;
      height: 55px;
      text-align: center;
      display: inline-block;
    }
  }
}
</style>