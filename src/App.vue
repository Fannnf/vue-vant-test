<template>
  <div>
    <button>{{a}}</button>
    <van-button type="primary">主要按钮</van-button>
    <van-button type="success">成功按钮</van-button>
    <van-button type="default">默认按钮</van-button>
    <van-button type="warning">警告按钮</van-button>
    <van-button type="danger">危险按钮</van-button>
 </div>
</template>

<script>
import {reactive} from 'vue'

export default {
  name: 'App',
  setup(){
    let a = reactive(1111)
    return{
      a
    }
  }
}
</script>
