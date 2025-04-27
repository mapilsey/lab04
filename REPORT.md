# Задание 1
## Вам поручили перейти на систему автоматизированной сборки CMake. Исходные файлы находятся в директории formatter_lib. В этой директории находятся файлы для статической библиотеки formatter. 

![изображение](https://github.com/user-attachments/assets/d83e4a2e-fe7b-4b02-82ff-2491cde4d20a)

![изображение](https://github.com/user-attachments/assets/83984e76-6483-4235-989f-4b4595b47a18)

![изображение](https://github.com/user-attachments/assets/f855b23d-64e8-4553-a134-99e5f7da8289)

![изображение](https://github.com/user-attachments/assets/2d19084f-a669-40fe-8655-0ae0772b7485)

## Создайте CMakeList.txt в директории formatter_lib, с помощью которого можно будет собирать статическую библиотеку formatter.
### Настройка имени проекта
![изображение](https://github.com/user-attachments/assets/1f5e6314-09fc-49e0-a0e7-cdc4033b052f)

### Настройка стандарта C++
![изображение](https://github.com/user-attachments/assets/5218cf64-e62f-43c2-b226-10e1125b3a9b)

### Создаем статическую библиотеку formatter
![изображение](https://github.com/user-attachments/assets/d1ef9b69-d4eb-49d7-b3c1-81718695762a)

### Создание build директории
![изображение](https://github.com/user-attachments/assets/555d4f41-b246-40bc-b677-c1d163ef0d14)

### Генерирация проекта
![изображение](https://github.com/user-attachments/assets/0fee4e8f-0ce7-4e09-abd0-a7307e8b2cc0)

![изображение](https://github.com/user-attachments/assets/3d76ce7d-be79-48e3-bf37-638f4976d020)

### Сборка библиотеки
![изображение](https://github.com/user-attachments/assets/19f4b729-ec02-4d71-9066-eaf7f3e90b01)

![изображение](https://github.com/user-attachments/assets/b5608533-e63d-4adc-9f2f-9c05527b30bd)

Статическая библиотека libformatter.a создана

# Задание 2
## У компании "Formatter Inc." есть перспективная библиотека, которая является расширением предыдущей библиотеки. Т.к. вы уже овладели навыком созданием CMakeList.txt для статической библиотеки formatter, ваш руководитель поручает заняться созданием CMakeList.txt для библиотеки formatter_ex, которая в свою очередь использует библиотеку formatter.
### Настройка имени проекта
![изображение](https://github.com/user-attachments/assets/485aca4e-45a9-4f2f-9143-e7dfb71fe95b)

### Настройка стандарта C++
![изображение](https://github.com/user-attachments/assets/da0c00fd-14ef-4406-9398-f73528f91cee)

### Создаем статическую библиотеку formatter_ex
![изображение](https://github.com/user-attachments/assets/99dc9c19-cbb1-49e1-8b33-3d24f234847b)

### Подключаем путь к formatter.h от библиотеки formatter
![изображение](https://github.com/user-attachments/assets/80cdf035-84ab-4f28-917a-e8930a525487)

### Подключаем библиотеку formatter
![изображение](https://github.com/user-attachments/assets/36bab1ae-affe-4eb3-80de-f5fe16544fc3)

### Создание build директории
![изображение](https://github.com/user-attachments/assets/434a93a7-7fb2-4d05-ba70-46ea8248df43)

### Генерирация проекта
![изображение](https://github.com/user-attachments/assets/fa6847b2-cc08-478a-8f73-94d276b92fb1)

### Сборка библиотеки
![изображение](https://github.com/user-attachments/assets/d4fd9b04-abfa-49fd-a333-92b7017d8b83)

![изображение](https://github.com/user-attachments/assets/c0135612-d9b0-4245-bd26-5064c0f1ff81)

Статическая библиотека libformatter_ex.a создана



