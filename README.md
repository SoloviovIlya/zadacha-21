//Напишите программу, которая принимает на вход координаты двух точек и находит расстояние между ними в 3D пространстве.
//A (3,6,8); B (2,1,-7), -> 15.84
//A (7,-5, 0); B (1,-1,9) -> 11.53

Console.WriteLine("Введите координаты первой точки: ");

float x1 = Convert.ToInt32(Console.ReadLine());

float x2 = Convert.ToInt32(Console.ReadLine());

float x3 = Convert.ToInt32(Console.ReadLine());

Console.WriteLine("Введите координаты второй точки: ");

float y1 = Convert.ToInt32(Console.ReadLine());

float y2 = Convert.ToInt32(Console.ReadLine());

float y3 = Convert.ToInt32(Console.ReadLine());

double z = Math.Pow((Math.Pow(y1 - x1, 2) + Math.Pow(y2 - x2, 2) + Math.Pow(y3 - x3, 2) * 1.0), 0.5);

Console.WriteLine(z);
