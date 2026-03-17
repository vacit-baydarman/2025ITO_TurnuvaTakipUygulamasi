# 🏆 İTO Turnuva Takip Sistemi

**Python ile Turnuva Yönetimi — Öğrenci Projesi**

<img width="905" height="222" alt="image" src="https://github.com/user-attachments/assets/24f322da-1515-44e7-a039-50e5c06909ab" />

---

## Proje Hakkında

Bu proje, **5., 6. ve 7. sınıf öğrencileriyle** bir dönem boyunca yürütülen Python dersinin dönem sonu ürünüdür. Her öğrenci projeye kendi geliştirdiği bir fonksiyonla katkıda bulunmuştur. Turnuva katılımcılarını ekleyip eşleştirmek, maç skoru girmek ve puan tablosunu takip etmek için kullanılabilir.

Proje **Programiz Online Python Compiler** üzerinde çalışmaktadır:
👉 https://www.programiz.com/online-compiler/4gypSoFYXuU13

---

## Katkıda Bulunan Öğrenciler

Her öğrenci bir ya da birden fazla fonksiyon geliştirmiştir. İsimler aşağıya eklenecektir:

| Okul No | Öğrenci Adı/Soyadı        | Sınıf/Şube | Geliştirdiği Fonksiyon     | Katkı Sağladığı Fonksiyon |
|--------|----------------------------|------------|-----------------------------|---------------------------|
| 1233   | Muhammed Adem BAYDARMAN    | 5/B        | puan_tablosu_goster         |                           |
| 1254   | Salih Emir GÖKDEMİR        | 5/B        | turnuva_logo, menu_goster   |                           |
| 1161   | Mehmet Ali AYDIN           | 6/C        | turnuva_giris, skor_goster  |                           |
| 1009   | Ahmet Yusuf ÇİNİCİ         | 7/B        | oyuncu_ekle                 |                           |
| 1115   | Muhammed Emin UMAÇ         | 6/A        | oyuncu_listesi_goster       | turnuva_ozeti             |
| 1206   | Aras Ege BAYTÖRE           | 5/A        | oyuncu_sil                  |                           |
| 1238   | Muhammed Eymen SARI        | 5/B        | oyuncu_guncelle             |                           |
| 1071   | Selim ŞANLI                | -          | mac_baslat                  | oyuncu_guncelle           |
| 1142   | Ömer Faruk GÖÇ             | 6/B        | eslestirmeleri_goster       |                           |
| 1018   | Enes Talha GÜLEN           | 7/C        | oyuncu_arama                |                           |
| 1230   | Mete Yağız ÇAVUŞOĞLU       | 5/B        | puan_tablosu_guncelle       |                           |
| 1104   | Ahmet Zafer YÜKSEL         | 6/A        | gol_animasyonu              |                           |
| 1240   | Muhammed Yahya ODABAŞ      | 5/A        | turnuva_ozeti               |                           |
| 1210   | Berzan ALKAN               | 5/A        | eslestirmeleri_olustur      |                           |
| 1202   | Ali Burak AKBAŞ            | 5/C        | kura_cek                    |                           |
| 1267   | Yiğit SARIYERLİOĞLU        | 5/C        | en_iyi_golcu                |                           |
| 1143   | Ömer Kerem KINKAÇ          | -          | skor_guncelle               |                           |


---

## Özellikler

- Oyuncu ekleme, silme ve güncelleme
- Rastgele eşleştirme (kura) sistemi
- Maç başlatma ve canlı skor takibi
- Gol animasyonu
- Puan tablosu (galibiyet = 3 puan, beraberlik = 1 puan)
- En iyi golcü sıralaması
- Turnuva özeti

---

## Nasıl Kullanılır?

### 1. Programı Başlatın

Programı çalıştırdığınızda önce giriş ekranı ve logo gösterilir, ardından menü açılır.

### 2. Önce Oyuncu Ekleyin

Menüden **1** seçerek turnuvaya katılacak oyuncuları ekleyin.

```
Seciminiz: 1
Eklenecek oyuncunun adi: Ali
Ali eklendi.
```

Yeterli sayıda oyuncu ekledikten sonra devam edin.

### 3. Eşleştirmeleri Oluşturun

Menüden **7** seçerek oyuncular rastgele eşleştirilir.

```
Seciminiz: 7
Eslestirmeler olusturuldu.
```

### 4. Eşleştirmeleri Görün

Menüden **5** seçerek kimlerin kiminle oynayacağını görün.

```
1. Mac: Ali  vs  Ahmet
2. Mac: Enes vs  Talha
```

### 5. Maç Başlatın

Menüden **10** seçin, hangi maçın oynanacağını girin. Maç sırasında gol atan tarafı seçin:

```
Gol atan taraf?
  1 - Ali
  2 - Ahmet
  3 - Mac bitti
Secim: 1
```

Gol girildiğinde animasyon gösterilir ve anlık skor güncellenir.

### 6. Maçı Bitirin

**3** seçeneği ile maçı bitirin. Kazanan otomatik belirlenir ve puan tablosu güncellenir.

### 7. Sonuçları Görün

| Menü | İşlev |
|------|-------|
| 6    | Puan tablosunu göster |
| 9    | En iyi golcüyü göster |
| 13   | Tüm turnuva özetini göster |

---

## Menü Referansı

| No | İşlev                        |
|----|------------------------------|
| 1  | Oyuncu ekle                  |
| 2  | Oyuncu sil                   |
| 3  | Oyuncu güncelle               |
| 4  | Oyuncu listesini göster       |
| 5  | Eşleştirmeleri göster         |
| 6  | Puan tablosunu göster         |
| 7  | Eşleştirmeleri oluştur        |
| 8  | Puan tablosunu güncelle       |
| 9  | En iyi golcüyü göster         |
| 10 | Maç başlat                   |
| 11 | Kura çek (rastgele oyuncu)   |
| 12 | Oyuncu ara                   |
| 13 | Turnuva özeti                |
| 0  | Çıkış                        |

---

## Puan Sistemi

| Sonuç      | Puan |
|------------|------|
| Galibiyet  | 3    |
| Beraberlik | 1    |
| Mağlubiyet | 0    |

---

## Teknik Bilgiler

- **Dil:** Python 3
- **Dış kütüphane:** Yalnızca `random` (standart kütüphane)
- **Platform:** Programiz Online Compiler veya yerel Python 3.x

---

## Öğretmen Notu

Bu proje her öğrenciye ayrı bir fonksiyon sorumluluğu verilerek geliştirilmiştir. Öğrenciler fonksiyonlarını birbirinden bağımsız yazmış, dönem sonunda parçalar bir araya getirilerek çalışır hale getirilmiştir. Kodun bazı yerlerinde öğrencilere ait orijinal yorumlar ve ifadeler bilinçli olarak korunmuştur.
