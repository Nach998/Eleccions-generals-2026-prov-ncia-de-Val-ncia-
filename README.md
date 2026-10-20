# Repartiment de diputats de València

Aplicació web per simular l'assignació de diputats de la
província de València mitjançant el sistema d'Hondt.

## Objectiu

L'objectiu del projecte és comprendre com es transformen els
vots de les diferents candidatures en escons i experimentar
amb diferents resultats electorals.

## Funcionalitats

- Modificar el nom de les candidatures.
- Editar el nombre de vots de cada partit.
- Afegir candidatures noves.
- Eliminar candidatures.
- Configurar el nombre d'escons.
- Modificar el percentatge de la barrera electoral.
- Introduir els vots en blanc.
- Calcular automàticament el repartiment.
- Consultar els quocients emprats en l'assignació.
- Visualitzar els escons i els percentatges de vots.
- Restaurar les dades inicials.

## Tecnologies

El projecte està desenvolupat amb:

- HTML5: estructura de la pàgina.
- CSS3: disseny adaptable i presentació visual.
- JavaScript: càlcul dels escons i actualització dels resultats.

No necessita instal·lacions, dependències externes ni servidor.

## Com executar-lo

1. Descarrega o clona el repositori.
2. Obri el fitxer `index.html` amb un navegador.
3. Modifica els noms dels partits i els vots.
4. Consulta els resultats actualitzats automàticament.

## Funcionament del sistema d'Hondt

El sistema d'Hondt és un mètode proporcional d'assignació
d'escons.

Els passos són:

1. Es calcula el llindar electoral establit.
2. S'exclouen les candidatures que no arriben al llindar.
3. Es divideixen els vots de cada candidatura admesa entre
   1, 2, 3, 4... fins al nombre d'escons disponibles.
4. S'ordenen els quocients de major a menor.
5. Els escons s'assignen als quocients més elevats.

En cas d'empat entre quocients, aquesta implementació prioritza
la candidatura que ha obtingut més vots.

## Configuració inicial

L'aplicació està configurada amb:

- Circumscripció: província de València.
- Nombre d'escons: 16.
- Barrera electoral: 3 %.
- Candidatures d'exemple: PP, PSOE, Compromís-Sumar i Vox.

Les dades inicials corresponen a un exemple de les eleccions
generals de 2023. No representen necessàriament els resultats
d'una convocatòria electoral actual.

## Publicació amb GitHub Pages

1. Crea un repositori públic a GitHub.
2. Puja els fitxers `index.html` i `README.md` a l'arrel.
3. Ves a Settings > Pages.
4. En Build and deployment, selecciona Deploy from a branch.
5. Selecciona la branca `main` i la carpeta `/ (root)`.
6. Guarda els canvis.
7. Espera que GitHub Pages publique el lloc web.

L'adreça tindrà aquest format:

https://USUARI.github.io/REPOSITORI/

Substitueix `USUARI` pel teu nom d'usuari de GitHub i
`REPOSITORI` pel nom del repositori.

## Referències

- Exemple de referència:
  https://iesbiaplicacions.github.io/hont/
- Explicació del sistema d'Hondt a València:
  https://programaelectoral.org/ley-dhondt/valencia

## Llicència

Projecte educatiu d'ús lliure.
