# Next.js Backend API

Bu loyiha Next.js va Vercel uchun tayyorlangan backend API hisoblanadi. CRUD (Create, Read, Update, Delete) funksiyalari mavjud.

## O'rnatish va Ishga Tushirish

1. **Node.js** o'rnatilganligiga ishonch hosil qiling.
2. Quyidagi buyruqlarni ishga tushiring:

```sh
npm install
npm run dev
```

## Vercelga Yuklash

1. Vercel CLI'ni o'rnating:
   ```sh
   npm install -g vercel
   ```
2. Vercelga login qiling:
   ```sh
   vercel login
   ```
3. Loyihani yuklang:
   ```sh
   vercel
   ```

Shundan so'ng, API `https://your-vercel-app.vercel.app/api/worker` kabi ishlaydi.

## API Endpointlar

- **GET** `/api/worker` - Ishchilarni olish
- **POST** `/api/worker` - Yangi ishchi qo‘shish
- **PUT** `/api/worker` - Ishchi ma’lumotlarini yangilash
- **DELETE** `/api/worker` - Ishchini o‘chirish

Boshqa endpointlar ham xuddi shu formatda ishlaydi.
