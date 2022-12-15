# Billed-App - Saas à destination des équipes de RH

> OpenClassrooms - "Développeur d'application - JavaScript React".  
> Débuggez et testez un SaaS RH

<p align="center">
  <img src="https://github.com/Yann-GitHub/Bill-App/blob/main/Docs/logo.png?raw=true" alt="Billed Logo"/>
</p>

## Objectifs

Billed est une entreprise qui produit des solutions Saas destinées aux équipes de ressources humaines. On retrouve dans l'application deux parcours utilisateurs (employé & admin RH) décrits dans le document de '[description des fonctionnalité](./Docs/Billed%2B-%2BDescription%2Bdes%2Bfonctionnalit%C3%A9s.pdf)'.

**État d’avancement du projet**

✅ Le back-end des deux parcours est prêt en version alpha.

🚧 Côté front-end :
↳ Parcours administrateur : il a été testé, il faut désormais le débugger.
↳ Parcours employé : il faut entièrement le tester et le débugger.

**Missions**

La fonctionnalité “note de frais” doit être lancée rapidement pour répondre aux délais.

Fiabiliser et améliorer le parcours employé en s'appuyant sur le document de [Mise en place de la fonctionnalité de 'note de frais'](./Docs/Billed%2B-%2BDescription%2Bdes%2Bfonctionnalit%C3%A9s.pdf). On y retrouve la description pratique des besoins et le rapport avec les bugs identifiés ([Kanban Notion](https://www.notion.so/a7a612fc166747e78d95aa38106a55ec?v=2a8d3553379c4366b6f66490ab8f0b90)).

## Livrables

- Le Code Base à jour pour répondre aux besoins et diponible sur un [repo GitHub public](https://github.com/Yann-GitHub/Bill-App/tree/main/Billed-app-FR-Front).
- Un [screenshot](./Docs/rapport_test.png) au format PNG du rapport de tests Jest sur l’ensemble des fichiers d’UI (src/views) et d’UX (src/containers).
- Un [screenshot](./Docs/rapport_couverture.png) au format PNG du rapport de couverture Jest.
- Un [document au format PDF](./Docs/plan_test_end2end.pdf) du plan de tests End-To-End pour le parcours employé.

## Compétences évaluées

- Jest (Javascript Testing Framework) et @testing-library.
- Rédiger des tests unitaires et d'intégrations pour permettre d'éliminer les bugs et éviter toutes régressions lors des prochaines évolutions.
- Rédiger un plan de test End-to-End manuel.
- Débugger une application web avec Chrome Debugger.
