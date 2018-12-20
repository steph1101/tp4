# Answers

Nom : VALTON
Prénom : Stephane
NB : 4

# 1.
A quoi sert l'A/B testing ? C'est pour voir l'impact d'une mise a niveau sur un panel d'utilisateurs

Comment appliquer de l'A/B testing grâce à Istio ? On instaure 2 routes avec 2 versions qui se situe entre 0 et 100 et leur somme doit etre egale a 100.

# 2.
Comment simuler un problème de timeout avec Istio ? Avec le fault injection

Comment le résoudre ? il est possible d'optimiser le code ou de modifier le timeout en paramettrant les applis

# 3.
Qu'est-ce que le canary release ? le canary realease sert a faire migrer une partie des users en version N+1 et laisser une majorite en version N.

En quoi est-ce utile ? Simplement pour tester l'update et de diminuer les risque et la surcharge.

Comment l'implémenter dans Istio ? C'est un peu la meme chose que pour l'A/B testing, on met un poids fauble pour la nouvelle version

# 4.

# 5.
Qu'est-ce qu'un Circuit Breaker ? Pattern desactivant l'envoi des flux de donnees en cas de disfonctionnement d'un service.

Comment l'implémenter dans un contexte Kubernetes ? il faut voir dans les config de kubernetes.

# 6.
Pourquoi avoir besoin de mirrorer le traffic vers un autre composant ? pour
limiter les risques d'une nouvelle version fonctionnant mal.

# 7.
Pourquoi bloquer le traffic vers un service ? Pour eviter d'avoir trop de retard et de ralentir les autres services

Comment l'implémenter simplement avec Istio ? implementer des rate limits

# 8.
Quelle est la problématique de tracing distribué ? tracer les requetes entre les services pour suivre en direct les performances du systeme

Quelle est la spécification du tracing distribué et son implémentation dans Istio ? il est dote d'un dashboard pour pister le flux.

# 9.
Comment s'appelle l'outil de récupération des métrics ? Prometheus

# 10.

# 11.
Comment s'appelle l'outil de visualisation des métrics ? Grafana

# 12.
A quoi sert un servicegraph ? A visualiser le traffic des donnees

Quel serait l'utilité dans le quotidien d'un ops ? surveiller le systeme et intervenir en cas de probleme
