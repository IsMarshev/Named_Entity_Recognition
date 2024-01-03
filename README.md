# Извлечение именованных сущностей (NER) с использованием трансформера на основе BERT
Обзор
Проект реализует модель извлечения именованных сущностей (NER) с использованием трансформера на основе BERT (bert-base-cased). NER - это задача обнаружения и классификации сущностей, таких как имена, организации и даты, в тексте.

Ключевые шаги
1. Подготовка данных: Данные для обучения подготавливаются в виде последовательностей токенов и соответствующих меток именованных сущностей.
2. Класс TransformeDataset: Создается класс для представления данных в формате, подходящем для использования в PyTorch. Метки преобразуются в числовой формат.
3. Токенизация и кодирование меток: Используется токенизатор BERT для представления текста в виде токенов. Метки и токены кодируются для подготовки к обучению модели.
4. Обучение модели NER: Модель обучается на подготовленных данных для распознавания именованных сущностей в тексте.
5. Применение модели: Обученная модель может использоваться для извлечения именованных сущностей из новых текстов.
