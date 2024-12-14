# 🏨 Hospedar
**Versão**: 0.1 - Desenvolvimento  
**Data de Início**: 16 de novembro de 2024  
**Data de Atualização**: 30 de novembro de 2024  
**Autor**: Silas Sefas de Souza Aquino  

## 📚 Descrição
Esta é a versão inicial do projeto, em fase de desenvolvimento. Inclui a documentação preliminar com a visão geral, requisitos funcionais e estrutura básica do design.  
Estado: Em desenvolvimento, sujeito a alterações constantes.  
Observação: Por se tratar de um projeto pessoal, não há previsão de lançamento oficial. Atualizações serão realizadas conforme a evolução do projeto.

---

## 1. 📝 Visão Geral

### 1.1 🎯 Objetivo do Projeto
O **Hospedar** é uma plataforma web destinada ao gerenciamento de hotéis, com o objetivo de otimizar e automatizar processos administrativos e operacionais. O sistema permitirá que os administradores do hotel possam:

- 🛏️ Cadastrar e gerenciar acomodações, como quartos e suítes.
- 📅 Gerenciar reservas feitas por hóspedes e colaboradores.
- 👤 Gerenciar hóspedes, incluindo cadastro, histórico de estadias e check-in/check-out.
- 🧳 Gerenciar insumos e estoque de itens utilizados nos quartos e nas áreas comuns.
- 📊 Auxiliar na administração geral, como gestão de pessoal e controle financeiro.

A plataforma permitirá que os administradores controlem a disponibilidade dos quartos, otimizem as operações de recepção e tenham uma visão ampla da administração do hotel por meio de relatórios e indicadores.

### 1.2 👥 Usuários
- Administradores e gestores de hotéis
- Recepcionistas
- Clientes e Hóspedes de hotéis

### 1.3 📏 Escopo

#### 1.3.1 Gestão do Hotel

1. **Cadastro e Gerenciamento de Acomodações**
   - Cadastro de diferentes tipos de acomodações (ex: Quarto Individual, Quarto Duplo, Suíte, etc.).
2. **Gerenciamento de Reservas**
   - Reservas por telefone e check-in sem reservas.
   - Gerenciar, confirmar, modificar e cancelar reservas.
3. **Gestão de Hóspedes**
   - Cadastro de hóspedes com informações detalhadas.
4. **Gestão de Insumos e Estoque**
   - Cadastro de itens de refeição e controle de estoque.
   - Controle de itens de limpeza e manutenção.
5. **Relatórios**
   - Relatórios de consumo, alertas de estoque baixo e ocupação.

#### 1.3.2 Gestão de Pessoal

1. **Cadastro de Funcionários**
   - Cadastro completo de funcionários com informações detalhadas como CPF, dados bancários, cargo, e histórico de desempenho.

---

## 2. 🧑‍💻 Requisitos

### 2.1 📋 Requisitos Funcionais

- **RF01**: O sistema deve permitir o cadastro e edição de quartos.
- **RF02**: O sistema deve permitir a reserva de quartos.
- **RF03**: O administrador deve poder alterar, cancelar ou confirmar reservas feitas.
- **RF04**: O sistema deve registrar e atualizar automaticamente as datas de check-in e check-out.

### 2.2 ⚙️ Requisitos Não Funcionais

- **RNF01**: A interface do sistema deve ser responsiva.
- **RNF02**: O tempo de resposta do sistema deve ser inferior a 2 segundos para ações principais.
- **RNF03**: O sistema deve suportar até 500 reservas simultâneas e 200 quartos cadastrados.

### 2.3 🧳 Casos de Uso/User Stories

- **CU01**: Como administrador, quero cadastrar novos quartos no sistema.
- **CU02**: Como administrador, quero gerenciar as reservas realizadas.

---

## 3. 🏗️ Design

### 3.1 🖥️ Arquitetura do Sistema
A arquitetura será dividida em três camadas principais:

1. **Frontend (Angular)**: Em desenvolvimento.
2. **Backend (Spring Boot)**: Usará Spring MVC, Spring Security com JWT para autenticação, e Spring Data JPA para persistência de dados.
3. **Banco de Dados SQL Server**: Usado para armazenamento de dados relacionais.

### 3.2 💾 Estrutura de Dados
- O sistema usará um banco de dados relacional com tabelas como `Usuários`, `Quartos`, `Reservas`, e `Hóspedes`.

