# Organo

![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6%2B-F7DF1E?logo=javascript&logoColor=black)
![CSS](https://img.shields.io/badge/CSS-3-1572B6?logo=css&logoColor=white)

Aplicação para organizar colaboradores por times, desenvolvida durante o curso de React da **Alura**. O usuário preenche um formulário e o card do colaborador aparece na seção do time escolhido, com a identidade visual daquele time.


## Funcionalidades

- Cadastro de colaboradores com nome, cargo, imagem e time
- Validação de campos obrigatórios
- Criação dinâmica de cards
- Cores personalizadas para cada time
- Exibição apenas dos times que têm colaboradores
- Limpeza automática do formulário após o cadastro

## Tecnologias

- React 19
- JavaScript (ES6+)
- CSS3
- Create React App

## Vercel
https://projeto-react-ochre.vercel.app/

## Como executar

```bash
git clone https://github.com/ChristianLiborioDEV/projeto-react.git
cd projeto-react
npm install
npm start
```

Acesse [http://localhost:3000](http://localhost:3000) no navegador.


## Aprendizados

- Criação de componentes funcionais e organização por pastas
- Comunicação entre componentes com **props** e **props.children**
- Gerenciamento de estado com o hook **useState**
- **Componentes controlados** em formulários (`value` + `onChange`)
- Envio de dados do filho para o pai por meio de funções de callback
- Atualização de estado de forma imutável com spread operator
- Renderização de listas com `map` e uso de `key`
- Filtragem de dados com `filter`
- Renderização condicional com `&&`
- Estilização com CSS por componente e estilos inline dinâmicos

