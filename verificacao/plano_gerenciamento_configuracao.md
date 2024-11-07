# Plano de Gerenciamento de Configuração do Software Ordem de Serviço

## Controle de Versões

| Versão | Data       | Autor(es)                          | Notas de Revisão                                                                                           |
|--------|------------|------------------------------------|------------------------------------------------------------------------------------------------------------|
| v1.0   | 01/10/24   | Anderson Rodrigues de Souza, Alicia Caldeira da Silva | Elaboração da Introdução do Plano de Gerenciamento de Configuração (Finalidade; Escopo; Definições, Acrônimos e Abreviações; Referência; Visão Geral). |
| v1.1   | 02/10/24   | Anderson Rodrigues de Souza, Alicia Caldeira da Silva | Revisão da Introdução.                                                                                     |
| v1.2   | 03/10/24   | Anderson Rodrigues de Souza, Alicia Caldeira da Silva | Elaboração do Gerenciamento de Configuração de Software (Organização, Responsabilidades e Interfaces; Ferramentas, Ambiente e Infraestrutura). |
| v1.3   | 04/10/24   | Anderson Rodrigues de Souza, Alicia Caldeira da Silva | Revisão do Gerenciamento de Configuração de Software.                                                      |
| v1.4   | 05/10/24   | Anderson Rodrigues de Souza        | Elaboração do Programa de Gerenciamento de Configuração (Identificação da Configuração; Controle de Configuração e Mudança). |
| v1.5   | 07/10/24   | Anderson Rodrigues de Souza        | Revisão do Programa de Gerenciamento de Configuração.                                                      |
| v1.6   | 08/10/24   | Anderson Rodrigues de Souza        | Elaboração dos marcos do Plano de Gerenciamento de Configuração.                                           |
| v1.7   | 09/10/24   | Anderson Rodrigues de Souza, Rennan de Souza Alves | Elaboração do Treinamento e Recursos (Ferramentas de Software; Treinamento; Equipe e Pessoal). |
| v1.8   | 12/10/24   | Anderson Rodrigues de Souza, Rennan de Souza Alves | Elaboração do Controle de Software de Subcontratados e Fornecedores.                                        |
| v1.9   | 15/10/24   | Kássia Ramos Oliveira              | Elaboração do Programa de Gerenciamento de Configuração (Estimativa do Status de Configuração).             |
| v1.10  | 21/10/24   | Kássia Ramos Oliveira              | Revisão da Estimativa do Status de Configuração.                                                           |

## 1. Introdução

O Plano de Gerenciamento de Configuração abrange todas as ações para o controle e gerenciamento de mudanças durante o ciclo de vida do produto. Ele visa garantir a estabilidade e a conformidade do software com suas especificações iniciais, permitindo adaptações de maneira controlada e organizada.

## 1.1 Finalidade

Este documento define diretrizes para o controle do produto, assegurando uniformidade e organização nas ações da equipe. Especifica os recursos necessários, responsabilidades e cronograma para facilitar a gestão eficiente do projeto.

## 1.2 Escopo

Destinado aos colaboradores da Soluções 2ADKR, este plano cobre todo o projeto Ordem de Serviço, proporcionando um guia para a gestão das configurações, assegurando integridade e eficiência na comunicação entre setores.

## 1.3 Definições, Acrônimos e Abreviações

- **Baseline**: Linha de base para desenvolvimento e controle de mudanças.
- **RUP**: Rational Unified Process, processo de engenharia de software da IBM.
- **IDE**: Integrated Development Environment.
- **C#**: Linguagem de programação orientada a objetos.
- **CCB**: Comitê de Controle de Mudanças.

## 1.4 Referências

