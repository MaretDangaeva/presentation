# Фото или нейросеть? · Урок 20

Игра на 8 раундов для детей 1–4 классов, запускается прямо в браузере через GitHub Pages.

## Запуск
https://maretdangaeva.github.io/presentation/kodik-lab/guess-ai/

**Все 16 изображений хранятся локально в `images/` этого репозитория.** Никаких запросов на Wikimedia Commons для загрузки картинок больше нет. Игра не требует регистрации.

## Происхождение изображений
Нейросетевые изображения: образцы генерации из репозиториев [CompVis/stable-diffusion](https://github.com/CompVis/stable-diffusion) и [CompVis/latent-diffusion](https://github.com/CompVis/latent-diffusion). Фото: реальные изображения из демонстрационного набора [OpenCV](https://github.com/opencv/opencv/tree/4.x/samples/data). Источники отдельных файлов указаны после каждого ответа в игре и далее в списке:

- `ai-1.png` — https://github.com/CompVis/stable-diffusion/blob/main/assets/stable-samples/txt2img/000002025.png
- `photo-1.jpg` — https://github.com/opencv/opencv/blob/4.x/samples/data/building.jpg
- `ai-2.png` — https://github.com/CompVis/stable-diffusion/blob/main/assets/stable-samples/txt2img/000002035.png
- `photo-2.jpg` — https://github.com/opencv/opencv/blob/4.x/samples/data/castle.jpg
- `ai-3.png` — https://github.com/CompVis/stable-diffusion/blob/main/assets/stable-samples/img2img/mountains-1.png
- `photo-3.jpg` — https://github.com/opencv/opencv/blob/4.x/samples/data/home.jpg
- `ai-4.png` — https://github.com/CompVis/stable-diffusion/blob/main/assets/stable-samples/img2img/mountains-2.png
- `photo-4.jpg` — https://github.com/opencv/opencv/blob/4.x/samples/data/aloeL.jpg
- `ai-5.png` — https://github.com/CompVis/stable-diffusion/blob/main/assets/stable-samples/img2img/mountains-3.png
- `photo-5.jpg` — https://github.com/opencv/opencv/blob/4.x/samples/data/butterfly.jpg
- `ai-6.png` — https://github.com/CompVis/latent-diffusion/blob/main/assets/txt2img-convsample.png
- `photo-6.jpg` — https://github.com/opencv/opencv/blob/4.x/samples/data/apple.jpg
- `ai-7.png` — https://github.com/CompVis/latent-diffusion/blob/main/assets/birdhouse.png
- `photo-7.jpg` — https://github.com/opencv/opencv/blob/4.x/samples/data/squirrel_cls.jpg
- `ai-8.png` — https://github.com/CompVis/latent-diffusion/blob/main/assets/a-photograph-of-a-fire.png
- `photo-8.jpg` — https://github.com/opencv/opencv/blob/4.x/samples/data/orange.jpg

Игра учит не полагаться на внешние признаки изображения и проверять его происхождение. Некоторые сравниваемые изображения изображают разные объекты; цель — потренировать проверку источников, а не заявлять, что ИИ всегда узнаётся по визуальным артефактам.

## Для преподавателя
Используйте игру во время ожидания второй генерации в Leonardo (~4–5 минут). При неудачном ответе показывается корректное происхождение обеих картинок. `index.html` и папка `images/` должны находиться рядом.

## Лицензии и атрибуция
Проверяйте условия исходных репозиториев и материалов перед дальнейшим переиспользованием. При распространении самой игры сохраняйте ссылки на первоисточники.
