# IA-GP-Growth-FAO

Analiza regulilor de asociere utilizând algoritmul FP-Growth pe date FAO privind consumul alimentar individual din România.

## Descriere
Acest repository conține codul sursă utilizat în cadrul proiectului pentru:
- preprocesarea datelor FAO (GIFT);
- definirea tranzacțiilor alimentare;
- aplicarea algoritmului FP-Growth;
- analiza comparativă între adulți și copii, respectiv pe criteriul de gen.

Rezultatele sunt utilizate și interpretate în raportul PDF asociat proiectului.

## Conținut
- `analysis_fp_growth_fao.ipynb` – notebook Python care conține întregul flux de analiză (curățare date, FP-Growth, rezultate);
- `README.md` – descrierea proiectului.

## Date
Datele utilizate provin din:
FAO – Global Individual Food Consumption Data Tool (GIFT)  
https://www.fao.org/gift-individual-food-consumption/data/en

## Tehnologii utilizate
- Python
- pandas
- mlxtend (FP-Growth)
- Jupyter Notebook / Google Colab

## Autor
Denis Minjineanu  
Facultatea de Automatică și Calculatoare
