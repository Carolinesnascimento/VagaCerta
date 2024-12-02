# Aplicativo VagaCerta

Este projeto é um aplicativo móvel desenvolvido com **React Native** e **Expo**, permitindo o gerenciamento de vagas e usuários.

---

## Como Baixar o Código do Aplicativo VagaCerta

1. Instale o Git no seu computador.  
2. Execute o seguinte comando no terminal:  

```bash
git clone https://github.com/Carolinesnascimento/VagaCerta.git
```  

---

## Como Executar o Aplicativo VagaCerta  

1. Acesse o diretório do projeto:  

```bash
cd VagaCerta
```  

2. Instale as dependências do projeto:  

```bash
npm install
```  

3. Inicie o aplicativo utilizando o Expo:  

```bash
npx expo start
```  

### Observações:  

- No arquivo **`api.ts`**, é necessário configurar o IP do servidor onde a API está alocada.  
- Certifique-se de que o aplicativo **Expo Go** esteja na versão **51** para executar o aplicativo corretamente.  

---

## Tecnologias Utilizadas  

- **React Native**: Framework para desenvolvimento de aplicativos móveis.  
- **Expo**: Plataforma para desenvolvimento de aplicativos React Native.  
- **Styled Components**: Biblioteca para estilização de componentes em React.  
- **Axios**: Biblioteca para fazer requisições HTTP.  
- **TypeScript**: Superset do JavaScript que adiciona tipagem estática.  

---

## Estrutura do Projeto  

- **App.tsx**: Arquivo principal da aplicação que configura o provedor de contexto, tema, navegação e status bar.  
- **src/theme/index.ts**: Configuração do tema da aplicação, incluindo cores e tamanhos de fonte.  
- **src/context/UserContext.tsx**: Provedor de contexto para gerenciar o estado do usuário autenticado.  
- **src/services/api.ts**: Configuração do Axios para fazer requisições HTTP à API.  
- **src/screens/Login/index.tsx**: Tela de login do usuário.  
- **src/screens/Form/index.tsx**: Tela de formulário para cadastro de usuário.  
- **src/screens/List/index.tsx**: Tela que lista as vagas disponíveis.  
- **src/screens/Profile/index.tsx**: Tela de perfil do usuário.  
- **src/screens/Details/index.tsx**: Tela de detalhes de uma vaga específica.  
- **src/screens/Logout/index.tsx**: Tela de logout do usuário.  
- **src/components/Button/index.tsx**: Componente de botão reutilizável.  
- **src/components/Input/index.tsx**: Componente de campo de entrada reutilizável.  
- **src/components/Logo/index.tsx**: Componente de logo da aplicação.  
- **src/components/VagaCard/index.tsx**: Componente de card para exibir informações de uma vaga.  
- **src/@types/png.d.ts**: Declaração de tipos para arquivos PNG.  
- **src/@types/styles.d.ts**: Declaração de tipos para o tema do styled-components.
