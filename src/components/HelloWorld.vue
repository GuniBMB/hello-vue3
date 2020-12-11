<!--
 * @Description: 
 * @Author: BMB
 * @Date: 2020-12-11 14:52:59
 * @LastEditTime: 2020-12-11 16:10:47
 * @LastEditors: BMB
-->
<template>
  <!-- <h1>{{ msg }}</h1> -->
  <button @click="count++">count is: {{ count }}</button>
  <p>
    Edit <code>components/HelloWorld.vue</code> to test hot module replacement.
  </p>
</template>

<script lang='ts'>
import { ref, reactive, onMounted } from "vue";
export default {
  // name: "HelloWorld",
  // props: {
  //   msg: String,
  // },
  // data() {
  //   return {
  //     count: 0,
  //   };
  // },
  setup() {
    let count = ref(0);

    onMounted(() => {});

    // const updateCount = ()=>{
    //   count = count + ref(1);
    // }

    return {
      count,
    };
  },
};
</script>
