# FACE_ANALIZER-MASTER-MAIN.PY
Распознавание лица,эмоций,возраста, пола,расы
#адрес d:\Pytonprogrammi\FACE_ANALIZER-MASTER\MAIN.PY
#Программа содержит 3 функции:
#1.)def face_verify(img_1,img_2):-функция ,которая сравнивает два файла img_1 и img_2- и выводит сообщение-проверка пройдена,если лица на фотографии одинаковые лица
# и сообщение -нарушитель задержать!,  если проверка не пройдена.
#2.)функция face_recogn():-,берет лицо из папки "faces\jim.jpg" и сравнивается с лицами из папки Emilia
#3.)face_analyze функция которая берет лицо из папки faces и определяет пол,возраст,настроение,расу.
from deepface import DeepFace
