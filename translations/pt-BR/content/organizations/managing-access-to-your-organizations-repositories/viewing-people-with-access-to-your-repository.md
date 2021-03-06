---
title: Exibir pessoas com acesso ao seu repositório
intro: 'Os proprietários da organização podem ver o acesso das pessoas a um repositório dentro de uma organização. Os proprietários de organizações que usam o {% data variables.product.prodname_ghe_cloud %} ou o {% data variables.product.prodname_ghe_server %} também podem exportar uma lista CSV de pessoas que têm acesso a um repositório.'
redirect_from:
  - /articles/viewing-people-with-access-to-your-repository
  - /github/setting-up-and-managing-organizations-and-teams/viewing-people-with-access-to-your-repository
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
topics:
  - Organizations
  - Teams
shortTitle: Visualizar pessoas com acesso
---

Os administradores podem usar essas informações para ajudar pessoas fora do quadro, coletar dados para conformidade e outras verificações gerais de segurança.

![Lista de permissões para pessoas no repositório](/assets/images/help/repository/repository-permissions-list.png)

## Exibir pessoas com acesso ao seu repositório

{% ifversion fpt or ghec %}
{% note %}

**Observação**: Você também pode ver uma visão geral combinada das equipes e pessoas com acesso ao seu repositório. Para obter mais informações, consulte "[Gerenciar equipes e pessoas com acesso ao seu repositório](/github/administering-a-repository/managing-teams-and-people-with-access-to-your-repository). "

{% endnote %}
{% endif %}

{% data reusables.repositories.navigate-to-repo %}
{% data reusables.repositories.accessing-repository-graphs %}
{% data reusables.repositories.accessing-repository-people %}

## Exportar uma lista de pessoas com acesso a um repositório

Os proprietários de organizações no {% data variables.product.prodname_ghe_cloud %} ou no {% data variables.product.prodname_ghe_server %} podem exportar uma lista CSV de pessoas que têm acesso a um repositório.

{% data reusables.repositories.navigate-to-repo %}
{% data reusables.repositories.accessing-repository-graphs %}
{% data reusables.repositories.accessing-repository-people %}
4. Clique em **Export CSV** (Exportar CSV). ![Guia People (Pessoas) na barra lateral do repositório](/assets/images/help/repository/export-repository-permissions.png)
