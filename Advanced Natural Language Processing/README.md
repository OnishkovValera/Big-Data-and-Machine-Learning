# Advanced Natural Language Processing / Продвинутая обработка естественного языка

Современные методы анализа и генерации текста, построение систем на основе языковых моделей и оценка качества их решений. Основные направления — LLM, агенты и RAG.

## Материалы курса

- [Лекции](Lectures/README.md).
- [Практические занятия](Practices/README.md).
- [Домашние работы](Homework/README.md).

## Что изучают

- Архитектура Transformer и основные семейства больших языковых моделей.
- Prompting: структура запросов, роли и история диалога, few-shot, структурированный вывод, самокоррекция и способы организации рассуждений.
- Агенты и многоагентные системы: память, вызов инструментов, планирование, ReAct, маршрутизация и human-in-the-loop.
- Поиск: полнотекстовые индексы, эмбеддинги, семантический и гибридный поиск, reranking, cross-encoders и метрики.
- RAG: ограничения контекста, диалоговый RAG, планирование, сжатие контекста, итеративный поиск, DeepSearch/DeepResearch.
- Мультимодальные модели для изображений и видео.
- Дообучение: SFT, instruction tuning, PEFT, LoRA/QLoRA, prefix/p-tuning, RLHF и DPO; в темах названы transformers и unsloth.
- Графы знаний, онтологии и KG-based RAG.
- Инференс и сервинг: квантование, MoE, vLLM, flash attention, continuous batching и prefix caching.
- Дистилляция компактных LLM, синтетические наборы данных и проверка человеком.

## Подготовка

Машинное обучение, глубокое обучение и Python.

## Формат и оценивание

| Параметр | Значение |
|---|---|
| Трудоёмкость | 3 з. е., 108 часов |
| Занятия | 20 часов лекций, 32 часа практики |
| Самостоятельная работа | 50,8 часа |
| Контроль | Экзамен |

## Материалы на GitHub

- [zer0deck/nlp: ANLP-2022 ITMO](https://github.com/zer0deck/nlp/blob/main/README.md) — материалы курса обработки естественного языка.
- [hw1](https://github.com/zer0deck/nlp/blob/main/hw1.ipynb) — очистка веб-текстов, стоп-слова и лемматизация, MinHash/LSH для близких дубликатов, шинглы, NMF/LDA/ARTM и качество тематических моделей.
- [hw2](https://github.com/zer0deck/nlp/blob/main/hw2.ipynb) — поиск дубликатов вопросов Quora, siamese LSTM с общими весами, triplet loss, train/validation/test и метрики.
- [transformer_chatbot](https://github.com/zer0deck/transformer_chatbot/blob/main/README.md) — магистерская ВКР 2023 года: эмоциональный Transformer для open-domain чатбота.

## Ссылки

- [Страница дисциплины](https://my.itmo.ru/programs/50797).
- [Программа курса ИТМО](https://int.itmo.ru/uploads/ad/advanced_natural_language_processing.pdf).
