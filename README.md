# API VALORANT

![Valorant Logo](https://cdn.vox-cdn.com/thumbor/wE9Nk1vjZK2KKcYwVh20g6jn0Uk=/1400x1400/filters:format(png)/cdn.vox-cdn.com/uploads/chorus_asset/file/19928713/valorant_logo.png)

## Descrição
Este projeto consiste em uma aplicação mobile que utiliza a API do Valorant para exibir informações sobre as skins das armas que são utilizadas dentro do jogo.

### URL DA DOCUMENTAÇÃO
- (https://valorant-api.com/v1/weapons/skins)
- Retorna dados e ativos de todas as skin de armas

### URL DE ACESSO A API 
- NÃO POSSUI TOKEN DE ACESSO

## Funcionalidades
- [ ] Exibi um catálogos de skins

## Métodos
-

| Campo                                 | Tipo    | Descrição                                                    |
|---------------------------------------|---------|--------------------------------------------------------------|
| id                                    | string  | ID da arma                                                   |
| displayName                          | string  | Nome da arma                                                 |
| category                              | string  | Categoria da arma (pistols, smgs, rifles, shotguns, snipers, heavy)|
| defaultSkinId                         | string  | ID da skin padrão                                            |
| displayIcon                           | string  | Ícone da arma                                                |
| assetPath                             | string  | Caminho para o modelo 3D da arma                              |
| skins                                 | objeto  | Objeto contendo todas as skins da arma                         |
| skins.{skinId}.displayName           | string  | Nome da skin                                                 |
| skins.{skinId}.displayIcon            | string  | Ícone da skin                                                |
| skins.{skinId}.levels                 | objeto  | Objeto contendo os níveis da skin                             |
| skins.{skinId}.levels.{level}.displayName | string | Nome do nível da skin                                        |
| skins.{skinId}.levels.{level}.displayIcon  | string | Ícone do nível da skin                                       |
| skins.{skinId}.levels.{level}.chromas      | objeto | Objeto contendo as variações cromáticas do nível da skin      |
| skins.{skinId}.levels.{level}.chromas.{chromaId}.displayName | string | Nome da variação cromática |
| skins.{skinId}.levels.{level}.chromas.{chromaId}.displayIcon  | string | Ícone da variação cromática |
| skins.{skinId}.levels.{level}.chromas.{chromaId}.fullRender    | string | Caminho para a renderização completa da variação cromática   |
| skins.{skinId}.levels.{level}.chromas.{chromaId}.swatch        | string | Caminho para a amostra de cores da variação cromática         |
| skins.{skinId}.levels.{level}.chromas.{chromaId}.uuid          | string | ID único da variação cromática                                |

## Software utilizado | Tecnologia 
- AndroidStudio | Java 

## Como utilizar
*|O usuário entraria na tela inicial e poderia localizar a skin busncando-a desejada combase no seu nome, ou pesquisando sobre a arma|*  

## Criador | Curso
Luiz Gustavo David de Barros | 3A Etim Desenvolvimento de Sistemas (3DS)

## Orientadora | Componente
Aline Faria Brito | PAM III
