# Hälsostudie – Del 1

## Om projektet

Det här projektet är en individuell examinationsuppgift
där jag analyserar data från en hälsostudie med Python.

Syftet är att undersöka deltagarnas hälsodata med
hjälp av statistik, visualiseringar och simuleringar.

## Dataset

Datasetet innehåller 800 deltagare och information om:

- Ålder och kön
- Längd och vikt
- Systoliskt blodtryck
- Kolesterol
- Rökvanor
- Sjukdomsstatus

## Genomförda analyser

1. Beskrivande statistik
2. Visualisering av hälsodata
3. Simulering med NumPy
4. Konfidensintervall
5. Hypotesprövning med Welchs t-test
6. Power-simulering

## Tekniker och bibliotek

- Python 3.14
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook

## Köra projektet

Skapa och aktivera en virtuell miljö:

```powershell
py -3.14 -m venv .venv
.\.venv\Scripts\Activate.ps1
```

Installera biblioteken:

```powershell
python -m pip install -r requirements.txt
```

Öppna sedan `health_study_del1.ipynb` i VS Code
och välj Python-miljön från `.venv`.

Kör notebookens alla celler från början till slut.

## Reproducerbarhet

Datasetet läses in med en relativ sökväg.
Simuleringarna använder fasta slumpfrön så att
resultaten kan återskapas.

## Källor

- https://numpy.org/doc/stable/
- https://pandas.pydata.org/docs/
- https://docs.scipy.org/doc/scipy/
- https://matplotlib.org/stable/
- https://seaborn.pydata.org/
```