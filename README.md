# Podstawy Uczenia Maszynowego - laboratoria

## Spis treści

* [Modele liniowe (linear models)](lab1)
* [Modele oparte o sąsiedztwo (nearest neighbors)](lab2)
* [Metody jądrowe (kernel methods)](lab3)
* [Metody probabilistyczne (probabilistic methods)](lab4)
* [Klasyfikacja niezbalansowana (imbalanced classification)](lab5)
* [Selekcja cech i redukcja wymiarowości (feature selection & dimensionality reduction)](lab6)

## Setup

Zależności potrzebne do wykonania notebooków są zawarte w `pyproject.toml` oraz `uv.lock`,
zarządzanych przez [uv](https://docs.astral.sh/uv/). Jeżeli korzystasz z PyCharma, stwórz
nowy projekt z dependency managerem uv (File -> Settings -> Project -> Python interpreter
-> Add interpreter -> uv). Uruchomienie w terminalu `uv sync` zainstaluje odpowiednią wersję
Pythona oraz wszystkie zależności. Pliki będą systematycznie aktualizowane na potrzeby
kolejnych laboratoriów.

Aktualizacja zależności wymaga wywołania ponownie `uv sync`. W razie potrzeby przebudowania
zależności w uv trzeba dodać ją do `pyproject.toml` oraz rozwiązać i zainstalować zależności
przez `uv sync`.

Repozytorium zawiera też bibliotekę [ruff](https://docs.astral.sh/ruff/) do formatowania
kodu. Sugerowane jest użycie [pre-commit hooka](https://docs.astral.sh/ruff/integrations/#pre-commit),
przykładową konfigurację zawarto w `.pre-commit-config.yaml`.