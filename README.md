# GPT-API

Bem-vindo ao GPT-API! Este repositório contém informações detalhadas sobre o projeto, como configurá-lo e usá-lo.

## Descrição

Este projeto é uma demonstração de como criar um aplicativo usando a API do GPT-3 da OpenAI. Ele mostra como usar o GPT-3 para tarefas de processamento de linguagem natural, como geração de texto.

## Pré-requisitos

Antes de começar, certifique-se de ter instalado o seguinte:

- [Node.js](https://nodejs.org/) - Ambiente de tempo de execução JavaScript
- [npm](https://www.npmjs.com/) - Gerenciador de pacotes do Node.js
- Uma chave de API da OpenAI - Você precisa obter uma chave de API da OpenAI e configurá-la como uma variável de ambiente.

## Configuração

Siga estas etapas para configurar o projeto:

1. Clone este repositório:

   ```bash
   git clone https://github.com/geraldoaax/gpt-api.git
   cd gpt-api
   ```

2. Instalação das Dependências

   ```bash
   npm install
   ```

3. Colocar a API Key no .env_sample
   OPENAI_API_KEY=SUA_CHAVE_DE_API_AQUI

4. Renomear o .env_sample para .env

5. Executar o Projeto

```bash
npm run start
```

## Uso

Após configurar o projeto e iniciá-lo, você pode acessar o aplicativo em http://localhost:3000.

O aplicativo permite que você insira um texto de entrada e use a API do GPT-3 para gerar uma resposta com base no texto fornecido. Você pode personalizar as configurações da chamada da API no código-fonte.

Regras de Crédito da API OpenAI:

Certifique-se de seguir as regras de crédito da API da OpenAI. Esta API pode incorrer em custos significativos, dependendo do uso. Consulte a documentação da OpenAI para entender as políticas de uso e os custos associados.

## Contribuição

Contribuições são bem-vindas! Se você deseja contribuir para este projeto, siga estas etapas:

Fork este repositório.

Crie uma branch para a sua feature:

```bash
Copy code
git checkout -b minha-feature
```

Faça as alterações desejadas e faça commit delas:

```bash
git commit -m 'Adiciona minha-feature'
Envie as alterações para o seu fork:
```

```bash
git push origin minha-feature
Abra um Pull Request para este repositório.
```

## Agradecimentos

Agradecimento especial à OpenAI por fornecer a API do GPT-3.

## Referências

Como configurar e exemplos no: https://platform.openai.com/docs/overview
