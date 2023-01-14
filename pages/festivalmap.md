---
title: Festival Map
permalink: /festivalmap
---
<html>
<body>
 <div id="googleMap" style="width:100%;height:400px;"></div>

<script>
function myMap() {
var mapProp= {
    center:new google.maps.LatLng(51.508742,-0.120850),
    zoom:5,
};
var map=new google.maps.Map(document.getElementById("googleMap"),mapProp);
}
</script> 
<iframe src="https://www.google.com/maps/d/embed?mid=1iocybSAgqXITlJxyuPm-Vo-BxEwqcVc&ehbc=2E312F" width="400" height="600"></iframe>
</body>
</html>
