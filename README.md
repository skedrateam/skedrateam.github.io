# Schedy — GitHub Pages Template

Bu klasör App Store Connect için gereken temel sayfaları sağlar:

- Marketing/Home: `index.html`
- Support: `support/index.html`
- Privacy Policy: `privacy/index.html`
- Terms: `terms/index.html`

## Kurulum (GitHub Pages)

1) GitHub’da bir repo oluştur:
   - Tercih edilen: `muhammedkilinc.github.io` (user page → URL kökten çalışır)
   - Alternatif: herhangi bir repo (project page → URL `/repo-adi/` altından çalışır)
2) Bu klasördeki dosyaları repo **root**’a kopyala.
3) Repo → Settings → Pages:
   - Source: `Deploy from a branch`
   - Branch: `main` / `/ (root)`
4) Yayına çıktıktan sonra URL’leri Fastlane metadata’ya yaz:
   - `fastlane/metadata/en-US/marketing_url.txt`
   - `fastlane/metadata/en-US/support_url.txt`
   - `fastlane/metadata/en-US/privacy_url.txt`

Not: Linkler project page senaryosunda da çalışması için **relative** tutuldu.

