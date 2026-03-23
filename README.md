# Assistente de Atendimento Automatizado (n8n + SQL + REST)

Este projeto consiste em um chatbot escalável desenvolvido no **n8n**, focado na experiência do usuário (UX) e integridade de dados. Ele realiza consultas em tempo real via API REST e validações em banco de dados **PostgreSQL**.

---

## 🏗️ Arquitetura do Sistema
Fluxo de funcionamento do sistema:

1. O bot recebe o input do usuário  
2. Valida os dados via SQL  
3. Consulta uma API externa  
4. Retorna a resposta ao usuário  

---

## 🚀 Tecnologias Utilizadas

- **n8n**: Orquestração de fluxos low-code  
- **PostgreSQL**: Armazenamento e logs de auditoria  
- **REST API**: Integração com sistemas de terceiros (ex: CRM e pagamentos)  
- **JavaScript**: Manipulação de dados complexos nos nós de função  

---

## 🛠️ Funcionalidades Técnicas

- **Monitoramento via SQL**  
  Implementação de queries para validar a integridade dos fluxos e identificar gargalos  

- **Arquitetura Stateless**  
  Garantia de alta performance e escalabilidade  

- **Tratamento de Erros**  
  Fluxos de contingência para falhas em APIs externas (fallback)  