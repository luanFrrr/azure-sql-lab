# 🛠️ Desafio DIO - Configuração de Instância de Banco de Dados no Microsoft Azure

## 📘 Descrição

Este repositório foi desenvolvido como parte do desafio da DIO com o objetivo de documentar a criação e configuração de uma **instância de Banco de Dados SQL no Microsoft Azure**. O conteúdo aqui apresentado serve como apoio para revisões, estudos e futuras implementações em ambientes reais.

---

## 🎯 Objetivos

- Aplicar na prática os conhecimentos aprendidos nas aulas;
- Criar uma instância gerenciada de banco de dados no Azure;
- Documentar o processo técnico de forma clara e acessível;
- Utilizar o GitHub como ferramenta de versionamento e compartilhamento de conhecimento.

---

## 🧠 Conceitos Importantes

### O que é o Azure SQL Database?
É um serviço de banco de dados gerenciado baseado no SQL Server, hospedado na nuvem do Azure, que permite criar e gerenciar bancos de dados sem precisar lidar com a infraestrutura física ou configuração detalhada de servidores.

### Benefícios:
- Alta disponibilidade;
- Escalabilidade automática;
- Backup automático;
- Segurança e criptografia gerenciadas.

---

## 🛠️ Etapas de Configuração da Instância SQL

1. **Acessar o Portal Azure**:  
   [https://portal.azure.com](https://portal.azure.com)

2. **Criar um recurso do tipo “Instância Gerenciada de SQL”**.

3. **Preencher as informações básicas**:
   - Nome da instância: `sql-dio-lab`
   - Região: Brasil Sul
   - Tipo de compra: Uso individual
   - Nome do servidor lógico e credenciais

4. **Configurar rede e segurança**:
   - Escolher ou criar uma rede virtual
   - Definir regras de firewall para permitir acesso (por IP ou por aplicativo específico)

5. **Revisar e criar**

6. **Conectar-se ao banco via SQL Server Management Studio (SSMS) ou Azure Data Studio**  
   Usando os dados da instância criada (nome do host, usuário e senha definidos anteriormente)

---

## 💡 Dicas Úteis

- Use IP fixo para configurar o firewall de forma mais segura.
- Habilite alertas de performance e consumo para evitar custos inesperados.
- Faça backup dos dados ou exporte o banco regularmente, mesmo que o Azure ofereça backups automáticos.
- Utilize o recurso de escalonamento automático conforme necessário para ajustar o desempenho.

---

## 📎 Recursos Complementares

- [Documentação Oficial - Criar Instância Gerenciada SQL](https://learn.microsoft.com/pt-br/azure/azure-sql/managed-instance/sql-managed-instance-paas-overview)
- [GitHub Markdown Guide](https://guides.github.com/features/mastering-markdown/)
- [Formação GitHub Certification - GitBook](https://certification.github.com/)

---

## ✍️ Autor

**Luan**  
Estudante focado em cloud computing e infraestrutura moderna.  
Conectando teoria com prática no ambiente real da nuvem.

