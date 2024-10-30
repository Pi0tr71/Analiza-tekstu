# Analiza Tekstu z Chmurą Słów, Analizą Sentymentu i LDA

Ten notebook Jupyter służy do analizy tekstu poprzez wykrywanie głównych tematów i emocji. Zawiera implementację chmury słów, analizę sentymentu, obliczenia średnich wyników emocji oraz identyfikację kluczowych tematów.

## Opis Działania

1. **Chmura Słów**: Generowanie wizualizacji chmury słów, przedstawiającej 10 najczęściej występujących słów.
2. **Analiza Sentymentu**: Obliczenie poziomu sentymentu (pozytywnego, negatywnego, neutralnego) dla tekstów.
3. **Średnie Wyniki Emocji**: Ocena średnich wyników dla różnych emocji, które występują w tekście, aby zidentyfikować dominujące emocje.
4. **Analiza Tematyczna z Modelem LDA**: Modelowanie tematyczne przy użyciu Latent Dirichlet Allocation (LDA) i wyodrębnienie trzech kluczowych tematów z tekstu, wraz z ich reprezentatywnymi słowami i wartościami beta.

## Wyniki

Notebook generuje:
- **Chmurę słów** dla 10 najczęstszych słów
- **Wykresy słupkowe** dla wyników sentymentu i emocji
- **Wizualizację tematów LDA** przedstawiającą 10 najważniejszych słów dla każdego z trzech tematów oraz ich wartości beta
