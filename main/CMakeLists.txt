# Edit following two lines to set component requirements (see docs)
idf_component_register( SRCS 
"captdns.c"
"cgiupdate.c"
"config.c"
"ds.c" 
"hd_bmp180.c" 
"hd_display.cpp"
"hd_http.c" 
"hd_main.c" 
"hd_pzem.c"
"hd_spi_i2c.c"
"hd_wifi.c" 
"OLEDDisplayFonts.c" 
"sh1106.c"
INCLUDE_DIRS "." "libesphttpd/include" "esp-request/include" "md5" "adafruit" 
#"ads1115"
REQUIRES "adafruit" "libesphttpd" "esp-request" "md5" "console nvs_flash" "json" "openssl" "app_update" "esp_netif" "tcpip_adapter")
# "ads1115")
                    
