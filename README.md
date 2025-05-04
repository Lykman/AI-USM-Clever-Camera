<h1 align="center">AI USM</h1>

<p align="center">
  Система смены лиц в режиме реального времени с одним кликом и использованием всего одного изображения.
</p>

<p align="center">
<a href="https://trendshift.io/repositories/11395" target="_blank"><img src="https://trendshift.io/api/badge/repositories/11395" alt="hacksider%2FDeep-Live-Cam | Trendshift" style="width: 250px; height: 55px;" width="250" height="55"/></a>
</p>

<p align="center">
  <img src="media/demo.gif" alt="Demo GIF" width="800">
</p>

##  Предупреждение

Данное программное обеспечение для замены лиц разработано как продуктивный инструмент для индустрии медиа, созданных с помощью ИИ. Оно может помочь художникам в анимации персонажей, создании привлекательного контента и даже использовании моделей для дизайна одежды.

Мы осознаем потенциал неэтичного применения и привержены превентивным мерам. Встроенная проверка предотвращает обработку неприемлемых материалов (обнаженные тела, графический контент, чувствительные материалы, такие как кадры военных действий и т.д.). Мы продолжим ответственно развивать этот проект, соблюдая закон и этику. Мы можем прекратить проект или добавить водяные знаки, если это потребуется по закону.

- Этичное использование: Ожидается, что пользователи будут использовать это программное обеспечение ответственно и законно. При использовании лица реального человека получите его согласие и четко обозначьте любой результат как дипфейк при публикации в интернете.

- Ограничения контента: Программное обеспечение включает встроенные проверки для предотвращения обработки неприемлемых материалов, таких как обнаженные тела, графический контент или чувствительные материалы.

- Соблюдение законов: Мы придерживаемся всех соответствующих законов и этических руководств. Если это потребуется по закону, мы можем прекратить проект или добавить водяные знаки к результатам.

- Ответственность пользователя: Мы не несем ответственности за действия конечного пользователя. Пользователи должны убедиться, что их использование программного обеспечения соответствует этическим стандартам и правовым требованиям.

Используя это программное обеспечение, вы соглашаетесь с этими условиями и обязуетесь использовать его способом, уважающим права и достоинство других.

Ожидается, что пользователи будут использовать это программное обеспечение ответственно и законно. При использовании лица реального человека получите его согласие и четко обозначьте любой результат как дипфейк при публикации в интернете. Мы не несем ответственности за действия конечного пользователя.

## Краткое руководство AI USM - Предварительно собранная версия (Windows)

  <a href="https://deeplivecam.net/index.php/quickstart"> <img src="media/Download.png" width="285" height="77" />

##### Это самая быстрая сборка, которую вы можете получить, если у вас есть дискретная видеокарта NVIDIA или AMD.
 
###### Эти предварительно собранные версии идеальны для нетехнических пользователей или тех, у кого нет времени или возможности вручную установить все требования. Имейте в виду: это проект с открытым исходным кодом, поэтому вы также можете установить его вручную.

