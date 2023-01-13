---
title: Festival Map
permalink: /festivalmap
---
<!DOCTYPE html>
<html>
<body>

<h1>Festival Map</h1>

<div id="googleMap" style="width:100%;height:400px;"></div>
<script>
function myMap() {
var mapProp= {
    top:new google.maps.LatLng(51.508742,-0.120850),
    zoom:5,
};
var map=new google.maps.Map(document.getElementById("googleMap"),mapProp);
}
</script>

<iframe src="https://www.google.com/maps/d/embed?mid=1iocybSAgqXITlJxyuPm-Vo-BxEwqcVc&ehbc=2E312F" width="640" height="480"></iframe>

</body>
</html>
