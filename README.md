# PyMusicBase64
Воспроизведение звука из переменной в кодировке base64 на Python

Этот код позволит воспроизводить звук во время исполнения файла Python

enc - переменная: в нее записан звук уведомления в формате base64
ели нужно изменить звук на свой, то пример ниже

enc = '''
тут звук в кодировке Base64
'''

по умолчанию название временного файла temp.mp3 (если вызываете функцию и не передаёте параметр tempName)


Принцип работы кода:
  1. перекодировка base64 в .mp3 файл
  2. Получение данных звука в формате raw
  3. Воспроизведение звука
  4. Удаление файла звука

