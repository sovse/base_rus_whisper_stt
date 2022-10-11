# base_rus_whisper_stt
Fine tuning of the base model from OpenAI Whisper in Russian language on the dataset Sber-golos


До обученная  модель распознавания речи " base " от https://github.com/openai/whisper под русский язык на данных сбер-голса из этой статьи https://habr.com/ru/company/sberdevices/blog/559496/. Fine tuning модели длился 10 эпох.

До обученная модель можно скачать по адресу https://disk.yandex.ru/d/ogeKhA-PfNpf9w - файл base_ru.pt . Она имеет размер 290,5 МБ , 71М параметров.

Точность модели на тесте Farfield wer=20.96% ( для сравнения , точность стандартной "base" модели от whisper на этом тесте имеет  wer=73.45%). Hо новая модель забыла пунктуацию.

Пример использования , можно посмотреть в ноутбуке asr_inferens.ipynb


