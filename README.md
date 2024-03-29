# VolcanoAlgorithmAnalysis
This project is used for the needs of improvement of volcano eruption detection algorithm.

The idea:<br>
Input consists of 2 types of images.<br>Ones are just images of volcano. And others are the result of volcano eruption detection algorithm where the field of eruption is highlighted:<br>
![Иллюстрация к проекту](https://github.com/aANAESTHESIAa/VolcanoAlgorithmAnalysis/blob/92b32ca2bfb47b7b7fc9e2d00696635de81629ee/volcano.png) <br>
As we can see, sometimes algorithm works improperly causing partial highlighting of eruption activity as on picture above(the central one).<br>
<br>
Thus we need to understand, why the border was drawn this way. <br>
For this purpose was decided to process every pixel of incorrect highlighting and to print its Luminance on it like this:<br>
![Иллюстрация к проекту](https://github.com/aANAESTHESIAa/CCFEBRAS-VolcanoAlgorithmAnalisys/raw/master/result.png)<br>
Green labeled pixels are those, where the algorithm boundary was drawn.<br><br>

How-to-use:<br>

<b>Step 1:</b> Select the image with algorithm result you want to observe.<br>
<b>Step 2:</b> In the window that opens, select the desired area. Close this window when you're done.<br>
The program outputs the processed image area that you've set to process. The resulting image is saved in result folder. 


<br><br>
P.S. #Ru-ru
<br>
Инструкция:<br>
Шаг 1: Выберите размеченное изображение с результатом алгоритма, которое хотите обработать.<br>
Шаг 2: Отмеченное изображение открывается в окне программы. Выберите область обработки на изображении. После выделения желаемой область,закройте окно программы со снимком.<br>
Результат работы программы, содержаpщий обработанное изображение, сохраняется в папку result.<br>
