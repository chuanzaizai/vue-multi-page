<template>
	<div class="index">
		<h1 class="title">这里是首页</h1>
		<div class="skip">
			<button @click="skip">点我跳转页面</button>
		</div>
	</div>
</template>


<script>
//公用的css
import commonCss from 'assets/css/common.css';
export default {
  data() {
    return {
    }
  },
  components: {
	
  },
  ready() {

  },
  methods: {
    skip() {
		setTimeout(()=>{
			window.location.href = "goodsDetail.html";
		},500);
	}
  }  
}
</script>

<style lang="scss" scoped>

	@import './index.scss';

</style>