- Template do Plano de Gerenciamento de Configuração, Ministério do Planejamento.
- [Repositório GitHub do projeto](https://github.com/arsouza81/GC_OrdemServico)

## 1.5 Visão Geral

Este plano oferece diretrizes para controle de configurações no projeto, assegurando a integridade e rastreabilidade de modificações e promovendo segurança e eficiência.

## 2. Gerenciamento de Configuração de Software

### 2.1 Organização, Responsabilidades e Interfaces

| Função              | Responsabilidade                                                                                                                                 |
|---------------------|---------------------------------------------------------------------------------------------------------------------------------------------------|
| Gerente do Projeto  | Solicitar criação de ambientes, autorizar mudanças e distribuir tarefas.                                                                        |
| Gerente de Configuração | Definir e manter políticas de configuração e apoiar a equipe em conformidade com linhas de base.                                         |
| Comitê de Mudanças  | Avaliar impactos das mudanças no projeto.                                                                                                       |
| Equipe de Desenvolvimento | Documentação e implementação das alterações.                                                                                            |
| Gerente de Teste    | Execução de testes e registro de não conformidades.                                                                                             |

### 2.2 Ferramentas, Ambiente e Infraestrutura

#### 2.2.1 Ferramentas

- **GitHub** (Free): Plataforma colaborativa para gerenciamento de projetos.
- **Git** (2.46.2): Controle de versão distribuído.
- **Markdown**: Linguagem de marcação leve para documentação.
- **Microsoft Visual Studio** (17.11.4): IDE para desenvolvimento em .NET.

#### 2.2.2 Ambientes

Desenvolvimento local em notebooks com Microsoft Visual Studio e repositório GitHub para compartilhamento e controle de versões.

#### 2.2.3 Infraestrutura

Recursos locais e GitHub; evolução para servidores dedicados ou computação em nuvem conforme necessário.

## 3. Programa de Gerenciamento de Configuração

### 3.1 Identificação da Configuração

Utilização de versionamento semântico e convenção para identificar cada item configurável do projeto.

### 3.2 Controle de Configuração e Mudança

Solicitações de mudança documentadas e aprovadas pelo CCB.

### 3.3 Estimativa do Status de Configuração

Visão geral dos itens de configuração, servindo como base para decisões durante o desenvolvimento.

### 3.3.1 Processamento de Mídia e Liberação do Projeto

- **Retenção e Backup**: GitHub e Google Drive para controle de versão e recuperação.
- **Mídias e Formatos**: Documentos em .docx, .pdf, .pptx e código em formato zip.
- **Liberação**: Realizada no GitHub com notas de lançamento e instruções de instalação.

### 3.3.2 Relatórios e Auditorias

Relatórios de configuração e progresso, com métricas para análise de qualidade e evolução.

## 4. Marcos

### Principais Marcos

- **Marco 1 (22/10/2024)**: Apresentação do Plano e da Baseline do Projeto.
- **Marco 2 (18/11/2024)**: Apresentação dos relatórios de inspeção e plano de testes.
- **Marco 3 (10/12/2024)**: Entrega da versão final com correções.

## 5. Treinamento e Recursos

### 5.1 Ferramentas de Software

- GitHub, GIT, Microsoft Visual Studio, MySQL, Markdown.

### 5.2 Treinamento

Treinamento para uso de Git, ASP.NET, C#, e controle de mudanças.

### 5.3 Equipe e Pessoal

Equipe de alunos de Engenharia de Software e especialistas de TI do ICET.

## 6. Controle de Software de Subcontratados e Fornecedores

- **Avaliação de Qualidade e Segurança**: Conformidade com padrões do projeto.
- **Licenciamento**: Garantia de conformidade legal para software externo.
- **Integração Controlada**: Acompanhamento de software externo dentro das diretrizes de configuração.

---

**Aprovado em 21 de outubro de 2024**

**Equipe Responsável**  
- Alicia Caldeira da Silva  
- Anderson Rodrigues de Souza  
- Diandre Pires Bruce  
- Kássia Ramos Oliveira  
- Rennan de Souza Alves
