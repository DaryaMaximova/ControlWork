Блок схема алгоритма (метод NewArr): programm.drawio

Описание решения:

Объявляем первый массив string[] arr1 = new string[3] {" ", " ", " "}; в котором задаем длину и значения 

Объявляем второй массив string[] arr2 = new string[arr1.Length]; в котором указываем что его длина будет равна длине первого массива

Создаем метод void NewArr(string[] arr1, string[] arr2) в качестве аргументов берем наши массивы

Объявляем переменную count и присваеваем ей значение int count = 0;

Метод включает в себя цикл for (int i = 0; i < arr1.Length; i++)

В цикле задаем условие if(arr1[i].Length <= 3)

Если условие выполняется элемент массива arr1 заносится в count элемент второго массива arr2[count] = arr1[i];

Затем переменная count увеличивается на единицу count++;

Возвращаемся к циклу for, где i увеличивается на единицу

Печатаем получившийся массив используя метод void PrintArr(string[] arr)