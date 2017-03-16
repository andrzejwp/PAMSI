# Lab3 - Projektowanie Obiektowe

https://docs.google.com/presentation/d/1hib5NXmkfxeLVpzg-AOwR8xdH6TIV4iT0bI0uHx2PJo/edit?usp=sharing

## Problemy z dziedziczeniem
 
Na podstawie artykułu Martina określamy podstawowe problemy, które mogą się pojawić,
gdy korzystamy z dziedziczenia, bez wcześniejszego zaprojektowania programu.
Np. implementujemy Modem1, potem korzystamy z Modem1 w programie graficznym, następnie
implementujemy Modem2, który dziedziczy po Modem1, ale zmienia jego kontrakt, musimy
więc uwzględnić te zmiany w programie graficznym. 

Określamy interfejsy, które będą implementowały programy pisane na kolejnych laboratoriach:

- IRunnable
- Stoper
- kształt programu głównego, który korzysta ze stopera i IRunnable aby zmierzyć czas wykonania obliczeń dla kolejnych programów


Zadanie domowe:
- przeprojektowanie kodu tablicy dynamicznej i stopera, aby był zgodny z projektem ustalonym na zajęciach
- ponowne pomiary dla tablicy dynamicznej, tym razem powtarzając X razy dla każdego zadanego rozmiaru tablicy, aby otrzymać uśredniony czas
- przeczytać o Abstrakcyjnych Typach Danych (Abstract Data Types - ADT), w szczególności dla listy, kolejki i stosu.

ADT
---
Abstract Data Type, co to jest, dlaczego chcemy z tego korzystac

