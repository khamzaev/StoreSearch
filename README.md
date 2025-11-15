# StoreSearch
<img width="410" height="847" alt="image" src="https://github.com/user-attachments/assets/f1f65779-d55b-4872-9737-30ae795ae75b" />
<img width="845" height="403" alt="image" src="https://github.com/user-attachments/assets/fe4003fa-e90a-448b-b940-dbcfd47f462b" />

StoreSearch — iOS-приложение для поиска и отображения результатов (табличный интерфейс). 
В проекте есть готовые xib-ячейки, Core Data модель и директории с контроллерами и моделям

Структура (основное)
--------------------
- StoreSearch/Base.lproj — локализация / LaunchScreen и другие ресурсы интерфейса  
- StoreSearch/Controllers/ — вьюконтроллеры (логика экрана поиска и результатов)  
- StoreSearch/Model/ — модели данных  
- StoreSearch/Resources/ — дополнительные ресурсы (иконки, изображения)  
- StoreSearch/StoreSearch.xcdatamodeld — модель Core Data  
- StoreSearch/Info.plist — настройки приложения  
- StoreSearch/SearchResultCell.xib — xib для отображения результата  
- StoreSearch/LoadingCell.xib — xib для индикатора загрузки  
- StoreSearch/NothingFoundCell.xib — xib для состояния "ничего не найдено"

Требования
----------
- macOS с Xcode (рекомендуется Xcode 12+)
- iOS SDK соответствующей целевой версии в проекте

Запуск
------
1. Откройте проект в Xcode (StoreSearch.xcodeproj или .xcworkspace, если есть).  
2. Выберите схему/таргет и симулятор или устройство.  
3. Постройте и запустите (Cmd+R).  
Примечание: проект использует Core Data (StoreSearch.xcdatamodeld) и кастомные xib-ячейки для списка.

Коротко про разработку
----------------------
- Код и ресурсы разделены по папкам Controllers / Model / Resources.  
- Добавляйте новые контроллеры в Controllers, модели в Model, интерфейсные xib в Resources или в корень модуля.  
- Для UI-изменений редактируйте соответствующие xib-файлы в Interface Builder.


Автор
-----
khamzaev — https://github.com/khamzaev
