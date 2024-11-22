# keras-autoencoder

### Eng

This is an autoencoder based on the Keras library. It takes 28*28 jpg images as input, compresses them and removes unnecessary information using an encoder, then restores the image using a decoder. Since the model is trained on the mnist dataset (a black and white dataset with handwritten digits), the predictions on custom images are not so good. The model has a fairly large loss, but this is my first experience in developing deep learning, so I plan to improve my skills in this.

The project has pre- and post-processing, as well as a function that allows you to display an image pixel by pixel using matplotlib (in post-processing, an image generated from numpy ndarray using PIL is returned)

### Rus

Это автоэнкодер на базе библиотеки Keras. На вход принимает jpg-изображения 28*28, сжимает их и удаляет лишнюю информацию с помощью энкодера, после восстанавливая изображение с помощью декодера. Так как модель обучена на датасете mnist (ч/б датасет с рукописными цифрами), то предсказания на кастомных картинках не такие хорошие. Модель имеет достаточно большой лосс, но это мой первый опыт разработки глубокого обучения, поэтому я планирую совершенствовать свои навыки в этом.

В проекте есть пред- и пост-обработка, а также функция, позволяющая попиксельно вывести изображение с помощью matplotlib (в постобработке возвращается сформированное с помощью PIL изображение из numpy массива)

# Requirements

-Keras  
-Pillow  
-NumPy  
-Matplotlib  
-Seaborn  
