PostHire — Vercel Ready Package
=================================

FILES:
  index.html       → Landing Page (homepage)
  dashboard.html   → User Dashboard
  admin.html       → Admin Panel
  vercel.json      → Vercel config (clean URLs)
  firestore.rules  → Paste in Firebase Console → Firestore → Rules

VERCEL DEPLOY:
  1. Go to vercel.com → New Project
  2. Upload this folder OR connect GitHub repo
  3. No build settings needed (static site)
  4. Deploy!

URLs after deploy:
  yourdomain.vercel.app/          → Landing Page
  yourdomain.vercel.app/dashboard → Dashboard
  yourdomain.vercel.app/admin     → Admin Panel

FIRESTORE RULES:
  Firebase Console → Firestore → Rules → paste firestore.rules → Publish

ADMIN LOGIN:
  Create admin user in Firebase Console → Authentication → Add user
  Email: admin@posthire.in
  Password: (set your own strong password)
