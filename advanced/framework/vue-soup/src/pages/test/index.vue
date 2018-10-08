<template>
    <div class="test">
        <Tabs type="card" value="name1">
        <TabPane label="标签一" name="name1">
            <DatePicker type="datetimerange" placeholder="Select date and time" placement="right-end" style="width: 300px"></DatePicker>
            asdfasdfa324324234234234234234234
        </TabPane>
        <TabPane label="标签二" name="name2">标签二的内容</TabPane>
        <TabPane label="标签三" name="name3">标签三的内容</TabPane>
    </Tabs>
        <!-- <DatePicker type="datetimerange" placeholder="Select date and time" style="width: 300px"></DatePicker> -->
    </div>
</template>
<script>
export default {
  data() {
    return {};
  }
};
</script>
<style lang="less">
@import "../../assets/less/common.less";
.test {
  width: 100%;
  height: 100%;
  /deep/.ivu-tabs .ivu-tabs-tabpane {
      min-height: 600px;
  }
  /deep/.ivu-tabs-nav {
      padding-left: calc(50% - 120px);
  }
}
</style>

