# Analiza Tematyczna z Modelem LDA i Wizualizacja

Ten notebook Jupyter demonstruje wykorzystanie modelu **Latent Dirichlet Allocation (LDA)** do analizy tematycznej na zbiorze dokumentów tekstowych. Notebook przeprowadza preprocessing danych, stosuje LDA do wyodrębnienia tematów, a następnie wizualizuje najważniejsze słowa dla każdego tematu.

## Opis Działania

1. **Ładowanie Danych**: Odczyt dokumentów z wybranych plików tekstowych.
2. **Preprocessing**: Wektorowanie tekstu za pomocą `CountVectorizer`.
3. **Analiza Tematyczna z Modelem LDA**: Wyodrębnienie tematów z danych tekstowych.
4. **Wizualizacja**: Generowanie wykresów słupkowych przedstawiających 10 najważniejszych słów i ich wartości beta dla każdego tematu.
