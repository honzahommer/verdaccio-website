---
id: version-3.8.6-ci
title: Непрерывная интеграция (CI)
original_id: ci
---

Вы можете использовать verdaccio с системами непрерывной интеграции при входе или публикации. Когда вы используете NPM для установки приватного модуля в окружении непрерывной интерграции, то сразу упираетесь в кирпичную стену. Команда NPM login была разработана для интерактивного использования. Это вызывает проблемы в CI, скриптах и т.п. Вот как нужно использовать команду NPM login на различных платформах непрерывной интеграции.

- [Travis CI](https://remysharp.com/2015/10/26/using-travis-with-private-npm-deps)
- [Circle CI 1.0](https://circleci.com/docs/1.0/npm-login/) или [Circle CI 2.0](https://circleci.com/docs/2.0/deployment-integrations/#npm)
- [Gitlab CI](https://www.exclamationlabs.com/blog/continuous-deployment-to-npm-using-gitlab-ci/)