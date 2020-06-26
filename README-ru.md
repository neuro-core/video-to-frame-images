# Video to frames

Скрипт для экспорта видео на кадры.
Кормим скрипту путь до видео или до папки с видео

## Установка

* git clone
* `python3 -m venv venv`
* `./venv/bin/pip3 install -r requirements.txt`

## Использование

* Один файл: `python3 video_to_frames.py --video_path file.mp4`
* Один файл из папки: `python3 video_to_frames.py --video_path folder/file.mp4`
* Все файлы в папке: `python3 video_to_frames.py --video_path folder-with-videos-inside`

Прочие аргументы:

* `--skip_first` - сколько кадров пропускать
    * `--skip_first 5` - будет выгружен только каждый пятый кадр
* `--rotate` - нужно ли повернуть изображение после выгрузки
    * `None` - не нужно
    * `0` - по часовой
    * `1` - против часовой

## License

* 2020, MIT, [NeuroCore Team](https://neuro-core.ru)
