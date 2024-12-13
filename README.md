# Car Model Project React

Bu proje, kullanıcıların otomobil modelleri hakkında kapsamlı bilgiye kolayca erişebilmelerini sağlamak amacıyla tasarlanmış modern bir web sitesidir. Otomobil modelleri hakkında tüm detayları bulabileceğiniz, kolayca gezilebilen ve kullanıcı dostu bir deneyim sunan bu siteyi oluşturduk. Aşağıda siteyle ilgili tüm özellikler ve katkılar detaylı olarak açıklanmıştır.

---

## 🚗 Animasyon Ekranı

Sitemizin kullanıcı dostu olmasını sağlamak için **özel bir animasyon ekranı** ekledik!  
- Siteye girdiğinizde sizi animasyon karşılıyor.  
- Animasyon sonrasında, **anında ana sayfaya** yönlendirilirsiniz ve otomobil modellerini keşfetmeye başlayabilirsiniz.

<img src="https://github.com/user-attachments/assets/79e0659a-065e-4835-b901-dd4db241f584" alt="Animation Screen" width="500"/>


---

## 🏠 Ana Sayfa ve Arama Fonksiyonu

### Ana Sayfa Tasarımı
Kullanıcı dostu, sade ve şık bir **ana sayfa tasarımı** yapıldı.  
- Bu sayfa, kullanıcıların otomobil modellerini kolayca incelemelerini sağlayan bir **tablo** içeriyor.

<img src="https://github.com/user-attachments/assets/9e0ee5f9-ece0-42bb-97af-f95a2c9f0df6" alt="Animation Screen" width="400"/>

### Arama Fonksiyonu
Artık istediğiniz otomobil modelini bulmak çok kolay!  
- **Marka veya model adıyla arama yapabileceğiniz bir fonksiyon** entegre edildi. Bu sayede, kullanıcılar istedikleri bilgiyi anında bulabiliyor.

<img src="https://github.com/user-attachments/assets/1e52dbe4-78bd-4f00-a5d5-0e2b1876e576" alt="Animation Screen" width="400"/>

---

## 🔍 Filtreleme Özelliği

### Filtreleme Butonu ve Seçenekler
**Otomobil modeli ararken filtreleme** yapmak ister misiniz?  
- Artık **marka, fiyat, tork, yıl** gibi çeşitli kriterlere göre sıralama yapabilirsiniz! Hızlıca filtreleme seçeneklerine ulaşmak için tıklamanız yeterli.

### Filtreleme İşlevselliği
Filtreleme butonuna tıkladığınızda açılan seçeneklerle otomobil modellerinizi istediğiniz gibi sıralayın.  
- Veriler, **büyükten küçüğe doğru sıralanır**, böylece en hızlı şekilde istediğiniz sonuca ulaşabilirsiniz.

<img src="https://github.com/user-attachments/assets/e59adc1f-743b-4c62-8dcc-894f242633d7" alt="Animation Screen" width="400"/>

---

## 📄 Sayfalar

Bu projede üç ana sayfa bulunmaktadır: **Ana Sayfa**, **Hakkımızda** ve **İletişim**. Her bir sayfa, kullanıcı deneyimini geliştirmek ve siteyi daha verimli hale getirmek amacıyla tasarlanmıştır. Aşağıda her bir sayfanın özelliklerine dair kısa açıklamalar bulabilirsiniz:

### 🏠 **Ana Sayfa**
Ana sayfa, kullanıcıların siteye girdiğinde ilk gördükleri araba ile ilgili bilgilerin yer aldığı tabloyu inceleyebilecekleri sayfadır.
**Özellikler:**
- **Arama fonksiyonu**: Marka veya model adıyla hızlı arama yapılabilir.  
- **Filtreleme seçenekleri**: Otomobil modelleri fiyat, yıl, tork gibi kriterlere göre sıralanabilir.

### ℹ️ **Hakkımızda**
Hakkımızda sayfası, projeyle ilgili daha fazla bilgi edinmek isteyen kullanıcılar için hazırlanmıştır. Burada projenin amacı ve genel özellikleri hakkında bilgiler yer alır.

<img src="https://github.com/user-attachments/assets/1f002fb2-2873-40a2-86df-22281741617a" alt="Animation Screen" width="400"/>

### 📧 **İletişim**
İletişim sayfası, kullanıcıların proje hakkında soru sormak veya geri bildirimde bulunmak için bizlere ulaşmalarını sağlar.

<img src="https://github.com/user-attachments/assets/95b16670-0151-488d-9c07-b759611b819d" width="400"/>

---

## 📑 Sayfalandırma - İleri/Geri

Büyük veri setlerinde gezinmek zor olabilir, değil mi?  
- **Sayfa kontrol butonları** eklendi! Bu sayede arama sonuçlarını sayfa sayfa gezebilirsiniz.  
- **Her sayfada 20 otomobil modeli** görüntülenir, böylece gezinti çok daha kolay ve keyifli hale gelir.

<img src="https://github.com/user-attachments/assets/ec035137-41f7-47a3-9597-7877924bc215" width="400"/>

---

## 🖥️ Axios | JSON Server

Bu projede **Axios** kullanarak HTTP istekleri yapılıyor ve **JSON Server** ile yerel veriler sunuluyor. `car.json` dosyasındaki veriler, bir yerel sunucu üzerinden sağlanıyor.

1. **JSON Server'ı başlatın**:
    ```bash
    json-server --watch src/data/car.json --port 3001
    ```
    Bu, sunucuyu `http://localhost:3001` adresinde çalıştırır ve verileri Axios ile çekebilir.

---

## 🛠️ Kullanılan Teknolojiler

Bu projede kullandığımız teknolojiler, siteyi daha hızlı ve verimli hale getirmemizi sağladı. İşte kullandığımız araçlar:

- **React.js**: Kullanıcı arayüzünü oluşturmak için kullanıldı.  
- **Axios**: JSON server'dan veri çekmek için kullanıldı.  
- **Reactstrap**: Bootstrap bileşenlerini React ile entegre ederek etkili tasarımlar oluşturuldu.  
- **CSS**: Görsel tasarım ve stil düzenlemeleri için kullanıldı.  
- **JSON Server**: Sahte bir REST API sağlamak için kullanıldı.

---

## 🧩 Veri Yapısı

JSON server'dan gelen veri yapısı aşağıdaki gibi ve toplamda **30 öğe** içermektedir:

- **ID**  
- **Marka**  
- **Model**  
- **Yıl**  
- **Fiyat**  
- **Tork**  

---

## 🚀 Performans ve Kullanılabilirlik

Bu projede performans iyileştirmeleri yaparak siteyi **daha hızlı** hale getirmeyi hedefledik. Ayrıca, kullanıcı geri bildirimlerine göre bazı geliştirmeler yaptık ve **React Table Sistemi** entegre ettik.


---

## 💻 Diğer Projeler

Aynı projenin **deploy edilmiş hali(netlify ve render)** versiyonunu başka bir repoda paylaştım. Eğer bu versiyonu denemek isterseniz, işte bağlantı:  
- [**CarModelProjectReact**](https://github.com/osmandemir2533/CarModelProjectReact)

---

Bu projede yaptığım çalışmalarla ilgili başka sorularınız varsa, bana her zaman ulaşabilirsiniz!  


[![Email](https://img.icons8.com/ios-filled/50/FF0000/gmail.png)](mailto:osman25dem@gmail.com) &nbsp;&nbsp; [![LinkedIn](https://img.icons8.com/ios-filled/50/0A66C2/linkedin.png)](https://www.linkedin.com/in/osmandemir2533/)
