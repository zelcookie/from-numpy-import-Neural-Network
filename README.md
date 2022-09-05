# from numpy import Neural Network

## Как сделать домашку
- Сделайте закрытый репозиторий
  - Используйте этот репозиторий как template, воспользуйтесь [инструкцией](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template)
  - Добавьте в репозиторий [команду курса](https://github.com/BobaZooba/DeepNLP#%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D0%B0-%D0%BA%D1%83%D1%80%D1%81%D0%B0)
    - [Инструкция как добавлять](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-access-to-your-personal-repositories/inviting-collaborators-to-a-personal-repository)
- Установите зависимости с помощью команды ```pip install -r requirements.txt```
- Сделайте задание
- Отправьте ссылку на репозиторий преподователю [@BobaZooba](https://github.com/BobaZooba)

## Описание задания
В этой домашке есть две версии: простая и сложная. 
В обоих версиях вам нужно будет реализовать нейронную сеть на numpy. 
Простая версия отличается от сложной тем, что в ней нужно сделать это непосредственно в цикле обучения и для двух слоев, 
то есть нужно будет описать `forward`, `backward` и шаг оптимизации прямо в цикле. 
В сложной версии нужно будет проделать примерно тоже самое, но в классах. Эта домашка нужна для лучшего понимания, но она будет сложнее из-за использования классов и, возможно, пока непривычной форме с классами.
Абстракции в этой домашке будут очень полезны для понимания того, что происходит в торче. Эта домашка прокачает вас гораздо сильнее, но и выполнить ее будет труднее. Вам нужно будет описать несколько слоев: `Linear`, `ReLU`, `BCELoss`.  Реализация `Sigmoid` уже есть в `our_library.layers`. Реализовав слои выше вы сможете сделать n-слойную нейронную сеть с любым количеством слоев. Это получается за счет того, что вы описали всю необходимую логику:
- Как нужно обработать входные данные и передать их дальше;
- Принять градиент с последующего слоя, сделать `backward` для текущего слоя и передать градиент предыдущему слою;
- Как обновить веса, если в слоев есть обучаемые веса.

Присылайте свои недоделанные сложные домашки, пусть они не пойдут совсем в стол. Я или ассистенты посмотрят, мы обсудим и доделаем.  
Поверьте, эта домашка стоит того, чтобы ее сделать! Вы получите бОльший опыт, выполнив сложную. Но нет ничего страшного, если вы выбирите простую. 
У вас еще будет большое количество возможностей проявить себя.

Простая домашка находится в ноутбуке `Homework Easy.ipynb`, сложная в `Homework Hard.ipynb`

## Установка зависимостей
Необходимые сторонние библиотеки  
`pip install -r requirements.txt`

## Оценивание
Будет проверятся корректность логики обучения, 
будут даваться комментарии что нужно исправить, 
если домашка будет сдана вовремя. 
Грамотность и красота кода проверяться не будут.
Максимальный балл: 10.

## Дедлайн
19/09/2022  
Далее максимальный балл за работу: 7

## Важные просьбы
- Не отправляйте ссылку на `colab` в форме, отправляйте ссылку на ваш репозиторий
- Прежде чем отправить задание на проверку, очистите свой код от неиспользоваемого кода и неважных комментариев
