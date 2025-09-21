🚀 Bootcamp Klabin – Desafio 03

Este repositório reúne os desafios do Bootcamp Klabin, abordando tanto a construção de relatórios criativos em Power BI quanto a modelagem e implementação de um banco de dados relacional.
🌐 Desafio de Projeto – Integrando Dados com MySQL Azure e Transformando com Power BI

🎯 Objetivo

Integrar dados de uma instância MySQL no Azure com o Power BI, explorando a base de dados relacional, corrigindo inconsistências e aplicando transformações para construção de relatórios analíticos.

📘 Ementa – Etapas do Desafio

- Descrevendo o desafio de projeto

- Criando uma instância do MySQL na Azure

- Explorando o Recurso - Instância do MySQL

- Criando Regra no Firewall na Azure para Acesso ao banco de dados

- Conectando ao MySQL na Azure utilizando Workbench

- Integrando Power BI com MySQL na Azure

📝 Descrição do Desafio

- Criação de uma instância na Azure para MySQL

- Criar o Banco de dados com base disponível no GitHub

- Integração do Power BI com MySQL no Azure

- Verificar problemas na base a fim de realizar a transformação dos dados

⚙️ Diretrizes para Transformação dos Dados

- Verifique os cabeçalhos e tipos de dados

- Modifique os valores monetários para o tipo double preciso

- Verifique a existência dos nulos e analise a remoção

- Os employees com nulos em Super_ssn podem ser os gerentes. Verifique se há algum colaborador sem gerente

- Verifique se há algum departamento sem gerente

- Se houver departamento sem gerente, suponha que você possui os dados e preencha as lacunas

- Verifique o número de horas dos projetos

- Separar colunas complexas

- Mesclar consultas employee e department para criar uma tabela employee com o nome dos departamentos associados aos colaboradores.

- Base: tabela employee

Atenção: essa informação influencia no tipo de junção

- Elimine as colunas desnecessárias

- Realize a junção dos colaboradores e respectivos nomes dos gerente.

- Mescle as colunas de Nome e Sobrenome para ter apenas uma coluna com o nome completo

- Mescle os nomes de departamentos e localização para criar combinações únicas

- Elimine colunas desnecessárias, que não serão usadas no relatório, de cada tabela

🔑 Melhorias aplicadas

- Renomeação de tabelas e colunas para consistência

- Uso de constraints nomeadas (pk_, fk_, chk_, unique_)

- Queries ajustadas para boas práticas de SQL (JOINs explícitos)

- Estrutura de repositório organizada em pastas por desafio

Desafio 03 – Integrando Dados com MySQL Azure e Transformando com Power BI| Bootcamp Klabin
Desenvolvido por Laila.
