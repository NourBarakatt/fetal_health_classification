# fetal_health_classification
# Projeto de Machine Learning – Classificação da Saúde Fetal

Universidade Presbiteriana Mackenzie

Este projeto foi desenvolvido como trabalho universitário da disciplina de Machine Learning.

O objetivo é aplicar técnicas de aprendizado de máquina para classificar a saúde fetal em três categorias:

* Normal
* Suspeita
* Patológica

A base de dados utilizada foi a **Fetal Health Classification Dataset**, composta por informações obtidas por meio de exames de cardiotocografia (CTG), como frequência cardíaca fetal, acelerações, desacelerações e contrações uterinas.

## Modelos utilizados

Foram comparados dois modelos principais:

* Regressão Logística
* Random Forest

Também foi aplicada a técnica **SMOTE (Synthetic Minority Over-sampling Technique)** para balanceamento das classes, especialmente para melhorar a identificação da classe patológica.

## Principais resultados

O melhor desempenho foi obtido com o modelo **Random Forest com SMOTE**, apresentando:

* Accuracy: 92,96%
* Recall da classe patológica: 91%

Esse resultado demonstra maior capacidade de identificar fetos em situação de risco, reduzindo falsos negativos e contribuindo para diagnósticos mais seguros.

## Arquivos

* `fetal_health.csv` → base de dados utilizada
* `Projeto_ML_Saude_Fetal.ipynb` → notebook principal do projeto

## Alunos

* Ryan Rodrigues Pereira – 10742607 – [10742607@mackenzista.com.br](mailto:10742607@mackenzista.com.br)
* Nour Hussein Barakat – 10738273 – [10738273@mackenzista.com.br](mailto:10738273@mackenzista.com.br)
* Guilherme de Araújo Esp. Santo – 10746294 – [10746294@mackenzista.com.br](mailto:10746294@mackenzista.com.br)
