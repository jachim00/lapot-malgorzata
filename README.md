# Małgorzata Łapot — fizjoterapia dziecięca

Landing page dla gabinetu fizjoterapii dziecięcej **Małgorzata Łapot**
(FizjoFinezja · Grodzisk Mazowiecki).

## Live

→ **https://<TWÓJ-LOGIN>.github.io/lapot-fizjoterapia/**

## Kontent

- **Nacisk na ćwiczenia z dziećmi** — jak Gosia pracuje, jakie ćwiczenia,
  dla kogo, co dziecko widzi w gabinecie
- **Specjalizacje**: wady postawy, skoliozy, MPD, zaburzenia neurorozwojowe
  (ADHD, spektrum autyzmu), wady genetyczne (Zespół Downa), niemowlęta,
  integracja sensoryczna, stopy
- **Metody**: DNS (Kolar), Integracja Sensoryczna (PSTIS), Zukunft-Huber,
  Igli/Medi, terapia skolioz, terapia neurorozwojowa
- **FAQ** z 8 najczęstszymi pytaniami rodziców
- **Kontakt**: tel 503 360 596, email lapot.malgorzata@gmail.com

## Stack

- Pure HTML + CSS (inline) — self-contained, zero build
- Fraunces + Inter (Google Fonts)
- Zdjęcia w `assets/` — rzeczywiste Małgorzaty + AI-generowane sceny ćwiczeń z dziećmi
- Responsive: desktop + tablet + mobile

## Struktura

```
/
├── index.html           # cała strona
├── assets/
│   ├── logo.jpg                        # logo MŁ Fizjoterapia Dziecięca
│   ├── ai-cwiczenie-plank.jpg          # hero — ćwiczenie stabilizacji
│   ├── ai-cwiczenie-poduszka.jpg       # ćwiczenie propriocepcji
│   ├── ai-diagnostyka-kregoslup.jpg    # konsultacja z rodzicem
│   ├── ai-hobby-plaza.jpg              # lifestyle
│   ├── real-gabinet-mata.jpg           # Małgorzata w gabinecie
│   ├── real-portret-niebieski.jpg      # portret zawodowy
│   ├── real-certyfikat-medi.jpg        # z certyfikatem Igli
│   ├── real-konferencja-awf.jpg        # konferencja Pro Scoliosis
│   └── real-jezioro.jpg                # hobby (fotografia)
└── .nojekyll                           # GitHub Pages — bez Jekyll
```

## Update strony

Edytuj `index.html` lokalnie, wrzuć na GitHub (drag & drop w repo),
commit → zmiany żyją w ~30 sek.
