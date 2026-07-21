# Projeto 21 - Detecção de Objetos Cotidianos com YOLOv8

##  Sobre o Projeto

Este projeto foi desenvolvido como atividade da disciplina de Inteligência Artificial do curso de **Análise e Desenvolvimento de Sistemas** do **Instituto Federal do Piauí (IFPI) – Campus Corrente**.

O objetivo é implementar um sistema de **detecção de múltiplos objetos** utilizando o modelo **YOLOv8** e o dataset **COCO128**, realizando experimentos com diferentes configurações de **Confidence Threshold** e **Intersection over Union (IoU)** para analisar seu impacto no desempenho do modelo.

---

##  Objetivos

- Compreender a arquitetura YOLOv8;
- Trabalhar com diferentes classes do dataset COCO;
- Avaliar diferentes limiares de confiança;
- Compreender o funcionamento do Non-Maximum Suppression (NMS);
- Analisar o equilíbrio entre precisão e velocidade do modelo.

---

##  Tecnologias Utilizadas

- Python 3
- Google Colab
- YOLOv8
- Ultralytics
- OpenCV
- Matplotlib
- NumPy
- Dataset COCO128

---

##  Dataset

Foi utilizada a versão **COCO128**, derivada do dataset COCO (Common Objects in Context), contendo imagens anotadas de aproximadamente 80 classes diferentes.

---

##  Experimentos Realizados

Foram comparadas três configurações diferentes:

| Experimento | Confidence | IoU |
|-------------|-----------:|----:|
| 1 | 0.25 | 0.45 |
| 2 | 0.50 | 0.45 |
| 3 | 0.50 | 0.70 |

---

##  Métricas Avaliadas

O desempenho do modelo foi analisado utilizando as seguintes métricas:

- mAP@0.5
- mAP@0.5:0.95
- Precisão
- Recall
- F1-score
- FPS (Frames por Segundo)

---

##  Como Executar

### 1. Clone o repositório

```bash
https://github.com/kleslyrocha-gif/PROJETO-IA-YOLOv8.git
```

### 2. Acesse a pasta

```bash
cd SEU-REPOSITORIO
```

### 3. Abra o notebook

Abra o arquivo `.ipynb` no **Google Colab**.

### 4. Instale as dependências

```python
!pip install ultralytics
```

ou

```bash
pip install ultralytics
```

### 5. Execute todas as células

Execute o notebook na ordem em que as células foram organizadas.

---

##  Resultados

O projeto realiza a detecção automática de objetos presentes nas imagens do dataset COCO128 utilizando o modelo YOLOv8, exibindo:

- Bounding Boxes;
- Classe detectada;
- Nível de confiança;
- Tempo de processamento.

Também são geradas métricas de avaliação para comparação entre diferentes configurações do modelo.

---

## Estrutura do Projeto

```
ProjetoIA.ipynb
README.md
images/
results/
```

---

## Autor

**Klesly de Souza Rocha**

Curso de Análise e Desenvolvimento de Sistemas

Instituto Federal do Piauí (IFPI) – Campus Corrente

---

##  Referências

- Ultralytics YOLO Documentation
- Microsoft COCO Dataset
- Google Colaboratory
