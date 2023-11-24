# **Chatbacana com Banco de Conhecimento em JSON** 😎
Grupo: Guilherme Pires, Mell Matsuda e Samuel Eichner

### **Descrição:**

Este projeto é um chatbot simples que utiliza um banco de conhecimento em JSON para responder a perguntas sobre Processamento de Linguagem Natural (PNL) e Inteligência Artificial (IA). O chatbot é projetado para funcionar em ambientes como Jupyter Notebook com Anaconda ou diretamente em uma máquina virtual no Google Colab.

Trabalho realizado para a disciplina de Introdução a Inteligência Artificial na Área da Saúde.

## **Instruções de Uso:**
### 1. Ambiente de Execução:
Se estiver usando o Jupyter Notebook com Anaconda, é necessário ajustar o diretório para o correto funcionamento do código. Certifique-se de definir corretamente o diretório onde o arquivo JSON está localizado.

```
base_conhecimento: dict = carregarconhecimento('caminho/do/seu/diretorio')
```

```
salvarconhecimento('caminho/do/seu/diretorio', base_conhecimento)
```

Se estiver usando o Google Colab, será necessário adicionar a base de conhecimento nos "Arquivos" da plataforma como é apresentado na imagem ```img_colab.jpg```.


### 2. Banco de Conhecimento em JSON:
O arquivo JSON contém perguntas e respostas relacionadas a PNL e IA. Certifique-se de que o arquivo JSON está presente no diretório correto.

### 3. Execução do Chatbot:
Execute o código do chatbot no ambiente escolhido (Jupyter Notebook ou Colab).

### 4. Interagindo com o Chatbot:
O chatbot responderá a perguntas com base no banco de conhecimento em JSON fornecido.
