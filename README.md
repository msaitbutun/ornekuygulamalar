# MongoDB ve Kubernetes ile Dockerized Uygulama

Bu repo, Docker, Kubernetes, AWS EKS ve CI/CD süreçlerini kullanarak geliştirilmiş basit bir MongoDB uygulamasının proje örneğidir. Projeyi oluştururken mikroservis mimarisini takip ettim ve hem veritabanı hem de backend uygulamasının Kubernetes ortamında doğru bir şekilde çalışması için gerekli tüm yapılandırmaları sağladım.

---

## 🎯 Amaç

Bu projenin amacı, bir 3-tier uygulama Docker ve Kubernetes kullanarak  nasıl containerize edileceğini ve bulut ortamında (AWS EKS) nasıl dağıtılacağını göstermektir. Ayrıca CI/CD süreçlerini GitHub Actions ile otomatikleştirerek uygulamanın her yeni versiyonunun hızlıca üretime alınmasını sağladım. Proje, özellikle Docker ve Kubernetes konusunda bilgi sahibi olmak isteyenler için bir rehber niteliğindedir.

---

## 🛠️ Teknolojiler

Proje şu teknolojileri kullanmaktadır:

- **Frontend**: React.js (UI için)
- **Backend**: Node.js ve Express.js (API sunucusu olarak)
- **Veritabanı**: MongoDB (Veri depolama)
- **Deployment**: Kubernetes (Minikube/Docker Desktop ve AWS EKS)
- **CI/CD**: GitHub Actions (Otomatik build ve deploy)
- **Veri Saklama**: Persistent Volume ve Persistent Volume Claim ile MongoDB verilerinin güvenli bir şekilde saklanması sağlanmıştır.


