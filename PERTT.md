# PERT - Moda Circular BCN

## Activitats i duracions

| Codi | Activitat | Predecessora | a | m | b | te | Variància |
|------|-----------|--------------|---|---|---|----|----------|
| A | Definició del problema, objectius i abast | - | 2 | 3 | 4 | 3 | 0,11 |
| B | Configuració de GitHub, Kanban i Gantt | - | 2 | 3 | 4 | 3 | 0,11 |
| C | Anàlisi del context de Gràcia | A | 3 | 5 | 7 | 5 | 0,44 |
| D | Mapeig d'usuaris i col·laboradors | C | 3 | 5 | 7 | 5 | 0,44 |
| E | Disseny del sistema (recollida/intercanvi) | D | 4 | 6 | 8 | 6 | 0,44 |
| F | Requisits del prototip digital | E | 3 | 4 | 5 | 4 | 0,11 |
| G | Desenvolupament del prototip (App Inventor) | F | 10 | 14 | 18 | 14 | 1,78 |
| H | Recursos, pressupost, riscos i indicadors | F | 5 | 7 | 9 | 7 | 0,44 |
| I | Revisió i avaluació de resultats | G, H | 3 | 4 | 5 | 4 | 0,11 |
| J | Preparació de la presentació final | I | 2 | 3 | 4 | 3 | 0,11 |

## Fórmules utilitzades

Duració esperada:

te = (a + 4m + b) / 6

Variància:

σ² = ((b - a) / 6)²
