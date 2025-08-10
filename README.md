# RELÁTORIO DE SERVIÇO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 10/08/2025
Empresa: Abstergo Industries
Responsável: Vinicius Teixeira

## 1. Introdução
Com a expansão de operações e o objetivo de otimizar custos, aumentar a eficiência e garantir escalabilidade, a adoção de soluções em cloud computing se torna uma estratégia essencial.  
Este relatório apresenta três ferramentas da **Amazon Web Services (AWS)** que podem auxiliar a Abstergo nesta transição, detalhando os benefícios e principais ganhos de cada uma.

---

## 2. Descrição do Projeto
O projeto tem como objetivo criar uma infraestrutura tecnológica robusta, segura e escalável para suportar as operações da Abstergo, permitindo:
- Redução de custos operacionais.
- Melhor desempenho no gerenciamento de dados e processos.
- Facilidade de expansão e integração com parceiros comerciais.
  
As ferramentas escolhidas da AWS são:
1. **Amazon S3** – Armazenamento seguro e escalável.
2. **Amazon RDS** – Banco de dados relacional gerenciado.
3. **AWS Lambda** – Execução de código sem provisionamento de servidores.

---

## 3. Serviços AWS Selecionados e Etapas de Implementação

### 3.1 Amazon S3 – Armazenamento de Arquivos
**Objetivo:** Armazenar documentos, catálogos, relatórios e dados de forma segura e acessível.  
**Como reduz custos:** Evita a necessidade de investir em infraestrutura física de armazenamento e permite pagar apenas pelo uso.  
**Principal ganho:** Alta disponibilidade e escalabilidade automática.

**Etapas de Implementação:**
1. Criar um bucket no Amazon S3 com configuração de permissões adequadas.
2. Implementar política de versionamento e backup automático.
3. Configurar regras de ciclo de vida para mover dados antigos para camadas de armazenamento mais baratas (Glacier).

---

### 3.2 Amazon RDS – Banco de Dados Relacional
**Objetivo:** Centralizar e gerenciar os dados transacionais da empresa (estoque, pedidos, histórico de vendas).  
**Como reduz custos:** Elimina gastos com manutenção e administração de servidores de banco de dados, reduzindo a necessidade de equipe especializada em infraestrutura.  
**Principal ganho:** Alta performance e segurança para operações críticas.

**Etapas de Implementação:**
1. Escolher o tipo de banco de dados (por exemplo, PostgreSQL ou MySQL).
2. Configurar instância RDS com backups automáticos e replicação para alta disponibilidade.
3. Migrar dados atuais para a nova instância utilizando AWS Database Migration Service.

---

### 3.3 AWS Lambda – Computação Serverless
**Objetivo:** Automatizar processos internos, como atualização de estoques e integração com sistemas de parceiros.  
**Como reduz custos:** Não é necessário manter servidores ativos, cobra-se apenas pelo tempo de execução do código.  
**Principal ganho:** Flexibilidade e escalabilidade automática para executar tarefas sob demanda.

**Etapas de Implementação:**
1. Criar funções Lambda para processar eventos (ex.: atualização automática de estoque).
2. Integrar com Amazon S3 e RDS para processar dados de forma automatizada.
3. Monitorar e otimizar funções através do Amazon CloudWatch.

---

## 4. Conclusão
A adoção das soluções **Amazon S3**, **Amazon RDS** e **AWS Lambda** permitirá à **Abstergo**:
- Reduzir custos de infraestrutura.
- Aumentar a segurança e a confiabilidade dos dados.
- Ganhar escalabilidade e flexibilidade nas operações.

Com a implementação planejada, a empresa estará pronta para crescer de forma sustentável, acompanhando a demanda do mercado e mantendo a competitividade no setor farmacêutico B2B.

---
