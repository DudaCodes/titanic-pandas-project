# 🧠 Análise de Dados do Titanic com Pandas

Projeto desenvolvido como exercício prático do curso de **Ciência de Dados com Python** na plataforma **Udemy**. A proposta é realizar análises exploratórias com o conjunto de dados do Titanic, utilizando **Python e Pandas**, aplicando técnicas de filtragem, ordenação e exportação de dados.

---

## 📌 Objetivo

Explorar e filtrar informações específicas do dataset do Titanic, como:
- Mulheres da 1ª classe que sobreviveram
- Crianças que sobreviveram
- Idosos que estavam a bordo

Os resultados são salvos em arquivos `.csv` para futura análise.

---

## 🧰 Tecnologias Utilizadas

- Python 3
- Biblioteca Pandas
- Arquivo `titanic.csv` como fonte de dados

---

## 📁 Funcionalidades do Script

O script executa três funções principais:

### 1. 👩‍🦳 Mulheres sobreviventes da 1ª classe
Filtra passageiras do sexo feminino, que estavam na **primeira classe** e **sobreviveram**. Os dados são ordenados por nome e exportados em `mulheres_sobreviventes_primeira_classe.csv`.

### 2. 👧 Crianças sobreviventes
Seleciona passageiros com idade **menor que 12 anos** e que **sobreviveram**. Os dados são organizados por idade e exportados em `criancas_sobreviventes.csv`.

### 3. 👴 Idosos a bordo
Filtra passageiros com **mais de 60 anos**, independentemente da sobrevivência. Ordenados por idade e exportados em `idosos_a_bordo.csv`.

---
