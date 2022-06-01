<template>
  <div class="header">
    <div class="w">
      <div class="logo">
        <a href="">
          <img src="//img10.360buyimg.com/img/jfs/t1/199487/20/23852/33747/62862238E18f45301/a50ec1c60e6aad22.jpg"
               alt="" width="190px" height="120px">
        </a>
      </div>
      <div class="search">
        <search></search>
        <div class="hotwords_slide">
          <slide height="16px" :pics="slideHotwords" :img=false ip="none" arrow="never" :interval=1500></slide>
        </div>
        <NavItem :items="hotwords" class="hotwords"></NavItem>
      </div>
      <div class="navigation">
        <NavItem :items="items" :colors="color" fs="15px"></NavItem>
      </div>
      <div class="car">
        <el-button type="danger">我的购物车<i class="el-icon-shopping-cart-full el-icon--right"></i></el-button>
      </div>
    </div>
  </div>
</template>

<script>

import NavItem from './NavItem.vue';
import search from "./search.vue";
import Slide from './slide.vue';

export default {
  data() {
    return {
      color: 'black',
      items: [
        {
          name: "秒杀",
          url: ""
        },
        {
          name: "优惠券",
          url: ""
        },
        {
          name: "PLUS会员",
          url: ""
        },
        {
          name: "品牌闪购",
          url: ""
        },
        {
          name: "拍卖",
          url: ""
        },
        {
          name: "京东家电",
          url: ""
        },
        {
          name: "京东超市",
          url: ""
        },
        {
          name: "京东生鲜",
          url: ""
        },
        {
          name: "京东国际",
          url: ""
        },
        {
          name: "京东云",
          url: ""
        },

      ],

      slideHotwords: [
        {
          url: "美妆， 护肤",
          Path: ""
        },
        {
          url: "付定减千元",
          Path: ""
        }
      ],
      hotwords: [

        {
          name: "小米新品",
          Path: ""
        },
        {
          name: "建材618",
          Path: ""
        },
        {
          name: "不止5折",
          Path: ""
        },
        {
          name: "京东京造",
          Path: ""
        },
        {
          name: "每100-50",
          Path: ""
        },
        {
          name: "拍拍好货",
          Path: ""
        },
        {
          name: "百亿补贴",
          Path: ""
        },
        {
          name: "汽车电瓶",
          Path: ""
        },
      ]
    }
  },
  name: "indexheader",
  components: {
    search,
    NavItem,
    Slide,

  },
};
</script>

<style lang="less" scoped>
.navigation {
  color: black;
}

.hotwords_slide {
  color: red;
  width: 70px;
  /* display: inline-block; */
  float: left;
}

.header {
  height: 140px;
  background-color: #fff;
  border-bottom: 1px solid #ddd;
  margin-bottom: 10px;
}

.header .w {
  position: relative;
}

.logo {
  position: absolute;
  left: 0;
  top: 10px;
  width: 190px;
  height: 120px;
}

.search {
  position: absolute;
  top: 30px;
  /* background-color: green; */
  left: 300px;
  width: 550px;
  /* height: 50px; */
}

.car {
  position: absolute;
  right: 200px;
  top: 30px;
  height: 50px;
  width: 100px;
}

.navigation {
  position: absolute;
  top: 120px;
  left: 300px;
  // background-color: rgb(183, 203, 123);
}

.hotwords {
  float: left;
  color: var(--darkgray);
}
</style>