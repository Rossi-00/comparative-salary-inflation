# Comparative Salary and Inflation

Este projeto tem como objetivo comparar o crescimento do salário mínimo brasileiro com o índice de inflação (IPCA) de 2010 a 2020. Através de uma interface simples no terminal, o usuário pode:

- Listar os salários mínimos de 2010 a 2020.
- Listar os índices de inflação (IPCA) de 2010 a 2020.
- Comparar o crescimento percentual do salário mínimo com o índice de inflação ano a ano.

## Funcionalidade

O projeto oferece três opções principais para o usuário:

1. **Listar os salários mínimos de 2010 a 2020.**
2. **Listar os índices de inflação (IPCA) de 2010 a 2020.**
3. **Comparar o crescimento salarial com o IPCA para cada ano.**

Ao escolher a opção de comparação, o programa calcula a variação percentual do salário mínimo a cada ano e a compara com o IPCA correspondente.

## Como Funciona

A aplicação apresenta os seguintes dados:

- **Salário Mínimo**: Histórico de valores anuais de 2010 a 2020.
- **IPCA (Inflação)**: Índice de preços ao consumidor (IPCA) de 2010 a 2020.
- **Crescimento Salarial**: Calcula o aumento percentual do salário mínimo de um ano para o outro.

## Como Usar

### 1. Clone este repositório:

Primeiro, faça o clone do repositório em seu computador local:

```bash
git clone https://github.com/rossi-00/comparative-salary-inflation.git
cd comparative-salary-inflation
```

### 2. Instale as dependências:

Este projeto depende do pacote `readline-sync` para coletar as respostas do usuário. Você pode instalar as dependências com o seguinte comando:

```bash
npm install readline-sync
```

### 3. Execute o Projeto:

Após instalar as dependências, basta rodar o seguinte comando para iniciar o programa:

```bash
npm run dev
```

A aplicação será executada e exibirá o menu para o usuário escolher a opção desejada.

### 4. Interaja com a Aplicação:

O usuário pode escolher entre as seguintes opções no menu:

```
Escolha uma das alternativas:

1 - Listar os salários minímos de 2010 à 2020
2 - Listar o índice IPCA de 2010 à 2020
3 - Comparação entre o percentual de aumento salarial e o IPCA
```

Dependendo da escolha, os dados serão exibidos conforme solicitado.

### Exemplo de Execução:

```
Escolha uma das alternativas:
1 - Listar os salários minímos de 2010 à 2020
2 - Listar o índice IPCA de 2010 à 2020
3 - Comparação entre o percentual de aumento salarial e o IPCA

Digite o numero da sua escolha: 3

Ano: 2010.................... Salário mínimo: R$ 510,00
Crescimento Salarial: -........ Inflação IPCA: 5,91%

Ano: 2011.................... Salário mínimo: R$ 545,00
Crescimento Salarial: 6,86%... Inflação IPCA: 6,50%

...

Fim da execução.
```
