-# :point_right: Recursos para Detecção de Vídeos Gerados por IA

Uma lista selecionada de bancos de dados, artigos e códigos para pesquisa em Detecção de Vídeos Gerados por IA, ideal para projetos de TCC. Se você deseja adicionar materiais a esta lista, sinta-se à vontade para iniciar um *pull request*.

Estamos felizes em ver sua contribuição!

## Visão Geral dos Bancos de Dados

| Banco de Dados | Foco Principal | Escala (Aprox. Vídeos) | Característica Principal |
|---|---|---|---|
| FaceForensics++ | Manipulação Facial | 1k Reais / 5k Falsos | Benchmark fundamental para métodos específicos (FaceSwap, etc.) [1, 2] |
| DFDC | Manipulação Facial | 23k Reais / 104k Falsos | Desafio em larga escala "in-the-wild" com métodos não vistos [3, 2] |
| Celeb-DF (v2) | Manipulação Facial | 590 Reais / 5.6k Falsos | Falsificações de alta qualidade com menos artefatos visuais; desafiador [4, 2] |
| DeeperForensics-1.0 | Manipulação Facial | 50k Reais / 10k Falsos | Adiciona perturbações do mundo real (compressão, ruído) [5, 6] |
| FakeAVCeleb | Deepfake Audiovisual | 500 Reais / 19.5k Falsos | Banco de dados multimodal com áudio e vídeo manipulados [5, 7] |
| GenVidBench | AIGV Geral | ~34k Reais / ~109k Falsos | Benchmark moderno para T2V/I2V; teste entre geradores [8, 9] |
| DeepAction | AIGV Geral | ~2.6k Totais | Foco na detecção de artefatos em movimento humano sintético [10] |

## Bancos de Dados para Detecção de Manipulação Facial (Deepfakes)

