# Распознавание болезни (пневмония) по пользовательским снимкам

### Задача:
Задача -  используя датасет Chest X-Ray Images (Pneumonia), необходимо обучить модель на обнаружение болезни, а также реализовать интерфейс с возможностью загрузки и обработки пользовательских снимков

### Что сделано:
* Использован датасет Chest X-Ray Images (Pneumonia).
* Использована предобученная сеть MobileNetV2 в качестве основы (без верхних слоев)
* Разработка пользовательского интерфейса для загрузки изобрадений.

#### Стек:
* Python.
* TensorFlow / Keras / NumPy / Gradio.

### Результат:
Рабочий прототип сверточной нейронной сети для классификации изображений


#### Пример использования:
Пользователь, с помощью интерфейса, загружает рентгеновский снимок и получает сообщение Норма/Пневмония 
