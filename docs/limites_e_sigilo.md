# Diretrizes de Limites de Sigilo
1. **Anonimização:** Substituir nome, CPF, telefone, e-mails e nomes de terceiros reais/fictícios sensíveis por *tags* (ex: `[REQUERENTE]`, `[CLIENTE 1]`).
2. **Uso de IA:** Proibido o uso de dados de entrada para treinamento dos modelos (Opt-out ativado).
3. **Ambiente Isolado:** O processamento deve ocorrer estritamente via prompts limitados aos arquivos da pasta `apoio/`.