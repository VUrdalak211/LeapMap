# LeapMap
Disparity map generator for LeapMotion
________________________

#Calibrator
Калибратор из сэмплов к opencvsharp.

#ChessboardSniffer
Получает картинку и ищет шахматную доску.

#DisparityGenerator
__Важная штука.__
Должен получать на вход два изображения.
Строит карту разностей.

#ImageProvider
__Важная штука.__
Берет картинки с липмоушена.
Вызывает ивент OnNewImages.

#MainForm
Формочка которая умеет выводит изображения с липмоушена и карту разностей

#Photographer
Сохраняет N изображений с липмоушена с некоторым отступом по времени.

#SmartPhotographer
Сохраняет только те изображения, которые содержат шахматную доску.

#StereoCalibrator
Калибровщик. _не работает_