## TLDR; Замена лиц в прямом эфире всего в 3 клика
![easysteps](https://github.com/user-attachments/assets/af825228-852c-411b-b787-ffd9aac72fc6)
1. Выберите лицо
2. Выберите камеру для использования
3. Нажмите Live!

## Функции и применение - Всё в реальном времени

### Маска рта

**Сохраняйте ваш оригинальный рот для точного движения с помощью Маски рта**

<p align="center">
  <img src="media/ludwig.gif" alt="resizable-gif">
</p>

### Сопоставление лиц

**Используйте разные лица на нескольких субъектах одновременно**

<p align="center">
  <img src="media/streamers.gif" alt="face_mapping_source">
</p>

### Ваш фильм, Ваше лицо

**Смотрите фильмы с любым лицом в реальном времени**

<p align="center">
  <img src="media/movie.gif" alt="movie">
</p>

### Прямой эфир

**Проводите живые шоу и выступления**

<p align="center">
  <img src="media/live_show.gif" alt="show">
</p>

### Мемы

**Создайте свой самый вирусный мем**

<p align="center">
  <img src="media/meme.gif" alt="show" width="450"> 
  <br>
  <sub>Создано с использованием функции Multiple Faces в AI USM</sub>
</p>

### Omegle

**Удивляйте людей на Omegle**

<p align="center">
  <video src="https://github.com/user-attachments/assets/2e9b9b82-fa04-4b70-9f56-b1f68e7672d0" width="450" controls></video>
</p>

## Установка (Ручная)

**Обратите внимание, что установка требует технических навыков и не предназначена для начинающих. Рассмотрите возможность загрузки предварительно собранной версии.**

<details>
<summary>Нажмите, чтобы увидеть процесс</summary>

### Установка

Этот вариант с большей вероятностью будет работать на вашем компьютере, но будет медленнее, так как использует CPU.

**1. Настройте вашу платформу**

-   Python (рекомендуется 3.10)
-   pip
-   git
-   [ffmpeg](https://www.youtube.com/watch?v=OlNWCpFdVMA) - ```iex (irm ffmpeg.tc.ht)```
-   [Visual Studio 2022 Runtimes (Windows)](https://visualstudio.microsoft.com/visual-cpp-build-tools/)

**2. Клонируйте репозиторий**

```bash
git clone https://github.com/yourusername/AI-USM.git
cd AI-USM
```

**3. Загрузите модели**

1. [GFPGANv1.4](https://huggingface.co/hacksider/deep-live-cam/resolve/main/GFPGANv1.4.pth)
2. [inswapper\_128\_fp16.onnx](https://huggingface.co/hacksider/deep-live-cam/resolve/main/inswapper_128_fp16.onnx)

Поместите эти файлы в папку "**models**".

**4. Установите зависимости**

Мы настоятельно рекомендуем использовать `venv` для избежания проблем.


Для Windows:
```bash
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
```
Для Linux:
```bash
# Убедитесь, что вы используете установленный Python 3.10
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

**Для macOS:**

Apple Silicon (M1/M2/M3) требует особой настройки:

```bash
# Установите Python 3.10 (конкретная версия важна)
brew install python@3.10

# Установите пакет tkinter (требуется для GUI)
brew install python-tk@3.10

# Создайте и активируйте виртуальное окружение с Python 3.10
python3.10 -m venv venv
source venv/bin/activate

# Установите зависимости
pip install -r requirements.txt
```

** В случае неполадок, если вам нужно переустановить виртуальное окружение **

```bash
# Деактивируйте виртуальное окружение
rm -rf venv

# Переустановите виртуальное окружение
python -m venv venv
source venv/bin/activate

# Установите зависимости снова
pip install -r requirements.txt
```

**Запуск:** Если у вас нет GPU, вы можете запустить AI USM используя `python run.py`. Обратите внимание, что при первом запуске будут загружены модели (~300MB).

### Ускорение GPU

**CUDA Execution Provider (Nvidia)**

1. Установите [CUDA Toolkit 11.8.0](https://developer.nvidia.com/cuda-11-8-0-download-archive)
2. Установите зависимости:

```bash
pip uninstall onnxruntime onnxruntime-gpu
pip install onnxruntime-gpu==1.16.3
```

3. Использование:

```bash
python run.py --execution-provider cuda
```

**CoreML Execution Provider (Apple Silicon)**

Специфичная установка для Apple Silicon (M1/M2/M3):

1. Убедитесь, что вы завершили настройку macOS выше с использованием Python 3.10.
2. Установите зависимости:

```bash
pip uninstall onnxruntime onnxruntime-silicon
pip install onnxruntime-silicon==1.13.1
```

3. Использование (важно: укажите Python 3.10):

```bash
python3.10 run.py --execution-provider coreml
```

**Важные примечания для macOS:**
- Вы **должны** использовать Python 3.10, а не более новые версии, такие как 3.11 или 3.13
- Всегда запускайте с командой `python3.10`, а не просто `python`, если у вас установлено несколько версий Python
- Если вы получаете ошибку о том, что отсутствует `_tkinter`, переустановите пакет tkinter: `brew reinstall python-tk@3.10`
- Если вы получаете ошибки загрузки моделей, проверьте, что ваши модели находятся в правильной папке
- Если вы сталкиваетесь с конфликтами с другими версиями Python, рассмотрите возможность их удаления:
  ```bash
  # Перечислите все установленные версии Python
  brew list | grep python
  
  # При необходимости удалите конфликтующие версии
  brew uninstall --ignore-dependencies python@3.11 python@3.13
  
  # Оставьте только Python 3.10
  brew cleanup
  ```

**CoreML Execution Provider (Apple Legacy)**

1. Установите зависимости:

```bash
pip uninstall onnxruntime onnxruntime-coreml
pip install onnxruntime-coreml==1.13.1
```

2. Использование:

```bash
python run.py --execution-provider coreml
```

**DirectML Execution Provider (Windows)**

1. Установите зависимости:

```bash
pip uninstall onnxruntime onnxruntime-directml
pip install onnxruntime-directml==1.15.1
```

2. Использование:

```bash
python run.py --execution-provider directml
```

**OpenVINO™ Execution Provider (Intel)**

1. Установите зависимости:

```bash
pip uninstall onnxruntime onnxruntime-openvino
pip install onnxruntime-openvino==1.15.0
```

2. Использование:

```bash
python run.py --execution-provider openvino
```
</details>

## Использование

**1. Режим изображения/видео**

-   Выполните `python run.py`.
-   Выберите исходное изображение лица и целевое изображение/видео.
-   Нажмите "Начать".
-   Результат будет сохранен в директории, названной по имени целевого видео.

**2. Режим веб-камеры**

-   Выполните `python run.py`.
-   Выберите исходное изображение лица.
-   Нажмите "Прямой эфир".
-   Дождитесь появления предпросмотра (10-30 секунд).
-   Используйте инструмент захвата экрана, например OBS, для стриминга.
-   Чтобы изменить лицо, выберите новое исходное изображение.

## Советы и хитрости

Ознакомьтесь с этими полезными руководствами, чтобы максимально эффективно использовать AI USM:

- **Раскрытие секретов идеального изображения** - Узнайте, как создать лучшую замену лица с полным покрытием головы
- **Видеозвонки с AI USM** - Сделайте ваши встречи более оживленными, используя AI USM с OBS и программным обеспечением для встреч
- **Пригласите особого гостя!** - Руководство по использованию сопоставления лиц для добавления особых гостей в ваш стрим
- **Смотрите фильмы с заменой лиц в реальном времени** - Станьте звездой любого видео без обработки видео
- **Лучшее качество без потери скорости** - Советы для достижения лучших результатов без влияния на производительность
- **Мгновенный виртуальный аватар!** - Легко создавайте новую персону/виртуального аватара с помощью Metahuman Creator

## Аргументы командной строки

```
options:
  -h, --help                                               показать это сообщение помощи и выйти
  -s SOURCE_PATH, --source SOURCE_PATH                     выбрать исходное изображение
  -t TARGET_PATH, --target TARGET_PATH                     выбрать целевое изображение или видео
  -o OUTPUT_PATH, --output OUTPUT_PATH                     выбрать выходной файл или директорию
  --frame-processor FRAME_PROCESSOR [FRAME_PROCESSOR ...]  обработчики кадров (варианты: face_swapper, face_enhancer, ...)
  --keep-fps                                               сохранить оригинальный fps
  --keep-audio                                             сохранить оригинальное аудио
  --keep-frames                                            сохранить временные кадры
  --many-faces                                             обработать каждое лицо
  --map-faces                                              сопоставить исходные и целевые лица
  --mouth-mask                                             маскировать область рта
  --video-encoder {libx264,libx265,libvpx-vp9}             настроить кодировщик выходного видео
  --video-quality [0-51]                                   настроить качество выходного видео
  --live-mirror                                            отображение живой камеры как вы видите его в рамке фронтальной камеры
  --live-resizable                                         рамка живой камеры изменяемого размера
  --max-memory MAX_MEMORY                                  максимальный объем оперативной памяти в ГБ
  --execution-provider {cpu} [{cpu} ...]                   доступные провайдеры выполнения (варианты: cpu, ...)
  --execution-threads EXECUTION_THREADS                    количество потоков выполнения
  -v, --version                                            показать номер версии программы и выйти
```

Ищете режим командной строки? Использование аргумента -s/--source запустит программу в режиме cli.

## Отзывы в прессе

**Мы всегда открыты для критики и готовы совершенствоваться.**

 - [*"AI USM становится вирусным, позволяя каждому стать цифровым двойником"*](https://arstechnica.com/information-technology/2024/08/new-ai-tool-enables-real-time-face-swapping-on-webcams-raising-fraud-concerns/) - Ars Technica
 - [*"Благодаря AI USM, оборотни теперь среди нас"*](https://dataconomy.com/2024/08/15/what-is-deep-live-cam-github-deepfake/) - Dataconomy
 - [*"Этот бесплатный ИИ-инструмент позволяет вам стать кем угодно во время видеозвонков"*](https://www.newsbytesapp.com/news/science/deep-live-cam-ai-impersonation-tool-goes-viral/story) - NewsBytes
 - [*"Это вирусное программное обеспечение для прямых трансляций действительно пугает"*](https://www.creativebloq.com/ai/ok-this-viral-ai-live-stream-software-is-truly-terrifying) - Creative Bloq
 - [*"ИИ-инструмент для дипфейков позволяет стать кем угодно в видеозвонке с помощью всего одной фотографии"*](https://petapixel.com/2024/08/14/deep-live-cam-deepfake-ai-tool-lets-you-become-anyone-in-a-video-call-with-single-photo-mark-zuckerberg-jd-vance-elon-musk/) - PetaPixel
 - [*"AI USM использует ИИ для преобразования вашего лица в реальном времени, включая знаменитостей"*](https://www.techeblog.com/deep-live-cam-ai-transform-face/) - TechEBlog
 - [*"Инструмент ИИ, который "делает вас похожим на кого угодно" во время видеозвонка, становится вирусным в сети"*](https://telegrafi.com/en/a-tool-that-makes-you-look-like-anyone-during-a-video-call-is-going-viral-on-the-Internet/) - Telegrafi
 - [*"Этот инструмент для дипфейков, превращающий изображения в прямые трансляции, возглавляет рейтинги GitHub"*](https://decrypt.co/244565/this-deepfake-tool-turning-images-into-livestreams-is-topping-the-github-charts) - Emerge
 - [*"Новый ИИ для замены лиц в реальном времени позволяет каждому имитировать знаменитостей"*](https://www.digitalmusicnews.com/2024/08/15/face-swapping-ai-real-time-mimic/) - Digital Music News
 - [*"Этот инструмент для веб-камеры с дипфейками в реальном времени вызывает тревогу о будущем кражи личности"*](https://www.diyphotography.net/this-real-time-webcam-deepfake-tool-raises-alarms-about-the-future-of-identity-theft/) - DIYPhotography

## Благодарности

-   [ffmpeg](https://ffmpeg.org/): за упрощение операций, связанных с видео
-   [deepinsight](https://github.com/deepinsight): за их проект [insightface](https://github.com/deepinsight/insightface), который предоставил хорошо созданную библиотеку и модели. Напоминаем, что [использование модели предназначено только для некоммерческих исследовательских целей](https://github.com/deepinsight/insightface?tab=readme-ov-file#license).
-   [havok2-htwo](https://github.com/havok2-htwo): за предоставление кода для веб-камеры
-   И всем разработчикам, стоящим за библиотеками, используемыми в этом проекте.
-   Всем замечательным пользователям, которые помогли сделать этот проект вирусным ❤️

## Вклады

Мы приветствуем вклады в развитие проекта AI USM! Если у вас есть идеи по улучшению системы или вы нашли ошибки, пожалуйста, не стесняйтесь создавать issues или pull requests.

## Растущая популярность 🚀

Следите за ростом популярности проекта AI USM и присоединяйтесь к нашему сообществу!
