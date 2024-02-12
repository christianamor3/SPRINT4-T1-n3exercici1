# Exercici Postman

Es tracta de provar els anteriors projectes des de Postman.

Crea dos entorns:

- Projecte Maven

- Projecte Gradle

 

Ambdós entorns tindran dues variables:

- Servidor, que en els dos casos tindrà el valor http://localhost

- Port, que en el cas del projecte Maven tindrà el valor 9000, i en el cas del projecte Gradle, 9001.

 

Que has d’entregar? (4 arxius):

- Els dos entorns exportats.

- Una captura de pantalla per cada entorn, on es vegi l’execució des de Postman usant l’entorn i les variables definides en ells.

- Pots provar l'URL: http://localhost:xxxx/HelloWorld/elmeunom, o qualsevol altra de les que admeten els dos projectes. (recorda que perquè l’execució funcioni correctament, hauràs de tenir en execució els dos projectes a Eclipse).

Executa des d’Eclipse els projectes creats als dos nivells anteriors, i mostra el retorn obtingut en cada projecte, quan crides a algunes de les peticions disponibles, fent servir els entorns creats i les seves variables.

Hauràs d’entregar dues captures de pantalla, una per l’execució de cada entorn, i dos arxius amb format JSON, amb els entorns exportats.
 

El segon mètode respondrà a una petició GET, i haurà de ser configurat per a rebre el paràmetre com una PathVariable. El paràmetre "nom" serà opcional.

Haurà de respondre a:

- http://localhost:9000/HelloWorld2
- http://localhost:9000/HelloWorld2/elmeunom
