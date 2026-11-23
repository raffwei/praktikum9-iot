# Praktikum 9: REST API Node-RED untuk Sistem IoT

Nama: Ahmad Rafi
NPM : 2410020032

## Isi repo
- simulasi_esp32.py : simulator sensor (MQTT publisher)
- iot_flow_v2.json : flow Node-RED (REST API, threshold, WebSocket, SQLite)
- iot.html : dashboard (Chart.js + WebSocket)
- settings_snippet.js : pengaturan settings.js yang diubah
- screenshot/ : bukti hasil pengujian

## Cara menjalankan
1. Jalankan Mosquitto: mosquitto -v
2. Jalankan Node-RED, import iot_flow_v2.json, lalu Deploy
3. Jalankan simulator: python simulasi_esp32.py
4. Buka http://localhost:1880/iot.html

Ganti GANTI_API_KEY dengan API key Anda di iot.html dan node Cek X-API-Key.
