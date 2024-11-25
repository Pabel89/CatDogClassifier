# Training
Zum Trainieren müssen Hunde- und Katzenbilder in den jeweiligen Unterordnern von dataset/train und dataset/val platziert
werden. 
Die Benennungen muss wie folgt sein: cat_1.jpg, cat_2.jpg,... dog_1.jpg, dog_2.jpg,...
Für das Training wurden 8500 Bilder je Hund und Katze als Trainingsbilder und 3000 Prüfbilder von Hunden und Katzen jeweils
benutzt. Die Bilder sollten immer so gewählt werden, dass man die Tiere erkennen kann.

# Informationen zu den vortrainierten Modellen

## image_classification_CNN
Die Genauigkeit ist bei 92%.

## image_classification_Resnet
Die Genauigkeit ist bei 93%.

## image_classification_with_pretrained_VGG16
Die Genauigkeit ist hier am Besten und liegt bei 97%. Da hier ein Großteil der Module vom vortrainierten VGG16 Netz aus Pytorch
benutzt wird. Dies erleichtert das Training für die Hund- und Katzeklassifierung. Hier wurde lediglich das Classifier Modul ueberschrieben mit dem meines Hund- und Katzeklassifizierernetzes. 

# Ausführung des Codes
Entweder nur mit Python und die jeweiligen Bibliotheken wie Pytorch installieren und den Code in .py Dateien packen um ihn auszuführen oder die Distribution Anaconda3 installieren, wo die passenden Tools unter anderem Jupyter Notebook drin enthalten sind.