
# 💼 Zadanie: System bankowy – podstawowe operacje

Zaprojektuj system, który będzie obsługiwał podstawowe operacje bankowe wykonywane na rachunku klienta.

## ✅ Zakres operacji

System powinien umożliwiać następujące działania:

- **Wpłata środków na konto**  
  - Możliwa **zawsze**.
  
- **Wypłata środków z konta**  
  - Dozwolona **tylko wtedy**, gdy na koncie znajduje się **wystarczająca ilość środków**.

- **Przelew środków z konta na konto**  
  - Możliwy **tylko wtedy**, gdy konto źródłowe ma odpowiednią ilość środków.
  - **Uwaga**: Przelewy są realizowane **dwa razy dziennie**.

## 🧩 Zadanie

Zaprojektuj zestaw klas w języku **Java**, które będą modelować zachowanie rachunku bankowego w trakcie powyższych operacji.

Możesz wspomóc się poniższym diagramem klas:  
![Diagram klas](http://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/PJMPR/lab05-Objects-Modelling/main/UML/diagram1.puml)

---

# 🏠 Zadanie domowe: Historia operacji

Rozszerz funkcjonalność systemu bankowego o mechanizm zapisywania historii operacji.

## 🔍 Szczegóły:

- Każda operacja (wpłata, wypłata, przelew) powinna być **zapisywana w historii rachunku** (lub rachunków – w przypadku przelewów).
- Klient powinien mieć możliwość **przeglądania historii operacji** z wybranego przedziału czasowego.

## 🧩 Zadanie

Zaprojektuj dodatkowy zestaw klas, który:

1. Będzie odpowiedzialny za **rejestrowanie historii operacji** na rachunku bankowym.
2. Umożliwi **filtrowanie historii** według zadanego zakresu dat.
