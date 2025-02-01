# 合成データハンズオン

Susumu Ota 2025-02-02

## ハンズオン資料

- [Persona-Hub によるマルチターン指示データ合成](notebooks/synth_persona.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/susumuota/synthetic-data-hands-on/blob/main/notebooks/synth_persona.ipynb)
- [LLM-as-a-Judge と Iterative DPO によるプリファレンスデータ合成](notebooks/synth_llm_judge.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/susumuota/synthetic-data-hands-on/blob/main/notebooks/synth_llm_judge.ipynb)

## コンパス イベントページ

- [Persona-Hub による SFT データ合成と LLM as a judge による DPO データ合成](https://matsuolab-community.connpass.com/event/343298/)

## 参考文献

- Xin Chan et al., "Scaling Synthetic Data Creation with 1,000,000,000 Personas”, arXiv preprint arXiv:2406.20094v1, 2024. https://arxiv.org/abs/2406.20094
- Hao Chen et al., "On the Diversity of Synthetic Data and its Impact on Training Large Language Models", arXiv preprint arXiv:2410.15226v2, 2024. https://arxiv.org/abs/2410.15226
- Guilherme Penedo et al., "The FineWeb Datasets: Decanting the Web for the Finest Text Data at Scale", arXiv preprint arXiv:2406.17557v2, 2024. https://arxiv.org/abs/2406.17557
- Lianmin Zheng et al., "Judging LLM-as-a-Judge with MT-Bench and Chatbot Arena", NeurIPS 2023, 2023. https://proceedings.neurips.cc/paper_files/paper/2023/hash/91f18a1287b398d378ef22505bf41832-Abstract-Datasets_and_Benchmarks.html
- Jiawei Gu et al., "A Survey on LLM-as-a-Judge", arXiv preprint arXiv:2411.15594v3, 2024. https://arxiv.org/abs/2411.15594
- Rafael Rafailov et al., "Direct Preference Optimization: Your Language Model is Secretly a Reward Model", NeurIPS 2023, 2023. https://papers.nips.cc/paper_files/paper/2023/hash/a85b405ed65c6477a4fe8302b5e06ce7-Abstract-Conference.html
- Hanze Dong et al., "RLHF Workflow: From Reward Modeling to Online RLHF", arXiv preprint arXiv:2405.07863v3, 2024. https://arxiv.org/abs/2405.07863
- Lozhkov et al., "FineWeb-Edu: the Finest Collection of Educational Content", アクセス日: 2025-01-28, https://huggingface.co/datasets/HuggingFaceFW/fineweb-edu
- Argilla, "FinePersonas", アクセス日: 2025-01-28, https://huggingface.co/datasets/argilla/FinePersonas-v0.1
- Kan Hatakeyama, "大規模言語モデルを開発するにあたっての事前・事後学習の戦略メモー特に合成データについてー", https://zenn.dev/matsuolab/articles/34036f017fae9e, アクセス日: 2025-02-01
- Someya, "Tanuki-8B, 8x8B - 事後学習の軌跡", https://zenn.dev/matsuolab/articles/62c75674190a41, アクセス日: 2025-02-01
- Arata, "TanukiモデルのAWQ、GPTQ、GGUF量子化について", https://zenn.dev/matsuolab/articles/2857bf0feeeb5d, アクセス日: 2025-02-01
- Arata, "Tanuki-8BにMagpieを適用して日本語の合成対話データセットを作成する", https://zenn.dev/aratako_lm/articles/a5ae43fb2bfbb3, アクセス日: 2025-02-01
- Mitsuhashi, "プロンプト進化を用いた日本語選好データセットの構築", https://zenn.dev/matsuolab/articles/10a1aa9d43e4fe, アクセス日: 2025-02-01
- knishimae, "Tanuki-8B, 8x8B - Supervised Fine-Tuning (SFT) 実行(11/24日勉強会公開用)", https://zenn.dev/matsuolab/articles/96d3c0118d3ca6, アクセス日: 2025-02-01
- knishimae, "Tanuki-8B, 8x8B - Direct Preference Optimization (DPO)実行(11/24日勉強会公開用)", https://zenn.dev/matsuolab/articles/62d99af24ff89a, アクセス日: 2025-02-01
- Mさん, "Tanuki8Bに対するMT-Benchを用いた評価を体験してみる", https://zenn.dev/matsuolab/articles/2aafa8a7ba7482, アクセス日: 2025-02-01
- Kan Hatakeyama, "大規模言語モデル Tanuki-8x8B の紹介と開発経緯など", 9/10 松尾研 LLM 開発プロジェクト "Tanuki-8x8B" 開発成果報告会 Vol.1, https://www.docswell.com/s/matsuo-lab_llm/51R2L4-2024-9-10-Tanuki%E9%96%8B%E7%99%BA%E5%A0%B1%E5%91%8A%E4%BC%9A-vol1, https://www.youtube.com/watch?v=IcpXpX-r6ZY, アクセス日: 2025-01-28
- Susumu Ota, "Persona-Hub による合成データ生成", 9/24 松尾研 LLM 開発プロジェクト "Tanuki-8x8B" 開発成果報告会 Vol. 3, https://www.docswell.com/s/matsuo-lab_llm/ZDNGR4-2024-9-24-Tanuki%E9%96%8B%E7%99%BA%E5%A0%B1%E5%91%8A%E4%BC%9A-vol3, https://www.youtube.com/watch?v=XAdc-OgLeOw, アクセス日: 2025-01-28
- [NEDO 採択プロジェクト] 多様な日本語能力の向上を目指した公開の基盤モデル開発, コードレポジトリ “synth_topic_multiturn.py”,アクセス日: 2025-01-28, https://github.com/matsuolab/nedo_project_code/blob/team_hatakeyama_phase2/team_hatakeyama_phase2/ota/topic-hub/synth_topic_multiturn.py
- [NEDO 採択プロジェクト] 多様な日本語能力の向上を目指した公開の基盤モデル開発, コードレポジトリ "iterative-dpo",アクセス日: 2025-01-28, https://github.com/matsuolab/nedo_project_code/tree/team_hatakeyama_phase2/team_hatakeyama_phase2/ota/iterative-dpo
- 松尾研LLMコミュニティメンバー, "「小型LlamaモデルのTRLライブラリを用いた事後学習」松尾研 LLM コミュニティ 勉強会シリーズ#3 (2024-11-24)", https://www.youtube.com/watch?v=ezNx6tB8jac, アクセス日: 2025-02-01

## ライセンス

- [Apache-2.0](LICENSE)

## 著者

- Susumu Ota
  - GitHub [susumuota](https://github.com/susumuota)
