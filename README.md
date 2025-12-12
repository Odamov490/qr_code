# PDF QR (GitHub Pages, serversiz)

Sodda yechim:
- PDF fayllar GitHub’da turadi
- QR doim bitta URL’ga qaraydi (o‘zgarmaydi)
- Keyin PDF yangilansa — faqat faylni almashtirasiz

## QR link
`https://USERNAME.github.io/REPO/p.html?id=ESW8-000124`

## Qanday joylash
1) GitHub’da repo yarating (masalan: `pdf-qr`)
2) Shu zipdagi `docs/` papkani repo ichiga joylang
3) Repo → Settings → Pages:
   - Deploy from a branch
   - Branch: main
   - Folder: /docs

## PDF qo‘shish
`docs/pdfs/ESW8-000124.pdf`

## QR yaratish + manifest yozuvi
`https://USERNAME.github.io/REPO/admin.html`

## PDF yangilash (QR o‘zgarmaydi)
Eng oson yo‘l:
- eski `docs/pdfs/ESW8-000124.pdf` ni
- yangi PDF bilan **o‘sha nomda** almashtiring (commit) ✅
