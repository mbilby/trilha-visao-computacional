# Nexvisual — Trilha de Visão Computacional

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mbilby/trilha-visao-computacional)
[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.x-EE4C2C?logo=pytorch&logoColor=white)](https://pytorch.org/)

Trilha prática de **Visão Computacional** do ecossistema Nexvisual. Do fundamento numérico à aplicação industrial — notebooks executáveis no Google Colab ou localmente, com foco em ferramentas adotadas no mercado: **OpenCV**, **PyTorch**, **Ultralytics (YOLO)**, **Hugging Face** e **CLIP**.

---

## Sumário

- [Visão geral](#visão-geral)
- [Estrutura do repositório](#estrutura-do-repositório)
- [Currículo](#currículo)
- [Stack tecnológica](#stack-tecnológica)
- [Como começar](#como-começar)
- [Mapeamento de nomes antigos](#mapeamento-de-nomes-antigos)
- [Contribuindo](#contribuindo)

---

## Visão geral

Esta trilha cobre cinco eixos progressivos:

| Módulo | Foco | Competência ao final |
|--------|------|----------------------|
| **M1** | Fundamentos | Arrays, visualização e processamento básico de imagens |
| **M2** | Visão clássica & DL introdutório | Features, modelos pré-treinados e transfer learning |
| **M3** | Deep learning aplicado | Fine-tuning, detecção de objetos e segmentação semântica |
| **M4** | Multimodal | Embeddings visão-linguagem com CLIP |
| **M5** | Aplicações industriais | Inspeção, OCR e vigilância com fine-tuning |

Cada notebook segue um fluxo consistente: **instalação → conceito → prática → próximos passos → atividade complementar**.

---

## Estrutura do repositório

```
trilha-visao-computacional/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── notebooks/
│   ├── 01-fundamentos/
│   │   ├── 01-numpy-arrays.ipynb
│   │   ├── 02-visualizacao-imagens.ipynb
│   │   └── 03-introducao-opencv.ipynb
│   │
│   ├── 02-visao-classica/
│   │   ├── 01-deteccao-caracteristicas.ipynb
│   │   └── 02-modelos-pre-treinados.ipynb
│   │
│   ├── 03-segmentacao/
│   │   ├── 01-transfer-learning-refinamento.ipynb
│   │   ├── 02-deteccao-objetos.ipynb
│   │   └── 03-segmentacao-semantica.ipynb
│   │
│   ├── 04-multimodal/
│   │   └── 01-fundamentos-clip.ipynb
│   │
│   └── 05-aplicacoes-industria/
│       ├── 01-inspecao-manufatura.ipynb
│       ├── 02-reconhecimento-texto-ocr.ipynb
│       └── 03-sistema-vigilancia.ipynb
│
├── assets/samples/          # imagens de exemplo versionadas
└── data/                    # datasets locais (gitignored)
```

Pastas numeradas indicam a **ordem de estudo**. Datasets pesados ficam em `data/` e são baixados em runtime pelos notebooks.

---

## Currículo

### M1 — Fundamentos

| Arquivo | Tópico | Colab |
|---------|--------|-------|
| `01-numpy-arrays.ipynb` | Manipulação de arrays com NumPy | [▶️ Abrir](https://colab.research.google.com/github/mbilby/trilha-visao-computacional/blob/main/notebooks/01-fundamentos/01-numpy-arrays.ipynb) |
| `02-visualizacao-imagens.ipynb` | Visualização de imagens com Matplotlib | [▶️ Abrir](https://colab.research.google.com/github/mbilby/trilha-visao-computacional/blob/main/notebooks/01-fundamentos/02-visualizacao-imagens.ipynb) |
| `03-introducao-opencv.ipynb` | Introdução ao OpenCV | [▶️ Abrir](https://colab.research.google.com/github/mbilby/trilha-visao-computacional/blob/main/notebooks/01-fundamentos/03-introducao-opencv.ipynb) |

### M2 — Visão clássica e modelos pré-treinados

| Arquivo | Tópico | Colab |
|---------|--------|-------|
| `01-deteccao-caracteristicas.ipynb` | Detecção e extração de características | [▶️ Abrir](https://colab.research.google.com/github/mbilby/trilha-visao-computacional/blob/main/notebooks/02-visao-classica/01-deteccao-caracteristicas.ipynb) |
| `02-modelos-pre-treinados.ipynb` | Modelos pré-treinados com PyTorch | [▶️ Abrir](https://colab.research.google.com/github/mbilby/trilha-visao-computacional/blob/main/notebooks/02-visao-classica/02-modelos-pre-treinados.ipynb) |

### M3 — Deep learning aplicado

| Arquivo | Tópico | Colab |
|---------|--------|-------|
| `01-transfer-learning-refinamento.ipynb` | Transfer learning e refinamento com redes pré-treinadas | [▶️ Abrir](https://colab.research.google.com/github/mbilby/trilha-visao-computacional/blob/main/notebooks/03-segmentacao/01-transfer-learning-refinamento.ipynb) |
| `02-deteccao-objetos.ipynb` | Detecção de objetos com Ultralytics (YOLO) | [▶️ Abrir](https://colab.research.google.com/github/mbilby/trilha-visao-computacional/blob/main/notebooks/03-segmentacao/02-deteccao-objetos.ipynb) |
| `03-segmentacao-semantica.ipynb` | Segmentação semântica (Ultralytics) | [▶️ Abrir](https://colab.research.google.com/github/mbilby/trilha-visao-computacional/blob/main/notebooks/03-segmentacao/03-segmentacao-semantica.ipynb) |

### M4 — Modelos multimodais

| Arquivo | Tópico | Colab |
|---------|--------|-------|
| `01-fundamentos-clip.ipynb` | Fundamentos de modelos multimodais (CLIP) | [▶️ Abrir](https://colab.research.google.com/github/mbilby/trilha-visao-computacional/blob/main/notebooks/04-multimodal/01-fundamentos-clip.ipynb) |

### M5 — Aplicações industriais

| Arquivo | Tópico | Colab |
|---------|--------|-------|
| `01-inspecao-manufatura.ipynb` | Inspeção visual em esteira de manufatura | [▶️ Abrir](https://colab.research.google.com/github/mbilby/trilha-visao-computacional/blob/main/notebooks/05-aplicacoes-industria/01-inspecao-manufatura.ipynb) |
| `02-reconhecimento-texto-ocr.ipynb` | Reconhecimento de texto (OCR) | [▶️ Abrir](https://colab.research.google.com/github/mbilby/trilha-visao-computacional/blob/main/notebooks/05-aplicacoes-industria/02-reconhecimento-texto-ocr.ipynb) |
| `03-sistema-vigilancia.ipynb` | Sistema de vigilância | [▶️ Abrir](https://colab.research.google.com/github/mbilby/trilha-visao-computacional/blob/main/notebooks/05-aplicacoes-industria/03-sistema-vigilancia.ipynb) |

---

## Stack tecnológica

| Biblioteca | Uso na trilha |
|------------|---------------|
| [NumPy](https://numpy.org/) | Representação e operação com arrays |
| [Matplotlib](https://matplotlib.org/) | Visualização de imagens |
| [OpenCV](https://opencv.org/) | Processamento clássico e features |
| [PyTorch](https://pytorch.org/) + [TorchVision](https://pytorch.org/vision/) | Deep learning, transfer learning e modelos pré-treinados |
| [Ultralytics](https://docs.ultralytics.com/) | YOLO — detecção, segmentação e fine-tuning |
| [Hugging Face Hub](https://huggingface.co/) | Download de datasets e modelos |
| [CLIP](https://github.com/openai/CLIP) | Embeddings multimodais visão + texto |

---

## Como começar

### Opção 1 — Google Colab (recomendado para iniciantes)

1. Escolha um notebook na [tabela do currículo](#currículo).
2. Clique em **Open in Colab** (badge no topo do notebook ou link da tabela).
3. Execute as células em ordem (`Runtime → Run all`).

> GPU gratuita no Colab acelera módulos M2–M5. Em `Runtime → Change runtime type`, selecione **T4 GPU**.

### Opção 2 — Jupyter local

```bash
git clone git@github.com:mbilby/trilha-visao-computacional.git
cd trilha-visao-computacional

python -m venv .venv
# Windows
.venv\Scripts\activate
# Linux/macOS
source .venv/bin/activate

pip install -U pip
pip install -r requirements.txt

jupyter lab notebooks/
```

**Pré-requisitos:** Python 3.10+, 8 GB+ RAM (16 GB recomendado para fine-tuning). GPU NVIDIA opcional, mas recomendada a partir do M2.

---

## Mapeamento de nomes antigos

Os notebooks foram renomeados e reorganizados. Use esta tabela se encontrar referências ao layout anterior:

| Nome antigo | Novo caminho |
|-------------|--------------|
| `M1A2_Manipulação_de_Arrays_com_Numpy.ipynb` | `notebooks/01-fundamentos/01-numpy-arrays.ipynb` |
| `M1A3_Visualização_de_Imagens.ipynb` | `notebooks/01-fundamentos/02-visualizacao-imagens.ipynb` |
| `M1A4_Introdução_ao_OpenCV.ipynb` | `notebooks/01-fundamentos/03-introducao-opencv.ipynb` |
| `M2A1_Detecção_e_Extração_de_Características.ipynb` | `notebooks/02-visao-classica/01-deteccao-caracteristicas.ipynb` |
| `M2A10_Modelos_Pré_Treinados.ipynb` | `notebooks/02-visao-classica/02-modelos-pre-treinados.ipynb` |
| `M3A3_Transfer_learning_e_Refinamento_com_Redes_Pré_treinadas_.ipynb` | `notebooks/03-segmentacao/01-transfer-learning-refinamento.ipynb` |
| `M3A5_Detecção_de_Objetos.ipynb` | `notebooks/03-segmentacao/02-deteccao-objetos.ipynb` |
| `M3A6_Segmentação_Semântica.ipynb` | `notebooks/03-segmentacao/03-segmentacao-semantica.ipynb` |
| `M4A5_Fundamentos_de_Modelos_Multimodais.ipynb` | `notebooks/04-multimodal/01-fundamentos-clip.ipynb` |
| `M5A1_Inspeção_Visual_de_Itens_em_Esteira_de_Manufatura.ipynb` | `notebooks/05-aplicacoes-industria/01-inspecao-manufatura.ipynb` |
| `M5A2_Reconhecimento_de_texto.ipynb` | `notebooks/05-aplicacoes-industria/02-reconhecimento-texto-ocr.ipynb` |
| `M5A4_Sistema_de_Vigilância.ipynb` | `notebooks/05-aplicacoes-industria/03-sistema-vigilancia.ipynb` |

---

## Contribuindo

Contribuições são bem-vindas: correções, novos exemplos, traduções ou melhorias de documentação.

1. Faça um fork do repositório.
2. Crie uma branch (`git checkout -b feat/minha-melhoria`).
3. Commit suas alterações.
4. Abra um Pull Request descrevendo o que mudou e por quê.

Ao adicionar notebooks, coloque-os na pasta do módulo correspondente e mantenha a estrutura: introdução, instalação, prática, próximos passos e atividade complementar.

---
