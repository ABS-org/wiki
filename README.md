Wiki ABS
====================
**Wiki para visão geral de projetos da Atenção Básica à Saúde**

Esta wiki reúne um conjunto de padrões para desenvolvimento de projetos. Incluem-se as normas e as melhores práticas para vários aspectos de um projeto, desde o levantamento de requisitos, passando pelo setup do projeto, desenvolvimento, até sua manutenção e análise qualitativa. Apesar de diferente, esta wiki teve como inspiração o guia [North](https://github.com/Snugug/north), que reune, mas com uma abrangência maior, padrões de desenvolvimento de projetos.

Esta wiki é um documento vivo. Tendo em vista que normas e melhores práticas mudam, este documento também deve mudar com elas. Para referenciar e acompanhar as mudanças usaremos [SEMVER] (http://semver.org/) como parâmetro de versionamento. Contribuições são mais do que bem-vindas, desde que as [Orientações de Contribuição] (#como-contribuir) sejam seguidas.

*Atualmente estamos na versão,[v0.0.1] (https://github.com/ABS-org/wiki/releases/tag/v0.0.1), que é o início de tudo. Ao passo em que a evolução for acontecendo, caminharemos para uma versão mais sólida e consistente.*

# Tabela de Conteúdo

1. [Guias de Alinhamento](#guias-de-alinhamento)
  * [Versionamento](#versionamento)
    * [Tags and Releases](#tags-and-releases)
    * [Git Submódulos](#git-submódulos)
    * [Branches](#)
  * [Visual Design](#visual-design)
    * [Style Guide](#)
    * [Layout Guide](#)
    * [Component Guide](#)
    * [Tipografia](#)
    * [Iconografia](#)
  * [Código](#código)
    * [Stylesheets](#)
      * [Convenções](#)
      * [Padrões e Mixins](#)
    * [Markup](#)
      * [HTML Semantics](#)
      * [Temas](#)
      * [Layouts](#)
      * [Partials](#)
      * [Componentes](#)
      * [Elementos](#)
        * [Tipos](#)
        * [States](#)    
2. [Gerenciamento](#gerenciamento)
  * [Ferramentas](#ferramentas)
3. [Manutenção](#manutenção)
  * [Testes](#testes)
  * [Performance](#performance)
  * [Acessibilidade](#acessibilidade)
4. [Análise](#análise)
  * [Google Analytics](#google-analytics)
  * [Desempenho](#desempenho)
5. **Links para consulta**
  * [Princípios para escrever CSS de forma consistente](http://tableless.com.br/principios-para-escrever-css-de-forma-consistente/)
  * **Drupal Commons**
    * [Releases](https://drupal.org/node/2067473)
    * [Issues](https://drupal.org/node/2067477)
6. [Como Contribuir](#como-contribuir)
  * [Requisitos](#requisitos)
  * [Issues](#issues)
    * [Criando uma Issue](#criando-uma-issue)
    * [Informando um Bug](#informando-um-bug)

# Guias de Alinhamento

São convenções para facilitar o desenvolvimento. São usadas para [Versionamento](#versionamento), [Visual Design](#visual-design) e para manter o [Código](#código) consistente, com padrões pré-estabelecidos.

## Versionamento

Usaremos [SEMVER] (http://semver.org/) (Semantic Versioning), e dividiremos cada sprint, em uma versão específica. É preciso ter noção do quanto a implementação irá impactar na aplicação como um todo. Assim podemos passar da *v0.0.1* direto para *v0.0.2* ou para *v0.0.15*, dependendo do tamanho da implementação feita, sempre seguindo as convenções do [SEMVER] (http://semver.org/).

O versionamento é importante principalmente quando se tem vários projetos correlacionados, em que um depende do outro para funcionar. Assim podemos referenciar uma dependência a uma versão específica e saber que features a versão desta dependência proporciona, se é estável ou não etc. Assim, a cada nova versão de uma dependência, teremos a escolha integra-la ou não em nosso projeto, sabendo com precisão seu estágio e o que ela proporciona.

### Tags and Releases

[Tags](http://git-scm.com/book/pt-br/Git-Essencial-Tagging) e [Releases](https://help.github.com/articles/creating-releases) tem como objetivo referenciar um estágio do desenvolvimento. A diferença entra elas, apesar de ambas serem "tags de referência", é que a release representa mudanças significativas no contexto da aplicação, enquanto a tag representa um estágio menos significativo. Pode-se dizer que uma release é um conjunto de tags compiladas.

### GIT Submódulos

## Visual Design

## Código

# Gerenciamento

[Ferramentas](#ferramentas) e explicação do(s) workflow(s) utilizados para gerenciar os projetos.

## Ferramentas

# Manutenção

Sobre as formas de [Teste](#testes), como melhorar a [Performance](#performance) e tornar a aplicação [Acessível](#acessibilidade) aos diferentes disposivos e pessoas com deficiência.

## Testes

## Performance

## Acessibilidade

# Análise

[Google Analytics](#google-analytics) e outras ferramentas para mensurar resultados e melhorar o [Desempenho](#desempenho) da aplicação.

## Google Analytics

## Desempenho

# Como Contribuir

Para contribuir é necessário ter as ferramentas listadas na seção de [Requisitos](#requisitos). Caso precise de ajuda e sua dúvida não esteja respondida nesta wiki, talvez a seção [Issues](#issues) poderá lhe ajudar.

## Requisitos

## Issues

São questões relacionadas ao projeto. Propostas de feature, aviso para um bug encontrado ou dúvidas. É possível [abrir uma issue](https://github.com/ABS-org/wiki/issues) e iniciar uma discussão para ter a dúvida respondida, bug corrigido ou feature implementada.

### Criando uma Issue

### Informando um Bug
