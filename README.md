# O-PrisioneiroDosDados (Hospital PT3)

Este projeto inclui a modelagem e povoamento do banco de dados com os seguintes requisitos adicionais:

Adição de Médicos e Especialidades:

Dez médicos foram adicionados, cobrindo sete especialidades diferentes: pediatria, clínica geral, gastroenterologia, dermatologia, cardiologia, neurologia e ortopedia.
Foi criada uma tabela de relacionamento entre médicos e especialidades.
Pacientes e Consultas:

Quinze pacientes foram cadastrados.
Vinte consultas foram registradas, com ao menos dez consultas contendo receituário de dois ou mais medicamentos.
As consultas ocorreram entre 01/01/2015 e 01/01/2022.
Convênios Médicos:

Quatro convênios foram adicionados.
Cinco pacientes foram associados a convênios, assim como cinco consultas.
Internações e Enfermaria:

Sete internações foram registradas, com dois pacientes tendo mais de uma internação.
Três tipos de quartos foram cadastrados: apartamentos, quartos duplos e enfermarias.
Cada internação foi associada a pelo menos dois enfermeiros.
Relacionamentos e Chaves Estrangeiras:

Foram ajustadas as chaves estrangeiras entre convênios e médicos.
Foi criada uma entidade de relacionamento entre internação e enfermeiro, incluindo chaves estrangeiras de médico e paciente na tabela de internação.
