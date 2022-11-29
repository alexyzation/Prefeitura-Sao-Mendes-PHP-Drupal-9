## Informações

Esta aplicação é uma solução para sites de prefeitura desenvolvido com o CMS Drupal.

## Informações Técnicas

- Drupal versão 9.4
- Php versão 8+
- MariaDB/Mysql 10.3+

## Plugins instalados

- Pathauto (Para patterns e urls amigáveis): https://www.drupal.org/project/pathauto/releases/8.x-1.10
    - Token (Dependência necessária): https://www.drupal.org/project/token/releases/8.x-1.10
    - Chaos Tools (Dependência necessária): https://www.drupal.org/project/ctools/releases/4.0.0
- Devel (Ferramentas de desenvolvimento): https://www.drupal.org/project/devel
  - Kint (Ferramenta de desenvolvimento): https://github.com/kint-php/kint

## Links que ajudaram no desenvolvimento

- Criar um novo template: https://www.drupal.org/project/drupal/issues/3050384
- Remover o cache do Twig: https://www.drupal.org/node/2598914
- Exemplo da nomeclatura das views: https://api.drupal.org/api/drupal/core!modules!views!views.theme.inc/group/views_templates/8.2.x
- Como acessar os objetos dentro do Twig:https://drupal.stackexchange.com/questions/208201/how-to-get-each-field-value-in-views-views-unformatted-view-machine-name-html-t
- Como inserir variaveis no template: https://stefvanlooveren.me/blog/get-views-row-count-twig-drupal-8
