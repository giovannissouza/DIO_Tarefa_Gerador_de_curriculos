# DIO_Tarefa_Gerador_de_curriculos
Gerador de currículos com IA

# 📄 ResumeCraft AI — Gerador de Currículos Otimizados para Vagas

> **Aplicação Web que analisa descrições de vagas de emprego e reestrutura seu currículo base para maximizar o alinhamento com sistemas ATS (Applicant Tracking Systems) e recrutadores.**

---

## 🎯 1. Qual Problema a Aplicação Solve

Muitos profissionais qualificados são descartados em processos seletivos antes mesmo de chegarem à fase de entrevista. Os principais motivos incluem:

* **Filtros Automáticos (ATS):** Os softwares de triagem descartam currículos genéricos que não contêm as palavras-chave e termos técnicos exatos presentes no anúncio da vaga.
* **Falta de Personalização:** Enviar o mesmo currículo genérico para dezenas de vagas diferentes reduz drasticamente a taxa de conversão.
* **Dificuldade de Destacar Impacto:** Candidatos costumam listar apenas descrições passivas de cargos, em vez de conquistas mensuráveis e competências alinhadas aos requisitos da empresa.
* **Gasto Excessivo de Tempo:** Reescrever e formatar manualmente um currículo para cada candidatura consome horas de trabalho.

O **ResumeCraft AI** resolve isso ao cruzar automaticamente a trajetória do candidato com as exigências do anúncio, gerando uma versão otimizada, estratégica e pronta para aplicação em segundos.

---

## 🤖 2. O Mega Prompt Utilizado e Sua Evolução

### Mega Prompt Final Utilizado na Aplicação

```text
Você é um Especialista em Recrutamento, Tech Recruiter e Engenheiro de Prompts para Otimização de Currículos (ATS Optimization).

Sua tarefa é receber dois insumos:
1. O CURRÍCULO BASE do usuário (histórico profissional, formação e competências).
2. A DESCRIÇÃO DA VAGA (Job Description) pretendida.

---

### DIRETRIZES DE PROCESSAMENTO E SEGURANÇA:
1. REGRA ZERO (ANTI-ALUCINAÇÃO): Você NUNCA deve inventar empresas, cargos, datas, certificados ou experiências que não existam no Currículo Base. Apenas reestruture, reescreva e reordene as informações reais do usuário.
2. EXTRAÇÃO DE PALAVRAS-CHAVE: Mapeie as 10 principais palavras-chave, requisitos técnicos (Hard Skills) e competências comportamentais (Soft Skills) da Vaga.
3. REESTRUTURAÇÃO TÁTICA:
   - Reescreva os resumos e pontos de experiência utilizando a metodologia STAR (Situação, Tarefa, Ação e Resultado).

<img width="1630" height="915" alt="image" src="https://github.com/user-attachments/assets/2e799161-afc8-4b6e-8227-ba46f288b5fb" />

LINK: https://ai.studio/apps/1ae57cda-d08c-4d25-a7c7-39af68846bab

   - Incorpore as palavras-chave extraídas naturalmente nas descrições de cargo.
   - Destaque resultados quantitativos/métricas sempre que disponíveis no texto original.
4. FORMATO DE SAÍDA:
   - Apresente um "Relatório de Compatibilidade (Match Score)" com percentual de aderência e lacunas identificadas.
   - Entregue o Currículo Otimizado em formato Markdown limpo, pronto para cópia ou exportação em PDF.
