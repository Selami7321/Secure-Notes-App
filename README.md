# Secure-Notes-App
Backend: Express/MongoDB, Frontend: React veya klasik HTML/JS ise ona göre, aşağıdaki şablon tüm fullstack not uygulamaları için uyumludur.


# Güvenli Not Uygulaması (Secure Notes App)

## Türkçe Açıklama

Bu proje, kullanıcıların notlarını güvenli şekilde kaydedebileceği, kategorize edebileceği ve önem seviyelerine göre filtreleyebileceği tam işlevli bir Güvenli Not Uygulamasıdır.  
Notlar kullanıcıya özeldir, şifrelenmiş olarak saklanır ve JWT ile kimlik doğrulama kullanılır.

- **Kullanıcı kayıt/giriş (JWT ile güvenli kimlik doğrulama)**
- **Not ekleme, düzenleme, silme**
- **Kategori ve önem derecesine göre filtreleme**
- **Notların şifreli olarak MongoDB'de saklanması**
- **Responsive ve modern frontend arayüzü**
- **Backend: Node.js/Express.js (RESTful API)**
- **Frontend: React.js veya klasik HTML/JS**

**Güvenlik:**  
Kullanıcı şifreleri bcrypt ile hashlenir.  
JWT ile oturum yönetimi yapılır.  
CORS ve güvenlik başlıkları etkinleştirilmiştir.  
Not içerikleri isteğe bağlı olarak şifrelenerek (CryptoJS, AES vs.) kaydedilir.

### Kurulum ve Kullanım

1. Gerekli kütüphaneleri yükleyin:

2. npm install
3. 2. `.env` dosyasına gerekli ortam değişkenlerini girin (örnek: `MONGO_URI`, `JWT_SECRET`).
 Sunucuyu başlatın:
npm start:
4. Frontend dizininde (varsa) aynı şekilde bağımlılıkları yükleyip başlatın.
5. Uygulama, tarayıcıdan `http://localhost:3000` (frontend) ve `http://localhost:5000` (backend) adreslerinden erişilebilir.

---

## English Description

This project is a fully functional **Secure Notes App** where users can safely save, categorize, and filter their notes by importance.  
Notes are user-specific, securely stored (encrypted) in the database, and authentication is handled via JWT.

- **User signup/login (secure authentication with JWT)**
- **Add, edit, delete notes**
- **Filter notes by category and importance**
- **Notes are stored encrypted in MongoDB**
- **Responsive and modern frontend interface**
- **Backend: Node.js/Express.js (RESTful API)**
- **Frontend: React.js or classic HTML/JS**

**Security:**  
User passwords are hashed using bcrypt.  
Session management is handled by JWT.  
CORS and security headers are enabled.  
Note contents can be stored encrypted (e.g., using CryptoJS/AES).

### Installation & Usage

1. Install dependencies:

npm install:
2. Set up environment variables in a `.env` file (e.g. `MONGO_URI`, `JWT_SECRET`).
3. Start the backend server:
npm start:
4. If you have a frontend directory, install its dependencies and start it similarly.
5. Access the app at `http://localhost:3000` (frontend) and `http://localhost:5000` (backend) in your browser.

---

**Not:** Bu proje eğitim ve demo amaçlıdır. Gerçek dünyada kullanırken ek güvenlik önlemleri almanız önerilir.

**Note:** This project is for educational/demo purposes. Please implement additional security precautions for production use.

---



