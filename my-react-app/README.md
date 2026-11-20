# EduPanel

O‘quv markazi uchun React asosidagi boshqaruv paneli.

## Ishga tushirish

Repo ildizida `npm install` va `npm run dev` buyruqlarini bajaring. Vite interfeysi `http://localhost:5173`, lokal JSON API esa `http://localhost:3001` manzilida ishlaydi. Kirish sahifasida **Ro‘yxatdan o‘tish** orqali yangi hisob yarating.

## Deploy

Ildizdagi `vercel.json` Vercel build sozlamalarini o‘z ichiga oladi. `npm run build` production frontend yaratadi.

## Ma’lumotlar va hisoblar

Ommaviy demo bazasi bo‘sh: unda oldindan yaratilgan login-parol yoki o‘quvchi ma’lumotlari yo‘q. Vercel demo rejimida foydalanuvchi hisobi va yozuvlar brauzerning `localStorage` xotirasida qoladi. Bu server tomonidagi autentifikatsiya va umumiy ma’lumotlar bazasining o‘rnini bosmaydi; haqiqiy production uchun alohida backend, xavfsiz parol xeshlash va ma’lumotlar bazasi kerak.