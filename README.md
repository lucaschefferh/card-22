# 🎭 Reconhecimento de Expressões Faciais - Card 22

## 📋 Descrição do Projeto
Sistema avançado de reconhecimento de expressões faciais implementado com **ensemble learning** para melhorar a robustez e acurácia das predições.

## 🎯 Objetivos
- Implementar técnicas avançadas de machine learning
- Comparar performance entre múltiplos modelos
- Aplicar ensemble learning (votação soft/hard)
- Analisar confiança e incerteza das predições

## 📁 Estrutura dos Arquivos

### Notebooks Principais
- `testes_pratica.ipynb` - **Projeto principal** com ensemble learning avançado
- `reconhecimento parte1_aula.ipynb` - Detecção básica em imagem única
- `reconhecimento parte2_aula.ipynb` - Treinamento e avaliação de modelo
- `reconhecimento video_aula.ipynb` - Aplicação em vídeo tempo real

## 🚀 Técnicas Implementadas

### 🤝 Ensemble Learning
- **Votação Soft**: Média das probabilidades de múltiplos modelos
- **Votação Hard**: Votação majoritária entre predições
- Carregamento automático de múltiplos modelos

### 📊 Análise Comparativa
- Avaliação de performance individual vs ensemble
- Métricas de acurácia, precisão, recall e F1-score
- Ranking automático dos modelos

### 🎯 Análise de Confiança
- Medição da confiança das predições
- Identificação de casos de baixa confiança (<0.6)
- Distribuição de incerteza

### 📈 Visualizações
- Gráficos comparativos de acurácia
- Matrizes de confusão
- Distribuição de confiança
- Análise soft vs hard voting

## 🛠️ Tecnologias Utilizadas
- **TensorFlow/Keras** - Deep Learning
- **OpenCV** - Processamento de imagens
- **scikit-learn** - Métricas e avaliação
- **matplotlib/seaborn** - Visualizações
- **NumPy** - Computação numérica

## 💡 Diferenciais Técnicos
- **Ensemble methods** aplicados corretamente
- **Análise de incerteza** para detectar predições duvidosas
- **Comparação quantitativa** rigorosa
- **Código modular** e reutilizável

## 🎓 Expressões Reconhecidas
1. Raiva
2. Nojo  
3. Medo
4. Feliz
5. Triste
6. Surpreso
7. Neutro

## 📊 Resultados
O ensemble learning demonstrou melhoria na robustez das predições, especialmente em casos de incerteza, validando a eficácia da abordagem implementada.

---
**Autor**: Lucas Scheffer  
**Projeto**: Card 22 - Lamia
