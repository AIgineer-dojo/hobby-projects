# Projekt timplanering

## Bakgrund

Vid planering av utbildare till specifik kurs behöver utbildningsledaren göra mycket handpåläggning för att få det administrativa att fungera. Detta är onödig "busy work" och kan vi hjälpa till i processen, kan UL göra annat som skapar värde för skolan och de studerande.

## Uppgift

Se excelfil i samma folder. Uppgiften är specad där, men handlar om att användaren matar in tid i excelceller och du ska ha ett skript som hanterar att beräkna ut antal timmar tiden motsvarar. Dessa timmar ska outputtas i excelfilen också.

Exempel på inputs och outputs

| Input    | Output |
| -------- | ------ |
| 9-16:30  | 6,5    |
| 10-16:30 | 5,5    |
| 10-12    | 2      |
| 13-16:00 | 3      |
| 13-16:30 | 3,5    |
| 11-16:30 | 4,5    |

OBS: notera att går vi igenom lunchtiden subtraheras en timme från totalen.

### Fler features 

- En knapp från excel som kör igång pythonskriptet. 

- Detta ska fungera utan att ha Python installerad på datorn. Detta blir värdefullt för en UL, men kan vara något svårt att lösa. (bonus)

- Outputta tiden i din outlookkalender i rätt datum och tid. Namnet på kursen och om det är distans eller på plats bör framgå också. Du kan editera excelfilen för att få in denna data. (bonus)

- I framtiden skulle man kunna göra ett exjobb där man hjälper UL i din skola att från denna excelfil inputta tiden i lärplattformens kalender. Detta kräver dock nära samarbete med UL och dess system, men går att automatisera även detta

## Verktyg

Notera att du kan välja verktyg, bibliotek, paket mm. Här är några exempel som skulle kunna användas: 

- pandas
- openpyxl
- xlrd
- pyxll
- [run python script from excel using VBA](https://waterprogramming.wordpress.com/2022/03/29/running-a-python-script-using-excel-macros/)
- requests
- msal