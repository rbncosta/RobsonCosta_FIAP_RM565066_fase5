# 🌱 FarmTech Solutions — Fase 5 (FIAP)

## 👤 Integrante
- **Nome:** Robson Costa  
- **RM:** 565066  
- **Curso:** Inteligência Artificial – FIAP  
- **Fase:** 5  

---

## 📌 Introdução
Este repositório contém a entrega da **Fase 5** do curso de Inteligência Artificial da FIAP.  
O projeto foi desenvolvido para a **FarmTech Solutions**, empresa que presta serviços de **IA aplicada ao agronegócio**.  

O desafio consiste em analisar uma base de dados com informações de **condições de solo e clima**, visando:  
1. Prever o **rendimento das safras** (modelos de regressão supervisionada).  
2. Explorar a **tendência de produtividade** com técnicas de aprendizado não supervisionado (clusterização).  
3. Identificar **outliers** e possíveis cenários discrepantes.  
4. Realizar a estimativa de custos de infraestrutura em **nuvem AWS** para hospedar a solução.  

---

## 📂 Estrutura do Repositório
- 📓 **`RobsonCosta_rm565066_pbl_fase4.ipynb`** → Notebook Jupyter **executado**, contendo:
  - Análise Exploratória de Dados (EDA)  
  - Clusterização (KMeans + PCA)  
  - Detecção de Outliers (Isolation Forest)  
  - Cinco modelos de regressão supervisionada  
  - Validação cruzada e hold-out  
  - Diagnósticos: resíduos e importância das variáveis  

- 📄 **`README.md`** → Este documento introdutório, com explicação geral e instruções.  

- 📦 **`requirements.txt`** → Dependências necessárias para rodar o notebook localmente.  

- 🖼️ **`assets/aws_costs.png`** → Gráfico comparativo dos custos AWS (N. Virgínia x São Paulo).  

---

## ▶️ Demonstração em Vídeo - Notebook
O vídeo explicativo, com até 5 minutos de duração, demonstra a execução do notebook, os principais resultados obtidos e a justificativa das escolhas de modelos.

🔗 [Clique aqui para assistir ao vídeo no YouTube](COLE_AQUI_SEU_LINK)

## ▶️ Demonstração em Vídeo - Estimativa AWS
O vídeo explicativo, com até 5 minutos de duração, demonstra a execução da estimativa de custos na AWS.

🔗 [Clique aqui para assistir ao vídeo no YouTube](COLE_AQUI_SEU_LINK)

---

## 🚀 Como Executar
### Opção 1 — Google Colab
1. Faça o upload do arquivo `RobsonCosta_rm565066_pbl_fase4.ipynb` no Colab.  
2. Faça upload do dataset `crop_yield.csv` na mesma pasta.  
3. Execute todas as células em ordem.  

### Opção 2 — Local (Jupyter Notebook ou VSCode)
1. Clone este repositório:  
   ```bash
   git clone https://github.com/SEU_USUARIO/farmtech-fiap-fase5.git
   cd farmtech-fiap-fase5
   ```
2. Instale as dependências:  
   ```bash
   pip install -r requirements.txt
   ```
3. Coloque o arquivo `crop_yield.csv` no diretório raiz.  
4. Abra o notebook em Jupyter/VSCode e execute as células.  

---

## 📊 Entregáveis
### Entrega 1 — Machine Learning
- Notebook Jupyter (`.ipynb`) executado e comentado.  
- Relatório em Markdown dentro do notebook.  
- Análise de EDA, clusterização, outliers e predição com 5 modelos.  
- Métricas de desempenho + diagnósticos finais.  
- Vídeo demonstrativo (até 5 minutos).  

### Entrega 2 — Computação em Nuvem (AWS)
Foi realizada uma simulação de custos na **AWS Pricing Calculator** para estimar os gastos mensais ao hospedar a solução de Machine Learning em nuvem com a seguinte configuração:  

- 2 CPUs  
- 1 GiB de memória  
- Até 5 Gigabit de rede  
- 50 GB de armazenamento  

#### 💲 Resultados
- **N. Virgínia (us-east-1):** ~US$ 11,59/mês  
- **São Paulo (sa-east-1):** ~US$ 17,76/mês  

O gráfico `aws_ec2_vs_s3_comparacao.png` apresenta a comparação visual.  

#### 📊 Justificativa da Escolha
- **Custo:** N. Virgínia é cerca de ~40% mais barato.  
- **Latência:** São Paulo oferece menor latência para sensores e usuários brasileiros.  
- **Legalidade:** Há exigências legais (LGPD) que podem obrigar o armazenamento dos dados dentro do país.  

#### ✅ Decisão Final
Apesar do custo mais baixo em N. Virgínia, a opção mais adequada é hospedar em **São Paulo (sa-east-1)**, pois garante conformidade legal, menor latência e maior confiabilidade para os dados da fazenda.  

---

## ⚠️ Observações
- O repositório foi entregue com todas as células do notebook **executadas**, para garantir transparência na correção.  
- Não serão realizados novos commits após a data de entrega, conforme instruções da FIAP.  
- O dataset `crop_yield.csv` não foi incluído, pois já é disponibilizado no portal FIAP.  

---

📌 **Em resumo:** Este README conduz o avaliador até o **notebook Jupyter**, onde está todo o passo a passo detalhado e descrito em Markdown.  
