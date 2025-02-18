# Algorytmy analizy skupień - NASA Close Approaches

Autor: Mateusz Pilch

## Opis projektu

Analiza danych Obiektów Bliskich Ziemi (NEO – near-Earth objects), opublikowanych przez NASA. Celem analizy jest zastosowanie algorytmów analizy skupień (clustering) do grupowania obiektów na podstawie ich parametrów orbitalnych.
Analiza przedstawia jak poszczególne algorytmy grupują obiekty, jaki wpływ na wyniki klasteryzacji mają parametry każego z algorytmów, określa jakość utworzonych klastrów oraz porównuje klastry utworzone w ramach różnych algorytmów.
 
## Struktura projektu
- Opis zbioru
- Preprocessing danych
- Algorytmy skupień
- Porównanie algorytmów

## Wykorzystane algorytmy

- K-means
- Hierarchiczne grupowanie (Agglomerative Clustering)
- DBSCAN

## Metryki ewaluacji

- Silhouette Score
- Davies-Bouldin Index
- Porównania klastrów: Normalized Mutual Information (NMI), Fowlkes-Mallows Index, Jaccard Index

## Biblioteki

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Yellowbrick
- NumPy

## Źródło danych

[NASA Close Approaches](https://cneos.jpl.nasa.gov/ca/)
