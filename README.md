# PAK_project
<h1>Flowers classification project</h1>
<h2>1. Введение</h2>
<p>Цель раюоты - создать модель для классификации цветов. Датасет был взят с kagle, модель обучалась на этом же сайте.<br>
Согласно условиям соревнования требовалось создать файл с предсказаниями моделей в формате .csv и отправить его.<br></p>
<h2>2. Выполнение задания</2>
<p>Для выполнения задания мыла выбранна модель ResNet50.</p>
<img src="./model.png">
<p>Общая архитектура модели Resnet</p>
<img src="./arhitec.png">
<p>В своей программе, для обучение модели, я использовал оптимайзер Адам, функцию потерь CrossEntropy, а так же sheduler, для того, чтобы коррективовать learning rate. Информацию по последнему я взял по <a href="https://neptune.ai/blog/how-to-choose-a-learning-rate-scheduler">этой ссылке</a></p>
<h2>3. Процесс обучения</h2>
<h4>Accuracy in training loop</h4>
<img src="training.png">
