# Automação de Marketing e Acompanhamento no HubSpot

## 1. Objetivo

Implementar uma automação para organizar os contatos recebidos pelo formulário do site e facilitar o acompanhamento dos novos interessados.

## 2. Gatilho de inscrição

O workflow é acionado quando um contato preenche o formulário denominado "Formulário site", disponível em qualquer página do site.

## 3. Ações automatizadas

Após o preenchimento do formulário, o HubSpot executa as seguintes ações:

1. Define a origem do contato como Formulário.
2. Define o tipo de contato como Lead.
3. Atualiza a fase do ciclo de vida para Novo Contato.
4. Define o status do lead como Novo.
5. Cria uma tarefa de acompanhamento intitulada "Acompanhar novo interessado".

## 4. Configuração da tarefa

- Título: Acompanhar novo interessado.
- Tipo: Chamada.
- Prazo: um dia após a criação.
- Calendário: somente dias úteis.
- Horário: 08h00.
- Responsável: proprietário do contato.
- Prioridade: baixa.

## 5. Finalidade da automação

A automação busca reduzir atividades manuais, padronizar a classificação dos contatos e facilitar o acompanhamento dos interessados recebidos pelo formulário do site.

## 6. Validação

O workflow foi configurado e publicado no HubSpot. A configuração da ação de criação de tarefa foi documentada por captura de tela.

A validação dos resultados deve considerar os registros efetivamente gerados pelo workflow, sem presumir que todos os contatos cadastrados foram originados pelo projeto.
