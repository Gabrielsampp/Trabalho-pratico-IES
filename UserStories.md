### [Voltar](./README.md)

# 🪪 User Stories

Agrupadas conforme o tipo de usuário a que estão direcionadas. Além de que todas as suas características estão definidas conforme as reuniões realizadas pela equipe.

<br>

## 🎓 Aluno da UFCA:

### 1. [US01] Cadastro de aluno:
```
Como aluno da UFCA, quero cadastrar-me no sistema para criar um perfil e acessar os recursos da plataforma.
```

 - **Estimativa:** 5
 - **Prioridade:** 🟡 Média
 - **Critérios de aceitação:**
    - _Tratamento/validação das informações digitadas pelo usuário._
    - _Exibir número de etapas necessárias para cadastrar-se e criar o perfil, bem como o número da etapa atual._
    - _A transição entre as etapas deve ser fluida e esteticamente agradável, mediante transições suaves e animações._
    - _Adaptabilidade aos tamanhos de tela mobile, desktop e tablets._
    - _Exibir pequenos cards com perfis de alunos aleatórios do sistema._
    - _Somente e-mails institucionais podem ser cadastrados._
    - _Redirecionar para tela de login caso o aluno já esteja cadastrado no sistema._
    - _Exibir o estado da operação (sucesso ou falha) mediante notificações flutuantes, utilizando a biblioteca react Toastify-js._


### 2. [US02] Autenticação de aluno:
```
Como aluno da UFCA cadastrado no sistema, quero autenticar-me no sistema utilizando e-mail e senha para acessar e gerenciar meus dados na plataforma.
```
 - **Estimativa:** 5
 - **Prioridade:** 🟡 Média
 - **Critérios de aceitação:**
    - _Adaptabilidade aos tamanhos de tela para dispositivos mobile, desktop e tablet._
    - _Exibir pequenos cards de perfis de alunos aleatórios do sistema._
    - _O estado da operação deve ser informado ao usuário mediante notificações flutuantes, utilizando biblioteca react Toastify-js._
    - _Caso o aluno não esteja cadastrado no sistema, exibir um modal com as seguintes opções: “Redirecionar para tela de cadastro” ou “Verificar e-mail informado”_

### 3. [US03] Atualizar perfil de aluno:
```
Como aluno da UFCA cadastrado no sistema, quero atualizar meu perfil profissional para exibi-lo na plataforma de maneira condizente com meus dados e status atual.
```
 - **Estimativa:** 5
 - **Prioridade:** 🟡 Média
 - **Critérios de aceitação:**
    - _Não permitir que o usuário remova dados obrigatórios._
    - _Adaptabilidade aos tamanhos de tela para dispositivos mobile, desktop e tablet._
    - _As alterações são salvas apenas quando o usuário clicar no botão “salvar”_
    - _Caso o usuário saia da tela sem salvar as alterações, exibir um modal informando que as informações serão perdidas e com as opções: “sair” ou “continuar editando”._

### 4. [US04] Dashboard aluno:
```
Como aluno da UFCA cadastrado no sistema, quero acessar uma página de dashboard que apresente dados a respeito do meu perfil, bem como às operações de gerenciamento do perfil.
``` 
 - **Estimativa:** 8
 - **Prioridade:** 🔴 Alta
 - **Critérios de aceitação:**
    - _Adaptabilidade aos tamanhos de tela para dispositivos mobile, desktop e tablet._
    - _Apresentar um gráfico com o número de visualizações na semana._
    - _Apresentar a quantidade total de visualizações do perfil_
    - _Apresentar listas das vagas salvas pelo usuário_
    - _Apresentar lista dos perfis de empresas salvas pelo usuário_
    - _Apresentar lista de perfis de alunos salvos pelo usuário_
    - _Apresentar botões para editar informações do perfil, bem como navegar pelas telas reservadas (busca de vagas, edição de perfil)._


### 5. [US05] Salvar perfis de alunos
```
Como aluno da UFCA cadastrado no sistema, quero salvar perfis de outros alunos, para colaborar com a visualização do perfil de ambos.
```
 - **Estimativa:** 
 - **Prioridade:** 
 - **Critérios de aceitação:**
    - _Ao salvar um perfil, a ação deve ser imediatamente registrada no banco de dados._
    - _O status da ação (sucesso ou falha) deve ser informado por notificações flutuantes, mediante uso da biblioteca react toastify-js._
    - _Perfis salvos devem ser exibidos na lista de perfis salvos presentes na página de dashboard._
    

