## float, overflow, clear

* overflow (parent which has floating children)
* float (to float left or right or both)
* clear (It will clear any float in left, right or both side)
~~~html
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
~~~

## html tag
* header
* footer
* aside

##  html entities 

~~~html
&entities_name;
&#entites_number;
&#entities_hexa_value;
~~~