### 3.3 🔄 Fluxo de Processos
1. Cadastro de Quartos
2. Reserva de Quartos
3. Processamento de Check-in/Check-out
4. Gestão de Estoque

---

## 4. 🧑‍🔧 Documentação Técnica

### 4.1 ⚙️ Configuração do Ambiente
- **Java 17** e **Spring Boot**.
- Banco de Dados **SQL Server** configurado no `application.properties`.

### 4.2 🚀 Instruções de Deploy
Instruções detalhadas para configuração do ambiente e deploy do sistema estarão disponíveis em breve.

---

## 5. 🧪 Testes

### 5.1 📝 Plano de Testes
- **Testes Unitários**: Verificação de funcionalidades isoladas.
- **Testes de Integração**: Validação da comunicação com o banco de dados.
- **Testes de Carga**: Garantir que o sistema lida bem com múltiplas reservas simultâneas.

### 5.2 🧳 Casos de Teste

- **CT01**: Verificar o processo de reserva de um quarto.
- **CT02**: Testar o processo de check-in e check-out.
- **CT03**: Validar a geração de relatórios financeiros.

---

## 6. 📖 Manual do Usuário

### 6.1 📋 Instruções para Usuários Finais
As instruções serão detalhadas no manual do usuário que está em desenvolvimento.

### 6.2 ❓ FAQ
Em breve, será adicionado um FAQ para resolver as dúvidas mais comuns.

### 6.3 🔧 Guia de Solução de Problemas
Guia com soluções para problemas comuns será disponibilizado após as versões iniciais.

---

## 7. 🔄 Manutenção

### 7.1 📑 Registro de Alterações
As alterações serão documentadas no repositório GitHub do projeto.

### 7.2 🔄 Planos de Atualização
O desenvolvimento ocorrerá de forma contínua, com atualizações semanais.

---

## 🚀 Funcionalidades Futuras

Em aberto, com possibilidade de integração com aplicativos móveis e outros módulos.

---

## ⚠️ Limitações

1. A versão inicial será apenas web, sem suporte a aplicativos móveis.
2. A interface ainda está em desenvolvimento.
3. A gestão de reservas será restrita a administradores e recepcionistas.

---

## 🎉 Conclusão

Este projeto visa transformar a gestão hoteleira em uma tarefa mais prática e eficiente, centralizando informações e automatizando processos essenciais para o sucesso do negócio.

---

## 📊 Status do Projeto

- ✅ **Concluído**: Definição do escopo e objetivo do projeto.
- 🛠️ **Em Desenvolvimento**: Planejamento, análise de requisitos, e início do desenvolvimento.
- ⏳ **Não Iniciado**: Testes, documentação final e implantação.

---

## 🔨 Passos do projeto

1. **Definir o Escopo e Objetivo**:
   - Compreenda a necessidade do usuário ou do cliente. ✅
   - Defina os requisitos principais e as funcionalidades essenciais. ✅

2. **Planejamento**:
   - Estabeleça prazos e recursos.✅
   - Escolha a arquitetura do sistema e as tecnologias a serem utilizadas. ✅

3. **Análise de Requisitos**:
   - Levante os requisitos funcionais e não funcionais.✅
   - Documente todas as funcionalidades iniciais do software.✅

4. **Desenho da Arquitetura**:
   - Modele a arquitetura do sistema (front-end, back-end, banco de dados, etc.).✅
   - Planeje a interação entre componentes e serviços.✅

5. **Protótipos e Mockups**:
   - Crie protótipos ou wireframes para validar a interface do usuário (UI).
   - Obtenha feedback inicial sobre a usabilidade.

6. **Desenvolvimento**:
   - Inicie a codificação do sistema, dividindo o trabalho em sprints ou etapas menores.
   - Utilize controle de versão (ex.: Git) para o desenvolvimento colaborativo.

7. **Testes**:
   - Realize testes unitários, integração e de aceitação.
   - Corrija bugs e melhore a performance conforme necessário.

8. **Documentação**:
   - Documente o código-fonte e o funcionamento do sistema.
   - Crie manuais de uso e documentação técnica para manutenção futura.

9. **Implantação**:
   - Prepare o ambiente de produção.
   - Faça o deploy do software no servidor ou infraestrutura escolhida.

10. **Manutenção e Suporte**:
    - Monitore o sistema em produção.
    - Ofereça suporte para resolver problemas e implemente melhorias.
