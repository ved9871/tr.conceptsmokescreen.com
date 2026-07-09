# tr.smoke-screen.com

Smoke Screen güvenlik dumanı sistemlerinin Türkiye pazarı için Türkçe web sitesi. [us.smoke-screen.com](https://us.smoke-screen.com) sitesinin yapısı ve tasarımı birebir korunarak içerik Türkçeye çevrilmiştir.

## Durum

- `index.html`, `products.html`, `about.html`, `videos.html`, `contact.html`, `news.html`, `thank-you.html` — tamamen Türkçeye çevrildi.
- `applications.html` — **çevrilmedi, kaynak site üzerinde bilinçli olarak dokunulmadı.** Kaynak dosyanın kendisi "Data Centres & Server Rooms" kartının ortasında kesiliyor (canlı sitede doğrulandı, 22.061 bayt, kapanış etiketleri, CTA veya footer yok). Bu sayfa çevrilmeden önce eksik içeriğin ABD sitesini yöneten ekipten temin edilmesi gerekiyor.
- `legal/privacy.html`, `legal/terms.html`, `blog/` — kaynak sitede mevcut değil (404), bu nedenle oluşturulmadı.

## Bekleyen kararlar (müşteriden gelecek)

- Türkiye ofis adresi, telefon numarası ve isimlendirilmiş yerel iletişim kişisi (şu an İngiltere merkez ofisi bilgileriyle geçici olarak dolduruldu).
- Case study (`news.html`, anasayfadaki vaka analizi bölümü) şu an Kanada'daki bir kuyumcuyla ilgili — Türkiye'ye özgü bir örnekle değiştirilmesi önerilir.
- İletişim formundaki Ülke/Mülk Türü açılır listelerinin son hali.
- Para birimi gösterimi (₺ / GBP / EUR / USD).
- "Sigorta Onaylı" iddiası şu an Türkiye'ye özgü bir sigorta şirketi referansı olmadan genel bırakıldı.
- `applications.html` içindeki "Cannabis Dispensaries" kartı Türkiye'de yasal bir perakende kategorisi değil — yerel bir sektörle değiştirilmesi önerilir.

## Çeviri kaynağı

Tüm çeviri eşleştirmeleri `../translations/smoke-screen-tr-translations.json` ve `.csv` dosyalarında saklanır (İngilizce → Türkçe, sayfa/anahtar bazında, notlarla birlikte).

## Dağıtım

Henüz bir GitHub deposuna veya `tr.conceptsmokescreen.com` alan adına dağıtılmadı. Form gönderim yönlendirmesi (`_next`) şu an `https://ved9871.github.io/tr.smoke-screen.com/thank-you.html` adresine ayarlı — gerçek dağıtım URL'si netleşince güncellenmeli.
