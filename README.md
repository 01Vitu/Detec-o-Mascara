# Detec-o-Mascara
Sistema de Visão Computacional para detecção automática de máscaras faciais em imagens usando redes neurais convolucionais (CNN), com pré-processamento via OpenCV.
# 🧠 Detecção de Máscaras Faciais com Visão Computacional

Este projeto implementa um sistema de **classificação automática de rostos com e sem máscara facial** utilizando técnicas de **Visão Computacional** e uma **Rede Neural Convolucional (CNN)** treinada com imagens reais.

---

## 📌 Objetivo

Desenvolver uma aplicação que analisa imagens e detecta se as pessoas estão:

- 😷 Com máscara  
- 😐 Sem máscara  
- 😕 Com máscara incorreta *(caso aplicável)*

---

## 🧪 Técnicas Utilizadas

- **OpenCV** para manipulação e leitura de imagens
- **Extração de rostos** a partir de anotações `.xml` (PASCAL VOC)
- **CNN (Rede Neural Convolucional)** com Keras
- **Pré-processamento:** recorte facial, redimensionamento, normalização
- **Visualização dos resultados:** matplotlib (com grade, título colorido e resolução HD)

---

## 🛠️ Ferramentas e Bibliotecas

- Python 3.x
- [OpenCV](https://opencv.org/)
- [TensorFlow / Keras](https://www.tensorflow.org/)
- Matplotlib
- NumPy
- Scikit-learn

### Instalação rápida:

```bash
pip install -r requirements.txt

