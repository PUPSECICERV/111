// See https://aka.ms/new-console-template for more information
// Console.WriteLine("Hello, World!");

// Написать программу, которая принимает трехзначное число и на 
// выходе показывает вторую цифрую

//Console.WriteLine("Генерируем трехзначное число");

//int number = new Random().Next(100, 1000);

//Console.WriteLine(number);

//int number1 = number % 100;

//int rezalt = number1 / 10;

//Console.WriteLine(rezalt);

 // Написать программу, которая принимает на вход цифру, 
 // обозначающую день недели, и проверяет, 
 // является ли этот день выходным.

 //Console.WriteLine("Введите цифру, соответствующую дню недели");

//int num = Convert.ToInt32(Console.ReadLine());

//if ((num == 6) || (num == 7) ) {
//     Console.WriteLine ("Выходной");
// } else {
//     Console.WriteLine ($"Не выходной");
// }

// напишите программу, которая выводит третью цифру 
// заданного числа

Console.WriteLine("введите любое число");

int numb = Int32.Parse(Console.ReadLine());

if (numb /100 == 0) {
     Console.WriteLine ("Третьего числа нет");
 } else 
 {
     Console.WriteLine ($"Третье число есть ");
 }
