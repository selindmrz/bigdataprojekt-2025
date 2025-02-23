# bigdataprojekt-2025
 
main.ipynb ist die Datei, in dem das CNN-Modell zur Klassifikation von Hund- und Katzenbildern programmiert ist.
Um diesen Code ausführen zu können, müssen die folgenden Bibliotheken installiert werden:

torch
torchvision
tensorflow
keras
pandas
numpy
Pillow
scikit-learn
matplotlib
seaborn

Anschließend können die Bibliotheken importiert werden. Danach soll der Code-Teil zur Abrufung und Aufteilung der Trainings- und Validierungsdaten ausgeführt werden. Letztendlich beinhaltet der letzte Code-Block das CNN-Modell. Das Modell durchläuft 20 Epochen, wobei das Early-Stopping einen vorherigen Stopp erzwingt, wenn das Modell nicht mehr dazulernt.

In CNN_model.keras ist das Modell zur Klassifikation von Hund- und Katzenbildern gespeichert.

model_validation.ipynb ist die Datei, in der das CNN-Modell validiert wird. Hierbei werden ungelabelte Testdaten aus dem Testordner (tes1) geladen und klassifiziert.