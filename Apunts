# Apunts UF2

## PROVES:

- Una bona prova es te que centrar en dos objectius:
  - 1. Provar si el software no fa el que te que fer.
  - 2. Provar si el software fa el que te que fer.
- Existeixen diferents **frameworks** per a la realització de les proves.

### FORMA DE LES PROVES:

- **Dinàmiques:** Requereixen la execució de l'aplicació. Permet medir el comportament de l'aplicació.

- **Estàtiques:** Es realitzen sense executar el codi de l'aplicació. S'examina el codi font.

### ESTRATEGIA DE PROVA:

- **Caixa negra:** S'estudia el sistema desde fora. Son proves de funcionalitat.

- **Caixa blanca:** S'examina el còdi font i la seva execució. Son proves estructurades.

![](assets/estrategia_prova.png)

### Caixa negra:

- S'estudia el sistema desde fora.
- Es treballa sobre l'interficie.
- No es tenen en compte els detalls interns de funcionament.
- es proporcionen entrades i s'estudiant les sortides.
- Principals técniques:
  - Particions d'equivalència.
  - Valors límit.

### Caixa blanca:

- S'examina el codi font i la seva execució.
- Es comproven els fluxes de execució dins de cada unitat (funció, clase, módul, etc.)
- També poden comprobar-se els fluxes entre unitats durant la integració.
- Principals técniques:
  - Cobertura de codi
  - Prova de bucles

### Tipus de Proves:

  - **Funcionals:** Evaluen el cumpliment dels requisits.

  - **No funcionals:** Evaluen aspectes adicionals com rendiment, seguretat, ...

### Funcionals

- Proves unitaries (o de unitat)
- Proves de regresió
- Proves de integració
- Proves de fum (smoke test)
- Proves del sistema
- Proves alfa i beta
- Proves de aceptació (validació per part del client)

### No Funcionals

- Provas de utilitat
- Proves de rendiment
- Proves de stress
- Proves de seguretat
- Proves de compatibilitat
- Proves de portabilitat
- ...

### Mecanismes de PROVES

- Manual
  - Mitjançant proves realitzades per personal de l'empresa o extern.


- Automàtic
  - Mitjançant software que executa codi de forma automatizada i compara els resultats obtinguts i els resultats esperats.

## FRAMEWORK:

- El **framework** (marc de treball) està format per:

  - Un conjunt de les millors pràctiques i suposicions.
  - Eines comunes
  - Biblioteques


- Permet unificar el proces de desenvolupament entre programadors.

- Java: JUnit, TestNG
- C++: CppUnit, Google Test
- PHP: PHPUnit
- Javascript: Mocha

### Cas de PROVA

- suma (2, 3) --> 5

### JUNIT4 - ANOTACIONS

- **@BeforeClass:** el mètode es invocat abans de iniciar tots els tests. Només pot haver un mètode amb aquesta anotació.
- **@AfterClass:** El mètode es invocat después de finalitzar tots els tests. Numés pot haver un mètode amb aquesta anotació.
- **Before:** S'executa abans de cada test.
-  **@After:** S'executa despúes de cada test.
- **@Ignore:** Els mètodes marcats amb aquesta anotació no seràn executats.
- **@Test:** Representa un test que es te que executar.

![](assets/asercions.png)

![](assets/exemple_anotacions.png)

## INTEGRACIÓ:

### FORMAS DE INTEGRACIÓ:

- Integració Big Bang
- Integració Descendent
- Integració Ascendent
- Integració Continua(CI)

### SERVIDORS DE INTEGRACIÓ CONTINUA:

CI: Integració CONTINUA
CD: Entrega CONTINUA

- Servidors de integració continua:
  - Jenkins
  - Bamboo
  - Travis CI

- Es una mesura que indica el porsentatge de codi que ha sigut executat durant les proves.
- Es aconsellable que sigui lo mes aproximat a 100%
- Si es del 100% s'ha executat tot el codi font durant les proves.
- Si es menor del 100% llavores existeix codi font que no s'ha execurtat durant les proves.

## CALITAT:

- Per aconseguir una:
  - Mediació de la calitat de un producte
- Necessitem realitzar
  - Proves

### QA & QC:

- **QA** es un conjunt d'activitats per a garantitzar la **calitat dels processos** mitjançant els cuals desenvolupan els productes.
- **QC** es un conjunt d'activitats per a garantitzar la **calitat dels productes**. Les activitats es centren en identificar defectes en els productes reals produïts.

- QA = Quality Assurance / QC = Quality Control

## FACTORS DE QUALITAT:

- Operació del producte
  - Correcció (Fa el software el que jo vull?)
  - Fiabilitat (Ho fa de forma exacte tot el temps?)
  - Eficiencia (Es segur?)
  - Seguretat (Es segur?)
  - Facilitat d'us (Puc executar-ho?)

- Revisió del producte
  - Mantenibilitat (Puc arreglar-ho?)
  - Flexibilitat (Puc provar-ho?)
  - Facilitat de prova (Puc modificar-ho?)

- Transició del producte
  - portabilitat (Podré comunicar-ho amb un altre sistema?)
  - Reusabilitat (Podre utilitzar-lo en una altre màquina?)
  - Interoperativitat (Podré reutilitzar part del software?)

### Modelo de Calidad de McCall:

![](assets/McCall.png)
