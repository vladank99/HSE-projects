# Diploma
Название проекта – адаптация зарубежных **шкал веры в генетический и социальный детерминизм** (перевод с английского языка на русский).   
Проект выполнен в R-studio (jupyter-notebook)

--- 
### Описание проекта:
- **Основная цель** – разработать шкалы, которые будут валидными и надежными для русскоязычной выборки
- Адаптировались две шкалы, которые оценивают субъективный уровень веры в генетику и социума в рамках объяснения обыденных вещей
- Перед анализом был проведен ряд адаптационных процедур:
  - *Прямой и Обратный перевод*  
       >  Прямой перевод – это перевод с английского языка на русский   
          Обратный перевод – это перевод с русского языка на английский   
          Процедуру выполняли эксперты лингвисты
  
  - *Экспертное оценивание перевода*  
       >  Экспертное оценивание – это процедура для оценки корректности перевода     
          Процедуру выполняли приглашенные эксперты в области социальной психологии 
  
  - *Когнитивные интервью*  
       >  Когнитивные интервью – это интервью с респондентами   
          Основная цель – понять, как люди интерпретируют суждения в шкалах (для их последующей корректировки)
  
  - *Web-probing*
      >  Web-probing – это аналог когнитивных интервью в виде анкетирования   
         Cбор данных для этой процедуры был выполнен, с помощью сервиса Яндекс. Толока 
         
- Основная процедура представляло собой опросник, выполненный на базе 1ka.si
- Выборка отбиралась на платформе Яндекс. Толока
- Для оценки репрезентативности выборки – использовались соц.дем. пропорции из Росстата
- Основной анализ включает в себя:
    - *Оценку надежности – подсчет Альфа-Кронбаха* 
      >  Метрика Альфа-Кронбаха демонстрирует связь каждого пункта с общим баллом по шкале.   
         Если все ок по результатам, то пункты направлены на оценку того же, что и оценивает вся шкала
         
     - *Оценку валидности – конвергентная и дискриминантная*  
      >  Конвергентная валидность – шкала действительно изучает то, что написано в ее названии. 
         Статистически, это представляет собой корреляционный анализ между основной шкалой и шкалой, которая изучает что-то похожее   
         Например, мы имеем шкалу тревоги и хотим оценить ее конвергентную валидность:
         Мы возьмем другую шкалу – страх неопределенности (которая была разработана кем-то другим), поскольку этот конструкт входит в тревогу
         И мы проверяем связаны ли эти шкалы? Если да, то конвергентная валидность подтвеждается
         
      >  Дискриминантная валидность – шкала действительно не изучает то, что не написано в ее названии. 
         Статистически, это представляет собой корреляционный анализ между основной шкалой и шкалой, которая изучает что-то другое.
         Например, мы имеем шкалу тревоги и хотим, чтобы эта шкала оценивала именно тревогу (оценить ее дискриминантную валидность):
            Мы возьмем другую шкалу – страх смерти (которая была разботана кем-то другим)
            И мы проверяем связаны ли эти шкалы? Если нет, то дискриминатная валидность подтверждается
           
      -  Конфиматорный факторный анализ 
       >  Мой диплом адаптирует две шкалы.   
          Следовательно, я ожидаю двухфакторную модель:
          - Фактор №1 – шкала веры в генетический детерминизм (и все суждения, которые входят в эту шкалу)
          - Фактор №2 – шкала веры в социальный детерминизм (и все суждения, которые входят в эту шкалу)
          Будет плохо, если не получится подтвердить двухфакторную структуру в модели, потому что это означает, что мои шкалы изучают что-то еще, помимо того, что у них написано в названии 
          
      - Мультигрупповой конфиматорный факторный анализ: 
      - 
         
        
