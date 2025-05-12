# Documentação do Sistema

## Sumário

1. [Dados do Cliente](#dados-do-cliente)
2. [Equipe de Desenvolvimento](#equipe-de-desenvolvimento)
3. [Introdução](#introdução)
4. [Objetivo](#objetivo)
5. [Escopo](#escopo)
6. [Backlogs do Produto](#backlogs-do-produto)
7. [Cronograma](#cronograma)
8. [Materiais e Métodos](#materiais-e-métodos)
9. [Resultados](#resultados)
10. [Conclusão](#conclusão)
11. [Homologação do MVP junto ao cliente](#homologação-do-mvp-junto-ao-cliente)
12. [Divulgação](#divulgação)
13. [Carta de Apresentação](#carta-de-apresentação)
14. [Carta de Autorização](#carta-de-autorização)
15. [Relato Individual do Processo](#relato-individual-do-processo)

---

## Dados do Cliente

**Título do Projeto:** Seco Game

**Cliente:** EcoVida Reciclagem Ltda.

**CNPJ/CPF:** 12.345.678/0001-90

**Contato:** Mariana Silva

**Email do contato:** mariana.silva@ecovida.com.br

---

## Equipe de Desenvolvimento

| Nome Completo | Curso | Disciplina |
|--------------|------|------------|
| Julia Roberta Veloso Guiraldeli | Ciência da Computação | Software Básico em C |
| Felipe de Carvalho Meira | Ciência da Computação | Software Básico em C |
| Gabriela Yaeko Onaka | Ciência da Computação | Software Básico em C |
| Matheus Aprigio de Jesus | Ciência da Computação | Software Básico em C |

**Professor Orientador:** Kesede Rodrigues Julio

---

## Introdução

A produção excessiva de resíduos e o descarte incorreto causam impactos ambientais significativos, como poluição e desperdício de recursos naturais. A coleta seletiva é uma solução essencial, permitindo a separação e o reaproveitamento de materiais recicláveis, reduzindo o volume de lixo destinado a aterros sanitários. Para isso, é fundamental conhecer a classificação dos resíduos: papel (azul), metal (amarelo), vidro (verde), plástico (vermelho), lixo orgânico (marrom), resíduos perigosos (branco) e rejeitos não recicláveis (cinza). A falta de conscientização faz com que toneladas de materiais recicláveis sejam desperdiçadas diariamente. O **Seco Game** busca educar de forma interativa, incentivando a correta separação do lixo e promovendo a sustentabilidade.

---

## Objetivo

O objetivo do **Seco Game** é conscientizar e educar os jogadores sobre a importância da coleta seletiva, ensinando de forma interativa a correta separação dos resíduos. Através da gamificação, busca-se estimular hábitos sustentáveis, reduzir o desperdício de materiais recicláveis e reforçar a responsabilidade ambiental, contribuindo para um planeta mais limpo e equilibrado.

---

## Escopo

O Seco Game será um jogo educativo focado na conscientização sobre a coleta seletiva de resíduos. O jogo será desenvolvido para plataforma web e/ou mobile, com mecânicas simples e interativas, permitindo que os jogadores aprendam sobre a separação correta do lixo enquanto se divertem.

Funcionalidades principais:

Cadastro de Usuário: O jogador poderá criar um perfil com nome e pontuação acumulada.

Cliente Fictício: O jogo contará com a empresa EcoVida Reciclagem Ltda. como cliente parceiro, reforçando a importância do descarte correto dos resíduos.

Classificação dos Resíduos: O jogador terá que separar corretamente os resíduos de acordo com as cores e categorias da coleta seletiva.

Pontuação e Feedback: Acertos e erros serão registrados, com feedback educativo para reforçar o aprendizado.

Dificuldade Progressiva: À medida que avança no jogo, o jogador enfrentará desafios maiores, como tempo reduzido ou tipos de resíduos mais complexos.

Ranking e Recompensas: Um sistema de pontuação incentivará a competição saudável, com premiações simbólicas para os melhores desempenhos.

O jogo será desenvolvido utilizando Python para manipulação de dados e poderá ter integração com Power BI para análise de desempenho e impacto. Ele será voltado para público geral, com foco em estudantes, empresas e comunidades interessadas em sustentabilidade.

---

## Backlogs do Produto

1. Configuração e Cadastro
✅ [US001] Cadastro de Usuário – O jogador pode criar um perfil com nome e acompanhar sua pontuação.
✅ [US002] Cliente Fictício – Implementar a empresa EcoVida Reciclagem Ltda. como parceira do jogo.
✅ [US003] Menu Inicial – Criar tela inicial com opções de jogar, ver ranking e acessar informações sobre reciclagem.

2. Mecânica do Jogo
✅ [US004] Classificação de Resíduos – Implementar um sistema onde o jogador arrasta ou seleciona o lixo para a lixeira correta.
✅ [US005] Cores da Coleta Seletiva – Associar resíduos às cores corretas (azul, amarelo, verde, vermelho, etc.).
✅ [US006] Feedback Educacional – Exibir mensagens de acerto/erro com informações sobre reciclagem.
✅ [US007] Níveis de Dificuldade – Criar progressão de níveis com desafios mais complexos.
✅ [US008] Cronômetro – Adicionar limite de tempo para incentivar o raciocínio rápido.

3. Pontuação e Competitividade
✅ [US009] Sistema de Pontuação – Recompensar acertos e penalizar erros.
✅ [US010] Ranking de Jogadores – Criar uma classificação com melhores pontuações.
✅ [US011] Recompensas Virtuais – Implementar medalhas ou certificados digitais para incentivar a participação.

4. Relatórios e Análises
✅ [US012] Histórico de Jogadas – Permitir que o jogador veja seu desempenho anterior.
✅ [US013] Integração com Power BI – Gerar relatórios sobre o impacto do jogo na conscientização ambiental.

5. Implementação e Testes
✅ [US014] Testes de Usabilidade – Garantir que o jogo seja intuitivo e acessível.
✅ [US015] Ajustes Finais e Publicação – Revisar e disponibilizar a versão final do jogo.

---

## Cronograma

Aqui está um cronograma sugerido para o desenvolvimento do **Seco Game**, dividido por fases e com estimativas de tempo para cada etapa:

---

### **Cronograma do Seco Game**

| **Fase**                             | **Atividade**                                     | **Duração Estimada** | **Data de Início** | **Data de Conclusão** |
|--------------------------------------|---------------------------------------------------|----------------------|--------------------|-----------------------|
| **1. Planejamento e Definição**      | Definir requisitos, escopo e funcionalidades do jogo | 1 semana             | 24/03/2025         | 30/03/2025            |
| **2. Design e Prototipação**         | Criação das telas e protótipos do jogo             | 2 semanas            | 31/03/2025         | 13/04/2025            |
| **3. Desenvolvimento Inicial**       | Implementação do cadastro e menu inicial          | 1 semana             | 14/04/2025         | 20/04/2025            |
| **4. Mecânicas do Jogo**             | Desenvolvimento da classificação de resíduos e sistema de feedback | 3 semanas            | 21/04/2025         | 11/05/2025            |
| **5. Sistema de Pontuação e Ranking**| Implementação de pontuação, ranking e recompensas | 2 semanas            | 12/05/2025         | 25/05/2025            |
| **6. Testes e Ajustes**              | Testes de usabilidade e ajustes finais            | 2 semanas            | 26/05/2025         | 08/06/2025            |
| **7. Integração com Power BI**       | Integração e geração de relatórios de impacto      | 1 semana             | 09/06/2025         | 15/06/2025            |
| **8. Publicação e Lançamento**       | Finalização e publicação do jogo                  | 1 semana             | 16/06/2025         | 22/06/2025            |

---

## Materiais e Métodos

### Modelagem do Sistema

<Inserir diagramas UML, como Casos de Uso, Diagrama de Classes, MER etc.>

### Tecnologias Utilizadas

React, Typescript, FastApi, banco Sqlite, Jira, Figma

### Arquitetura do Sistema

<Inserir uma imagem do fluxo do sistema e sua arquitetura.>

---

## Resultados

### Protótipo

<Inserir capturas de tela do sistema com descrições.>

### Códigos das principais funcionalidades

<Trechos de código relevantes com comentários explicativos.>

---

## Conclusão

### Impacto do Sistema

<Como o sistema melhorou o processo do cliente.>

### Melhorias Futuras

<Enumere possíveis melhorias para versões futuras.>

---

## Homologação do MVP junto ao cliente

<Inserir fotos da homologação do MVP, incluindo reunião e apresentação.>

### Lista de Presentes na Homologação

<Inserir foto da lista de presença.>

---

## Divulgação

### LinkedIn do Projeto

[Perfil no LinkedIn](#)  

https://www.linkedin.com/in/seco-game-60069a358/
<Inserir print da página do LinkedIn do projeto.>

### Seminário de Projetos de Software

[Vídeo da Apresentação](#)  

<Inserir fotos da apresentação.>

### FENETEC: Feira de Negócios em Tecnologia

[Vídeo da Apresentação](#)  

<Inserir fotos do evento e apresentação.>

---

## Carta de Apresentação

<Inserir a carta de apresentação para o cliente.>

---

## Carta de Autorização

<Inserir a carta de autorização para a realização das atividades acadêmicas.>

---

## Relato Individual do Processo

| Nome do Aluno | Relato |
|--------------|--------|
| <Aluno 1> | <Breve relato pessoal> |
| <Aluno 2> | <Breve relato pessoal> |
| <Aluno 3> | <Breve relato pessoal> |
| <Aluno 4> | <Breve relato pessoal> |
| <Aluno 5> | <Breve relato pessoal> |

---
