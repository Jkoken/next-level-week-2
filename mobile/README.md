# Estruturação do App Mobile: 

## Projeto criado com Expo;

## Landing Page estruturada e Estilizada:
    * Estilização utilizando expo google fonts, assim como sua importação e implementação no App.tsx;

## Navegação da Landing Page:
    * Utilização de rotas (com a biblioteca React Navigation), implementação em botões para trocas de telas e conteúdos;
    * Utilizando a navegação Stack e Tabs;

## Realizando a listagem e filtro de Professores;

## Conectando com a API:
    * Mostrando o total de conexões e a lista de professores de acordo com um filho aplicado;

## Contato via Whatsapp;
    * Conexão por deep link;
    * Importando o Linking do react-native;

## Adicionar e Remover favoritos da lista de favoritos:
    * Utilizando o expo async storage;
    * Utilizando também o splice, para remover;
    * Utilizando o useFocusEffect ao invés do useEffect, pois com o useFocusEffect, toda vez que a aba for trocada o valor será atualizado, coisa que não acontece com o useEffect.

