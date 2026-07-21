# 7. Test Case'ler (UAT)

---

## TC-01: İade Oranlarının Görüntülenmesi

**Senaryo:** Kullanıcı iade oranlarını görüntüler  

**Ön Koşul:** Sistemde sipariş ve iade verisi bulunmalıdır  

**Adımlar:**
1. Kullanıcı sisteme giriş yapar  
2. Raporlama ekranına gider  
3. İade oranları sayfasını açar  

**Beklenen Sonuç:**  
- Ürün bazlı iade oranları görüntülenmelidir  
- Kategori bazlı iade oranları görüntülenmelidir  
- Veriler doğru olmalıdır  

---

## TC-02: Teslimat Gecikmelerinin Görüntülenmesi

**Senaryo:** Kullanıcı geciken siparişleri analiz eder  

**Ön Koşul:** Teslimat süresi verisi mevcut olmalıdır  

**Adımlar:**
1. Kullanıcı raporlama ekranına gider  
2. Teslimat performansı sayfasını açar  

**Beklenen Sonuç:**  
- Geciken siparişler listelenmelidir  
- Teslimat süreleri doğru hesaplanmalıdır  
- Gecikme oranı görüntülenmelidir  

---

## TC-03: İade Nedenlerinin Görüntülenmesi

**Senaryo:** Kullanıcı iade nedenlerini analiz eder  

**Ön Koşul:** İade verisi ve nedenleri sisteme girilmiş olmalıdır  

**Adımlar:**
1. Kullanıcı analiz ekranına gider  
2. İade nedenleri raporunu açar  

**Beklenen Sonuç:**  
- İade nedenleri kategorilere ayrılmış şekilde gösterilmelidir  
- En sık iade nedenleri listelenmelidir  

---

## TC-04: Gecikme Uyarı Sistemi

**Senaryo:** Sistem gecikme durumunda uyarı üretir  

**Ön Koşul:** Geciken sipariş bulunmalıdır  

**Adımlar:**
1. Sistem teslimat süresini kontrol eder  
2. Gecikme tespit edilir  

**Beklenen Sonuç:**  
- Sistem uyarı oluşturmalıdır  
- Uyarı ilgili kullanıcıya iletilmelidir  

---

## TC-05: Veri Doğruluğu Kontrolü

**Senaryo:** Sistem eksik verileri kontrol eder  

**Ön Koşul:** Eksik veri içeren kayıt bulunmalıdır  

**Adımlar:**
1. Kullanıcı veri giriş ekranına gider  
2. Eksik veri ile kayıt oluşturmaya çalışır  

**Beklenen Sonuç:**  
- Sistem hata mesajı vermelidir  
- Eksik alanlar belirtilmelidir  
