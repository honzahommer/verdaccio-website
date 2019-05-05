# Verdaccio 4 released today !!!

#### Release name: Freedom

Verdaccio is a free open source Javascript package proxy registry.  It is fully compatible with pnpm, yarn and npm package management clients. It follows the CommonJS compliant package  specifications. 

You can install and upgrade to the latest version by following commands:
using **npm** 
````
npm install -g verdaccio@4.0.0
````

or using **Yarn** 
````
yarn global add verdaccio@4.0.0
````

or using **pnpm** 
````
yarn global add verdaccio@4.0.0
````

You can find detailed installation instructions  [here](https://verdaccio.org/docs/en/installation)

## Why 'Freedom' ?
Verdaccio originated from sinopia 3 years ago and since then verdaccio team maintaining and releasing major release every year. Since the fork, the project has evolved in many ways, making the project’s code base modern, easier to debug and more straightforward to contribute to by the community! 

The name freedom holds a true meaning for version 4 release. The verdaccio is a strong community of many contributors and developers from across the world, providing an ideal platform for everyone to give control on their code. Also version 4 is free from tech debt of  legacy code and stands on design patterns of modern era which consist React, Typed plugin system, JWT, Docker & kubernetes.  We can call it Freedom in true sense. 

Let's take a quick look at the life cycle and development of verdaccio community:

- **Verdaccio@2 (Release name: Birth)** -  focused on stability, code quality, improvement in  architecture of the old sinopia project and the most important community development. 

- **Verdaccio@3 (Release name: Hope)** - revamped the user interface in React and introduced the simplicity of the plugin development. The verdaccio team and many contributors made the project almost bug free and robust. This was the time project started to grow and big players started using it. 

It's the first release, verdaccio is coming up with many exciting new CLI commands for package management,  Fast and Responsive user interface,  Security upgrades and easy deployments.

Excited ?? Yes !!! Let's go !!

## So what's changed ? TL;DR
- [New User Interface](#new-ui)
    - [New search Process](#new-search-process)
    - [Package card](#package-card)
    - [Detailed Page](#detailed-page)
    - [Package sidebar](#package-sidebar)
- [New Router APIs](#router-api) 
- [New commands](#new-npm-commands)
    - [npm star](#npm-start)
    - [npm profile](#npm-profile)
    - [npm token](#npm-token)
- [Plugins](#plugins)
- [Drop node 6 support, minimum requirement node 8](#remove-node-6)
- [Update notification](#notification-banner)
- [JWT token](#jwt-token)
- [Docker improvements](#docker-improvements)
- [Tech updates](#tech-updates)
    - Eslint config
    - Typescript
    - React & Material UI
    - UI as a separate package

## <a id="new-ui"></a> New user interface

Version 4 comes with a new shiny appealing user interface, providing more details to show and easy to navigate. We did major changes in verdaccio web application and everything is designed from scratch. 

### <a id="new-search-process"></a> New search Process
In version 3, verdaccio has a limited search functionality and it was all on web ui. Verdaccio 4 provides fast and quick search results from backend.

### <a id="packages-card"></a> Package card
Now package card provides more information about a package, easy to open issues and read the documentation without navigating into package details. 

### <a id="detailed-package"></a> Detailed Page
We have detailed package in a more categorized manner for readme, dependencies, version and uplinks. 

### <a id="package-sidebar"></a> Package sidebar

Package sidebar includes most relevant information from package metadata. You can open an issue, see readme and download the package tarball. It also clearly shows the package's minimum requirements on node and npm. 

Also package sidebar shows *Author*, *Maintainers* and *Contributors* in different sections. When you click on anyone one of the avatar, you'll be able to contact that person via email.


## <a id="router-api-ui"></a> New Router APIs
Till, verdaccio@2 we have hash router implementation on frontend application routes. We faced a lot of problem with hash router in readme section. Readmes also uses (#) hash for the heading tags and anchor elements. 

In verdaccio@3, we moves hash router to more cleaner look to browser router. ( No more hashes in URLs).


## <a id="new-npm-commands"></a> New commands

We are really excited to add some npm cli commands to verdaccio. Now you can use `npm star`, `npm profile` and `npm token`

### <a id="npm-star"></a> npm star

Now a user can mark their favorite package. 

```
npm star [<package>..]
```
### <a id="npm-profile"></a> npm profile

With npm profile an user change their profile settings. 

*Note:* verdaccio does not support two factor authentication yet.

```
npm profile get [--json|--parseable] [<property>]
npm profile set [--json|--parseable] <property> <value>
npm profile set password
```

Check out more at https://docs.npmjs.com/cli/profile

### <a id="npm-token"></a> npm token
@jaunpicado

## <a id="plugins"></a> Plugins
@juanpicado

## <a id="jwt-token"></a> JWT token
@juanpicado

## <a id="docker-improvements"></a> Docker improvements
@juanpicado

## <a id="remove-node-6"></a> Node 8 is minimum requirement

Node JS 6 went to end of life on April 30, 2019. Verdaccio@4 will drop the support for node6 and node8  will be the minimum requirement.