| # | Nome do Banco de Dados | Título do Artigo & Link | Link do Banco de Dados |
|---|---|---|---|
| 1 | FaceForensics++ |(https://arxiv.org/abs/1901.08971) [11] | [Formulário de Acesso](https://www.google.com/search?q=https://docs.google.com/forms/d/e/1FAIpQLSdRRR3L5zAv6tQ_CKxmK4W96tAab_pfBu2EKAgQbeDVhmXagg/viewform) [11] |
| 2 | Celeb-DF (v2) |(https://arxiv.org/abs/1909.12962) [4] | [Página do Projeto](https://github.com/yuezunli/celeb-deepfakeforensics) [4] |
| 3 | DFDC |(https://arxiv.org/abs/2006.07397) [12] | [Página de Acesso](https://ai.meta.com/datasets/dfdc/) [3] |
| 4 | DeeperForensics-1.0 |(https://arxiv.org/abs/2001.03024) [6] | [Página do Projeto](https://github.com/EndlessSora/DeeperForensics-1.0) [6] |
| 5 | FakeAVCeleb |(https://arxiv.org/abs/2105.03003) [5] | [Página do Projeto](https://github.com/DASH-Lab/FakeAVCeleb) [7] |
| 6 | ForgeryNet |([[https://arxiv.org/abs/2103.00399](https://arxiv.org/abs/2103.00399)](https://openaccess.thecvf.com/content/CVPR2023/papers/Tan_Learning_on_Gradients_Generalized_Artifacts_Representation_for_GAN-Generated_Images_Detection_CVPR_2023_paper.pdf)) [5] |((https://github.com/Daisy-Zhang/Awesome-Deepfakes-Detection)) [2] |

## Bancos de Dados para Vídeos Gerados por IA em Geral (AIGV)

| # | Nome do Banco de Dados | Título do Artigo & Link | Link do Banco de Dados |
|---|---|---|---|
| 1 | GenVidBench |(https://arxiv.org/abs/2501.11340) [13] | [Página do Projeto](https://github.com/genvidbench/GenVidBench) [9] |
| 2 | DeepAction |(https://arxiv.org/abs/2412.00526) [10] | [Hugging Face](https://huggingface.co/datasets/faridlab/deepaction_v1) [10] |
| 3 | GenVideo |([https://arxiv.org/abs/2404.05633](https://arxiv.org/abs/2404.05633)) [14] | Mencionado em((https://github.com/chenhaoxing/Awesome-AI-Generated-Video-Detection)) [14] |
| 4 | IVY-FAKE |([https://arxiv.org/abs/2402.10959](https://arxiv.org/abs/2402.10959)) [14] | Mencionado em((https://github.com/chenhaoxing/Awesome-AI-Generated-Video-Detection)) [14] |

## Métodos de Detecção & Artigos

| # | Categoria | Título & Link | Link do Código |
|---|---|---|---|
| 1 | Survey |([https://arxiv.org/abs/2403.17881](https://arxiv.org/abs/2403.17881)) [15] | - |
| 2 | Survey |([https://arxiv.org/abs/2001.00179](https://arxiv.org/abs/2001.00179)) [12] | - |
| 3 | Artefatos Espaciais |(https://arxiv.org/abs/1912.13458) [16] | [Código](https://www.google.com/search?q=https://github.com/JStehouwer/FF-X-ray) |
| 4 | Análise de Frequência |((https://www.google.com/search?q=https://openaccess.thecvf.com/content/CVPR2021/html/Qian_Frequency-Aware_Discriminative_Feature_Learning_Supervised_by_Single-Center_Loss_for_CVPR_2021_paper.html)) [2] | - |
| 5 | Inconsistência Temporal |([https://arxiv.org/abs/1811.00661](https://arxiv.org/abs/1811.00661)) [16] | - |
| 6 | Sinais Biológicos |([https://arxiv.org/abs/1806.02877](https://arxiv.org/abs/1806.02877)) [17] | - |
| 7 | Espaçotemporal (Geral) |(https://openaccess.thecvf.com/content/ICCV2023/papers/Xu_TALL_Thumbnail_Layout_for_Deepfake_Video_Detection_ICCV_2023_paper.pdf) [2] | [Código](https://github.com/rainy-xu/TALL4Deepfake) [2] |
| 8 | Espaçotemporal (Geral) |([https://ieeexplore.ieee.org/document/10173099](https://ieeexplore.ieee.org/document/10173099)) [14] | - |
| 9 | AIGV Geral |(https://arxiv.org/abs/2404.05633) [14] | [Código](https://github.com/chenhaoxing/DeMamba) [14] |
| 10 | Audiovisual |(https://nips.cc/virtual/2024/poster/94610) [2] | [Código](https://github.com/Eleven4AI/SpeechForensics) [2] |

## Principais Códigos-Fonte Abertos

| # | Repositório | Descrição | Link |
|---|---|---|---|
| 1 | DFDC 1st Place Solution | Solução vencedora do Deepfake Detection Challenge. Um pipeline completo usando EfficientNets. [18] | [selimsef/dfdc_deepfake_challenge](https://github.com/selimsef/dfdc_deepfake_challenge) [18] |
| 2 | Spatiotemporal Models | Implementação em PyTorch de várias redes espaçotemporais (R3D, MC3, I3D) avaliadas no Celeb-DF. [19] |((https://github.com/oidelima/Deepfake-Detection)) [19] |
| 3 | GenVidBench Baselines | Código oficial para treinar e avaliar modelos de base no dataset GenVidBench para detecção geral de AIGV. [9] |((https://github.com/genvidbench/GenVidBench)) [9] |
| 4 | FaceForensics Baselines | Repositório oficial do dataset FaceForensics++, incluindo scripts para manipulação de dados e modelos de base. [1] | [ondyari/FaceForensics](https://github.com/ondyari/FaceForensics) [1] |
| 5 | Awesome Lists | Uma meta-lista de recursos selecionados. Um ótimo ponto de partida para encontrar mais artigos e códigos. |((https://github.com/Daisy-Zhang/Awesome-Deepfakes-Detection)) [2] |
| 6 | Awesome Lists | Outra lista abrangente cobrindo geração e detecção. |((https://github.com/qiqitao77/Awesome-Comprehensive-Deepfake-Detection)) [5] |

# Contato

:sunglasses: Se você quiser fazer contribuições, incluir seus trabalhos ou simplesmente discutir, sinta-se à vontade para me enviar um e-mail. :sunglasses:

:sparkling_heart: Se você achou esta coleção útil, por favor, dê uma estrela neste projeto! Obrigado! :sparkling_heart:
