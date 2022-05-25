# Gerenciamento de contatos
Repositório apenas para uso na matéria de Mobile (1,2 e 3) no curso tícnico da Fema.

YouTube no link: <a href="https://www.youtube.com/playlist?list=PLdDT8if5attEd4sRnZBIkNihR-_tE612_">Curso React Native (aprendize) - One Bit Code</a>. A playlist contém uma série de vídeos sobre desenvolvimento de aplicações mobile com React Native.

A API usada para trabalhar com navegação na aplicação é apresentada e demonstrada nos seguintes vídeos em específico:

- <a href="https://www.youtube.com/watch?v=O49tGxZBvNw&list=PLdDT8if5attEd4sRnZBIkNihR-_tE612_&index=18">Navegação (StackNavigator, TabNavigator e Drawer) - Aula 7 - Parte 1 | Curso React Native (aprendiz)</a>
- <a href="https://www.youtube.com/watch?v=RGp5xdidde8&list=PLdDT8if5attEd4sRnZBIkNihR-_tE612_&index=19">Navegação (StackNavigator, TabNavigator e Drawer) - Aula 7 - Parte 2 | Curso React Native (aprendiz)</a>
- <a href="https://www.youtube.com/watch?v=ah25k0Ib7vw&list=PLdDT8if5attEd4sRnZBIkNihR-_tE612_&index=19">Navegação (StackNavigator, TabNavigator e Drawer) - Aula 7 - Parte 3 | Curso React Native (aprendiz)</a>

## Rodando e testando o projeto
Abaixo o passo a passo após clonar o projeto:

```
# Navegando para a pasta raíz do projeto
cd mobile-fema
# instalando as dependências
npm install
# rodando o comando que sobe o server de desenvolvimento
npm run start
```
Esse repositório foi criado usando a ferramenta de linha de comando expo-cli. Rodando os seguintes comandos:

```
# criando o projeto com o expo (template blank)
expo init react-native-exemplo-navegacao
# Instalando as dependências do react-navitaion para react native
npm install @react-navigation/native
npm install @react-navigation/stack
npm install @react-navigation/drawer
npm install @react-navigation/bottom-tabs
# dependências para o expo (https://reactnavigation.org/docs/5.x/getting-started)
expo install react-native-gesture-handler react-native-reanimated react-native-screens react-native-safe-area-context @react-native-community/masked-view
# SQlite e relacionados
expo install expo-sqlite
```

# Referências
- React Navigation Getting Started DOC: https://reactnavigation.org/docs/getting-started
- Instalação da ferramenta ExpoCli: https://docs.expo.dev/get-started/installation/
- Utilização do jsconfig.json e diretiva de compilação checkJs: https://code.visualstudio.com/docs/languages/jsconfig
- Configurando o SQLite no expo: https://docs.expo.dev/versions/v44.0.0/sdk/sqlite/
- Using SQLite in React Native & Expo: https://reactdevstation.github.io/2020/04/04/sqllite.html
  
