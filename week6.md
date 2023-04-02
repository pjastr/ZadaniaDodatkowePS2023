# Zadania dodatkowe - Programowanie Strukturalne - Tydzień 6

## WEEK6 TASK1

Napisz funkcję, która otrzymuje dwa argumenty: dodatnią liczbę całkowitą
$n$ (rozmiar) oraz $n$-elementową tablicę `tab` o elementach typu `int`.
Funkcja ma zwrócić ile razy przekazana do funkcji ma elementy, które
“zmieniają znak”. Stwórz przypadek testowy dla funkcji.

Przykłady:

- dla tablicy \`{1, -3, -4, 0, 5} elementy tablicy zmieniają znak dwa
  razy,
- dla tablicy \`{-3, -11, -2} elementy tablicy nie zmieniają znaku,
- dla tablic \`{2, 3, 3, -3, -4, -11} elementy tablicy zmieniają znak
  jeden raz.

Źródło: <https://www.codewars.com/kata/5bbb8887484fcd36fb0020ca/c>.

## WEEK6 TASK2

Napisz funkcję `void find_longest_subsequence(int arr[], int n)`, która
przyjmuje jednowymiarową tablicę liczb całkowitych oraz jej rozmiar, a
następnie wyświetla długość oraz elementy najdłuższej rosnącego
podciągu. Stwórz przypadek testowy dla funkcji.

## WEEK6 TASK3

Napisz funkcję `double find_median(int arr[], int n)`, która przyjmuje
jednowymiarową tablicę liczb całkowitych oraz jej rozmiar, a następnie
zwraca medianę elementów tablicy. Stwórz przypadek testowy dla funkcji.
Wskazówka: <https://www.matemaks.pl/mediana.html>.

## WEEK6 TASK4

Napisz funkcję `void rotate_array(int arr[], int n, int k)`, która
przyjmuje jednowymiarową tablicę liczb całkowitych, jej rozmiar oraz
dodatnią liczbę całkowitą `k`, a następnie rotuje zawartość tablicy o
`k` pozycji w lewo. Stwórz przypadek testowy dla funkcji.

Przykład: Tablica `{2,-3,4,-1,6,7,11}, n=7, k=3`. Wtedy po przesunięciu
tablica powinna wyglądać `{-1,6,7,11,2,-3,4}`.
