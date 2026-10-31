# Himoya Yordamchi — o'rnatish yo'riqnomasi

Bu ilovada AI yo'q va API puli kerak emas. U mashq va tartib uchun vositalar to'plami: nutq taymeri, savollar kartochkalari, reja va Claude uchun tayyor promptlar. AI qismi Claude'dagi Himoya Agenti Project'ida ishlaydi.

## Fayllar
- `index.html` — ilovaning o'zi
- `manifest.json`, `sw.js`, `icon-192.png`, `icon-512.png` — telefonga o'rnatish va oflayn ishlash uchun

## 1-yo'l: eng oson (APK shart emas)
1. Papkani bepul hostingga joylang, masalan **GitHub Pages** yoki **Netlify Drop** (papkani sudrab tashlash kifoya).
2. Telefonda Chrome'da olingan havolani oching.
3. Menyu (⋮) → **«Bosh ekranga qo'shish»** / **«Ilovani o'rnatish»**.
4. Ilova oddiy ilova kabi ochiladi va internetsiz ham ishlaydi.

## 2-yo'l: APK olish
1. Yuqoridagi 1-qadamdagi hosting havolasi tayyor bo'lsin (HTTPS bo'lishi shart).
2. **pwabuilder.com** saytini oching, havolani kiriting va **Start** bosing.
3. **Package for stores → Android** ni tanlang, **Generate** qiling va APK ni yuklab oling.
4. Telefonga ko'chirib o'rnating (Sozlamalarda «noma'lum manbalardan o'rnatish»ga ruxsat kerak bo'lishi mumkin).

## Ishlatish tartibi
1. **Bosh**: himoya sanasi va dissertatsiya ma'lumotlarini kiriting.
2. **Claude**: rejimni tanlang → «Nusxalash» → Claude Project'iga joylang.
3. **Savol**: Claude'dagi `/savol` natijasini ommaviy qo'shishga joylang va kartochkalar bilan mashq qiling.
4. **Nutq**: nutqni joylab, taymer bilan ayting.
5. **Reja**: tayyorgarlik bandlarini belgilab boring.

Ma'lumotlar faqat telefoningiz brauzerida saqlanadi. Vaqti-vaqti bilan **Bosh → Zaxira nusxa** ni ishlating.
