import folium

map=folium.Map(location=[24.179020, 120.648312], #設定地圖中心點
            zoom_start=25, #設定初始縮放尺度
)
def utf2asc(s):
    return str(str(s).encode('ascii','xmlcharrefreplace'))[2:-1]

folium.PolyLine([
    [24.179583, 120.646858],
    [24.179592, 120.647325],
    [24.178986, 120.647352],
    [24.179005, 120.649438],
    [24.178457, 120.649438],
    [24.178503, 120.650047],
    [24.178374, 120.650053]
],color='purple').add_to(map)
map.save('map01.html')
map
txt=utf2asc("""
    <h1>建築館</h1><br>
    <img src="jpeg.jpg" width="150px"></img>
""")
popup=folium.Popup(html=txt)
folium.Marker([24.179583, 120.646858],popup=popup,tooltip=utf2asc('起點'),icon=folium.Icon(color='red',
                    prefix='fa',
                    icon='cloud'#https://fontawesome.com/v4.7.0/icon/
                    )).add_to(map)
map

txt=utf2asc("""
    <h1>商學大樓</h1><br>
    <img src="123456.jpg" width="150px"></img>
""")
popup=folium.Popup(html=txt)
folium.Marker([24.178374, 120.650053],popup=popup,tooltip=utf2asc('迄點'),icon=folium.Icon(color='green',
                    prefix='fa',
                    icon='cloud'#https://fontawesome.com/v4.7.0/icon/
                    )).add_to(map)
map

txt=utf2asc("""
    <h1>目前位置</h1><br>
    <img src="654321.jpg" width="150px"></img>
    <h10>(24.179010, 120.648307)</h10><br>
""")
popup=folium.Popup(html=txt)
folium.Marker([24.179010, 120.648307],popup=popup,tooltip=utf2asc('目前位置'),icon=folium.Icon(color='blue',
                    prefix='fa',
                    icon='leaf'#https://fontawesome.com/v4.7.0/icon/
                    )).add_to(map)
map

txt=utf2asc("""
    <h6>預估時間10分鐘</h6><br>
    <img src="780.jpg" width="50px" height="50px"></img>
""")
popup=folium.Popup(html=txt,show=True,max_width='50%')
folium.PolyLine([
    [24.179010, 120.648307],
    [24.179005, 120.649438],[24.178457, 120.649438],[24.178503, 120.650047]],popup=popup,tooltip=utf2asc('目前位置'),icon=folium.Icon(color='blue',
                    prefix='fa',
                    icon='leaf'#https://fontawesome.com/v4.7.0/icon/
                    )).add_to(map)
map.save('map02.html')
map

