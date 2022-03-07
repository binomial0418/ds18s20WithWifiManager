# ds18s20WithWifiManager
# 本專案使用ESP8266+ds18s20取得溫度，並且上傳至後台紀錄數據。
# 提供WIFI設定介面
<br>
0.請先在開發板上傳並執行一次uploadFileToFS.ino，建立需要的檔案。<br><br>
1.使用開發板為ESP8266（ESP-12F，CH9102X），MAC版驅動請連結https://github.com/Xinyuan-LilyGO/LilyGo-T-Call-SIM800/files/7037260/CH9102_Mac_Driver.zip 。<br> <br>
2.含WIFI設定介面，flash按三下可進入AP模式，請連接名稱『ESP-****』的AP後瀏覽器開啟192.168.4.1進行WIFI設定。<br> <br>
3.額外函式庫：<br>
  ArduinoJson：內建程式庫管理員中下載。<br>
  ESPAsyncTCP：內建程式庫管理員中下載。<br>
  ESPAsyncWebServer：內建程式庫管理員中下載。<br>
  EasyButton：內建程式庫管理員中下載。<br><br>
4.接線方式:ds18s20 data腳位 <----> esp8266 D7(13)
