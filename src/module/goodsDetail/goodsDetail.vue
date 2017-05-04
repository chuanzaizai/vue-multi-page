<template>

  <div class="goodsdetail">
    <h1 class="title">这里是商品详情页面</h1>
  </div>

</template>

<script>

//公用的css
import commonCss from 'assets/css/common.css';    
import moduleHead from 'components/module-head';
import $ from 'jquery';

export default {
  data() {
    return {
		  list:[]	
    }
  },
  components: {
    // 注册模块
	  moduleHead:moduleHead
  },
  ready() {

  },
  
  methods: {

  }  
}
</script>

<style lang="scss" scoped>

  @import './goodsDetail.scss';

</style>







