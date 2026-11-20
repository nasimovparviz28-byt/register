# EduPanel

O‘quv markazi uchun React asosidagi boshqaruv paneli.

## Ishga tushirish

Repo ildizida `npm install` va `npm run dev` buyruqlarini bajaring. Vite interfeysi `http://localhost:5173`, lokal JSON API esa `http://localhost:3001` manzilida ishlaydi. Kirish sahifasida **Ro‘yxatdan o‘tish** orqali o‘zingizning login-parolingizni yarating.

## Namuna ma’lumotlari

Boshlang‘ich demo bazada to‘rtta guruh, to‘qqizta namuna talaba, beshta to‘lov va uchta davomat yozuvi bor. Ismlar va telefonlar sinov uchun to‘qib chiqarilgan. Oldindan yaratilgan admin hisobi yo‘q.

## Deploy va saqlash

Ildizdagi `vercel.json` Vercel build sozlamalarini o‘z ichiga oladi. `npm run build` production frontend yaratadi. Vercel demo rejimida ma’lumotlar brauzerning `localStorage` xotirasida saqlanadi. Bu umumiy, server tomonidagi autentifikatsiya va ma’lumotlar bazasining o‘rnini bosmaydi.