# Corporate Bankruptcy Prediction Analysis – Altman Z-Score Model

A brief analysis evaluating the predictive accuracy of the original Edward Altman Z-score model (1968) on a sample of Polish enterprises. The project was implemented in R.

## Repository Contents
* `AltmansModel.Rmd` – Source code of the analysis in R Markdown format (calculations, classification, and conclusions).
* `AltmansModel.html` – The generated, ready-to-read report with results.
* `5year.arff` – The dataset used for the analysis (from the UCI Machine Learning Repository).

## Main Results
The evaluation of the original model on the studied sample showed average predictive effectiveness:
* **79.2%** accuracy – after excluding the "gray area" (companies with ambiguous financial indicators).
* **70.5%** accuracy – after including the gray area and forcing a cutoff point (2.675) for the entire sample.

The main reason for the reduced effectiveness (compared to the original 95%) is the necessity to use the book value of equity instead of the market value (distorting the X4 ratio) and the different specificities of the Polish market.

## Technologies
* R
* R Markdown

---

# Analiza predykcji upadłości firm – Model Altmana

Krótka analiza skuteczności oryginalnego modelu Z-score Edwarda Altmana (1968) w przewidywaniu bankructwa na próbie polskich przedsiębiorstw. Projekt został zrealizowany w języku R.

## Zawartość repozytorium
* `AltmansModel.Rmd` – Kod źródłowy analizy w formacie R Markdown (obliczenia, klasyfikacja i wnioski).
* `AltmansModel.html` – Wygenerowany, gotowy do odczytu raport z wynikami.
* `5year.arff` – Zbiór danych wykorzystany do analizy (pochodzący z bazy UCI Machine Learning Repository).

## Główne wyniki
Ewaluacja oryginalnego modelu na badanej próbie wykazała przeciętną skuteczność predykcyjną:
* **79.2%** zgodności – po odrzuceniu "szarej strefy" (firm o niejednoznacznych wskaźnikach).
* **70.5%** zgodności – po uwzględnieniu szarej strefy i wymuszeniu punktu odcięcia (2.675) dla całej próby.

Główną przyczyną obniżonej skuteczności (względem oryginalnych 95%) jest konieczność zastosowania księgowej wartości kapitału zamiast rynkowej (zaburzony wskaźnik X4) oraz odmienna specyfika polskiego rynku.

## Technologie
* R
* R Markdown
