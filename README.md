# Bootcamp Microsoft DIO - Explore an Azure AI Search index (UI)

## 🚀 Objetivo
Este laboratório tem como objetivo utilizar os recursos do Azure de IA para a realização de pesquisa em documentos.

### Serviços: Azure Cognitive Search
Vamos imaginar que você trabalha para a Fourth Coffee, uma rede nacional de cafés. Você foi solicitado a ajudar a criar uma solução de mineração de conhecimento que facilite a busca de insights sobre as experiências dos clientes. Você decide criar um índice do Azure AI Search usando dados extraídos de avaliações de clientes.

Para realizar os testes desse repositório é necessário ter uma conta no Microsoft Azure

Fonte e configurações do Azure
* https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html

Os seguintes recursos no AZURE são necessários para a pesquisa:

* Um recurso do Azure AI Search , que gerenciará a indexação e a consulta.
* Um recurso de serviços de IA do Azure , que fornece serviços de IA para habilidades que sua solução de pesquisa pode usar para enriquecer os dados na fonte de dados com insights gerados por IA.
* Uma conta de armazenamento com contêineres de blobs, que armazenará documentos brutos e outras coleções de tabelas, objetos ou arquivos.
Nota Os recursos do Azure AI Search e dos serviços Azure AI devem estar no mesmo local!

## Etapas resumidas das configurações no AZURE

Seguindo as etapas da documentação:
 * Criação do recurso do Azure AI Search
 * Criação de um recurso de Serviços Cognitivos
 * Criar um conta de armazemento e inserir dos documentos que serão analisados
 * Importar os dados (selecionar) para o recurso de Azure AI Search criado, nesta etapa 
você poderá ligar com o recurso de Serviços Cognitivos na etapa "Adicionar habilidades cognitivas (opcional), alem de adicionar enriquecimentos e ativar a opção de OCR.

### Dados de origem para análise:

Os documentos que contém as experiências dos clientes da rede de cafés pode ser encontrado no link:
 * https://aka.ms/mslearn-coffee-reviews

### Resultado:
Resultado após uma pesquisa nos documentos, onde queremos somente os reviews positivos dos clientes da rede de cafés:

![alt text](https://github.com/AlexandreSato2023/labdio04/blob/main/outputs/analise_1.png?raw=true)
