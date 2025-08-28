# Lab 6: Visualizações Interativas de Chuva - Vitória Pimentel

## Descrição do Laboratório

Este laboratório consiste na criação de **duas visualizações interativas** usando a biblioteca **Apache ECharts** em arquivos HTML.  
Os dados representam a **distribuição pluviométrica da Fazenda Carnaúba, Taperoá - PB**, entre 2013 e 2025 (parcial), com foco nos anos de **2015 a 2024**.

---

## Arquivos

### 1. Lab6-VitoriaPimentel-Projeto1.html
- **História contada:** Volume de chuva acumulada por ano.
- **Dados usados:** `ano` e `total_chuva_mm` (2015–2024).
- **Visualização:** Gráfico de barras, com tooltip exibindo o total em mm e dataZoom para ampliar/reduzir a série.
- **Objetivo:** Permitir ao público geral entender a quantidade de chuva anual no período.

### 2. Lab6-VitoriaPimentel-Projeto2.html
- **História contada:** Variação da chuva acumulada em relação ao ano anterior.
- **Dados usados:** diferença ano a ano do `total_chuva_mm` (2015–2024).
- **Visualização:** Gráfico de barras divergentes, cores indicam aumento (**azul**) ou diminuição (**vermelho**) de chuva em relação ao ano anterior.
- **Elementos interativos:** Tooltip, dataZoom, visualMap para cores.
- **Objetivo:** Destacar anos mais e menos chuvosos em relação ao ano anterior.

---

## Observações

- Os dados estão **embutidos** nos arquivos HTML, não é necessário carregar CSV externo.
- Ambos os gráficos foram desenvolvidos visando **clareza visual, interatividade e estética**, conforme as diretrizes do laboratório.
- O **Projeto 1** foca em volume total, enquanto o **Projeto 2** enfatiza variações ano a ano.