### 6. [US06] Salvar perfis de contratantes
```
Como aluno da UFCA cadastrado no sistema, quero salvar perfis de contratantes, para receber notificações quando essas empresas disponibilizarem vagas ou atualizarem seus perfis.
```
 - **Estimativa:** 
 - **Prioridade:** 🟢 Baixa
 - **Critérios de aceitação:**
    - _Ao salvar um perfil, a ação deve ser imediatamente registrada no banco de dados._
    - _O status da ação (sucesso ou falha) deve ser informado por notificações flutuantes, mediante uso da biblioteca react toastify-js._
    - _Perfis salvos devem ser exibidos na lista de empresas salvos presentes na página de dashboard._
    

### 7. [US07] Salvar perfis de vagas
```
Como aluno da UFCA cadastrado no sistema, quero salvar perfis de vagas, para facilitar o acesso e receber notificações sobre status ou atualizações.
```
 - **Estimativa:**
 - **Prioridade:** 🟢 Baixa
 - **Critérios de aceitação:**
    - _Ao salvar uma vaga, a ação deve ser imediatamente registrada no banco de dados._
    - _O status da ação (sucesso ou falha) deve ser informado por notificações flutuantes, mediante uso da biblioteca react toastify-js._
    - _Vagas salvas devem ser exibidas na lista de vagas salvas presentes na página de dashboard._




---

<br>

## 💼 Contratante: 
Uma empresa ou instituição, pública ou privada

### 1. [US08] Cadastro de contratante
```
Como contratante (uma empresa ou instituição, pública ou privada), quero cadastrar-me no sistema para criar um perfil e acessar os recursos da plataforma.
```
 - **Estimativa:**
 - **Prioridade:** 🟡 Média
 - **Critérios de aceitação:**
    - _Tratamento/validação das informações digitadas pelo usuário._
    - _Exibir número de etapas necessárias para cadastrar-se e criar o perfil, bem como o número da etapa atual._
    - _A transição entre as etapas deve ser fluida e esteticamente agradável, mediante transições suaves e animações._
    - _Adaptabilidade aos tamanhos de tela mobile, desktop e tablets._
    - _Exibir pequenos cards com perfis de contratantes aleatórios do sistema._
    - _A validação do contratante é baseada em CNPJ._
    - _Redirecionar para tela de login caso o contratante já esteja cadastrado no sistema._
    - _Exibir o estado da operação (sucesso ou falha) mediante notificações flutuantes, utilizando a biblioteca react Toastify-js._


### 2. [US09] Autenticação de contratante
```
Como contratante (uma empresa ou instituição, pública ou privada) cadastrado no sistema, quero autenticar-me utilizando e-mail e senha para acessar e gerenciar meus dados na plataforma.
```
 - **Estimativa:**
 - **Prioridade:** 🟡 Média
 - **Critérios de aceitação:**
    - _Adaptabilidade aos tamanhos de tela para dispositivos mobile, desktop e tablet._
    - _Exibir pequenos cards de perfis de alunos aleatórios do sistema._
    - _O estado da operação deve ser informado ao usuário mediante notificações flutuantes, utilizando biblioteca react Toastify-js._
    - _Caso o contratante não esteja cadastrado no sistema, exibir um modal com as seguintes opções: “Redirecionar para tela de cadastro” ou “Verificar e-mail informado”_

### 3. [US10] Atualizar perfil
```
Como contratante (uma empresa ou instituição, pública ou privada) cadastrado no sistema, quero atualizar meu perfil profissional para exibi-lo na plataforma de maneira condizente com meus dados e status atual.
```
 - **Estimativa:**
 - **Prioridade:** 🟡 Média
 - **Critérios de aceitação:**
    - _Não permitir que o usuário remova dados obrigatórios._
    - _Adaptabilidade aos tamanhos de tela para dispositivos mobile, desktop e tablet._
    - _As alterações são salvas apenas quando o usuário clicar no botão “salvar”_
    - _Caso o usuário saia da tela sem salvar as alterações, exibir um modal informando que as informações serão perdidas e com as opções: “sair” ou “continuar editando”._

--- 

## 🎓 Aluno da UFCA + 💼 Contratante

### 1. [US11] Pesquisa de vagas
```
Como contratante (uma empresa ou instituição, pública ou privada) ou aluno da UFCA cadastrado no sistema, quero acessar uma página de pesquisa de vagas para encontrar vagas com base em filtros específicos.
```
 - **Estimativa:**
 - **Prioridade:** 🔴 Alta
 - **Critérios de aceitação:**
    - _Adaptabilidade aos tamanhos de tela para dispositivos mobile, desktop e tablet._
    - _Apresentar caixas de pesquisa e seleção para definição dos filtros._
    - _Disponibilizar paginação personalizada para exibição de um número controlado de itens._
    

