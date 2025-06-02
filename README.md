# SpaceX Explorer - Aplicação React

![SpaceX Explorer Screenshot](public/screenshot.png)

## Descrição

SpaceX Explorer é uma aplicação web construída com React que consome a API pública da SpaceX para exibir informações sobre foguetes, lançamentos e cápsulas espaciais. A aplicação oferece uma interface intuitiva e visualmente atraente para explorar os dados do programa espacial da SpaceX.

## Funcionalidades

- Visualização de foguetes da SpaceX (Falcon 1, Falcon 9, Falcon Heavy, Starship)
- Listagem de lançamentos recentes com status de sucesso/falha
- Informações sobre cápsulas espaciais
- Design responsivo que funciona em desktop e mobile
- Animações e efeitos visuais temáticos
- Navegação entre páginas

## Tecnologias Utilizadas

- React.js
- React Router
- Axios (para requisições HTTP)
- CSS Modules
- Font Awesome (ícones)
- SpaceX API (v4)

## Como Executar o Projeto

### Pré-requisitos

- Node.js (v14 ou superior)
- npm (v6 ou superior)

### Instalação

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/spacex-explorer.git
cd spacex-explorer
```

2. Instale as dependências:

```bash
npm install
```

3. Inicie o servidor de desenvolvimento:

```bash
npm start
```

4. Acesse a aplicação no navegador:

```
http://localhost:3000
```

## Estrutura do Projeto

```
spacex-explorer/
├── public/                  # Arquivos públicos
├── src/
│   ├── components/          # Componentes reutilizáveis
│   ├── pages/               # Páginas da aplicação
│   ├── services/            # Serviços (API calls)
│   ├── App.js               # Componente principal
│   ├── App.css              # Estilos globais
│   └── index.js             # Ponto de entrada
├── package.json
└── README.md
```

## API Utilizada

A aplicação consome a API pública da SpaceX (v4):
- Documentação: [https://docs.spacexdata.com/](https://docs.spacexdata.com/)
- Endpoints utilizados:
  - Foguetes: `https://api.spacexdata.com/v4/rockets`
  - Lançamentos: `https://api.spacexdata.com/v4/launches`
  - Cápsulas: `https://api.spacexdata.com/v4/capsules`

## Contribuição

Contribuições são bem-vindas! Siga os passos abaixo:

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## Licença

Distribuído sob a licença MIT. Veja `LICENSE` para mais informações.
