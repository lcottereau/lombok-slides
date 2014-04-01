_Quickie_ sur [Lombok](http://projectlombok.org/) pour [Devoxx France 2014](http://cfp.devoxx.fr/cfp/proposal/new)
=============

## Idée de plan

* Introduction. Consensus autour de l'implémentation de _Design Patterns_. Annotations.
* Exemples de patterns qui me semblent importants (`@Getter` et `@Setter`, `@Data`, `@Builder`, `@Delegate`,...)
* Evocation rapide de certains autres (`@Lazy`, `@XXXConstructors`, `@Value`, `@Cleanup`, `@Log`,...) Indiquer pour `@Value` que cela permet (en plus du code généré) de documenter facilement [l'immutabilité](http://blogs.msdn.com/b/ericlippert/archive/2007/11/13/immutability-in-c-part-one-kinds-of-immutability.aspx).
* Pointeurs sur les référentiels ([stables](http://projectlombok.org/features/), [expérimentaux](http://projectlombok.org/features/experimental/) et [playground](https://github.com/peichhorn/lombok-pg)) et possibilité de créer ses extension.
* Difficultés
 * intégration avec les outils de dev (plugins IDEs, mises à jour JVM, sonar)
 * debug
 * compréhension du code
 * mesurer l'impact (performances par exemple avec `@toString`)
* Points forts
 * remaniement facile car seulement à la compilation
 * ne noie pas le code métier, la plus value
 * pas d'enfermement grâce à `delombok`
* Conclusion sur la maintenabilité plus que sur la rapidité d'écriture. Réduction du nombre de lignes et concentration sur le métier (grosse différence avec guava ou apache commons). La plomberie/complexité technique n'est pas à maintenir dans le projet


## Soumission à [Devoxx](http://cfp.devoxx.fr/cfp/proposal/new)

### Titre de la présentation (125)

Les « design patterns » clés en main avec Lombok. La maintenabilité en bonus.

### Résumé de votre présentation pour le participant (500)

Vous souhaitez appliquer les _design patterns_ reconnus par vos pairs développeurs. Vous souhaitez que ce soit (très) facile. Vous souhaitez par ailleurs que cette plomberie technique ne surcharge pas votre code afin de pouvoir vous concentrer sur le métier. C'est possible grâce à la bibliothèque [Lombok](http://projectlombok.org/).

### Message pour le comité de sélection (3500)

Après avoir expliqué le principe de [Lombok](http://projectlombok.org/), je présenterai avec un exemple des patterns qui me semblent les plus importants (`@Getter` et `@Setter`, `@Data`, `@Builder`, `@Delegate`,...) et en évoquerai rapidement d'autres (`@Lazy`, `@XXXConstructors`, `@Value`, `@Cleanup`, `@Log`,...) Je discuterai de difficultés liées à l'utilisation de l'outil (intégration aux outils de développement, debug, compréhension du code) et indiquerai que, grâce à `delombok`, on peut tester Lombok sans s'enfermer. Pour conclure, j'insisterai sur l'intérêt en terme de maintenabilité plus que sur la rapidité d'écriture ; tout ce qui est code technique _évident_ (puisque le résultat d'une forme de consensus de l'industrie) ne pollue pas le code métier.

Ce quickie vise plutôt les publics qui ne connaissent pas encore le projet. Le format rapide me semble intéressant pour éviter une liste rébarbative de l'ensemble des possibilités de l'outil qui ne remplacera pas l'expérience de son utilisation. Par ailleurs, ce format me semble suffisant pour que les participants puissent repartir avec les bons pointeurs et avoir envie d'expérimenter de leur côté. Si cela cadre mieux avec votre programme global, je peux envisager de faire un _Tools In Action_ avec du live coding plutôt que des diapositives, et aussi plus d'extensions présentées. Si cela vous intéresse, merci de me contacter pour que je fasse la nouvelle proposition.

Je n'ai jamais présenté à un événement de la taille de Devoxx. J'ai néanmoins une grande habitude de présentation en public ; je fais des présentations techniques [depuis une dizaine d'années](http://fr.linkedin.com/in/lcottereau/fr), en particulier à destination de mes collègues. Je suis intervenu à [IUT Agile cette année](https://github.com/lcottereau/po-non-certifie-slides) et je donne [des cours en licence pro et en école d'ingénieurs](https://github.com/lcottereau/maintainability-slides). Si vous le souhaitez, je peux vous fournir des références. Par ailleurs, j'ai travaillé il y a quelques années avec David Gageot et vous pouvez vous tourner vers lui si vous souhaitez en savoir un peu plus sur moi.

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
