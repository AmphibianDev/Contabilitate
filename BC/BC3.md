### Prescurtări folosite
- `CPP` - Contul de Profit si Pierdere
- `ReX` - Rezultatul exercițiului
- `V` - Venit
- `Ch` - Cheltuială
- `A` - Active
- `P` - Pasive
- `D` - Datorii
- `Dfz` - Datorii furnizori

Valoare rezultatului exercițiului (ReX) **implicit** este egal cu cel **explicit**:
- **Implicit** -> în bilanț, doar valoarea (ReX-ul)
- **Explicit** -> în Contul de Profit si Pierdere (CPP) unde este detaliat fiecare venit și cheltuială
- `ReX = V - Ch` -> provine din CPP
- `A = Cp + D`
- `A = (Cp' + ReX) + D`
- `A = [Cp' + (V - Ch)] + D`

## Definirea și caracterizarea venitului și cheltuielilor

### Cheltuielile
- Ch = ↓ beneficii economice viitoare => ↓ A sau ↑ D => ↓ ReX => ↓ Cp

Etapele:
1. Angajarea cheltuielilor
2. Consumul
3. Plata
4. Incorporearea în rezultat (operațiune strict contabilă în care Ch sunt înscrise în CPP)

### Veniturile
- V = ↑ beneficii economice viitoare => ↑ A sau ↓ D => ↑ ReX => ↑ Cp

Etapele:
1. Obținerea
2. Vânzare
3. Încasarea
4. Incorporarea în rezultat

### Exemplu practic:

1. Doi amici înființează o societate comercială, aducând ca aport 50.000 lei în cont la bancă.
   - ↑ A: Db | ↑ P: Cp' (CSV)
   - `A + X = [Cp' + X + (V - Ch)] + D`
   - `0 + 100.000 = [100.000 + (0 - 0)] + 0`

2. Societatea prestează și facturează un serviciu de consultanță unui client, la un tarif de 20.000 lei.
   - ↑ A: Cr | ↑ P: ReX (V)
   - `A + X = [Cp' + (V + X - Ch)] + D`
   - `100.000 + 20.000 = [100.000 + (0 + 20.000 - 0)] + 0`

3. Societatea aprovizionează de la un furnizor materii prime în valoare de 2.000 lei.
   - ↑ A: St.Mp | ↑ P: D (Dfz)
   - `A + X = [Cp' + (V  - Ch)] + D + X`
   - `120.000 + 2.000 = [100.000 + (20.000 - 0)] + 2.000`

4. Societatea dă în consum jumătate din materiile prime existente în stoc.
   - ↓ A: Mp | ↓ P: ReX (↑ Ch)
   - `A - X = [Cp' + V  - (Ch + X)] + D`
   - `122.000 - 1.000 = [100.000 + 20.000 - (0 + 1.000)] + 2.000`

5. Un asociat se retrage și îi se plătește imediat contravaloarea părților sociale.
   - ↓ A: Db | ↓ P: Cp' (CSV)
   - `A - X = [Cp' - X + (V - Ch)] + D`
   - `121.000 - 50.000 = (100.000 - 50.000 + (20.000 - 1.000)) + 2.000`

6. Furnizorul solicită și îi se aprobă ca în schimbul datoriei față de el, să devină asociat.
   - A | P: ↑ Cp' și ↓ D (Dfz)
   - `A  = [Cp' + X + (V - Ch)] + D - X`
   - `71.000 = [50.000 + 2.000 + (20.000 - 1.000)] + 2.000 - 2.000`

7. Societatea primește de la un furnizor factura care reprezintă serviciile de transport prestate de către el, în sumă de 3.000 lei. (Achiziții servicii transport)
   - A | P: ↑ D (Dfz) și ↑ Ch (↓ ReX, ↓ Cp)
   - `A  = [Cp' + V - (Ch + X)] + D + X`
   - `71.000 = [52.000 + 20.000 - (1.000 + 3.000)] + 0 + 3.000`

8. Furnizorul acordă o reducere de 1.000 lei din datoria din care societatea o are față de el.
   - A | P: ↓ D (Dfz) și ↑ V (↑ ReX, ↑ Cp)
   - `A  = [Cp' + (V + X - Ch)] + D - X`
   - `71.000 = [52.000 + (20.000 + 1.000 - 4.000)] + 3.000 - 1.000`