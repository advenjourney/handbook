# What is our stack ??

## Marketing Analytics
- Mautic, https://www.mautic.org/

## Design / UX
- Figma, https://www.figma.com/ @LukasHirt

## Docs
- Markdown @FelixBoehm
- Hugo @FelixBoehm


## Frontend
- Repo: https://github.com/advenjourney/novaturient
- Maintainers: @LukasHirt @FelixBoehm

### Web and mobile
Our frontend is built with [Vue.js](https://vuejs.org/) for both native mobile apps (thanks to [Nativescript](https://nativescript-vue.org/)) and web.

The project has been bootstrapped by [vue-cli](https://cli.vuejs.org/) together with [vue-cli-native-script-plugin](https://github.com/nativescript-vue/vue-cli-plugin-nativescript-vue) which allows us to share the codebase for all platforms.

Additional technologies are [Vuex](https://vuex.vuejs.org/) for global state and [Vue Router](https://router.vuejs.org/) for routing. Vue router handles only navigation in the web app. Navigating in the app is done via [Nativescript-Vue navigate method](https://nativescript-vue.org/en/docs/routing/manual-routing/#navigatetocomponent-options).

### Testing
- Unit and integration tests: [Jest](https://jestjs.io/) with [Vue test utils](https://vue-test-utils.vuejs.org/)
- E2E tests: [Cypress](https://www.cypress.io/)

If you're interested in contributing to frontend, please, refer to the [readme of our frontend repository](https://github.com/advenjourney/novaturient/blob/main/README.md).

## Backend
- Go
  - Project Layout https://github.com/golang-standards/project-layout
  - configuration [viper](github.com/spf13/viper)
  - cli github.com/urfave/cli/v2
- GraphQL https://graphql.org/

## CI/CD
- Github Actions
- Drone ??

## Microservice design considerations
- [Hexagonal Architecture](https://netflixtechblog.com/ready-for-changes-with-hexagonal-architecture-b315ec967749)
- [Hexagonal Architecture](https://alistair.cockburn.us/hexagonal-architecture/)
- [Go implementation](https://github.com/PacktPublishing/Learning-Functional-Programming-in-Go/tree/master/Chapter06/04_onion/src/domain)

## Infra
- S3 Storage for Terraform States and for User Assets
- Backblaze for dev phase
- Terraform for VM Provisioning
- Ansible for Host Config Management
- microk8s as dev orchestration runtime

## Pairing
- Git Life for vs code, https://marketplace.visualstudio.com/items?itemName=TeamHub.teamhub
- Life share, https://visualstudio.microsoft.com/de/services/live-share/ Interoperable between VS Code and all JetBrains IDEs