### 2. [US12] Visualizar vaga
```
Como contratante (uma empresa ou instituição, pública ou privada) ou aluno da UFCA cadastrado no sistema, quero acessar uma página de visualização de vaga para consultar informações de uma vaga específica.
```
 - **Estimativa:**
 - **Prioridade:** 🔴 Alta
 - **Critérios de aceitação:**
    - _Adaptabilidade aos tamanhos de tela para dispositivos mobile, desktop e tablet._
    - _Apresentar todos os dados públicos do perfil conforme o banco de dados._
    - _Apresentar um componente que informa o quanto uma vaga está alinhada ao perfil do usuário que está visualizando a página._
    - _Apresentar botão com link do sistema utilizado pela empresa para registrar candidaturas._

---

## 🌐 Usuário (cadastrado ou não)

### 1. [US13] Acessar página Home
```
Como usuário (cadastrado ou não), quero acessar uma página home para encontrar informações sobre a plataforma, links rápidos e ter um primeiro contato com o sistema.
```
 - **Estimativa:**
 - **Prioridade:** 🔴 Alta
 - **Critérios de aceitação:**
    - _Adaptabilidade aos tamanhos de tela para dispositivos mobile, desktop e tablet._
    - _Apresentar componente hero atrativo e que incremente a identidade visual do sistema._
    - _Apresentar barra de navegação fixa na parte superior da tela, com links apenas para as páginas públicas do site._
    - _Apresentar dados quantitativos do sistema, como número de usuários, perfis, vagas abertas._
    - _Apresentar carrosséis para exibição dos últimos perfis e vagas cadastrados (um para alunos, um para contratantes e um para vagas), sendo que apenas os cards de aluno e contratante redirecionam para páginas de visualização específica._
    - _Apresentar componente com comentários da comunidade_
    - _Apresentar botões e componentes com as opções de: cadastro como contratante e cadastro como aluno._


### 2. [US14] Pesquisar perfis
```
Como usuário (cadastrado ou não), quero acessar uma página de pesquisa de perfis para consultar perfis profissionais de alunos com base em filtros específicos.
```
 - **Estimativa:**
 - **Prioridade:** 🔴 Alta
 - **Critérios de aceitação:**
    - _Adaptabilidade aos tamanhos de tela para dispositivos mobile, desktop e tablet._
    - _Apresentar caixas de pesquisa e seleção dinâmica para definição dos filtros._
    - _Disponibilizar paginação personalizada para exibição de um número controlado de itens._
    - _A visualização dos perfis deve ser feita por meio de componentes de card padrão._


### 3. [US15] Pesquisar contratantes
```
Como usuário (cadastrado ou não), quero acessar uma página de pesquisa de contratantes para consultar perfis profissionais de empresas com base em filtros específicos.
```
 - **Estimativa:**
 - **Prioridade:** 🔴 Alta
 - **Critérios de aceitação:**
    - _Adaptabilidade aos tamanhos de tela para dispositivos mobile, desktop e tablet._
    - _Apresentar caixas de pesquisa e seleção para definição dos filtros._
    - _Disponibilizar paginação personalizada para exibição de um número controlado de itens._
    - _A visualização dos perfis deve ser feita por meio de componentes de card padrão._
    

### 4. [US16] Visualizar perfil
```
Como usuário (cadastrado ou não), quero acessar uma página de visualização de perfil para visualizar de modo mais abrangente as informações do perfil profissional de um aluno específico.
```
 - **Estimativa:**
 - **Prioridade:** 🟡 Média/Alta
 - **Critérios de aceitação:**
    - _Adaptabilidade aos tamanhos de tela para dispositivos mobile, desktop e tablet._
    - _Apresentar todos os dados públicos do perfil conforme o banco de dados._


### 5. [US17] Visualizar contratante
```
Como usuário (cadastrado ou não), quero acessar uma página de visualização de contratante para consultar informações específicas sobre uma empresa cadastrada no sistema.
```
 - **Estimativa:**
 - **Prioridade:** 🟡 Média/Alta
 - **Critérios de aceitação:**
    - _Adaptabilidade aos tamanhos de tela para dispositivos mobile, desktop e tablet._
    - _Apresentar todos os dados públicos do perfil conforme o banco de dados._