<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>高精度战略地图定制工具</title>
    <link rel="stylesheet" href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css"/>
    <script src="https://unpkg.com/leaflet@1.9.4/dist/leaflet.js"></script>
    <style>
        body { padding: 0; margin: 0; }
        #map { height: 100vh; width: 100%; }
        .popup-content {
            font-family: 'Courier New', Courier, monospace;
            font-size: 14px;
        }
        .popup-content input {
            width: 95%;
            margin-top: 5px;
            border: 1px solid #ccc;
            padding: 2px;
        }
    </style>
</head>
<body>

<div id="map"></div>

<script>
    // 初始化地图到海州区
    var map = L.map('map').setView([34.600, 119.225], 14);

    // 添加底图图层
    L.tileLayer('https://webrd0{s}.is.autonavi.com/appmaptile?lang=zh_cn&size=1&scale=1&style=8&x={x}&y={y}&z={z}', {
        subdomains: ["1", "2", "3", "4"],
        attribution: '高德地图'
    }).addTo(map);

    // 创建一个临时的弹出窗口
    var popup = L.popup();

    // 定义地图点击事件
    function onMapClick(e) {
        var lat = e.latlng.lat.toFixed(5); // 获取纬度，保留5位小数
        var lng = e.latlng.lng.toFixed(5); // 获取经度，保留5位小数
        
        var content = `
            <div class="popup-content">
                <b>精确坐标已捕获!</b><br>
                纬度 (lat): ${lat}<br>
                经度 (lng): ${lng}<br>
                <hr>
                <b>请复制以下代码:</b>
                <input type="text" value="{ level: 'S', lat: ${lat}, lng: ${lng}, name: '在此输入地点名' }," readonly onclick="this.select()">
            </div>
        `;

        popup
            .setLatLng(e.latlng)
            .setContent(content)
            .openOn(map);
    }

    // 将点击事件绑定到地图上
    map.on('click', onMapClick);

</script>

</body>
</html>
