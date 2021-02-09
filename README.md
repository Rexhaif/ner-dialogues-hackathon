# Минихакатон - задание от команда NER Dialogs
Привет!

Спасибо что согласились взяться за решения нашей задачи!

Суть того что нужно сделать - попробовать какой-либо подход для решения NER задачи на наших данных(см. папку  /data)

Целевая метрика - micro-average span-level F1 score на тестовой части данных (test.conll). Имплементацию метрики можно взять в репозитории [seqeval](https://github.com/chakki-works/seqeval) либо использовать встроенную в flair.

## Что мы хотим получить в итоге?
Мы хотим чтобы каждый из вас попробовал какой-либо подход для решения задачи, предоставил код его реализации и обученную модель(если таковая будет), а так же посчитал и сообщил значение метрики на тестовой части данных.

В идеале, вам необходимо сделать форк этого репозитория, добавить в него папочку с своим кодом/моделями/описанием и сделать пул-реквест к этому репозиторию. Но если с этим будут какие-то проблемы - можно передать любым другим способом(отправить мне(@daniil) в телеграме, например)

## Baselines
Для того, чтобы вы могли начать эксперименты с минимальными усилиями мы подготовили несколько базовых вариантов решений, они находятся в папке /baselines.

Вот тут список:
- Бейзлайн на основе фреймворка flair (Test F1-score: 0.5496) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rexhaif/ner-dialogues-hackathon/blob/master/baselines/flair/Baseline-Flair.ipynb)
- Бейзлайн на основе фреймворка huggigface/transformers (Test F1-score: 0.7238) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rexhaif/ner-dialogues-hackathon/blob/master/baselines/transformers/Baseline-Transformer.ipynb)
