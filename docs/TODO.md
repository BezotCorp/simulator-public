# TODO — BezotCorp Simulator Public API

Ce document suit les travaux relatifs au dépôt public.

Il ne décrit pas l’architecture interne ni les composants propriétaires de BezotCorp Simulator.

## API publique

- [ ] Définir les premiers contrats réellement nécessaires aux extensions.
- [ ] Ajouter les types partagés uniquement lorsqu’un besoin concret de compatibilité le justifie.
- [ ] Éviter d’exposer des détails d’implémentation internes.
- [ ] Définir une stratégie de versionnement de l’API publique.
- [ ] Définir les règles de compatibilité entre versions de l’API.

## Extensions

- [ ] Définir les éléments publics nécessaires à l’identification d’une extension.
- [ ] Définir progressivement les contrats nécessaires au développement d’extensions.
- [ ] Vérifier que les extensions officielles et communautaires peuvent utiliser le même mécanisme public.
- [ ] Tester l’API avec une première extension expérimentale avant de stabiliser inutilement des abstractions.

## Documentation

- [ ] Documenter chaque élément public au moment où il devient réellement utilisable.
- [ ] Ajouter des exemples minimaux d’utilisation lorsque l’API commence à se stabiliser.
- [ ] Documenter les règles de compatibilité et de versionnement.
- [ ] Maintenir le README français/anglais.
- [ ] Maintenir les versions française et anglaise de la licence et des communications officielles.

## Qualité

- [ ] Ajouter les vérifications CI nécessaires au workspace public.
- [ ] Vérifier régulièrement que le dépôt public ne contient aucun élément propriétaire destiné au dépôt privé.
- [ ] Tester le packaging de `simulation-api` avant toute publication.
- [ ] Préparer la publication de `simulation-api` lorsque son contenu justifiera une première version publique.
