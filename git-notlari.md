# 🚀 Git ve Terminal Notlarım

# GitHub Nedir?
Git projelerini internet üzerinde saklama platformudur. Portföy oluşturmak için kullanılır ve açık kaynak projeler paylaşılabilir.
# Git Nedir?
Git bir versiyon kontrol sistemidir. Kodun geçmişini saklar. Değişiklikleri takip eder. Geri dönmeyi sağlar. Takım çalışmasını kolaylaştırır.
GitHub da Repository oluşturma, git push, Pull Request, Clone, Fork ve Private repository kullanımı.
## GitHub Temel İşlevleri 👇🏻 ##
- **Repository** → Proje alanı
- **Push** → GitHub’a gönderme
- **Pull Request** → Değişiklik önerme
- **Clone** → İndirme
- **Fork** → Kopyalama
- **Private** → Gizli proje

## Klasör ve Dosya Komutları
- **ls** → Bulunduğun klasördeki dosyaları listeler.
- **ls -a** → Gizli dosyaları gösterir.
- **ls -l** → Detaylı liste gösterir.
- **ls -la** → Gizli + detaylı liste.
- **pwd** → Bulunduğun konumu gösterir.
- **cd** → Klasör değiştirir.
- **cd ..** → Bir üst klasöre çıkar.
- **mkdir** → Yeni klasör oluşturur.
- **touch** → Yeni boş dosya oluşturur.
- **rm** → Dosya siler.
- **rm -rf** → Klasör ve içindekileri siler.
- **clear** → Terminali temizler.
- **mv** → Dosya veya klasör taşır.

## Git Temel Komutlar
- **git init** → Yeni repository (dönüştürme) başlatır.
- **git status** → Git’in güncel durumunu gösterir.
- **git add** → Dosyayı takibe alır (staging area).
- **git commit -m "mesaj"** → Değişiklikleri kalıcı kaydeder.
- **git log** → Commit geçmişini gösterir.
- **git log --oneline** → Commit geçmişini tek satır halinde gösterir.
- **git --version** → Yüklü Git sürümünü gösterir.
- **git config --global user.name** → Kullanıcı adını ayarlar.
- **git config --global user.email** → Email adresini ayarlar.

## Kavramlar
- **Repository (Repo)** → Versiyon kontrolü yapılan proje deposu.
- **Commit** → Değişikliklerin anlık görüntüsü (snapshot).
- **Branch** → Ana koddan ayrı bir çalışma hattı (dal).Aynı projede farklı çalışma alanları oluşturur. Ana dal main’dir. Yeni özellikler için ayrı branch açılır. Örnek: feature-login, bug-fix.

- **Staging Area** → Commit öncesi hazırlık alanı.
- **Insertions** → Ekleme.
- **Deletions** → Silme.
- **Head** → Git’in şu anda bulunduğu noktayı gösterir ve hangi branch’te olduğumuzu belirtir.
- **git stash** → Geçici kaydetme.
- **git stash pop** → Saklanan değişiklikleri geri getirir.
- **Checkout** → Branch değiştirme.(Geçmişe Dönme)
- **Reset** → Geçmişi geri alma.
- **Revert** → Güvenli şekilde geri alma ve yeni commit oluşturma.
- **Merge** → Branch’leri birleştirme işlemidir ve bir dalda yapılan değişiklikleri ana dala ekler.
- **Merge Conflict** → Aynı dosyada aynı satır değişirse oluşur. Git çakışmayı bildirir ve kullanıcı manuel olarak çözer.
**Gitignore** → Git’in takip etmesini istemediğimiz dosyalar için kullanılır. .gitignore dosyası oluşturulur. Örnek: node_modules, .env ve gereksiz sistem dosyaları.
