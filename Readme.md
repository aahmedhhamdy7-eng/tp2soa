# CalculatriceWS – Service Web SOAP avec Jakarta XML Web Services

TP2 – Architecture SOA et services web | LSI3-GLSI
Faculté des Sciences de Sfax | Année universitaire 2026-2027
*Réalisé par : Hamdi Ahmed*


---

## 1. Description

CalculatriceWS est une application Java qui expose un service web SOAP de calculatrice. Elle propose quatre opérations : somme, soustraction, multiplication et division.

Le service est développé avec Jakarta XML Web Services (JAX-WS), géré par Maven, publié avec Endpoint.publish et testé avec SoapUI.


### Activité 1 : Projet Maven


Fichier pom.xml

![pom.xml](image/p.png)


### Activités 2 et 3 : Interface, classe métier et annotations

*Interface ICalculatrice*

![Interface ICalculatrice](image/i.png)

*Classe Calculatrice*

![Classe Calculatrice](image/c.png)

### Activité 4 : Publication du service

*Classe ServeurJWS*

![Classe ServeurJWS](image/s.png)

Console du serveur

![Console du serveur](image/11.png)

voici url : http://localhost:8080/CalculatriceWS?wsdl

WSDL généré

![WSDL](image/2.png)



### Activité 5 : Tests avec SoapUI

Création du projet SoapUI

![Nouveau projet SoapUI](image/soap.png)

Opérations importées

![Arborescence SoapUI](image/img.png)

*Opération somme*

![Somme](image/req.png)
![Somme](image/er.png)
*Opération soustraction*

![Soustraction](image/99.png)

*Opération multiplication*

![Multiplication](image/22.png)

*Opération division*

![Division](image/77.png)





## 12. Auteur

Ahmed Hamdi – LSI3-GLSI – Faculté des Sciences de Sfax – 2026-2027    
localhost