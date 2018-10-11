<template>
    <div class="example">
        <!-- <Tabs type="card" value="name1">
        <TabPane label="标签一" name="name1">
            <DatePicker type="datetimerange" placeholder="Select date and time" placement="right-end" style="width: 300px"></DatePicker>
            asdfasdfa324324234234234234234234
        </TabPane>
        <TabPane label="标签二" name="name2">标签二的内容</TabPane>
        <TabPane label="标签三" name="name3">标签三的内容</TabPane>
    </Tabs> -->
        <!-- <DatePicker type="datetimerange" placeholder="Select date and time" style="width: 300px"></DatePicker> -->
        <!-- <sliderTest :initNumList="value1"></sliderTest>
        <sliderTest :initNumList="value2"></sliderTest> -->
        <div class="myDragdiv" v-drag="{age:'sdfsf'}"></div>
    </div>
</template>
<script>
import sliderTest from './slider-test'
export default {
  name: "example",
  components: {
      sliderTest
  },
  data() {
    return {
      startNumber: "",
      endNumber: "",
      numberList: [],
      value1: [10, 50],
      value2: [30, 80]
    };
  },
  methods: {
    
  }
};
</script>
<style lang="less">
@import "../../assets/less/common.less";
.example {
    width: 300px;
    height: 200px;
    .myDragdiv {
        width: 100px;
        height: 100px;
        background-color:red;
    }
}
</style>

