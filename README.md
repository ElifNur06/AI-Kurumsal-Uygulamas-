# 🚀 AI Kurumsal Uygulaması (Next.js & Gemini RAG)

Bu proje; modern bir kurumsal web sitesi, gelişmiş bir **Bayi Portalı** ve döküman tabanlı çalışan (RAG - Retrieval-Augmented Generation) bir **Yapay Zeka Asistanı** içeren uçtan uca bir çözümdür.

## 🛠️ Kullanılan Teknolojiler

- **Frontend:** Next.js 16 (App Router & Turbopack)
- **Styling:** Tailwind CSS & Lucide Icons
- **Backend/Veritabanı:** Firebase (Firestore & Auth)
- **AI:** Google Gemini API (Dinamik Bağlamlı RAG Altyapısı)
- **Proxy/Middleware:** Gelişmiş Rota ve Dil Yönetimi

## ✨ Temel Özellikler

### 🤖 Yapay Zeka (RAG) Entegrasyonu
- Uygulama, sadece genel bilgileri değil, **Admin Paneli** üzerinden yüklediğiniz teknik dökümanları ve fiyat listelerini referans alarak cevap verir.
- `src/app/api/chat/route.ts` üzerinden Firestore verileri anlık olarak "System Instruction"a eklenir.

### 🏢 Gelişmiş Bayi Portalı
- **Gerçek Zamanlı Veri:** Sipariş durumu ve bekleyen işlemler Firebase `onSnapshot` ile sayfa yenilenmeden güncellenir.
- **Dinamik Dashboard:** Cari bakiye, döküman kütüphanesi ve duyuru sistemi.
- **Çoklu Dil Desteği:** TR, EN, DE, FR dilleri için tam entegrasyon.

### 🔐 Yönetim (Admin) Paneli
- Ürün yönetimi, haber/duyuru ekleme.
- AI ayarları ve teknik döküman yönetimi.
- Kullanıcı yetkilendirme ve sistem logları.

## 📂 Dosya Yapısı
src/app/[locale] - Çok dilli sayfa yapıları.
src/app/api/chat - RAG mekanizmasının çalıştığı AI endpoint'i.
src/proxy.ts - Gelişmiş yönlendirme ve güvenlik katmanı.
src/lib/firebase - Veritabanı konfigürasyonu.
src/components - Ortak kullanılan UI bileşenleri.

## Görseller
<img width="1198" height="675" alt="image" src="https://github.com/user-attachments/assets/76ce4338-8120-45c5-8eae-f0956ec0ff71" />
<img width="1199" height="674" alt="image" src="https://github.com/user-attachments/assets/add3f11d-d806-4900-8321-f3b9c3c65aa5" />
<img width="1200" height="678" alt="image" src="https://github.com/user-attachments/assets/dad60261-ee06-4404-a3e1-a9e2d5864951" />
<img width="1197" height="672" alt="image" src="https://github.com/user-attachments/assets/39fb8c32-519a-4fba-af2d-2b095f01f32d" />
<img width="1203" height="675" alt="image" src="https://github.com/user-attachments/assets/f6ed039b-0304-42d3-8e30-31ce293ae9bd" />
<img width="1200" height="673" alt="image" src="https://github.com/user-attachments/assets/b776cb61-9d65-4189-9dfb-8f3527d9d1eb" />
<img width="1197" height="674" alt="image" src="https://github.com/user-attachments/assets/50c14d28-47a4-498d-a04d-94af706c0e62" />
<img width="1198" height="673" alt="image" src="https://github.com/user-attachments/assets/5094cd82-35de-425a-9c76-536494e5ac9c" />
<img width="1204" height="675" alt="image" src="https://github.com/user-attachments/assets/b09d442e-1e2c-4996-bb86-565cb9121c07" />
<img width="1199" height="673" alt="image" src="https://github.com/user-attachments/assets/14714780-ea9a-4088-b0ab-fa0c487a969a" />
<img width="1198" height="676" alt="image" src="https://github.com/user-attachments/assets/4d27c0fc-ffc1-4594-b2f9-ff2f938da1e0" />
<img width="1200" height="675" alt="image" src="https://github.com/user-attachments/assets/5bfba735-f745-4313-a0a3-b9e3ce9f1548" />
<img width="1202" height="672" alt="image" src="https://github.com/user-attachments/assets/12a08fba-648b-4f5b-b1e9-d48137d2d2ec" />
<img width="1197" height="678" alt="image" src="https://github.com/user-attachments/assets/e36c89bb-5042-406f-90b2-6e11165b192f" />
<img width="1201" height="673" alt="image" src="https://github.com/user-attachments/assets/30b2b97b-bfdf-40b0-8bb3-885289c2c9de" />
<img width="1202" height="672" alt="image" src="https://github.com/user-attachments/assets/30b4587e-a886-45e3-abce-44660c310524" />
<img width="1203" height="677" alt="image" src="https://github.com/user-attachments/assets/f91dafd2-3b9d-4f53-8cbd-01597e7db0e2" />
<img width="1197" height="674" alt="image" src="https://github.com/user-attachments/assets/e44aec85-2d3c-48a4-bf76-dcba0c7810d3" />
<img width="1200" height="673" alt="image" src="https://github.com/user-attachments/assets/2046fc25-7106-43ce-9a12-499ee6ee8294" />
<img width="1197" height="674" alt="image" src="https://github.com/user-attachments/assets/6cacdafa-25e8-4361-aea3-34060dfe6c96" />


## 📝 Notlar
Bu uygulama, özellikle sanayi bölgelerinde (Aksaray OSB gibi) faaliyet gösteren şirketlerin bayi ağlarını yönetmesi ve dökümanlarını dijital bir asistan aracılığıyla sunması için optimize edilmiştir.

## 👨‍💻 Geliştirici: Elif Nur Ayhan
