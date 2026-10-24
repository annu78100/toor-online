# Toor Online — Website Starter

یہ ایک مفت، responsive، single-page ویب سائٹ ہے۔ اسے چلانے کے لیے کوئی paid framework یا build tool ضروری نہیں۔

## فائلیں
- `index.html` — مکمل ویب سائٹ (HTML، CSS، JavaScript ایک ہی فائل میں)

## کمپیوٹر پر دیکھنے کا طریقہ
1. ZIP فائل extract کریں۔
2. `index.html` پر double-click کریں۔
3. ویب سائٹ browser میں کھل جائے گی۔

## شائع کرنے سے پہلے لازمی تبدیلی
1. `index.html` کو کسی text/code editor میں کھولیں۔
2. آخر میں JavaScript میں یہ لائن تلاش کریں:
   `const BUSINESS_EMAIL = "YOUR_EMAIL@example.com";`
3. `YOUR_EMAIL@example.com` کی جگہ اپنا اصل business email لکھیں۔
4. پورٹ فولیو کے sample tiles کو اپنے اصل کام سے بدلیں۔
5. Starter / Product Promo / Campaign کے deliverables اور prices اپنی اصل سروس کے مطابق طے کریں۔

## موبائل سے ترمیم
آپ کسی text/code editor ایپ میں `index.html` کھول کر تبدیلی کر سکتے ہیں۔ بہتر ہے کہ اصل ZIP کی ایک backup copy محفوظ رکھیں۔

## مفت Cloudflare Pages پر شائع کرنے کا آسان طریقہ
Cloudflare کے dashboard میں Pages کھولیں۔ اگر آپ کے اکاؤنٹ میں Direct Upload دستیاب ہو تو نئی Pages project بنائیں اور extracted فائلیں upload کریں۔ ورنہ GitHub پر repository بنائیں، `index.html` اپلوڈ کریں، پھر Cloudflare Pages میں Git repository connect کریں۔ Static HTML کے لیے build command درکار نہیں؛ output directory میں `index.html` موجود ہونا چاہیے۔ Dashboard کے موجودہ labels مختلف ہو سکتے ہیں۔

سرکاری گائیڈ:
https://developers.cloudflare.com/pages/get-started/

## اپنا domain
پہلے مفت `*.pages.dev` address پر ویب سائٹ test کریں۔ Custom domain بعد میں Cloudflare Pages کے Custom domains حصے سے add کیا جا سکتا ہے۔ اپنا domain عام طور پر خریدنا پڑتا ہے؛ hosting کا مفت ہونا domain کو مفت نہیں بناتا۔
https://developers.cloudflare.com/pages/configuration/custom-domains/

## اہم حدود
- یہ static website ہے؛ form فی الحال آپ کے device پر email app کھولنے کی کوشش کرتا ہے، server پر messages محفوظ نہیں کرتا۔
- email placeholder بدلے بغیر form inquiry وصول نہیں کرے گا۔
- Online payment, user accounts, admin dashboard اور order database شامل نہیں ہیں۔ یہ بعد میں الگ backend یا third-party service سے شامل کیے جا سکتے ہیں۔
