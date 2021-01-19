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
18. myvercelgit-2gt42dd9w.vercel.app
19. Un pull request sert à faire merger 2 branches.