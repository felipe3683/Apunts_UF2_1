## Entorns de desenvolupament
### Objectius de les proves
- Comprovar si el software no fa el que **ha de fer**
- Comprovar si el software fa el que **no ha de fer**
Hi ha diferents frameworks per fer proves.

### Framework
- Esta composat per:
    - Conjunt de millores pràctiques i suposicions
    - Eines comuns
    - Llibreries
- Permet unificació del procés als desenvolupadors.

### Proves
Es distingueixen en dos tipus:
- **Proba dinàmica:** Requereix execució de l'aplicació i permet veure el seu comportament.
- **Proba estàtica:** Es realitza sense executar el codi, examina el codi font.

### Estrategies
- **Caixa negra:** Estudi desde fora, són les proves de funcionalitats.
- **Caixa blanca:** Examinament del codi i execució. Són proves estructurals.

#### Caixa negra
- Estudi del sistema des de fora
- Es treballa sobre l'interfaç
- No es necessari saber el funcionament internet.
- Es proporciona entrada i es verifica la sortida.
- Tècniques principals:
    - **Particions equivalents**
    - **Valors límit**

#### Ciaxa blanca
- Estudi del codi font i execució
- Comprovació dels fluxos d'execució(funció, clase, mòdul,etc).
- Comprovació dels fluxs entre les unitats a l'integració, i també entre subsistemes.
- Principals tècniques:
    - **Cobertura de codi**
    - **Proba de bucles**

### Tipus de proves
- **Funcionals**: Evaluació de cumpliments dels requisits.
- **No funcionals**: Evaluació dels aspectes adicionals(rendiment, seguretat, etc).

#### Proves funcionals
- **Proves unitàries**
- **Proves de regresió**
- **Proves d'integració**
- **Proves de fum(smoke test)**
- **Proves del sistema**
- **Proves alfa i beta**
- **Proves d'acceptació(validat pel client).**

#### Proves no funcionals
- **Proves d'usabilitat**
- **Proves de rendiment**
- **Proves de stress**
- **Proves de seguretat**
- **Proves de compabilitat**
- **Proves de portabilitat**

### Mecanismes de prova
- **Manual:** Realitzades per personal intern/extern de l'empresa.
- **Automàtic:** Software que executa el codi de forma automàtica i compara els resultats obtinguts amb els esperats.

### Supports del depurador
- **Punts de ruptura(breakpoint)**
- **Execució pas a pas**
- **Anàlisis de variables**

### Automatització de proves
- **Frameworks de prova(_xUnit_)**
- **Aserciones**

#### Frameworks per proves
- **Java:** jUnit, TestNG
- **C++:** CppUnit, Google Test
- **PHP:** PHPUnit
- **Javascript:** Mocha

### cas de prova
- Es tracta d'una entrada conocida i una sortida esperada, com exemple una suma sapiguent el resultat.

### Integració
#### Formes d'integració
- Integració de Big bang
- Integració Descendent
- Integració Ascendent
- Integració Continua (CI)

#### Servidors d'integració continua
- **Jenkins**
- **Bamboo**
- **TravisCI**
- **CircleCI**

#### Cobertura del codi
Mesura que indica el porcentatge de codi que ha sigut executat durant les proves.
El recomanable es que sea el més aprop a 100%.

### Qualitat
Per aconseguir la medició de qualitat del producte, fa falta realitzar proves.

#### Qualitat del procés/Producte QA/QC
**QA: Quality Assurance:** són el conjunt d'activitats per garantir la qualitat en els processos mitjançant es desenvolupen els productes.
**QC: Quality control:** Les activitats son centrades en identificar els defectes dels productes ja produits.

### Factores de calidad
- **Model de qualitat de McCall** defineix 11 factors de qualitat.
- S'agrupen 3 àmbits:
  - Operació del producte
  - Revisió del producte
  - Transició del producte

![Model McCall](https://i.pinimg.com/474x/c6/be/96/c6be96491c4f3072a3a68934ebf66312.jpg)

#### Operació del producte
- **Correció**
- **Fiabilitat**
- **Eficiència**
- **Seguretat**
- **Facilitat d'ús**

#### Revisió del producte
- **Mantenibilitat**
- **Flexibilitat**
- **Facilitat d'ús**

#### Transició del producte
- **Portabilitat**
- **Reusabilitat**
- **Interoperativitat**
