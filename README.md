<p align="center">
  <img src="https://img.shields.io/badge/IA-Generativa-7b1fa2?style=for-the-badge">
  <img src="https://img.shields.io/badge/Modelo-Stable_Diffusion_1.5-3949ab?style=for-the-badge">
  <img src="https://img.shields.io/badge/Execução-GPU_T4-455a64?style=for-the-badge">
  <img src="https://img.shields.io/badge/Tradução_PT→EN-Automática-00897b?style=for-the-badge">
  <img src="https://img.shields.io/badge/Projeto-Em_Andamento-f57f17?style=for-the-badge">
  <img src="https://img.shields.io/badge/Open_Source-100%25-2e7d32?style=for-the-badge">
</p>

# 🎨 Projeto de IA Generativa de Imagem (Stable Diffusion & DPMSolver)
Repositório para meu experimento, pipeline e protótipos em **IA Generativa**, com foco em geração de imagem, usando tecnologias **open source**.
Este laboratório reúne meus estudos, ensaios e técnicas práticas da certificação em IA
---

Pipeline completo para gerar imagens a partir de prompts, usando **Stable Diffusion 1.5 e DPMSolver**.

### 🧠 Ferramentas utilizadas
- Google Colab + GPU T4
- Conexão com modelos de difusão: Stable Diffusion 1.5 e DPMSolver
- Pré-processamento e pós-processamento
- Tradução PT → EN automática para melhorar prompts
- Integração com Google Drive
- Ingração Google Colab
- Integração GitHub

### 💡 O que esse pipeline permite
- Criar imagens sob demanda
- Integrar com Power BI para cenários visuais
- Criar experiências multimodais (texto → imagem → ação)
- Conectar em intranets para fluxos institucionais
- Criar assistentes visuais para jornadas de CX/CS

📁 V1 do projeto  
👉 [Acessar versão 1](https://iajesse.netlify.app/)

---

# 🧭 Visão geral do experimento

- Estudar e criar uma IA generativa na prática
- Construir pipelines reais  
- Documentar aprendizados  
- Criar protótipos funcionais  
- Explorar multimodalidade (imagem, texto)  
- Aplicar IA em cenários de CX, educação, acessibilidade e comunicação global, Discoverys de produtos, Cenários

---

# 🛠️ Tecnologias principais

- Python  
- PyTorch  
- Stable Diffusion  
- DPMSolver
- XTTS v2  
- LatentSync  
- InsightFace  
- Kornia  
- Deep Translator  
- FFmpeg  
- Google Colab
- JavaScript/CSS/HTML (frontend)  
- Git e GitHub

---

## 🗺️ Roadmap

- [ ] Criar API Backend para conectar o frontend a modelos generativos
- [ ] Adicionar suporte multiplo (SDXL, Flux, etc)
- [ ] Criar interface web simples (HTML/JS)
- [ ] Criar versão multimodal (texto → imagem → ação)
- [ ] Criar galeria de imagens geradas
- [ ] Implementar histórico de prompts
- [ ] Adicionar suporte a LoRAs
- [ ] Criar pipeline de upscaling automático
- [ ] Criar documentação técnica detalhada
- [ ] Deploy do frontend via Netlify

# 📌 Estrutura do repositório

Generative-AI-Lab/
│
├── README.md
├── notebooks/
│   └── sd15_pipeline.ipynb
├── samples/
│   ├── prompts/
│   └── generated/
├── pipeline/
│   ├── stable-diffusion/
│   └── utils/
└── assets/
    └── thumbnails/
