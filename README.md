# Dashboard de Análise de Salários na Área de Dados

## 📊 Sobre o Projeto
Este dashboard foi desenvolvido durante a Imersão de Dados com Python da Alura. O projeto analisa dados salariais de profissionais da área de dados, oferecendo visualizações interativas e insights importantes sobre o mercado de trabalho.

## 🛠️ Tecnologias Utilizadas
- **Streamlit**: Framework para criação de aplicações web com Python : https://dadospython-5ovzfydzj7mkwu769le2gj.streamlit.app
- **Pandas**: Manipulação e análise de dados
- **Plotly Express**: Criação de gráficos interativos

## 🔍 Funcionalidades

### Filtros Interativos
O dashboard possui uma barra lateral com os seguintes filtros:
- Ano
- Senioridade
- Tipo de Contrato
- Tamanho da Empresa

### Métricas Principais (KPIs)
Exibe informações cruciais como:
- Salário médio
- Salário máximo
- Total de registros
- Cargo mais frequente

### Visualizações
1. **Top 10 Cargos por Salário Médio**
   - Gráfico de barras horizontal
   - Ordenado por média salarial
   - Cores em tons de verde mar

2. **Distribuição de Salários Anuais**
   - Histograma
   - Mostra a frequência das faixas salariais
   - Utiliza tons de verde médio mar

3. **Proporção dos Tipos de Trabalho**
   - Gráfico de rosca (donut chart)
   - Visualização da distribuição entre trabalho remoto e presencial
   - Combinação de verde claro e verde mar

4. **Mapa de Salários de Cientistas de Dados**
   - Mapa coroplético mundial
   - Média salarial por país
   - Escala de cores em gradiente de verde

## 📈 Dados
O dataset utilizado contém informações sobre:
- Salários em USD
- Localização das empresas
- Modalidade de trabalho (remoto/presencial)
- Nível de senioridade
- Tipos de contrato
- Tamanho das empresas

## 🚀 Como Executar

### Requisitos
```
pandas==2.2.3
streamlit==1.44.1
plotly==5.24.1
```

### Execução Local
1. Clone o repositório
2. Instale as dependências:
   ```
   pip install -r requirements.txt
   ```
3. Execute o aplicativo:
   ```
   streamlit run Application.py
   ```

## 💡 Insights Principais
- Visualização clara da distribuição salarial no mercado de dados
- Comparação entre diferentes cargos e suas remunerações
- Análise da proporção entre trabalho remoto e presencial
- Distribuição geográfica dos salários de Cientistas de Dados

## 🎯 Objetivos do Dashboard
- Fornecer uma visão abrangente do mercado de trabalho em dados
- Permitir análises comparativas entre diferentes cargos
- Facilitar a compreensão das tendências salariais
- Auxiliar profissionais e empresas em decisões relacionadas a carreira e contratações

## ✨ Características Especiais
- Interface intuitiva e responsiva
- Filtros interativos para análise personalizada
- Visualizações dinâmicas e interativas
- Paleta de cores em tons de verde para melhor experiência visual
- Dados atualizados do mercado de trabalho em dados
