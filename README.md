# 💰 VIREXA

### Sistema Inteligente de Gestão Financeira Pessoal

> **Seu dinheiro. Sua visão. Suas decisões.**

O **VIREXA** é um sistema web de gestão financeira pessoal desenvolvido para auxiliar usuários a **organizar, controlar e compreender melhor sua vida financeira**.

Mais do que registrar receitas e despesas, o VIREXA transforma os dados financeiros do usuário em **informações úteis para tomada de decisões**, apresentando indicadores, gráficos, alertas, metas e projeções.

O projeto foi desenvolvido como parte do curso de **Análise e Desenvolvimento de Sistemas — FATEC Araraquara**.

---

# 📌 Índice

- [Sobre o projeto](#-sobre-o-projeto)
- [Problema](#-problema)
- [Objetivo](#-objetivo)
- [Objetivos específicos](#-objetivos-específicos)
- [Público-alvo](#-público-alvo)
- [Proposta de valor](#-proposta-de-valor)
- [Funcionalidades](#-funcionalidades)
- [Diferencial](#-diferencial)
- [Tecnologias](#-tecnologias)
- [Arquitetura](#-arquitetura)
- [Banco de dados](#-banco-de-dados)
- [Regras de negócio](#-regras-de-negócio)
- [Segurança](#-segurança)
- [Testes](#-testes)
- [Estrutura do projeto](#-estrutura-do-projeto)
- [Instalação](#-instalação)
- [Execução](#-execução)
- [Versionamento](#-versionamento)
- [Roadmap](#-roadmap)
- [Objetivo acadêmico](#-objetivo-acadêmico)
- [Autor](#-autor)

---

# 📖 Sobre o projeto

O **VIREXA** foi desenvolvido para solucionar um problema comum: a dificuldade que muitas pessoas encontram para **organizar suas finanças e entender seus próprios hábitos financeiros**.

Planilhas e aplicativos tradicionais normalmente permitem apenas registrar entradas e saídas.

O VIREXA propõe uma abordagem diferente:

> **Registrar → Organizar → Analisar → Alertar → Planejar**

Dessa forma, o sistema não se limita ao armazenamento de informações.

Ele utiliza os dados registrados para apresentar uma visão mais clara da situação financeira do usuário.

---

# ❗ Problema

A falta de organização financeira pode provocar:

- Gastos excessivos;
- Falta de planejamento;
- Endividamento;
- Dificuldade para economizar;
- Falta de controle sobre cartões;
- Perda de controle sobre compras parceladas;
- Dificuldade para identificar gastos desnecessários;
- Falta de planejamento para objetivos futuros.

Além disso, simplesmente saber **quanto foi gasto** não significa necessariamente saber **por que o dinheiro está sendo gasto**.

O VIREXA busca solucionar esse problema através da organização e análise das informações financeiras.

---

# 🎯 Objetivo

Desenvolver uma plataforma web capaz de auxiliar o usuário no **controle, organização e planejamento de suas finanças pessoais**, permitindo registrar movimentações financeiras e transformá-las em informações úteis através de dashboards, gráficos, alertas e projeções.

---

# 🎯 Objetivos específicos

O sistema deverá permitir:

- Criar uma conta de usuário;
- Realizar autenticação;
- Registrar receitas;
- Registrar despesas;
- Criar categorias;
- Gerenciar contas;
- Gerenciar cartões de crédito;
- Controlar compras parceladas;
- Controlar despesas recorrentes;
- Criar metas financeiras;
- Acompanhar o progresso das metas;
- Visualizar saldo;
- Consultar histórico financeiro;
- Visualizar gráficos;
- Comparar períodos;
- Identificar alterações nos padrões de gastos;
- Emitir alertas;
- Realizar projeções;
- Gerar relatórios.

---

# 👥 Público-alvo

O VIREXA será destinado principalmente a:

- Estudantes;
- Trabalhadores;
- Autônomos;
- Famílias;
- Pessoas que desejam organizar suas finanças;
- Pessoas que possuem dificuldade em controlar seus gastos.

---

# 💡 Proposta de valor

O VIREXA busca transformar a maneira como o usuário observa sua vida financeira.

Em vez de simplesmente apresentar:

> **"Você gastou R$ 2.500."**

O sistema busca apresentar:

> **"Você gastou R$ 2.500, sendo que seus gastos com alimentação aumentaram 28% em relação ao mês anterior."**

A proposta é transformar **números em informação**.

---

# ⚙️ Funcionalidades

## 👤 Gestão de usuários

- Cadastro;
- Login;
- Logout;
- Alteração de dados;
- Alteração de senha;
- Recuperação de senha;
- Perfil do usuário.

---

# 💰 Receitas

O usuário poderá cadastrar diferentes fontes de receita.

### Exemplos:

- Salário;
- Freelance;
- Comissão;
- Benefícios;
- Rendimentos;
- Outras receitas.

Cada receita poderá possuir:

```text
Descrição
Valor
Data
Categoria
Conta
Recorrência
Observação
```

---

# 💸 Despesas

O usuário poderá registrar seus gastos.

### Exemplos:

- Alimentação;
- Transporte;
- Moradia;
- Saúde;
- Educação;
- Lazer;
- Compras;
- Assinaturas.

Cada despesa poderá possuir:

```text
Descrição
Valor
Data
Categoria
Forma de pagamento
Conta ou cartão
Parcelamento
Recorrência
Observação
```

---

# 🏦 Contas

O usuário poderá cadastrar suas contas financeiras.

Exemplos:

- Conta corrente;
- Conta poupança;
- Carteira;
- Conta digital.

O sistema poderá apresentar:

- Saldo;
- Entradas;
- Saídas;
- Histórico de movimentações.

---

# 💳 Cartões de crédito

O usuário poderá cadastrar seus cartões.

### Informações:

- Nome;
- Banco;
- Limite;
- Dia de fechamento;
- Dia de vencimento.

### Informações apresentadas:

- Limite total;
- Limite utilizado;
- Limite disponível;
- Fatura atual;
- Faturas futuras;
- Compras parceladas.

---

# 🔄 Parcelamentos

O sistema permitirá registrar compras parceladas.

Exemplo:

```text
Notebook
Valor: R$ 3.000
Parcelas: 10x
Valor da parcela: R$ 300
```

O sistema deverá controlar automaticamente:

- Quantidade total de parcelas;
- Parcelas pagas;
- Parcelas restantes;
- Valor restante;
- Próximo vencimento.

---

# 📅 Despesas recorrentes

Será possível cadastrar despesas que se repetem automaticamente.

### Exemplos:

- Aluguel;
- Internet;
- Streaming;
- Academia;
- Telefone;
- Assinaturas.

---

# 🎯 Metas financeiras

O usuário poderá criar objetivos financeiros.

### Exemplo:

```text
META
Comprar computador

Objetivo: R$ 3.000
Acumulado: R$ 1.500
Progresso: 50%
```

O sistema exibirá visualmente o progresso da meta.

---

# 📊 Dashboard

O dashboard será a principal área do VIREXA.

Ele apresentará:

- Saldo atual;
- Receitas;
- Despesas;
- Economia;
- Gastos por categoria;
- Evolução financeira;
- Metas;
- Cartões;
- Alertas.

### Exemplo:

```text
┌───────────────────────────────────────┐
│                VIREXA                 │
├───────────────────────────────────────┤
│ Saldo              R$ 1.250,00        │
│ Receitas           R$ 3.500,00        │
│ Despesas           R$ 2.250,00        │
│ Economia           R$ 1.250,00        │
├───────────────────────────────────────┤
│ MAIORES GASTOS                       │
│ Moradia             R$ 900            │
│ Alimentação         R$ 550            │
│ Transporte          R$ 400            │
│ Lazer               R$ 200            │
├───────────────────────────────────────┤
│ META: COMPUTADOR                     │
│ ███████████████░░░░░ 50%             │
├───────────────────────────────────────┤
│ ⚠️ ALERTA                             │
│ Alimentação aumentou 25%              │
│ em relação ao mês anterior.           │
└───────────────────────────────────────┘
```

---

# 📈 Gráficos e indicadores

O VIREXA utilizará gráficos para facilitar a interpretação dos dados.

### Indicadores:

- Receita mensal;
- Despesa mensal;
- Saldo;
- Taxa de economia;
- Média de gastos;
- Maior categoria de despesa.

### Gráficos:

- Gastos por categoria;
- Evolução mensal;
- Receitas x despesas;
- Evolução do saldo;
- Progresso das metas.

---

# 🧠 Inteligência financeira

O principal diferencial do VIREXA será sua capacidade de **analisar os dados financeiros registrados pelo usuário**.

O sistema poderá identificar padrões e apresentar informações relevantes.

### Exemplo:

> ⚠️ **Atenção**
>
> Seus gastos com alimentação aumentaram **25%** em comparação ao mês anterior.

---

### Outro exemplo:

> 📈 **Tendência**
>
> Seus gastos aumentaram nos últimos três meses consecutivos.

---

### Exemplo de recomendação:

> 💡 **Análise**
>
> Alimentação representa 24% das suas despesas mensais.
>
> Uma redução de 10% nessa categoria poderia gerar uma economia aproximada de R$ 70 no próximo mês.

---

# 🔮 Projeções financeiras

O VIREXA poderá utilizar o histórico financeiro do usuário para realizar estimativas.

### Exemplo:

```text
Média de receitas:
R$ 3.500

Média de despesas:
R$ 2.700

Economia média:
R$ 800

Projeção:
Saldo estimado → R$ 800
```

As projeções serão apresentadas como **estimativas baseadas nos dados disponíveis**, não como garantia de resultados futuros.

---

# 🚨 Sistema de alertas

O sistema poderá identificar situações que merecem atenção.

### Exemplos:

- Cartão próximo do limite;
- Aumento significativo de uma categoria;
- Saldo insuficiente;
- Meta atrasada;
- Despesa recorrente próxima do vencimento;
- Gastos acima da média;
- Aumento consecutivo de despesas.

---

# 🧾 Relatórios

O usuário poderá consultar relatórios financeiros.

### Relatórios previstos:

- Receitas;
- Despesas;
- Saldo;
- Gastos por categoria;
- Gastos por período;
- Compras parceladas;
- Cartões;
- Evolução financeira;
- Metas.

Uma futura versão poderá permitir exportação em **PDF e Excel**.

---

# 🛠️ Tecnologias

## Frontend

### HTML5

Responsável pela estrutura das páginas e componentes.

### CSS3

Responsável pelo:

- Layout;
- Design;
- Responsividade;
- Tipografia;
- Componentes visuais.

### JavaScript

Responsável por:

- Interatividade;
- Validação;
- Manipulação do DOM;
- Comunicação com a API;
- Atualização dos dados;
- Gráficos.

### Chart.js

Biblioteca utilizada para criação de:

- Gráficos financeiros;
- Comparações;
- Indicadores;
- Evolução de receitas e despesas.

---

# 🐍 Backend

## Python

Principal linguagem utilizada no backend.

Responsável por:

- Regras de negócio;
- Processamento de dados;
- Cálculos;
- Autenticação;
- Comunicação com banco de dados;
- Análises financeiras.

---

## Flask

Framework web utilizado para construção da API.

Responsável por:

- Rotas;
- Endpoints;
- API REST;
- Comunicação com frontend;
- Autenticação;
- Integração com banco de dados.

---

# 🗄️ Banco de dados

## MySQL

O MySQL será utilizado para armazenamento persistente das informações.

O banco deverá armazenar dados relacionados a:

- Usuários;
- Contas;
- Categorias;
- Receitas;
- Despesas;
- Cartões;
- Parcelamentos;
- Metas;
- Alertas.

---

# 🏗️ Arquitetura

O VIREXA utilizará uma arquitetura dividida em camadas.

```text
                    VIREXA
                       │
                       ▼
              ┌─────────────────┐
              │    FRONTEND     │
              │ HTML CSS JS     │
              └────────┬────────┘
                       │
                  HTTP / JSON
                       │
                       ▼
              ┌─────────────────┐
              │     BACKEND     │
              │ Python + Flask  │
              └────────┬────────┘
                       │
                      SQL
                       │
                       ▼
              ┌─────────────────┐
              │    DATABASE     │
              │      MySQL      │
              └─────────────────┘
```

---

# 🗂️ Banco de dados

## Principais entidades

```text
USUÁRIO
   │
   ├── CONTAS
   │
   ├── CARTÕES
   │
   ├── RECEITAS
   │
   ├── DESPESAS
   │
   ├── CATEGORIAS
   │
   ├── PARCELAMENTOS
   │
   ├── METAS
   │
   └── ALERTAS
```

---

# 🧩 Principais tabelas

## usuarios

```text
id
nome
email
senha_hash
data_cadastro
```

## contas

```text
id
usuario_id
nome
tipo
saldo
data_criacao
```

## categorias

```text
id
usuario_id
nome
tipo
```

## receitas

```text
id
usuario_id
conta_id
categoria_id
descricao
valor
data
recorrente
```

## despesas

```text
id
usuario_id
conta_id
categoria_id
descricao
valor
data
forma_pagamento
recorrente
```

## cartoes

```text
id
usuario_id
nome
banco
limite
dia_fechamento
dia_vencimento
```

## parcelamentos

```text
id
usuario_id
cartao_id
descricao
valor_total
quantidade_parcelas
valor_parcela
parcelas_pagas
```

## metas

```text
id
usuario_id
nome
valor_objetivo
valor_atual
data_limite
status
```

## alertas

```text
id
usuario_id
tipo
titulo
mensagem
data_criacao
lido
```

---

# 📐 Regras de negócio

O sistema deverá seguir regras para garantir a consistência das informações.

### Regra 01 — Saldo

```text
Saldo = Receitas - Despesas
```

---

### Regra 02 — Meta

```text
Progresso (%) =
(valor atual / valor objetivo) × 100
```

---

### Regra 03 — Limite do cartão

O sistema deverá impedir que o limite disponível seja apresentado como negativo em situações normais de utilização.

---

### Regra 04 — Parcelamento

Cada compra parcelada deverá gerar suas respectivas parcelas e controlar:

- Vencimento;
- Status;
- Valor;
- Parcela atual.

---

### Regra 05 — Alertas

O sistema poderá gerar um alerta quando o gasto de determinada categoria ultrapassar um percentual definido em relação à média histórica.

---

# 🔐 Segurança

O VIREXA deverá utilizar boas práticas de segurança.

Entre elas:

- Senhas armazenadas utilizando hash;
- Validação de dados;
- Autenticação;
- Controle de acesso;
- Proteção de rotas;
- Variáveis de ambiente;
- Proteção contra SQL Injection;
- Não armazenamento de senhas em texto puro.

Informações sensíveis não deverão ser armazenadas diretamente no código-fonte.

---

# 🧪 Testes

O backend utilizará **Pytest** para testes automatizados.

Serão realizados testes para:

- Cadastro;
- Login;
- Receitas;
- Despesas;
- Cálculo de saldo;
- Metas;
- Parcelamentos;
- Alertas;
- Regras de negócio.

### Exemplo

```text
Receitas = R$ 3.000
Despesas = R$ 2.000

Resultado esperado:
Saldo = R$ 1.000
```

---

# 📁 Estrutura do projeto

```text
virexa/
│
├── backend/
│   ├── app.py
│   ├── config.py
│   │
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── services/
│   └── utils/
│
├── frontend/
│   ├── index.html
│   ├── login.html
│   ├── cadastro.html
│   ├── dashboard.html
│   ├── receitas.html
│   ├── despesas.html
│   ├── cartoes.html
│   └── metas.html
│
├── css/
│   └── style.css
│
├── js/
│   ├── app.js
│   ├── dashboard.js
│   ├── receitas.js
│   ├── despesas.js
│   ├── cartoes.js
│   └── metas.js
│
├── database/
│   ├── schema.sql
│   └── seed.sql
│
├── tests/
│
├── docs/
│
├── .gitignore
├── requirements.txt
└── README.md
```

---

# 📦 Instalação

## 1. Clonar o projeto

```bash
git clone https://github.com/seu-usuario/virexa.git
```

## 2. Entrar na pasta

```bash
cd virexa
```

## 3. Criar ambiente virtual

```bash
python -m venv venv
```

## 4. Ativar o ambiente virtual

### Windows

```bash
venv\Scripts\activate
```

### Linux/macOS

```bash
source venv/bin/activate
```

## 5. Instalar dependências

```bash
pip install -r requirements.txt
```

---

# 🗄️ Configuração do banco

Criar o banco MySQL:

```sql
CREATE DATABASE virexa;
```

Depois executar o arquivo:

```text
database/schema.sql
```

As informações de conexão deverão ser configuradas através de variáveis de ambiente.

Exemplo:

```text
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=sua_senha
DB_NAME=virexa
```

---

# ▶️ Execução

Com o ambiente virtual ativado:

```bash
python backend/app.py
```

Depois acessar:

```text
http://localhost:5000
```

---

# 🔀 Controle de versões

O projeto utilizará **Git e GitHub**.

### Padrão de commits

```text
feat: adiciona cadastro de despesas
feat: implementa dashboard
feat: adiciona controle de cartões
feat: implementa metas financeiras

fix: corrige cálculo do saldo
fix: corrige validação de formulário

docs: atualiza documentação
refactor: reorganiza estrutura do backend
test: adiciona testes para despesas
```

---

# 🗺️ Roadmap

## 🟢 Fase 1 — Planejamento

- [x] Nome do projeto
- [x] Definição do problema
- [x] Definição dos objetivos
- [x] Definição das tecnologias
- [ ] Requisitos funcionais
- [ ] Requisitos não funcionais
- [ ] Casos de uso
- [ ] DER
- [ ] Modelo lógico do banco

---

## 🟡 Fase 2 — Desenvolvimento básico

- [ ] Banco de dados
- [ ] Cadastro
- [ ] Login
- [ ] Dashboard
- [ ] Receitas
- [ ] Despesas
- [ ] Categorias
- [ ] Contas

---

## 🟠 Fase 3 — Gestão financeira

- [ ] Cartões
- [ ] Parcelamentos
- [ ] Despesas recorrentes
- [ ] Metas
- [ ] Histórico
- [ ] Relatórios

---

## 🔴 Fase 4 — Inteligência

- [ ] Alertas
- [ ] Comparação mensal
- [ ] Identificação de padrões
- [ ] Análise de gastos
- [ ] Projeções
- [ ] Recomendações

---

## 🔵 Fase 5 — Finalização

- [ ] Testes automatizados
- [ ] Correção de bugs
- [ ] Responsividade
- [ ] Melhorias de UX
- [ ] Documentação
- [ ] Deploy
- [ ] Preparação da apresentação

---

# 🚀 Futuras versões

O VIREXA poderá futuramente receber:

- Aplicativo mobile;
- Notificações;
- Importação de extratos;
- Exportação para Excel;
- Exportação para PDF;
- Integração bancária;
- Reconhecimento automático de categorias;
- Inteligência artificial;
- Assistente financeiro;
- Planejamento familiar;
- Controle de investimentos.

---

# 🎓 Objetivo acadêmico

O projeto tem como objetivo aplicar conhecimentos adquiridos no curso de **Análise e Desenvolvimento de Sistemas**, envolvendo:

- Análise de requisitos;
- Engenharia de software;
- Banco de dados;
- Programação;
- Desenvolvimento web;
- APIs;
- Arquitetura de software;
- Segurança;
- Testes;
- Controle de versões;
- Experiência do usuário.

O VIREXA também busca demonstrar como um sistema pode evoluir de uma simples ferramenta de registro para uma solução capaz de **analisar informações e auxiliar na tomada de decisões**.

---

# 👨‍💻 Autor

**Leonardo Jose Tebar**

**Análise e Desenvolvimento de Sistemas — FATEC Araraquara**

---

# 📄 Licença

Projeto desenvolvido para fins acadêmicos.

A definição da licença poderá ser realizada posteriormente conforme a finalidade do projeto.

---

# 💰 VIREXA

### **Seu dinheiro. Sua visão. Suas decisões.**

**Organize. Analise. Planeje. Evolua.**
