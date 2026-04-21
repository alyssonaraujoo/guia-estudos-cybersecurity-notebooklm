# Guia de Estudos: Cibersegurança com NotebookLM 🛡️

## 📝 Contexto e Objetivos
Este repositório contém um caderno temático focado em **Fundamentos de Cibersegurança**. O objetivo é utilizar a IA NotebookLM para sintetizar documentos técnicos e criar um material de consulta rápida para exames e certificações.

## 📚 Curadoria de Fontes
Para este projeto, foram utilizadas as seguintes fontes (disponíveis na pasta `/docs` deste repositório):
* NIST Cybersecurity Framework - (https://www.ibm.com/br-pt/think/topics/nist)
* OWASP Top 10 Guide - (https://www.cloudflare.com/pt-br/learning/security/threats/owasp-top-10/)
* [Link ou Nome do PDF 3] - Ex: Guia de Redes Seguras (Cisco/CISA)

## 🧠 Engenharia de Prompts e "Cicatrizes"
Aqui registro o processo de refinamento das respostas da IA:

| Prompt Inicial | Refinamento (Prompt Estratégico) | Dificuldade/Solução |
| :--- | :--- | :--- |
| "O que é firewall?" | "Explique a diferença entre Firewall Stateful e Stateless baseado nos textos." | A IA foi muito genérica; precisei pedir foco técnico. |
| "Resuma o texto 2." | "Crie um resumo em tópicos focando apenas em vulnerabilidades de rede." | Ajustei para evitar que a IA trouxesse info externa. |

## 📖 Miniguia de Estudo (Entrega Final)

### 1. Resumo Estruturado
* **Modelo OSI e Segurança:** Como proteger cada camada.
* **Ameaças Comuns:** Phishing, Man-in-the-Middle e Ransomware.

### 2. Glossário de Conceitos
* **IDS/IPS:** Sistemas de detecção e prevenção de intrusão.
* **Criptografia Simétrica:** Uso de uma única chave para cifrar e decifrar.

### 3. Prompts Reutilizáveis
> Use estes prompts para revisar o conteúdo futuramente:
> * *"Atue como um instrutor de CCNA e me faça 3 perguntas sobre segurança de camada 2."*
> * *"Relacione o conceito de Zero Trust com o conteúdo dos PDFs fornecidos."*
