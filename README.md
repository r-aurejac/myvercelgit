![Angular Logo](https://github.com/vercel/vercel/blob/master/packages/frameworks/logos/angular.svg)

# Angular Example

This directory is a brief example of an [Angular](https://angular.io/) app that can be deployed with Vercel and zero configuration.

## Deploy Your Own

Deploy your own Angular project with Vercel.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/vercel/vercel/tree/master/examples/angular)

_Live Example: https://angular.now-examples.now.sh_

### How We Created This Example

To get started with Angular, you can use the [Angular CLI](https://cli.angular.io/) to initialize the project:

```shell
$ ng new
```


4. vercel -v
5. vercel init <nomDuProjet>
6. cd angular
   vercel
7. vercel ls
8. vercel logs https://myvercel-six.vercel.app
9. inspect sert à recuperer des informations sur un déploiment ou sur les déploiment d'une production
10. Les variables d'environnement servent à injecter des valeurs que l'on ne souhaite pas placer directement
	dans notre code source et de modifier son comportement en fonction de l'environnement dans lequel il s'exécute.
11. vercel env add plain maVariable production
12. vercel env ls 
13. les variables secrètes sont cryptées et fournissent un moyen sûr de stocker et de partager des informations sensibles entre les déploiements.
15. vercel secrets add secret1 test_value
	vercel env add secret secret_variable production
16. production, preview, development
	L'intérêt d'avoir plusieurs environnement, c'est de pouvoir faire des tests sans casser l'application. On développe sur l'environnement de développement,
	puis après on fait les tests sur preview pour ainsi "pousser" les modifications finales sur l'environnement de production disponible au clients.
17.
18. myvercelgit-2gt42dd9w.vercel.app
19. Un pull request sert à faire merger 2 branches.
20. Vercel vérifie la compatibilité du code.
21. La branche main correspond à la production et l'autre branche créée au developpement.
	Un pull request permet de fusionner deux branches tout en pouvant éliminer d'eventuel problème de compatibilité.
	Workflow d'une feature permet la modification sur la branche dev (développement) dans le working tree, 
	l'envoi (commit et push) des modification sur la branche dev du dépôt Git,
	d'effectuer pull-request et merge de la branche dev du dépôt vers la branche master (production) du dépôt,
	la récupération de la branche master de dépôt (pull) vers la branche master du working tree (la vraie application)
22. L’architecture serverless est un modèle dans lequel le fournisseur de services cloud (AWS, Azure ou Google Cloud) 
	est responsable de l’exécution d’un morceau de code en allouant de manière dynamique les ressources

	L'interet du serverless :
    -Pas besoin de maintenir les serveurs disponibles même lorsqu’il n’y a pas de requêtes à traiter.
	-On est plus responsable de la disponibilité et de la maintenance des serveurs et de leurs ressources.
    -On est plus responsables d’appliquer les patches de sécurité sur les serveurs.	
    -On a plus besoin d'ajuster les serveurs avec la charge : augmenter lorsque la charge arrive et diminuer lorsque la charge redescend.