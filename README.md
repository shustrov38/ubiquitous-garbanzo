# ubiquitous-garbanzo

Одна из особенностей данного проекта - приложение наименьшего количества усислий по написанию кода. Поэтому большую часть кода я буду генерировать через популярные **LLM**ы и буду вести подсчет количества потраченных промптов.

---

**Количество промптов**:
- ChatGPT-o1: `1`

---

- **Идея проекта**  
  - [ ] Задача: классификация звуков (городские шумы / природные звуки / музыкальные жанры).  
  - [ ] Выбрать датасет (например, [UrbanSound8K](https://urbansounddataset.weebly.com/urbansound8k.html), [ESC-50](https://github.com/karolpiczak/ESC-50), [GTZAN](http://marsyas.info/downloads/datasets.html)).  

- **Формирование датасета**  
  - [ ] Для каждого файла вычислить мел-спектрограммы и сохранить в удобном формате (изображения или NumPy-массивы).  

- **Выбор и настройка модели**  
  - [ ] Рассмотреть **CNN на спектрограммах** или **предобученную аудиомодель** (PANNs, wav2vec2.0).  

- **Финальная доводка**  
  - [ ] Добавить аугментации аудио (time shift, pitch shift, add noise).  
  - [ ] Оптимизировать гиперпараметры (learning rate, batch size) и следить за переобучением.

- **Презентация результатов**  
  - [ ] Описать процесс: задача, датасет, модель, результаты.  
  - [ ] (Опционально) Создать небольшое демо (CLI-скрипт или веб-интерфейс) для загрузки и классификации аудио.

---

## Референсы

- [Deep Convolutional Neural Networks for Environmental Sound Classification (arXiv:1608.04363)](https://arxiv.org/abs/1608.04363)  
- [PANNs: Large-Scale Pretrained Audio Neural Networks for Audio Pattern Recognition (arXiv:1912.10211)](https://arxiv.org/abs/1912.10211)  
- [wav2vec 2.0 (arXiv:2006.11477)](https://arxiv.org/abs/2006.11477)  
- [Librosa: документация](https://librosa.org/doc/latest/index.html)  
- [Torchaudio: документация](https://pytorch.org/audio/stable/)  

