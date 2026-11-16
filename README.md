# Akademik Makale & Atıf Ağı Kaşifi (Standalone Edition)

OpenAlex ve Crossref üzerinden 250M+ bilimsel yayını konu, yazar, kurum veya DOI ile tarayın; açık erişim PDF, yıllara göre atıf grafiği ve tek tıkla APA/IEEE/MLA/BibTeX kaynakça üretin.

- **Canlı Demo (GitHub Pages):** https://melihkarasu.github.io/akademik-radar/
- **Ana Proje (Monorepo):** [melihkarasu/VibeCodedApps](https://github.com/melihkarasu/VibeCodedApps)

## Mimari & Gizlilik Özellikleri
- **Sıfır Backend (Zero-Backend):** Tamamen tarayıcı üzerinde çalışır; kullanıcı verileri VibeRuntime üzerinden yalnızca localStorage içinde saklanır.
- **KVKK & GDPR Uyumu:** Google Fonts CDN veya 3. taraf takip betiği içermez; tüm fontlar (vendor/fonts/*.woff2) yerel olarak paketlenmiştir.

## Lokal Çalıştırma
```bash
npx serve .
```
