<p align="center">
  <img src="assets/logo.png" alt="TrioBank Logo" width="150" />
</p>

<h1 align="center">TrioBank</h1>

<p align="center">
  Modern, ölçeklenebilir bir çevrimiçi bankacılık uygulaması.
  <br />
  Bu proje, okul ödevi kapsamında "mikroservis mimarisi" ve "olay güdümlü tasarım" (Event-Driven Architecture) kullanılarak geliştirilmektedir.
  <br /><br />
  <img src="https://img.shields.io/badge/status-development-yellow" alt="Proje Durumu: Geliştirme Aşamasında" />
  <img src="https://img.shields.io/badge/team-3_developers-blue" alt="Ekip Büyüklüğü" />
</p>

---

### 🚀 Proje Vizyonu ve Hedefleri

**TrioBank**, modern bankacılık sistemlerinin temel gereksinimlerini karşılayan, **ölçeklenebilir**, **dayanıklı (resilient)** ve **bakımı kolay** bir sistem oluşturmayı amaçlar. Bu projede özellikle aşağıdaki teknik hedeflere odaklanıyoruz:

* **Mikroservis Mimarisi:** İş mantığını bağımsız servisler (Kullanıcı, Hesap, Transfer vb.) üzerinden yönetmek, servisler arası bağımlılığı en aza indirmek.
* **Olay Güdümlü (Event-Driven) Tasarım:** Servisler arası iletişimi asenkron mesajlaşma (Apache Kafka, RabbitMQ) ile sağlamak.
* **Outbox Pattern:** Veritabanı işlemleri ile mesaj gönderimlerini atomik hale getirerek veri tutarlılığını garanti altına almak.
* **Polyglot Programlama:** İş gereksinimlerine göre doğru araçları kullanmak; örneğin **Java (Spring Boot)** ve **Go (Golang)**.

---

### 💻 Teknoloji Yığını (Tech Stack)

| Kategori | Teknoloji |
| :--- | :--- |
| **Backend** | <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" /> <img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white" alt="Spring" /> <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go" /> |
| **Frontend** | <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" /> |
| **Veritabanı** | <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" /> |
| **Mesajlaşma & Olay** | <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" alt="Kafka" /> <img src="https://img.shields.io/badge/Debezium-316192?style=for-the-badge&logo=debezium&logoColor=white" alt="Debezium" /> |
| **Araçlar & DevOps** | <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" /> <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes" /> <img src="https://img.shields.io/badge/GitHub-A4AAFF?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /> |

---

### 🏗️ Yüksek Seviye Mimari (High-Level Architecture)

Sistem mimarisi temel olarak şu katmanlardan oluşur:

1. **API Gateway:** Tüm istekleri karşılar, kimlik doğrulama ve yönlendirme sağlar.
2. **Mikroservisler:** Account, Transaction, Payment vb. bağımsız servisler.
3. **Mesajlaşma Katmanı:** Servisler arası asenkron veri iletimi için Kafka kullanılır.
4. **Veritabanı:** Her servis kendi veri deposuna sahiptir.

---

### 👥 Ekibimiz (The "Trio")

| Avatar | İsim | GitHub |
| :---: | :---: | :---: |
| <img src="https://github.com/akyurekridvan2101.png?size=75" alt="Rıdvan Akyürek" width="75" style="border-radius:50%"> | Rıdvan AKYÜREK | [@akyurekridvan2101](https://github.com/akyurekridvan2101) |
| <img src="https://github.com/bereketis72.png?size=75" alt="Bereket İş" width="75" style="border-radius:50%"> | Bereket İŞ | [@bereketis72](https://github.com/bereketis72) |
| <img src="https://github.com/samedozturk.png?size=75" alt="Samed Öztürk" width="75" style="border-radius:50%"> | Samed ÖZTÜRK | [@samedozturk](https://github.com/samedozturk) |

---

### 📂 Proje Depoları (Repositories)



---

### 📜 Lisans

Bu proje MIT Lisansı altında yayımlanmıştır. Detaylar için `LICENSE` dosyasına bakabilirsiniz.
