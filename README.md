# Titry — файли для завантаження

Тут лежать лише готові файли програми **Titry** (українські субтитри для відео, Windows 10/11).
Завантажити програму: <https://titry.airwire.online>

Програма сама завантажує звідси потрібні їй частини і перевіряє кожен файл (SHA-256 і підпис).

## Що всередині

| Частина | Звідки | Ліцензія |
|---|---|---|
| whisper.cpp (розпізнавання мовлення) | <https://github.com/ggml-org/whisper.cpp> (b5454) | MIT |
| Модель `ggml-large-v3-turbo-uk` | <https://huggingface.co/ihnatov-yuri/whisper-large-v3-turbo-uk>, перетворено у формат ggml | MIT |
| FFmpeg 7.1 (essentials) | <https://www.gyan.dev/ffmpeg/builds/> · код: <https://github.com/FFmpeg/FFmpeg/tree/n7.1> | GPLv3 |
| Бібліотеки NVIDIA CUDA 12.4 | входять до збірки whisper.cpp | NVIDIA CUDA EULA |
| Microsoft Visual C++ Runtime | Microsoft | Microsoft Software License Terms |

---

Files only: binaries of the Titry subtitle app for Windows. No source code lives here.
