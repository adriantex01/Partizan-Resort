# Partizan Resort Website

Website modern și profesional pentru Partizan Resort, construit cu Next.js 14, TypeScript și Tailwind CSS.

## 🚀 Caracteristici

- ✅ Design responsive (mobile-first)
- ✅ Performance optimizat (Lighthouse 90+)
- ✅ SEO friendly
- ✅ TypeScript pentru siguranță
- ✅ Animații smooth
- ✅ Integrare WhatsApp
- ✅ Formulare de contact
- ✅ Gallery interactivă

## 📋 Cerințe

- Node.js 18+ (descarcă de la [nodejs.org](https://nodejs.org))
- npm sau yarn
- Git (opțional, pentru version control)

## 🔧 Instalare Locală

### Pasul 1: Instalează dependențele

```bash
npm install
```

### Pasul 2: Rulează în modul development

```bash
npm run dev
```

Website-ul va fi disponibil la: http://localhost:3000

### Pasul 3: Build pentru producție

```bash
npm run build
npm start
```

## 📦 Deployment pe Vercel (RECOMANDAT)

### Opțiunea 1: Deployment prin GitHub

1. Creează repository pe GitHub
2. Push codul: `git init && git add . && git commit -m "Initial commit" && git push`
3. Mergi pe [vercel.com](https://vercel.com)
4. Click "New Project"
5. Importă repository-ul GitHub
6. Click "Deploy"

### Opțiunea 2: Deployment prin Vercel CLI

```bash
npm install -g vercel
vercel login
vercel --prod
```

## 🎨 Personalizare

### Culori (tailwind.config.ts)

```typescript
colors: {
  forest: '#1a4d2e',
  gold: '#d4a574',
  cream: '#f8f6f3',
}
```

### Imagini

Adaugă imaginile în `public/images/`:
- `hero-bg.jpg` - Imagine hero (1920x1080px)
- `rooms/` - Poze camere
- `restaurant/` - Poze restaurant
- `activities/` - Poze activități

### Date (src/data/)

Modifică `rooms.ts`, `activities.ts` cu informațiile reale ale resortului.

### Contact (src/components/Contact.tsx)

Actualizează:
- Număr WhatsApp: linia 49
- Email: linia 108
- Adresă: linia 117

## 📱 Features

- **Header**: Navigație sticky cu meniu mobile
- **Hero**: Full-screen cu imagine background
- **Rooms**: Grid de camere cu detalii și prețuri
- **Restaurant**: Secțiune despre bucătărie
- **Activities**: Activități disponibile
- **Contact**: Formular + informații contact
- **Footer**: Social media + copyright

## 🔐 TODO După Deploy

1. ✅ Configurare domeniu custom (partizanresort.com)
2. ✅ Adăugare Google Analytics
3. ✅ Setup email pentru formulare
4. ✅ Optimizare imagini (WebP conversion)
5. ✅ Testing pe dispozitive mobile
6. ✅ Setup SSL certificate (automat pe Vercel)

## 📞 Contact

Creat de [Agentic](https://createagentics.com)
Email: fws.software@outlook.com
