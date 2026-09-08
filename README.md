# ECMWF – Temperatura a 2 metros

Script em Python desenvolvido para obtenção, processamento e visualização de previsões de **temperatura do ar a 2 metros (T2M)** do modelo numérico **ECMWF**.

O notebook foi desenvolvido em ambiente **Google Colab** e permite gerar mapas de previsão de temperatura para a América do Sul, com destaque para a distribuição espacial das temperaturas previstas.

## Sobre o projeto

A variável **T2M (2 metre temperature)** representa a temperatura do ar a aproximadamente 2 metros acima da superfície.

O script processa os dados de previsão do ECMWF e produz um mapa espacial da temperatura prevista, permitindo visualizar a distribuição das temperaturas e identificar diferentes padrões térmicos sobre a região analisada.

## 📊 Dados utilizados

* **Modelo:** ECMWF
* **Variável:** Temperatura a 2 metros (T2M)
* **Região:** América do Sul
* **Unidade:** °C
* **Ambiente de desenvolvimento:** Google Colab

## 🛠️ Tecnologias

* Python
* NumPy
* Xarray
* Matplotlib
* Cartopy
* GeoPandas

## 🚀 Funcionamento

O script realiza, de forma geral, as seguintes etapas:

1. Configuração da rodada e do período de previsão;
2. Obtenção dos dados de temperatura do ECMWF;
3. Leitura e processamento dos dados;
4. Conversão da temperatura para graus Celsius;
5. Aplicação de suavização aos dados;
6. Definição de uma escala de cores personalizada;
7. Geração do mapa utilizando Cartopy;
8. Adição dos limites estaduais do Brasil;
9. Geração da legenda e identificação da rodada e do período de previsão;
10. Exibição do produto final.

## 🗺️ Produto gerado

O resultado é um mapa de **temperatura a 2 metros prevista pelo ECMWF**, com escala de cores personalizada e identificação da rodada e do período de previsão.
<img width="2961" height="3746" alt="image" src="https://github.com/user-attachments/assets/93eb1a74-12cd-4d99-8e08-083a30ee20c6" />

O mapa foi configurado para abranger a América do Sul e apresentar as temperaturas em graus Celsius.

## 📁 Arquivo

`Temp2mECMWF.ipynb`

O notebook contém o código utilizado para processar os dados e gerar o produto meteorológico.

## 👨‍💻 Autor

**Vitor Castilho**

Meteorologista | Mestrando em Meteorologia pela UFPEL

Este projeto faz parte de uma coleção de scripts desenvolvidos para análise, previsão e visualização de dados meteorológicos utilizando Python.
