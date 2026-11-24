# Trade Journal — GitHub Pages-д нийтлэх заавар

Энэ багцад аппын бүх шаардлагатай файл орсон. Тусдаа build хийх шаардлагагүй.

## Нийтлэх алхам
1. `trade-journal-github-pages.zip` файлыг татаж аваад задлана.
2. Доторх файлуудыг GitHub repository-ийн үндсэн хавтас руу бүгдийг нь оруулна. ZIP файлыг дангаар нь оруулж болохгүй.
3. GitHub дээр өөрчлөлтөө `main` салбарт хадгална (commit).
4. Repository → **Settings → Pages** рүү орно.
5. **Deploy from a branch** сонгоပြီး branch ကို `main`, folder ကို `/(root)` လုပ်ပြီး သိမ်းပါ.
6. Publish ပြီးသွားတဲ့အခါ app link ကို ဖွင့်ပါ။

Таны repository `Trade-Journal-` нэртэй бол нийтлэгдсэн manifest-ийн жишээ хаяг:
`https://kyuk57913-source.github.io/Trade-Journal-/manifest.webmanifest`

Энэ холбоос нээгдэхэд JSON текст харагдах ёстой. Хэрэв 404 гарвал файл root түвшинд ороогүй эсвэл Pages deployment дуусаагүй байна.

## Өгөгдлөө хамгаалах
Trade мэдээлэл утас/браузерын дотоод санах ойд хадгалагдана. Тогтмол Backup export хийж хадгалаарай. Аппыг устгахаас өмнө заавал нөөц хуулбар үүсгэнэ.

## Багцын файлууд
- `index.html` — апп
- `manifest.webmanifest` — суулгах мэдээлэл
- `sw.js` — offline cache
- `assets/app-icon-192.png`, `assets/app-icon-512.png` — app icon
- `assets/app-icon-master.png` — өндөр нягтаршилтай эх logo
- `.nojekyll` — GitHub Pages тохиргооны файл
