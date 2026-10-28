# 🐾 Clínica Veterinária Patinhas Felizes

Projeto de Banco de Dados - MySQL

Aluna: Paola Cristine Silva Bastos
Curso: Desenvolvimento de Sistemas
Data: 28/Outubro/2026

## 📋 Descrição
Sistema de gerenciamento para clínica veterinária com controle de clientes, animais, veterinários e consultas.
(https://github.com/user-attachments/files/34084662/Documento.sem.titulo.pdf)


## 🗂️ Estrutura do Banco
- **cliente** (id_cliente, nome, telefone, email)
- **animal** (id_animal, nome, especie, raca, peso, id_cliente)
- **veterinario** (id_veterinario, nome, especialidade, crmv)
- **consulta** (id_consulta, data, valor, id_animal, id_veterinario)

## 🚀 Como Rodar

1. No MySQL Workbench: Server > Data Import
2. Import from Self-Contained File > selecione `dump_patinhas_felizes.sql`
3. Clique em Start Import

Ou pelo terminal:
```sql
mysql -u root -p patinhas_felizes < dump_patinhas_felizes.sql📊 Consultas
15 consultas SQL no arquivo consultas.sql, incluindo:
Peso médio dos animais: 10.520000 kgTotal de consultas, faturamento, etc.📁 Arquivosdump_patinhas_felizes.sql - Dump completo (11KB)tabelas.sql - Criação das tabelasdados.sql - Insertsconsultas.sql - 15 consultas solicitadas✔️ StatusDump exportado e validado - MySQL Workbench
