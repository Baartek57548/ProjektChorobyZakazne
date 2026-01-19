# ProjektChorobyZakazne
## DEADLINE 13.01.2026 WYSŁANIE KOMPLETNEJ PRACY.
## 20.01.2026 PREZENTACJA O GODZ.13:30 SALA 105


Analiza i modelowanie dynamiki chorób zakaźnych w Europie na podstawie danych ECDC


temat: Analiza i modelowanie dynamiki chorób zakaźnych w Europie na podstawie danych ECDC


Pozyskanie danych o wybranej chorobie zakaźnej (np. odra, grypa, salmonelloza) z ECDC Surveillance Atlas of Infectious Diseases – dane roczne/miesięczne dla krajów UE/EOG. 
Oczyszczenie danych: ujednolicenie formatów, obsługa braków, sprawdzenie zgodności populacji referencyjnej (incidence per 100 000).
Integracja z danymi kontekstowymi z Eurostatu/GUS (np. struktura wieku, wyszczepialność, wskaźniki socjoekonomiczne – jeśli dostępne). 
Eksploracyjna analiza danych: trendy czasowe, różnice między krajami/regionami, sezonowość, korelacje z wybranymi wskaźnikami.
Konstrukcja modelu regresyjnego przewidującego współczynnik zapadalności w kolejnym okresie (np. rok/miesiąc) dla danego kraju lub grupy krajów.


Prezentacja: https://docs.google.com/presentation/d/1vNR_EW6dVKXqNUNAIC2QE9y6yzLXGaGvQzI2-ep-FtA/edit


Analiza: https://docs.google.com/document/d/1xkOipy4r-JPxMDW0zWanblqGV2l0M5U05MSuOrjjhDY/edit?fbclid=IwY2xjawPbEvNleHRuA2FlbQIxMABicmlkETBQbEFRbGc5cm04OFNDVEJRc3J0YwZhcHBfaWQQMjIyMDM5MTc4ODIwMDg5MgABHrx_nA22rNECipajuHISLjj3uABAqkzzPzJ4t1gmsgcKrfJgi8OAHJhPNM-0_aem_CSr1mfUPVjHGgzTYp1Uu8w&tab=t.0#heading=h.k81xmo4f6391

 1. Kacper – Pozyskanie i przygotowanie danych
Checklist
 Wejść na ECDC Surveillance Atlas of Infectious Diseases.

 Wybrać chorobę (odra/grypa/salmonelloza – zgodnie z ustaleniem zespołu).

 Pobierać dane: roczne/miesięczne, kraje UE/EOG.

 Eksportować dane do CSV/XLSX.

 Sprawdzić dostępne miary (incidence, liczba przypadków, populacja).

 Ujednolicić formaty dat i nazw krajów.

 Wstępnie sprawdzić braki i anomalia (np. zero vs brak).

 Przygotować pierwszy surowy dataset dla Bartka.

✅ 2. Bartek – Oczyszczanie danych + integracja z Eurostat/GUS
Checklist
 Oznaczyć i obsłużyć braki (imputacja lub usunięcie).

 Sprawdzić zgodność wskaźników (czy incidence = per 100 000).

 Pozyskać dane kontekstowe:

struktura wieku (Eurostat),

wskaźniki szczepień (ECDC/WHO, jeśli dostępne),

dane socjoekonomiczne (Eurostat/GUS).

 Ujednolicić jednostki i formaty.

 Złączyć wszystkie dane w jeden spójny dataset.

 Przygotować finalną tabelę wejściową do analiz.

✅ 3. Sebastian – Eksploracyjna analiza danych (EDA)
Checklist
 Sprawdzić rozkład danych (wartości ekstremalne, odstające).

 Analiza trendów czasowych dla każdego kraju.

 Wykrycie sezonowości (jeśli dane miesięczne).

 Porównania między krajami i regionami.

 Korelacje z danymi kontekstowymi (wiek, szczepienia, socio‑econ).

 Wygenerować wykresy (line, heatmap, boxplot).

 Przygotować wnioski i rekomendacje dla Pawła.

✅ 4. Paweł – Modelowanie regresyjne i predykcja
Checklist
 Przygotować dane treningowe/testowe (np. split czasowy).

 Wybrać model:

regresja liniowa,

Poisson/Negative Binomial,

model mieszany,

ARIMA/SARIMA (jeśli dane miesięczne).

 Przetestować różne konfiguracje.

 Walidacja: RMSE, MAE, AIC/BIC.

 Wygenerować predykcję dla kolejnego okresu.

 Zinterpretować wyniki (które czynniki są istotne?).

 Przygotować krótkie podsumowanie dla całego zespołu.
