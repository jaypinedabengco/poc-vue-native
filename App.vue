<template>
  <view class="container">
    <view :style="{flex: 1, justifyContent: 'center'}">
      <activity-indicator size="large" color="#0000ff" />
    </view>
  </view>
</template>

<script>
export default {
  methods: {
    renderList: function(item) {
      return `<Text>{${item}}<Text>`;
    }
  }
};
</script>

<style>
.container {
  background-color: white;
  align-items: center;
  justify-content: center;
  flex: 1;
}
</style>