# EduPanel

O'quv markazi boshqaruv paneli. Frontend `my-react-app` ichida joylashgan.

## Ishga tushirish

Node.js o'rnatilgan bo'lishi kerak. Repo ildizida `npm install` va `npm run dev` buyruqlarini bajaring. Vite interfeysi `http://localhost:5173`, lokal JSON API esa `http://localhost:3001` da ishlaydi.

Yangi hisob yaratish uchun kirish sahifasidagi **Ro'yxatdan o'tish** tugmasidan foydalaning. Nashr qilinadigan demo bazada oldindan yaratilgan admin, parol yoki shaxsiy o'quvchi ma'lumotlari yo'q.

## Deploy

Repo Vercel bilan ulanganda ildizdagi `vercel.json` build komandasi, output papkasi va React Router rewrite qoidalarini sozlaydi. Build: `npm run build`.

## Ma'lumotlar va hisoblar

Vercel demo rejimida yozuvlar shu brauzerning localStorage xotirasida saqlanadi; akkaunt va ma'lumotlar turli qurilmalar/brauzerlar orasida sinxronlanmaydi. Bu frontend demo hisoblanadi, production uchun server tomondagi autentifikatsiya, parol xeshlash va umumiy ma'lumotlar bazasi alohida sozlanishi kerak.