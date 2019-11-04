Smart Mode
=====
La fonction smart va vous permettre d'anticiper le passage des modes en fonction de l'historique. 
Le plugin va scruter les changements d'états sur les précédentes semaines et déterminer les probabilités de passage dans l'état. 
L'avantage principal est la gestion du chauffage afin d'avoir une pièce à température lors de l'arrivée. 

![presence98](../images/presence_smart_exemple.png)

Pour activer la fonction : 
- Se rendre sur l'onglet Programmation de l'objet et activer le mode smart.

  Pour le mode automatique :
  - Renseigner le thermostat sur lequel sera basé les coefficients

  Pour le mode manuel :
  - Renseigner les coefficients de chauffe et d'inertie.
  - Renseigner les capteurs de température. 

- Sur les modes pour lesquels vous voulez utiliser la fonction renseigner une température cible a utiliser. 
- Renseigner les actions qui seront exécutées. 

L'information Mode doit être historisée (Activée par défaut).
Allouer un délai d'un mois d'historique avant de voir les anticipations.

![presence99](../images/presence_smart_mode.png)

__Coefficient chauffage manuel :__ il s’agit du gain du système de régulation . Cette valeur est multipliée par l’écart entre la consigne et la température intérieure mesurée.

__Coefficient inertie manuel :__ ce coefficient est multiplié par l’écart entre la consigne et la température extérieure mesurée.
