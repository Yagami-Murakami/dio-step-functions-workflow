# Anotações sobre AWS Step Functions

## 1. Ideia principal

O AWS Step Functions é utilizado para criar workflows automatizados.

Ele ajuda a organizar processos em etapas, permitindo controlar melhor a execução, as decisões e os possíveis erros durante o fluxo.

## 2. Máquinas de estado

Uma máquina de estado representa o fluxo completo da aplicação ou automação.

Cada etapa desse fluxo é chamada de estado.

## 3. Tipos de estados

Alguns tipos de estados importantes são:

* `Pass`: repassa informações sem executar uma tarefa externa;
* `Task`: executa uma tarefa;
* `Choice`: cria condições e decisões;
* `Wait`: aguarda um tempo definido;
* `Succeed`: finaliza o fluxo com sucesso;
* `Fail`: finaliza o fluxo com erro.

## 4. Amazon States Language

A Amazon States Language é baseada em JSON e serve para definir os workflows do Step Functions.

Ela descreve:

* O estado inicial;
* Os estados existentes;
* As transições entre estados;
* As condições de decisão;
* O encerramento do fluxo.

## 5. Benefícios

Os principais benefícios percebidos foram:

* Melhor organização do processo;
* Visualização clara do workflow;
* Facilidade para acompanhar execuções;
* Tratamento de erros;
* Integração com outros serviços da AWS;
* Documentação mais clara da automação.

## 6. Insights

O Step Functions é útil quando um processo possui várias etapas e precisa ser controlado de forma organizada.

Ele pode ser aplicado em fluxos de aprovação, automações internas, processamento de pedidos, pipelines de dados e integração entre serviços.

## 7. Conclusão

O laboratório ajudou a entender como estruturar workflows automatizados e como documentar esse conhecimento em um repositório no GitHub.
