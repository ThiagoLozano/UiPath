# Project: Course Invoice

O projeto tem como objetivo automatizar o proceso de coletar faturas através de um email (Outlook), realizar o desconto de cada cliente e retornar por email com suas informações alteradas.

## Índice

- [Visão Geral](#visão-geral)
- [Steps](#steps)
- [Ferramentas](#ferramentas)
- [Softwares](#softwares)
- [Instalação](#instalação)
- [Observações](#observações)

## Visão Geral

A automação deve acessar via email o sistema Outlook, coletando todos os emails referentes ao "Course Invoice", extraindo as planilhas deixadas em anexo. Ao realizar essa extração, a automação deve ser capaz de abrir cada planilha e coletar o código de cada cliente. Após obter os códigos, ele deve acessar o sistema ACME (Simulação) preenchendo o código do cliente e recebendo como retorno o valor do desconto que o mesmo deve receber. Esse valor de desconto deve ser coletado e inserido na planilha, ou seja, a automação também deve ser capaz de realizar alterações na planilha em uma célula específica. Após a alteração, ele deve retornar como rascunho um email com todas as planilhas alteradas.

## Steps

1. Abrir o sistema Outlook;
2. Localizar os emails refentes as faturas;
3. Abrir cada email e extrair os seus anexos;
4. Salvar os anexos em um arquivo a parte;
5. Extrair o código do cliente de cada planilha;
5. Acessar o site do sistema ACME;
6. Acessar a etapa correta;
7. Preencher o código do cliente;
8. Extrair o valor de desconto;
9. Alterar a planilha com o valor de desconto na celula correta;
10. Ao finalizar todas as planilhas, junta-las e salva-las como rascunho via Outlook;

## Ferramentas

* Uipath Studio
* UiPath Orchestrator
* Uipath Assistant

## Softwares

* Microsoft Outlook
* Sistema ACME (Simulação)

## Instalação

1. Clonar este repositório em sua máquina local.
2. Instalar o UiPath Studio (se ainda não instalado).
3. Abrir o projeto CourseInvoiceRPA.uipath no UiPath Studio.
4. Configurar as credenciais do Outlook e do sistema ACME(conforme as instruções no projeto).

## Observações

* Este projeto foi desenvolvido para fins educacionais e pode ser adaptado para atender às suas necessidades específicas.

* O foco desse projeto é a utilização da ferramentas em algumas situações como, leitura de e-mails, acesso a web, alteração de planilhas e criação de arquivos.