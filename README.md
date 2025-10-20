# CK44 Gold Intense Dashboard (Soft Shine + CK44 Signature)

**Domain:** https://panel231153.vercel.app/

Dashboard promosi CK44 dengan tema **Gold Intense**. Seluruh planner (Instagram, TikTok, YouTube, X, Threads, Reddit, LinkedIn, Medium) dimuat via `<iframe>` dari `public/assets/planners/`.

## Struktur
```
public/
  index.html
  assets/
    planners/
      CK44_Instagram_30Day_Planner_GoldIntense.html
      CK44_TikTok_30Day_Planner_GoldIntense.html
      CK44_YouTube_30Day_Planner_GoldIntense.html
      CK44_X_30Day_Planner_GoldIntense.html
      CK44_Threads_30Day_Planner_GoldIntense.html
      CK44_Reddit_30Day_Planner_GoldIntense.html
      CK44_LinkedIn_30Day_Planner_GoldIntense.html
      CK44_Medium_Planner_1_GoldIntense.html
vercel.json
.gitignore
```

## Deploy ke Vercel
1. Push folder ini ke **GitHub**.
2. Hubungkan repo ke **Vercel**.
3. Deploy → website tampil di domain project Vercel kamu.
4. Buka `https://panel231153.vercel.app/` → dashboard langsung tampil.

## Catatan
- File planner **harus** di `public/assets/planners/` agar dapat diakses iframe.
- `vercel.json` mengizinkan iframe (ALLOWALL) + CORS safe.
