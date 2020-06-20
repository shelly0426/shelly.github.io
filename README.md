<!DOCTYPE html>
<head>    
    <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
    
        <script>
            L_NO_TOUCH = false;
            L_DISABLE_3D = false;
        </script>
    
    <script src="https://cdn.jsdelivr.net/npm/leaflet@1.6.0/dist/leaflet.js"></script>
    <script src="https://code.jquery.com/jquery-1.12.4.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/js/bootstrap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/leaflet@1.6.0/dist/leaflet.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap-theme.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.6.3/css/font-awesome.min.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.css"/>
    <link rel="stylesheet" href="https://rawcdn.githack.com/python-visualization/folium/master/folium/templates/leaflet.awesome.rotate.css"/>
    <style>html, body {width: 100%;height: 100%;margin: 0;padding: 0;}</style>
    <style>#map {position:absolute;top:0;bottom:0;right:0;left:0;}</style>
    
            <meta name="viewport" content="width=device-width,
                initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
            <style>
                #map_218775dca9ba4a25948e5363828c24b0 {
                    position: relative;
                    width: 100.0%;
                    height: 100.0%;
                    left: 0.0%;
                    top: 0.0%;
                }
            </style>
        
</head>
<body>    
    
            <div class="folium-map" id="map_218775dca9ba4a25948e5363828c24b0" ></div>
        
