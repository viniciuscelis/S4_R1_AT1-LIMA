# Portal Institucional — nãoROCKSTAR

Protótipo de página institucional desenvolvido em HTML puro, apresentando um catálogo de jogos populares (Roblox, Minecraft, Fortnite, EA Sports FC e Call of Duty), como atividade de aplicação sobre estrutura semântica em HTML5.

## 📋 Sobre o projeto

A página simula o portal de uma empresa fictícia do ramo de jogos ("nãoROCKSTAR"), organizando o conteúdo em seções temáticas, cada uma dedicada a um jogo, além de uma área de recomendação externa e informações de contato.

## 🗂️ Estrutura do documento

| Tag | Uso no projeto |
|---|---|
| `<header>` | Logo (imagem) e título principal da empresa |
| `<nav>` | Menu de navegação com âncoras para cada seção |
| `<section>` | Uma seção por jogo (`#roblox`, `#minecraft`, `#fortnite`, `#eaSportsFc`, `#callOfDuty`) |
| `<article>` | Conteúdo descritivo de cada jogo dentro da sua seção |
| `<aside>` | Link de recomendação para site externo de avaliação de jogos |
| `<footer>` | Informações de contato (telefone, endereço e copyright) |

## 🎮 Conteúdo abordado

- Roblox
- Minecraft
- Fortnite
- EA Sports FC
- Call of Duty

## ⚠️ Pontos de atenção

Alguns ajustes recomendados para a versão final do protótipo:

- [ ] O atributo `src` da imagem no `<header>` está vazio — adicionar o logotipo da empresa.
- [ ] O link de "Call of Duty" está duplicado no `<nav>`.
- [ ] As seções de **Minecraft** e **Call of Duty** estão sem a tag de fechamento `</article>`.
- [ ] O atributo `lang` do `<html>` está definido como `en`, mas o conteúdo é em português — trocar para `lang="pt-BR"`.
- [ ] Adicionar texto alternativo (`alt`) descritivo na imagem do cabeçalho.

## 🚀 Como executar

1. Clone o repositório ou baixe o arquivo.
2. Abra o arquivo `portal_empresa.html` diretamente no navegador, ou use a extensão **Live Server** no VS Code para visualizar com recarregamento automático.

## 🛠️ Tecnologias utilizadas

- HTML5 (tags semânticas)

## 📄 Licença

Projeto de caráter acadêmico, sem fins comerciais.