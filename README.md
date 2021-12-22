# FIS3
ОИБ - лаб. №3 - вар. №9
Осокин 6212


Алгоритм шифрования IDEA
Дата появления: 1990 год
Разработчики алгоритма: Ксуеджа Лай и Джеймс Мэсс


Изначально носил назвение PES (Proposed Encryption Standard). 
Через год алгоритм был модифицирован с целью усиления криптостойкости к дифференциальному криптоанализу, в связи счем был переименован в IPES (Improved PES).
Спустя ещё 1 год получил современное название IDEA (International Data Encryption Algorithm).



Области применения IDEA:
1. Шифрование аудио и видео данных для кабельного телевидения, видеоконференций, дистанционного обучения
2. Защита коммерческой и финансовой информации
3. Линии связи через модем, роутер или ATM(асинхронный способ передачи данных) линию,
   GSM(глобальный стандарт цифровой мобильной связи с разделением каналов по времени и частоте) технологию
4. Смарт-карты
5. Общедоступный пакет конфиденциальной версии электронной почты PGP v2.0
   (компьютерная программа, также библиотека функций, позволяющая выполнять операции шифрования и цифровой подписи сообщений)



Криптостойкость алгоритма IDEA:
В алгоритме IDEA использует 64-битные блоки. Длина блока должна быть достаточной, 
  чтобы скрыть статистические характеристики исходного сообщения. 
Но с увеличением размера блока экспоненциально возрастает сложность реализации криптографического алгоритма. 
В алгоритме IDEA используется 128-битный ключ. Длина ключа должна быть достаточно большой, 
  чтобы предотвратить возможность перебора ключа.
  
Высокая криптостойкость IDEA обеспечивается также следующими характеристиками:
— запутывание — шифрование зависит от ключа сложным и запутанным образом
— рассеяние   — каждый бит незашифрованного текста влияет на каждый бит зашифрованного текста
    
Хотя существут "слабые ключи" (порядка 2^63, 2^23+2^35+2^51 и 2^53+2^56+2^64 ключей),
  на практическую криптостойкость алгоритма IDEA они не влияют, 
  так как полное число всех возможных ключей равно 2^128.



Алгоритм IDEA не является международным стандартом шифрования.
Тем не менее, является одним из наиболее распространенных в мире алгоритмов шифрования.