# AccessControlRFID
## Папки
- **libraries** - библиотеки проекта. Заменить имеющиеся версии
- **firmware** - прошивка для Arduino, файл в папке открыть в Arduino IDE
- **schemes** - принципиальные схемы
## Схема
 ![Alt-текст](https://github.com/yarestem/AccessControlRFID/blob/main/schemes/scheme_v2.png)
 ## Мини инсрукция
 - **При первом включении мигают поочередно красный и зеленый светодиоды** - режим програмирования админ метки.
- **Поднесли карту к считывателю загорелся красный светодиод** - метка не прошита в систему.
- **Поднесли админ карту к считывателю мигают красный и зеленый светодиоды** - режим програмирования, поднесите метку которую хотите записать в систему ожидайте индикации мигания зеленым светодиодом, после поднесите админ метку что бы выйти с этого режима.
- **Удалить метку записаную ранее**: войдите в режим програмирования поднесите метку которыю нужно уадлить, ожидайте индикации красным светодиодом и выйдите с режима програмирования.
