<style>
  .parent {
    overflow: hidden;
  }
  .child {
    float: left;
    width: 33%;
    padding: 20px;
    box-sizing: border-box;
  }
  .parent-sibling {
    clear: both;
  }
</style>
<div class="parent">
  <div class="child"></div>
  <div class="child"></div>
  <div class="child"></div>
</div>
<div class="parent-sibling"></div>