SQLite Data Modeling – Online Courses

Este projeto consiste em um exercício de modelagem de dados relacional a partir de arquivos JSON, simulando o backend de uma plataforma de cursos online.

O foco não foi apenas criar tabelas, mas traduzir regras de negócio em estrutura de dados, garantindo integridade, consistência e relacionamento entre entidades.

🎯 Objetivo

Transformar dados semi-estruturados (JSON) em um modelo relacional

Definir corretamente chaves primárias, estrangeiras e restrições

Garantir regras de unicidade, integridade referencial e ciclo de vida dos dados

🧠 Regras de negócio implementadas

Slug do curso único

Slug da aula único por curso

Controle de aulas concluídas por usuário

Emissão de certificado por curso e usuário

Remoção automática de aulas concluídas e certificados ao deletar um usuário (ON DELETE CASCADE)

Campo booleano (free) validado com CHECK

Uso de tabelas STRICT no SQLite

🛠️ Tecnologias

SQLite

SQL (DDL)

Modelagem de dados relacional

🗂️ Estrutura do banco

O modelo inclui as seguintes tabelas:

users

courses

lessons

lessons_completed

certificates

📌 Aprendizados

Este exercício reforçou a importância de pensar primeiro nas regras de negócio e depois no SQL, algo essencial para análises confiáveis e sistemas escaláveis.

📄 Script

O script completo de criação das tabelas está disponível neste repositório.

Feedbacks e sugestões de melhoria são bem-vindos.
