# Batas Provinsi-provinsi di Indonesia (GeoJSON)

Ini adalah batas semua provinsi di Indonesia dalam format GeoJSON dengan ekstensi file `json`. Terdapat 38 provinsi (pasca pemekaran Papua tahun 2022) dengan kode provinsi sudah diperbarui.

Entri sebuah provinsi memiliki kunci bernama `properties` yang memiliki dua kunci lagi di dalamnya, yaitu `KODE_PROV` dan `PROVINSI`. Contoh:

```json
"properties":{"kode_provinsi":"97","nama_provinsi":"Papua Pegunungan"}
```

Selebihnya, struktur file geojson adalah standar dan minimal.

Tersedia dua file: 

1. `indonesia-province-simplified.json`: versi yang sudah disederhanakan koordinat dan jumlah poligonnya menggunakan Visvalingam / weighted area
2. `indonesia-province.7z`: versi akurasi tinggi dengan ribuan poligon (dikompres menggunakan 7z, gunakan aplikasi 7zip untuk mengekstrak - ukuran asli sekitar 450 MB)

Versi yang disederhanakan berguna jika file json akan dilayankan bersama dokumen HTML. 
