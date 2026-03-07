# 🏆 İTO Turnuva Takip Sistemi

**Python ile Turnuva Yönetimi — Öğrenci Projesi**

---

## Proje Hakkında

Bu proje, **5., 6. ve 7. sınıf öğrencileriyle** bir dönem boyunca yürütülen Python dersinin dönem sonu ürünüdür. Her öğrenci projeye kendi geliştirdiği bir fonksiyonla katkıda bulunmuştur. Turnuva katılımcılarını ekleyip eşleştirmek, maç skoru girmek ve puan tablosunu takip etmek için kullanılabilir.

Proje **Programiz Online Python Compiler** üzerinde çalışmaktadır:
👉 https://www.programiz.com/online-compiler/4gypSoFYXuU13

---

## Katkıda Bulunan Öğrenciler

Her öğrenci bir ya da birden fazla fonksiyon geliştirmiştir. İsimler aşağıya eklenecektir:

| Okul No | Öğrenci Adı       | Geliştirdiği Fonksiyon                        |
|---------|-------------------|-----------------------------------------------|
| 1254    | _______________   | `turnuva_logo`, `menu_goster`                 |
| 1161    | _______________   | `turnuva_giris`, `skor_goster`                |
| 1009    | _______________   | `oyuncu_ekle`                                 |
| 1115    | _______________   | `oyuncu_listesi_goster`, `turnuva_ozeti`      |
| 1206    | _______________   | `oyuncu_sil`                                  |
| 1238    | _______________   | `oyuncu_guncelle`                             |
| 1071    | _______________   | `mac_baslat`, `oyuncu_guncelle` (katkı)       |
| 1142    | _______________   | `eslestirmeleri_goster`                       |
| 1018    | _______________   | `oyuncu_arama`, `eslestirmeleri_olustur`, `kura_cek` |
| 1230    | _______________   | `puan_tablosu_guncelle`                       |
| Ahmet Zafer | ___________   | `gol_animasyonu`                              |
| 1240    | _______________   | `turnuva_ozeti` (katkı)                       |

> Öğretmen notu: Boş bırakılan alanlara öğrencilerin adlarını ekleyebilirsiniz.

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
