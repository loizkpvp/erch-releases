# Erch

Бесплатный музыкальный плеер для Windows. Ищите песни, сохраняйте любимые треки, собирайте очередь, импортируйте плейлисты и читайте текст во время прослушивания. Можно слушать и музыку с компьютера.

Erch ищет музыку в каталогах Deezer и SoundCloud и подбирает доступную полную запись. Звук поступает от музыкальных площадок через их официальные плееры или доступные прямые потоки. Доступность конкретной песни зависит от источника и вашей сети.

[Скачать для Windows](https://github.com/loizkpvp/erch-releases/releases/latest) · [Сайт Erch](https://erch-seven.vercel.app)

<details>
<summary>Приложение открывается, но музыка не играет</summary>

Сеть может ограничивать доступ к музыкальной площадке или её аудиопотокам. Если вы используете [zapret-discord-youtube](https://github.com/Flowseal/zapret-discord-youtube), добавьте приведённые ниже домены в `lists/list-general-user.txt` внутри папки zapret. Сохраните свои существующие записи. В этой сборке zapret поддомены учитываются автоматически.

```text
cdn-images.dzcdn.net
erch-api.dodloz385.workers.dev
erch-seven.vercel.app
github.com
googlevideo.com
mipxgdbumehdzejtnhpx.supabase.co
mixcloud.com
objects.githubusercontent.com
release-assets.githubusercontent.com
rutube.ru
sndcdn.com
soundcloud.com
youtube-nocookie.com
youtube.com
ytimg.com
```

Записывайте по одному домену на строке, без `https://`, путей и IP-адресов. После сохранения перезапустите используемую стратегию zapret. Если она не помогает, подбор стратегии описан в документации zapret.

Это начальный список для Erch, сайта, входа, обновлений и основных музыкальных источников. В нём есть домены аудио и видео: одного адреса сайта Erch для воспроизведения недостаточно. Дополнительные источники могут использовать другие домены.

Настройка добровольная. Erch не устанавливает zapret и не меняет системный файл hosts. Работа этой настройки без VPN в России и Беларуси пока не подтверждена. Zapret не устраняет все виды ограничений сети или самой площадки.

</details>
