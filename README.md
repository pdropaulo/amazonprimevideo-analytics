# 🎬📊 Amazon Prime Video - Análise de Dados e Dashboard Tableau  

Este projeto foi desenvolvido com base no dataset **[Amazon Prime Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/amazon-prime-movies-and-tv-shows)** do Kaggle.  
O objetivo é explorar os dados da plataforma e apresentar insights relevantes através de um **dashboard interativo no Tableau**.  

---

## 📂 Sobre o Dataset  
O conjunto de dados contém informações sobre **filmes e séries disponíveis na Amazon Prime Video**, incluindo:  
- 🎥 Títulos de filmes e séries  
- 📅 Ano de lançamento  
- 🌍 País de origem  
- 🎭 Gênero  
- ⏱️ Duração  
- ⭐ Classificação etária  

---

## 📊 O Dashboard  
No Tableau, criei um painel interativo para responder perguntas como:  
- Quantos títulos foram lançados ao longo dos anos? 📈  
- Qual é a distribuição entre **filmes** e **séries**? 🎬📺  
- Quais os gêneros mais comuns? 🎭  
- Para quais faixas etárias são produzidos mais conteúdos? 🔞   

> 🔗 **[Link do Dashboard no Tableau](https://public.tableau.com/app/profile/pedro.andrade2292/viz/amazonprimevideo_17582246203010/Capa)**  

---

## 🚀 Tecnologias Utilizadas  
- [Tableau](https://www.tableau.com/) para criação do dashboard  
- [Python](https://www.python.org/) e [Pandas](https://pandas.pydata.org/) para tratamento de dados *(se aplicável)*  
- Dataset do [Kaggle](https://www.kaggle.com/datasets/shivamb/amazon-prime-movies-and-tv-shows)  

---

## 📸 Prévias do Dashboard  
1. Capa inicial:  
<img width="759" height="718" alt="amazon capa (1)" src="https://github.com/user-attachments/assets/50a3cf49-53f0-4a25-b4fa-164fe42ea057" />

2. Painel criado:  
<img width="760" height="723" alt="IMG_20250918_165713 (1)" src="https://github.com/user-attachments/assets/99df3f85-0d83-4c3e-93a0-b7b17499d733" />

### **Considerações:** o painel foi simples, apenas para treinar técnicas de visualização e testar os resultados;
Em relação às categorias (ratings) de classificação indicativa, o sistema norte-americano (padrão deste dataset) foi adaptado para o padrão brasileiro, tentando driblar qualquer tipo de inconsistência, a partir de um estudo prévio de como o sistema estadunidense é usado. 
Também foram adaptadas imagens às formas (shapes) para um gráfico de barras mais interativo e comunicativo com o usuário.

---

## 🧰 Procedimento
O procedimento teve como etapas a extração dos dados e suas transformações necessárias.
1. A fim de que os dados de classificação indicativa utilizassem o sistema brasileiro, adaptação do atributo ` Ratings ` foi usada a partir de grupos, conforme:
<img width="209" height="213" alt="sheet group" src="https://github.com/user-attachments/assets/bd58c2b7-b00d-4d0a-8805-6e9872c48ca5" />
<img width="413" height="430" alt="group detailed" src="https://github.com/user-attachments/assets/6dd15a7b-50da-4ef6-8003-cbce3580cea5" />

2. Além disso, formas foram procuradas na internet e colocadas no repositório tableau para serem usadas em um gráfico de barras, tendo a interação com o usuária da forma adequada, caso a ordem das barras seja reordenada pelo autor.
<img width="457" height="366" alt="rating sheet brazilian " src="https://github.com/user-attachments/assets/a9623501-a7ac-47c3-a0c8-a73a6741bb98" />

3. Uma capa para o dashboard foi criada, e um pequeno "controle" de acesso foi produzido a partir do Canvas:
<img width="1584" height="396" alt="Painel títulos do catálogo Amazon_20250918_161008_0000" src="https://github.com/user-attachments/assets/26f90205-8900-41a2-abdc-5e4315c139b2" />


---

## 📌 Conclusões  
A análise dos dados da Amazon Prime Video permite identificar padrões de lançamentos, popularidade de gêneros e distribuição da classifição indicativa dos filmes. Também seria possível extrair mais informações dessa base, mas ela dispõe de poucos atributos, e os processos de transformação trouxeram algumas inconsitências.  
Esse tipo de visualização pode auxiliar em **estratégias de marketing**, **negócios de streaming** e no entendimento do catálogo disponível.  

---

## 📬 Contato  
Caso queira trocar uma ideia sobre dados, BI ou Tableau, entre em contato:  

- 💼 LinkedIn: [Pedro Andrade](https://www.linkedin.com/in/pdropaulora)  
- 📧 E-mail: [contato gmail](p.paulo.pp08@gmail.com)  
- 🐙 GitHub: [GitHub](https://www.github.com/pdropaulo)  

---
