# 🐶🐱 Streamlit Pet Classifier

Este projeto foi **desenvolvido em aula da Pós-Graduação em Ciência de Dados** na matéria de **Machine Learning** e consiste em uma aplicação web criada com **Streamlit** que utiliza **Deep Learning (ResNet18)** para extração de características de imagem e um **classificador SVM** para identificar se a imagem enviada é de um **gato (Cat)** ou **cachorro (Dog)**.

---

## 🌐 Link para teste

A aplicação pode ser acessada no link abaixo:

🔗 https://cat-and-dog-classificator.streamlit.app/


---

## 🚀 Como funciona

O usuário faz upload de uma imagem de um pet e a aplicação retorna a classificação:

- ✅ Cat  
- ✅ Dog  

Tudo em tempo real pela interface web criada com **Streamlit**.

---

## 🛠️ Tecnologias utilizadas

- Python  
- Streamlit  
- PyTorch / Torchvision  
- Scikit-learn  
- Joblib  
- Numpy  
- Pillow (PIL)  
- Pandas  

---

## 🧠 Como é feita a classificação

1. O usuário envia uma imagem
2. A imagem é redimensionada e normalizada
3. A **ResNet18 (pré-treinada)** extrai as características
4. O modelo **SVM treinado** classifica:
   - `0` → Cat 🐱
   - `1` → Dog 🐶

---