</body>
<script>    
    
            var map_218775dca9ba4a25948e5363828c24b0 = L.map(
                "map_218775dca9ba4a25948e5363828c24b0",
                {
                    center: [24.17902, 120.648312],
                    crs: L.CRS.EPSG3857,
                    zoom: 25,
                    zoomControl: true,
                    preferCanvas: false,
                }
            );

            

        
    
            var tile_layer_3a33acc190e1447a8d01039681cd3aa2 = L.tileLayer(
                "https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png",
                {"attribution": "Data by \u0026copy; \u003ca href=\"http://openstreetmap.org\"\u003eOpenStreetMap\u003c/a\u003e, under \u003ca href=\"http://www.openstreetmap.org/copyright\"\u003eODbL\u003c/a\u003e.", "detectRetina": false, "maxNativeZoom": 18, "maxZoom": 18, "minZoom": 0, "noWrap": false, "opacity": 1, "subdomains": "abc", "tms": false}
            ).addTo(map_218775dca9ba4a25948e5363828c24b0);
        
    
            var poly_line_831b4f416e91402ab5bbb84f42142e70 = L.polyline(
                [[24.179583, 120.646858], [24.179592, 120.647325], [24.178986, 120.647352], [24.179005, 120.649438], [24.178457, 120.649438], [24.178503, 120.650047], [24.178374, 120.650053]],
                {"bubblingMouseEvents": true, "color": "purple", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "purple", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "opacity": 1.0, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(map_218775dca9ba4a25948e5363828c24b0);
        
    
            var marker_5ac4b3eb01904c748764a18408533caa = L.marker(
                [24.179583, 120.646858],
                {}
            ).addTo(map_218775dca9ba4a25948e5363828c24b0);
        
    
            var icon_3749bcf9f51142619af76f4cd495b4ee = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cloud", "iconColor": "white", "markerColor": "red", "prefix": "fa"}
            );
            marker_5ac4b3eb01904c748764a18408533caa.setIcon(icon_3749bcf9f51142619af76f4cd495b4ee);
        
    
        var popup_e6c65ae2580840648c4572f454e5e45c = L.popup({"maxWidth": "100%"});

        
            var html_7f785fda46924791aa27c029f542e26d = $(`<div id="html_7f785fda46924791aa27c029f542e26d" style="width: 100.0%; height: 100.0%;">\n    <h1>&#24314;&#31689;&#39208;</h1><br>\n    <img src="jpeg.jpg" width="150px"></img>\n</div>`)[0];
            popup_e6c65ae2580840648c4572f454e5e45c.setContent(html_7f785fda46924791aa27c029f542e26d);
        

        marker_5ac4b3eb01904c748764a18408533caa.bindPopup(popup_e6c65ae2580840648c4572f454e5e45c)
        ;

        
    
    
            marker_5ac4b3eb01904c748764a18408533caa.bindTooltip(
                `<div>
                     &#36215;&#40670;
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_4e3713607a4949388d91dba275ce59d5 = L.marker(
                [24.178374, 120.650053],
                {}
            ).addTo(map_218775dca9ba4a25948e5363828c24b0);
        
    
            var icon_3fbc9919cccb44439daf07d83b715515 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cloud", "iconColor": "white", "markerColor": "green", "prefix": "fa"}
            );
            marker_4e3713607a4949388d91dba275ce59d5.setIcon(icon_3fbc9919cccb44439daf07d83b715515);
        
    
        var popup_b9edba49f5624d5382f16f664ce69b63 = L.popup({"maxWidth": "100%"});

        
            var html_6401348cfd234e6f81db7a3b52b5119d = $(`<div id="html_6401348cfd234e6f81db7a3b52b5119d" style="width: 100.0%; height: 100.0%;">\n    <h1>&#21830;&#23416;&#22823;&#27155;</h1><br>\n    <img src="123456.jpg" width="150px"></img>\n</div>`)[0];
            popup_b9edba49f5624d5382f16f664ce69b63.setContent(html_6401348cfd234e6f81db7a3b52b5119d);
        

        marker_4e3713607a4949388d91dba275ce59d5.bindPopup(popup_b9edba49f5624d5382f16f664ce69b63)
        ;

        
    
    
            marker_4e3713607a4949388d91dba275ce59d5.bindTooltip(
                `<div>
                     &#36804;&#40670;
                 </div>`,
                {"sticky": true}
            );
        
    
            var marker_93f5cfb13cd44233ae2d9aa0bffacaab = L.marker(
                [24.17901, 120.648307],
                {}
            ).addTo(map_218775dca9ba4a25948e5363828c24b0);
        
    
            var icon_400fb3f1f5a44ac59976e293471317d4 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "leaf", "iconColor": "white", "markerColor": "blue", "prefix": "fa"}
            );
            marker_93f5cfb13cd44233ae2d9aa0bffacaab.setIcon(icon_400fb3f1f5a44ac59976e293471317d4);
        
    
        var popup_2ef0192241734fe5a5fcdd9cf69b3200 = L.popup({"maxWidth": "100%"});

        
            var html_8f18e96a5bd64523aaa064f715dbb94b = $(`<div id="html_8f18e96a5bd64523aaa064f715dbb94b" style="width: 100.0%; height: 100.0%;">\n    <h1>&#30446;&#21069;&#20301;&#32622;</h1><br>\n    <img src="654321.jpg" width="150px"></img>\n    <h10>(24.179010, 120.648307)</h10><br>\n</div>`)[0];
            popup_2ef0192241734fe5a5fcdd9cf69b3200.setContent(html_8f18e96a5bd64523aaa064f715dbb94b);
        

        marker_93f5cfb13cd44233ae2d9aa0bffacaab.bindPopup(popup_2ef0192241734fe5a5fcdd9cf69b3200)
        ;

        
    
    
            marker_93f5cfb13cd44233ae2d9aa0bffacaab.bindTooltip(
                `<div>
                     &#30446;&#21069;&#20301;&#32622;
                 </div>`,
                {"sticky": true}
            );
        
    
            var poly_line_8b55b1cfbd4b456bbf9a76fa56cee6ab = L.polyline(
                [[24.17901, 120.648307], [24.179005, 120.649438], [24.178457, 120.649438], [24.178503, 120.650047]],
                {"bubblingMouseEvents": true, "color": "#3388ff", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "#3388ff", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "opacity": 1.0, "smoothFactor": 1.0, "stroke": true, "weight": 3}
            ).addTo(map_218775dca9ba4a25948e5363828c24b0);
        
    
        var popup_a2c9277f0c0e48acababf62637fbfdf4 = L.popup({"autoClose": false, "maxWidth": "50%"});

        
            var html_114a0101b0f741f69878a1269d3cb554 = $(`<div id="html_114a0101b0f741f69878a1269d3cb554" style="width: 100.0%; height: 100.0%;">\n    <h6>&#38928;&#20272;&#26178;&#38291;10&#20998;&#37912;</h6><br>\n    <img src="780.jpg" width="50px" height="50px"></img>\n</div>`)[0];
            popup_a2c9277f0c0e48acababf62637fbfdf4.setContent(html_114a0101b0f741f69878a1269d3cb554);
        

        poly_line_8b55b1cfbd4b456bbf9a76fa56cee6ab.bindPopup(popup_a2c9277f0c0e48acababf62637fbfdf4)
        .openPopup();

        
    
    
            poly_line_8b55b1cfbd4b456bbf9a76fa56cee6ab.bindTooltip(
                `<div>
                     &#30446;&#21069;&#20301;&#32622;
                 </div>`,
                {"sticky": true}
            );
        
</script>
