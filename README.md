lombok-slides
=============

Quickie sur lombok

## Idée de plan

* à quoi ça sert ? Parler de patterns gratuits et bien faits
* parler de maintenabilité : tout ce qui n'est pas écrit n'est pas à maintenir
* expliquer les plus intéressants sur un exemple complet : getters, tostring, data, hascodeandequals, lazy, constructors
* d'autres rapidement : value, cleanup (java 6-) log, builder
* indiquer plein d'autres et catégories (stables, expé et [autres](https://github.com/peichhorn/lombok-pg))
* indiquer problèmes éventuels (intégration outils/IDEs/JVMs/sonar, debug, WTF)
* conclusion : réduction du nombre de lignes et extraction de la complexité technique pour mettre en valeur le code métier

à étudier
* extensionmethode
* value
* on peut en sortir facilement (delombok)
* regarder le asfunction

## Resources

* http://projectlombok.org/features/index.html
* la vidéo sur http://projectlombok.org/
* http://jnb.ociweb.com/jnb/jnbJan2010.html
* http://www.devoxx.com/display/FR12/Depoussierez+votre+code+java+avec+Lombok+!
* http://www.parleys.com/play/528df66ce4b054cd7d2ef496/chapter0/about
* la vidéo du paris jug sur lombok ?

## Soumission à [Devoxx](http://cfp.devoxx.fr/cfp/proposal/new)

### Titre de la présentation (125)

Les _Design Patterns_ clé en main avec Lombok. La maintenabilité en bonus.

### Résumé de votre présentation pour le participant (500)

Vous souhaitez appliquer les _design patterns_ reconnus par vos pairs développeurs. Vous souhaitez que ce soit (très) facile. Vous souhaitez par ailleurs que cette plomberie technique ne surcharge pas votre code, pour pouvoir vous concentrer sur le métier. C'est possible grâce au projet Lombok.

### Message pour le comité de sélection (3500)

Après avoir expliqué le principe de Lombok, je donnerai des exemples de patterns qui me semblent les plus importants (`@Getter` et `@Setter`, `@Data`, `@Builder`, `@Delegate`,...) et aborderai rapidement certains autres (`@Lazy`, `@Value`, `@Cleanup`, `@Log`,...) Je discuterai de difficultés liées à l'utilisation de l'outil (intégration aux outils de dev, debug, compréhension du code). Pour conclure, j'insisterai sur l'intérêt en terme de maintenabilité plus que sur la rapidité d'écriture ; tout ce qui est code technique _évident_ puisque le résultat d'une sorte de consensus de l'industrie ne pollue pas le code métier.

Lombok a déjà été présenté à différentes reprises. Ce quickie vise plutôt les publics qui ne connaissent pas encore le projet. Le format rapide me semble intéressant pour éviter une liste rébarbative de l'ensemble des possibilités de l'outil qui ne remplace pas l'expérience. Par ailleurs, cela me semble adapté pour que les participants puissent repartir avec les bons pointeurs et avoir envie d'expérimenter de leur côté.

## Agenda

- Ouverture du CFP : Lundi 2 décembre 2013
- Fermeture du CFP : Dimanche 2 février 2014 minuit
- Annonce du programme : février/mars 2014
