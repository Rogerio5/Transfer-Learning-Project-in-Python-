# Transfer-Learning-Project-in-Python-

# 🐱🐶 Classificação de Gatos e Cachorros com MobileNetV2 + Grad‑CAM

![Capa do Projeto](assets/capa_projeto.png)

---

## 🏅 Badges

- 📦 Tamanho do repositório / Repository Size:  
  ![GitHub repo size](https://img.shields.io/github/repo-size/seuusuario/classificacao_gatos_cachorros)

- 📄 Licença do projeto / Project License:  
  ![GitHub license](https://img.shields.io/github/license/seuusuario/classificacao_gatos_cachorros)

- 📊 Acurácia do modelo / Model Accuracy:  
  ![Accuracy](https://img.shields.io/badge/accuracy-95%25-brightgreen)

---

## 📋 Índice / Table of Contents

- [Descrição / Description](#descrição--description)
- [Status / Status](#status--status)
- [Funcionalidades / Features](#funcionalidades--features)
- [Estrutura do Projeto / Project Structure](#estrutura-do-projeto--project-structure)
- [Tecnologias / Technologies](#tecnologias--technologies)
- [Instalação / Installation](#instalação--installation)
- [Dataset / Dataset](#dataset)
- [Execução / Run](#execução--run)
- [Resultados e Visualizações / Results--visuals](#resultados-e-visualizações--results--visuals)
- [Possíveis Melhorias Futuras / Future Improvements](#possíveis-melhorias-futuras--future-improvements)
- [Desenvolvedor / Developer](#desenvolvedor--developer)
- [Licença / License](#licença--license)
- [Conclusão / Conclusion](#conclusão--conclusion)

---

## 📖 Descrição / Description

**PT:**  
Este projeto treina uma rede neural baseada no **MobileNetV2** para classificar imagens de gatos e cachorros utilizando o dataset **Cats vs Dogs**.  
Inclui:
- **Fine‑tuning** para alta precisão
- Exportação para **TensorFlow Lite**
- **Grad‑CAM** para interpretar previsões

**EN:**  
A deep learning project using **MobileNetV2** to classify cat and dog images from the **Cats vs Dogs** dataset.  
Includes:
- **Fine‑tuning** for high accuracy
- Export to **TensorFlow Lite**
- **Grad‑CAM** for interpretability

---

## 🚧 Status / Status

✅ **Concluído e pronto para uso** / **Completed and ready to use**

---

## ⚙️ Funcionalidades / Features

| 🧩 Funcionalidade (PT)                  | 💡 Description (EN)                       |
|-----------------------------------------|-------------------------------------------|
| 🖼️ Classificação de imagens             | 🖼️ Image classification                  |
| 🔄 Data augmentation                    | 🔄 Augmentation to improve generalization |
| 🎯 Fine‑tuning                          | 🎯 Increased accuracy via fine‑tuning     |
| 📊 Métricas e gráficos                   | 📊 Metrics & charts visualization        |
| 🔥 Grad‑CAM                             | 🔥 Visual heatmaps for model focus        |
| 📱 Exportação para TensorFlow Lite      | 📱 Mobile-ready lightweight model         |

---


---

## 📥 Dataset

O dataset **Cats vs Dogs** é baixado automaticamente pelo `tensorflow_datasets`.  
Não é necessário realizar o download manualmente.

---

## ▶️ Execução / Run

bash
python script_treino.py

---

## 🧰 Tecnologias / Technologies

- Python 3.10+
- TensorFlow (Keras API)
- TensorFlow Datasets
- NumPy
- Pandas
- Matplotlib
- Seaborn
- OpenCV

<p>
  <img align="left" alt="Python" width="30px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg"/>
  <img align="left" alt="TensorFlow" width="30px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/tensorflow/tensorflow-original.svg"/>
  <img align="left" alt="Pandas" width="30px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pandas/pandas-original.svg"/>
  <img align="left" alt="Numpy" width="30px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/numpy/numpy-original.svg"/>
  <img align="left" alt="Git" width="30px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg"/>
  <img align="left" alt="GitHub" width="30px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/github/github-original.svg"/>
</p>

<br clear="all"/>

---

## 📦 Instalação / Installation

---

bash
git clone https://github.com/seuusuario/classificacao_gatos_cachorros.git
cd classificacao_gatos_cachorros
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
pip install -r requirements.txt

 ---
 ## 👨‍💻 Pessoa Desenvolvedor do Projeto / Project Developer

- [Rogerio](https://github.com/Rogerio5)

---

## 📜 Licença / License

Este projeto está sob licença MIT. Para mais detalhes, veja o arquivo `LICENSE`.

This project is under the MIT license. For more details, see the `LICENSE` file.

---

🏁 Conclusão / Conclusion

Um projeto de visão computacional que entrega alta acurácia, interpretabilidade com Grad‑CAM e portabilidade para dispositivos móveis.
