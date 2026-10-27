# Reaktör Üst Kafa Analizi

Nükleer basınçlı kap üst kafası (cıvatalı düz kapak) için yapılan sonlu elemanlar analizlerinin
karşılaştırma sitesi.

Site: https://hanifidikici.github.io/reakt-r/

## İçerik

- Tezdeki Workbench modeli ile ANSYS MAPDL'de (APDL) yeniden kurulan iki modelin karşılaştırması:
  cıvatalı/contalı kapak ve kapağı gövdeye birleşik kabul edilen model
- 3D reaktör modeli ve 3D sonuç görüntüleyici (von Mises, σ1, yer değiştirme; üzerine gelince değer)
- Doğrusallaştırılmış gerilmeler (ASME VIII-2 Bölüm 5), limit analizi (TES / TI), normalizasyon serileri, GCI
- Makaledeki depolanmış enerji ve güvenlik çemberi hesabının güncellenmiş senaryoları

Tasarım verileri: SA-516 Gr.70, σy = 260 MPa, p = 0,597 MPa, E = 200 GPa, ν = 0,30.

Statik bir sitedir (`index.html`, `img/`, `fe/`); derleme gerektirmez. `fe/` klasöründeki dosyalar 3D
görüntüleyicinin ağ ve düğüm sonucu verileridir (gzip + base64).

Hazırlayan: Muhammet Hanifi Dikici · Ekim 2026
