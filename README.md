# Turaeva_kr2_leafs

Файлы leafs и leafs_transfer содержат в себе код обучения моделей на основе следующего датасета https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset?resource=download . При желании переобучения модели и запуска кода необходимо загрузить датасет в систему. В самих файлах используется подключение к диску и копирования оттуда архива, который распоковывается уже в системе. При работе не в Colab загрузка может отличаться. (Например в Jupiter достаточно распоковать архив в папку в файлом и пропустить часть "Загрузка данных")

Для работы с файлом Leafs_diseases нужно скачать файл model_leafs_resnet.keras с диска https://disk.yandex.ru/d/GBN5Sux1PSZWig или сохранить собственный файл функцией model.save (есть в файлах) после нового обучения модели. Затем необходимо загрузить скаченный файл и интересующее фото, после окончания загрузки запучтить код
