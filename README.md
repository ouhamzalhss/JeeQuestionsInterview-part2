## <samp>Les Questions pour un entretien profile JAVA/JEE!</samp>

#### Partie 3: Web service

- 1 .	Un API (Application Programming Interface) est un ensemble de règles : interfaces Annotations et des classes abstraites.

- 2 .	Service web : c’est des composants web basés sur HTTP pour la communication et l'échange de données entre applications et systèmes distribués. On a deux spécifications  (JAX-WS et JAX-RS)

- 3 .	JAX-RS est une spécification JEE pour créer des web service basé sur la norme Restful. et interagit avec les messages XML, JSON, HTML… 
(Implementations REST Easy ET Jersey, Spring MVC RestController, spring data rest).

- 4 .	JAX-WS est une spécification JEE pour créer des web service basé sur le protocole SOAP et interagit avec les messages XML

- 5 .	Jersey est une implémentation de référence de JAX-RS.

- 6 .	SoapUI est une application de test de services web SOAP (Simple Object Access Protocol)  et  REST.

- 7 .	RESTful  ou REST : est un style architectural utilisé dans le développement de services web.

- 8 .	JMS est une spécification pour la communication asynchrone entre les applications.

- 9 .	KafKa : est un broker (provider)  pour le stockage ( file d’attente)  et l'échange  des messages entre les applications en mode asynchrone.

- 10 . WSDL(Web Service Description language) : un document XML qui contient la description de l’interface de web service.( méthodes de web service, paramètres d’entrée et sortie)

- 11 . UDDI (Universal Description Discovery and Integration) : Annuaire des web service permettant à la fois la publication (Register) et l’exploration (Discover) de web services.

- 12 . JAXB : Une librairie Java pour le mapping OXM objet / xml.  Ex(@XMLTransieint)

- 13 . XML : Format de données un peu lourd mais avec les schémas XSD on a la garantie que les données sont valides.

- 14 . JACKSON : Une librairie Java pour le mapping objet / JSON. Ex(@JsonIgnore)

- 15 . JSON : Format léger d’échange de données. 

- 16 .	Projection : Citez les attributs d’une classe retournés par un service web.

- 17 .	Spécifications et implémentations

Spécification | Implémentation de référence (Oracle) | Autres implémentations 
--- | --- | --- 
JAX-WS | JaxWSImpl (Oracle) | CXF 
--- | --- | --- 
JAX-RS | Jersey (Oracle) | RestEasy(Jboss), SpringMVC 
--- | --- | --- 
JPA | Eclipselink (Oracle) | Hibernate (Jboss), Ibatis 
--- | --- | --- 
Serveur Application | Glassfish (Oracle) | Wildfly (Jboss), websphere(IBM) 
--- | --- | --- 
Bean validation | Hibernate Validation | Apache Bean Validation (formerly agimatec)

