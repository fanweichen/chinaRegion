# chinaRegion
a js for china region

#### REQUIRE 
this js requires jQuery
使用该js请加载jQuery
#### USAGE 
```
//region is a Dom  about the select
<div  id="region">
  <label class="">所在地址</label>
  <!--省-->
  <select  name="province" id="province">
    <option  value="">请选择一个选项</option>
  </select>
  <!--市-->
  <select name="city" id="city">
    <option  value="">请选择一个选项</option>
  </select>
  <!--区-->
  <select name="area" id="area">
    <option  value="">请选择一个选项</option>
  </select>
</div>

<script type="text/javascript">
  var region = $('#region');
  setRegionSelect(region, regionId = null);
</script >
```
