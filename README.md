_Quickie_ sur [Lombok](http://projectlombok.org/) pour [Devoxx France 2014](http://cfp.devoxx.fr/cfp/proposal/new)
=============

## Idée de plan

* Introduction. Consensus autour de l'implémentation de _Design Patterns_. Annotations.
* Exemples de patterns qui me semblent importants (`@Getter` et `@Setter`, `@Data`, `@Builder`, `@Delegate`,...)
* Evocation rapide de certains autres (`@Lazy`, `@XXXConstructors`, `@Value`, `@Cleanup`, `@Log`,...)
* Pointeurs sur les référentiels ([stables](http://projectlombok.org/features/), [expérimentaux](http://projectlombok.org/features/experimental/) et [playground](https://github.com/peichhorn/lombok-pg)) et possibilité de créer ses extension.
* Difficultés
 * intégration avec les outils de dev (plugins IDEs, mises à jour JVM, sonar)
 * debug
 * compréhension du code
* Pas d'enfermement grâce à `delombok`
* Conclusion sur la maintenabilité plus que sur la rapidité d'écriture. Réduction du nombre de lignes et concentration sur le métier. La plomberie/complexité technique n'est pas à maintenir dans le projet


## Soumission à [Devoxx](http://cfp.devoxx.fr/cfp/proposal/new)

### Titre de la présentation (125)

Les _Design Patterns_ clé en main avec Lombok. La maintenabilité en bonus.

### Résumé de votre présentation pour le participant (500)

Vous souhaitez appliquer les _design patterns_ reconnus par vos pairs développeurs. Vous souhaitez que ce soit (très) facile. Vous souhaitez par ailleurs que cette plomberie technique ne surcharge pas votre code afin de pouvoir vous concentrer sur le métier. C'est possible grâce à la bibliothèque [Lombok](http://projectlombok.org/).

### Message pour le comité de sélection (3500)

Après avoir expliqué le principe de [Lombok](http://projectlombok.org/), je présenterai avec un exemple des patterns qui me semblent les plus importants (`@Getter` et `@Setter`, `@Data`, `@Builder`, `@Delegate`,...) et en évoquerai rapidement d'autres (`@Lazy`, `@XXXConstructors`, `@Value`, `@Cleanup`, `@Log`,...) Je discuterai de difficultés liées à l'utilisation de l'outil (intégration aux outils de dev, debug, compréhension du code) et indiquerai que, grâce à `delombok`, on peut tester Lombok sans s'enfermer. Pour conclure, j'insisterai sur l'intérêt en terme de maintenabilité plus que sur la rapidité d'écriture ; tout ce qui est code technique _évident_ puisque le résultat d'une sorte de consensus de l'industrie ne pollue pas le code métier.

Lombok a déjà été présenté à différentes reprises. Ce quickie vise plutôt les publics qui ne connaissent pas encore le projet. Le format rapide me semble intéressant pour éviter une liste rébarbative de l'ensemble des possibilités de l'outil, qui ne remplacera pas l'expérience de son utilisation. Par ailleurs, ce format me semble suffisant pour que les participants puissent repartir avec les bons pointeurs et avoir envie d'expérimenter de leur côté.

Je n'ai jamais présenté à un évènement de la taille de Devoxx. J'ai néanmoins une grande habitude de présentation en public ; je fais des présentations techniques [depuis une dizaine d'années](http://fr.linkedin.com/in/lcottereau/fr), en particulier à destination de mes collègues. Je suis intervenu à [IUT Agile cette année](http://www.iutagile.com/?page_id=25) et je donne [des cours en licence pro et en écode d'ingénieurs](https://github.com/lcottereau/maintainability-slides). Si vous le souhaitez, je peux vous fournir des références.

## Agenda

- Ouverture du CFP : Lundi 2 décembre 2013
- Fermeture du CFP : Dimanche 2 février 2014 minuit
- Annonce du programme : février/mars 2014

## Resources

* http://projectlombok.org/features/index.html
* la vidéo sur http://projectlombok.org/
* http://jnb.ociweb.com/jnb/jnbJan2010.html
* http://www.devoxx.com/display/FR12/Depoussierez+votre+code+java+avec+Lombok+!
* http://www.parleys.com/play/528df66ce4b054cd7d2ef496/chapter0/about
* la vidéo du paris jug sur lombok ?
