# Testmedusa E-commerce Project

A full-stack e-commerce application built with Medusa and Next.js.

## 🚀 Live Demo

- **Storefront**: [Coming Soon - Backend deployment required]
- **Repository**: [https://github.com/successfulfadwa/testmedusa](https://github.com/successfulfadwa/testmedusa)

## 📦 Project Structure

```
testmedusa/
├── testmedusa/              # Medusa backend
│   ├── src/
│   │   ├── admin/          # Admin dashboard customizations
│   │   ├── api/            # Custom API routes
│   │   ├── workflows/      # Business logic workflows
│   │   └── ...
│   └── medusa-config.ts    # Backend configuration
│
└── testmedusa-storefront/   # Next.js storefront
    ├── src/
    │   ├── app/            # Next.js 15 app directory
    │   ├── modules/        # Feature modules
    │   └── lib/            # Utilities and data layer
    └── next.config.js      # Frontend configuration
```

## 🛠️ Tech Stack

### Backend (Medusa)
- Medusa v2
- TypeScript
- PostgreSQL
- Redis (optional)

### Frontend (Next.js Storefront)
- Next.js 15
- React 19
- TypeScript
- Tailwind CSS
- Medusa UI

## 🏃 Running Locally

### Prerequisites
- Node.js 18+ 
- PostgreSQL
- Yarn or npm

### Backend Setup

```bash
cd testmedusa
npm install
npm run dev
```

The Medusa backend will run on `http://localhost:9000`

### Storefront Setup

```bash
cd testmedusa-storefront
npm install
npm run dev
```

The storefront will run on `http://localhost:8000`

## 🔑 Environment Variables

### Backend (.env)
```env
DATABASE_URL=postgresql://...
REDIS_URL=redis://...
JWT_SECRET=...
COOKIE_SECRET=...
```

### Storefront (.env.local)
```env
NEXT_PUBLIC_MEDUSA_PUBLISHABLE_KEY=pk_...
MEDUSA_BACKEND_URL=http://localhost:9000
NEXT_PUBLIC_BASE_URL=http://localhost:8000
NEXT_PUBLIC_DEFAULT_REGION=us
```

## 📚 Documentation

- [Medusa Documentation](https://docs.medusajs.com)
- [Next.js Documentation](https://nextjs.org/docs)

## 👩‍💻 Author

**Fadwa Aljaoui**
- GitHub: [@successfulfadwa](https://github.com/successfulfadwa)
- LinkedIn: [fadwa-aljaoui](https://www.linkedin.com/in/fadwa-aljaoui-5846b523b/)
- Website: [www.Aljaoui.com](http://www.aljaoui.com/)

## 📄 License

This project is open source and available under the MIT License.

---

⭐ If you find this project useful, please consider giving it a star!
