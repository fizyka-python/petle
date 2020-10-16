# Ćwiczenia z pętli i warunków


Poniżej znajduje się zestaw zadań, które należy wykonać. Każde z nich powinno być zrealizowane w osobnym pliku o podanej nazwie.

## Wielkie litery

Nazwa pliku: `wielkie_litery.py`

Należy napisać program, który poprosi użytkownika o wprowadzenie jakiegoś tekstu i wypisze na ekranie ilość WIELKICH LITER. Na przykład:

    Podaj tekst: Fizyka na Politechnice jest SUPER!  
    7

## Hasło

Nazwa pliku: `haslo.py`

Należy napisać program, który poprosi użytkownika o wprowadzenie hasła, a następnie wydrukuje dokładnie jeden z następujących komunikatów: `Hasło jest bezpieczne.` bądź `Hasło jest niebezpieczne!`. Bezpieczne hasło musi spełniać następujące warunki:

* posiadać przynajmniej jedną małą literę,
* posiadać przynajmniej jedna wielką literę,
* posiadać przynajmniej jedną cyfrę.

Przykłady:

    Podaj hasło: Katar7yna  
    Hasło jest bezpieczne.

    Podaj hasło: katastrofa01  
    Hasło jest niebezpieczne!

## Trójkąt prostokątny

Nazwa pliku: `trojkat1.py`

Należy napisać program, który zapyta użytkownika o liczbę całkowitą (wielkość trójkąta) a następnie wydrukuje trójkąt prostokątny (z kątem prostym w lewym dolnym rogu) złożony ze znaków `*` o zadanej wielkości. Na przykład:

    Podaj wielkość trójkąta: 4
    *
    **
    ***
    ****

## Trójkąt równoramienny

Nazwa pliku: `trojkat2.py`

Należy napisać program, który zapyta użytkownika o liczbę całkowitą (wielkość trójkąta) a następnie wydrukuje trójkąt równoramienny złożony ze znaków `*` o zadanej wielkości. Na przykład:

    Podaj wielkość trójkąta: 3
      *
     ***
    *****

Wskazówka: aby właściwie wyrównać znaki, na początku każdej linijki można wydrukować właściwą liczbę spacji.

## Przybliżenia liczby _π_

Nazwa pliku: `przyblizenia_pi.py`

Należy napisać program, który policzy 10 000 kolejnych przybliżeń liczby _π_ według wzoru Wallisa:

           ∞     4 n²
    π = 2  ∏   ————————
          n=1  4 n² - 1

Powyższy wzór jest dokładny dla iloczynu nieskończonego. W kolejnych przybliżeniach wartość _n_ zmienia się od 1 do pewnej liczby _N_. Kolejne przybliżenia, to obliczone wartości dla rosnącej górnej granicy _N_.

Co setne przybliżenie (dla _N_ ∈ 100, 200, 300...) powinno zostać wypisane na ekranie:

    3.133787490628162
    3.137677900950937
    3.138980103882128
    3.1396322219293986

    ...

    3.14151168992377
    3.1415125160309456
    3.1415133254501364
    3.1415141186819566
