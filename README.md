# calibracao_brilho_estrelas
O objetivo é simular um conjunto de 1.000 observações de brilho para esta estrela, realizar uma análise de inferência para estimar se a média observada condiz com o valor teórico esperado e identificar possíveis anomalias nos dados captados.

## 👥 Autor
- **Aluno**: Eduardo Nascimento do Vale
- **Professores**: Sérgio Monteiro, D.Sc. e Manuel Martins, D.Sc.

## 📊 Metodologia
1. **Simulação de Dados**: Geração de 1.000 amostras usando distribuição Normal (μ=15.5, σ=0.8)
2. **Análise Visual**: Histograma com curva de densidade e Q-Q Plot
3. **Inferência Estatística**: Intervalo de Confiança (95%) e Teste t
4. **Detecção de Outliers**: Boxplot e regra dos 3σ

## 📈 Principais Resultados
- **Média amostral observada**: 15.4793
- **Intervalo de Confiança (95%)**: [15.4296, 15.5291]
- **Teste t (p-valor)**: 0.415503
- **Outliers detectados**: 
  - Método do Boxplot (IQR): 11 outliers (1.1% dos dados)
  - Regra dos 3σ: 4 outliers (0.4% dos dados)

## 💡 Conclusão
A análise permitiu validar estatisticamente as observações da estrela, identificando possíveis falhas instrumentais através da detecção de outliers.

## 🛠️ Tecnologias Utilizadas
- R Language
- Google Colab
- Pacotes: ggplot2, dplyr, gridExtra

## 📁 Estrutura do Repositório
- `analise_estrelas_variaveis.ipynb`: Notebook completo com a implementação
- `README.md`: Este arquivo
