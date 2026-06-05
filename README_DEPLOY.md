# Olesya Saifullina — bilingual portfolio landing

Внутри уже есть:
- `index.html` — одностраничный лендинг с переключателем RU / EN;
- `assets/olesya-photo.png` — фотография;
- `assets/Olesya_Saifullina_CV_RU.pdf` — русское резюме;
- `assets/Olesya_Saifullina_CV_EN.pdf` — английское CV.

## Как опубликовать на GitHub Pages

1. Создайте репозиторий, например `olesya-portfolio`.
2. Загрузите содержимое этой папки в корень репозитория: `index.html`, папку `assets`, файл `.nojekyll`.
3. Откройте `Settings → Pages`.
4. Включите публикацию из ветки `main`, папка `/root`.
5. Если есть поддомен, в поле `Custom domain` укажите его, например `cv.repiq.ru` или `olesya.repiq.ru`.
6. У провайдера домена добавьте DNS-запись CNAME:
   - имя: `cv` или `olesya` — зависит от выбранного поддомена;
   - значение: `ВАШ_ЛОГИН.github.io`.
7. После проверки DNS включите `Enforce HTTPS`.

## Если хотите задать домен через файл CNAME

Создайте файл `CNAME` в корне репозитория и впишите в него только домен, например:

```text
cv.repiq.ru
```

или

```text
olesya.repiq.ru
```
