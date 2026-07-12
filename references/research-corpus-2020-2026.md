# Pantheon Research Corpus, 2020–2026

This is Pantheon's 140-paper reading corpus: **20 relevant papers for each calendar year, 2020–2026**. It is deliberately broader than detection. A useful account of humanizing AI-assisted writing needs evidence about authorship signals, style transfer, human evaluation, factual fidelity, and hybrid human–AI revision.

## How to read this corpus

- **[PR]** = peer-reviewed or archived conference/journal paper. **[PP]** = public preprint or working paper; use its claims more cautiously.
- **D** = detection/provenance, **S** = style and authorship, **E** = evaluation, **F** = factuality/content preservation, **H** = human–AI writing.
- Inclusion does **not** endorse hiding AI use or beating a detector. Several papers show why detector scores cannot establish individual authorship; Pantheon uses that result to focus on truthful, substantive revision.
- Titles link to primary venues, DOI pages, or the authors' preprint. Publication/preprint year is the year used below.

## Cross-year synthesis used by Pantheon

1. **Humanization is not a word substitution task.** Across style-transfer and evaluation work, a valid rewrite must preserve meaning while changing only authorized aspects of style; otherwise it can introduce a semantic or factual error.
2. **There is no universal AI word list.** Detection and linguistic-comparison work consistently finds sensitivity to genre, topic, language, model, length, prompt, and revision history. A term may be useful, ordinary, or overused depending on the document.
3. **Voice needs a real source.** Author samples, a stated audience, concrete decisions, and the writer's own evidence are safer inputs than an instruction to “sound human.” Do not invent biography, emotions, local knowledge, or dialect.
4. **Evaluate on several axes.** Meaning and factual support, audience fit, coherent reasoning, authorial voice, and readability are separate checks. A polished surface cannot compensate for unsupported claims.
5. **Treat detector output as fallible evidence, not an editorial target.** The corpus documents distribution shift, false positives, fairness problems, and vulnerability to rewriting. Pantheon never promises a detector result.

## 2020 — foundations: generation, style, and evaluation (20)

| # | Paper | Type | Why it belongs |
| --- | --- | --- | --- |
| 1 | [Automatic Detection of Generated Text is Easiest when Humans are Fooled](https://aclanthology.org/2020.acl-main.164/) | PR · D/E | Contrasts human and automated detection cues. |
| 2 | [What Does it Take to Fool a Neural Language Model?](https://aclanthology.org/2020.coling-main.208/) | PR · D/E | Examines perceived naturalness and adversarially generated text. |
| 3 | [The Limitations of Stylometry for Detecting Machine-Generated Fake News](https://aclanthology.org/2020.cl-2.8/) | PR · D | Shows limits of stylistic authorship inference. |
| 4 | [Authorship Attribution for Neural Text Generation](https://aclanthology.org/2020.emnlp-main.673/) | PR · D/S | Tests attribution of neural generators. |
| 5 | [TweepFake: About Detecting Deepfake Tweets](https://arxiv.org/abs/2008.00036) | PP · D | Short informal text exposes domain-specific detection issues. |
| 6 | [DGST: A Dual-Generator Network for Text Style Transfer](https://aclanthology.org/2020.emnlp-main.578/) | PR · S/F | Treats content retention and style as separate objectives. |
| 7 | [Learning to Generate Multiple Style Transfer Outputs for an Input Sentence](https://aclanthology.org/2020.ngt-1.2/) | PR · S | Shows target style is not one fixed surface form. |
| 8 | [Cycle-Consistent Adversarial Autoencoders for Unsupervised Text Style Transfer](https://aclanthology.org/2020.coling-main.201/) | PR · S/F | Focuses on content preservation in transfer. |
| 9 | [Contextual Text Style Transfer](https://aclanthology.org/2020.findings-emnlp.263/) | PR · S/F | Makes surrounding context part of the rewrite. |
| 10 | [How Positive Are You: Text Style Transfer Using Adaptive Style Embedding](https://aclanthology.org/2020.coling-main.191/) | PR · S | Separates degrees and dimensions of a style. |
| 11 | [Rich Syntactic and Semantic Information Helps Unsupervised Text Style Transfer](https://aclanthology.org/2020.inlg-1.17/) | PR · S/F | Supports checking syntax and semantics, not only vocabulary. |
| 12 | [Improving Disentangled Text Representation Learning with Information-Theoretic Guidance](https://aclanthology.org/2020.acl-main.673/) | PR · S | Studies content/style disentanglement. |
| 13 | [Semi-supervised Formality Style Transfer Using Language Model Discriminator and Mutual Information Maximization](https://aclanthology.org/2020.findings-emnlp.212/) | PR · S/F | Formality changes can degrade content and fluency. |
| 14 | [Reformulating Unsupervised Style Transfer as Paraphrase Generation](https://aclanthology.org/2020.emnlp-main.55/) | PR · S/F/E | Warns that style transfer can silently alter meaning. |
| 15 | [Neural Syntactic Preordering for Controlled Paraphrase Generation](https://aclanthology.org/2020.acl-main.22/) | PR · S/F | Connects rewrite diversity to controlled syntax. |
| 16 | [Retrieval-Augmented Controllable Review Generation](https://aclanthology.org/2020.coling-main.207/) | PR · S/F | Grounds generation in relevant reference text. |
| 17 | [A Gold Standard Methodology for Evaluating Accuracy in Data-to-Text Systems](https://aclanthology.org/2020.inlg-1.22/) | PR · E/F | Accuracy needs explicit human checking. |
| 18 | [Twenty Years of Confusion in Human Evaluation: NLG Needs Evaluation Sheets and Standardised Definitions](https://aclanthology.org/2020.inlg-1.23/) | PR · E | Defines evaluation criteria instead of vague “human-like.” |
| 19 | [Disentangling the Properties of Human Evaluation Methods](https://aclanthology.org/2020.inlg-1.24/) | PR · E | Separates quality dimensions and evaluation design. |
| 20 | [BERTScore: Evaluating Text Generation with BERT](https://arxiv.org/abs/1904.09675) | PR · E/F | Semantic similarity is useful but not a full fidelity check. |

## 2021 — authorship, target style, and human judgement (20)

| # | Paper | Type | Why it belongs |
| --- | --- | --- | --- |
| 1 | [TURINGBENCH: A Benchmark Environment for Turing Test in the Age of Neural Text Generation](https://aclanthology.org/2021.findings-emnlp.172/) | PR · D/E | Benchmarks human-versus-generator discrimination. |
| 2 | [All That’s “Human” Is Not Gold: Evaluating Human Evaluation of Generated Text](https://aclanthology.org/2021.acl-long.565/) | PR · E | Human raters also vary by task and domain. |
| 3 | [Unsupervised Text Style Transfer with Content Embeddings](https://aclanthology.org/2021.ranlp-1.27/) | PR · S/F | Uses content representations to constrain transfer. |
| 4 | [Chinese Text Style Transfer Based on Stylized Embedding](https://aclanthology.org/2021.ccl-1.26/) | PR · S | Extends the issue beyond English defaults. |
| 5 | [NAST: A Non-Autoregressive Generator with Word Alignment for Unsupervised Text Style Transfer](https://aclanthology.org/2021.findings-acl.138/) | PR · S/F | Explicitly aligns retained source content. |
| 6 | [Contextualizing Variation in Text Style Transfer Datasets](https://aclanthology.org/2021.inlg-1.22/) | PR · S/E | Dataset “style” depends on how it is realized. |
| 7 | [Enhancing Content Preservation in Text Style Transfer Using Reverse Attention and Conditional Layer Normalization](https://aclanthology.org/2021.acl-long.8/) | PR · S/F | Makes preservation a first-class objective. |
| 8 | [On Learning Text Style Transfer with Direct Rewards](https://aclanthology.org/2021.naacl-main.337/) | PR · S/E | Optimizes style and semantic similarity separately. |
| 9 | [TextSETTR: Few-Shot Text Style Extraction and Tunable Targeted Restyling](https://aclanthology.org/2021.acl-long.293/) | PR · S | Uses examples for targeted, multi-dimensional restyling. |
| 10 | [Multi-Pair Text Style Transfer for Unbalanced Data via Task-Adaptive Meta-Learning](https://aclanthology.org/2021.metanlp-1.4/) | PR · S | Style systems must cope with mismatched domains. |
| 11 | [The GEM Benchmark: Natural Language Generation, its Evaluation and Metrics](https://aclanthology.org/2021.gem-1.10/) | PR · E | Establishes an evolving, multilingual NLG evaluation framework. |
| 12 | [On the Dangers of Stochastic Parrots](https://dl.acm.org/doi/10.1145/3442188.3445922) | PR · H | Places language-model writing in social and data context. |
| 13 | [TruthfulQA: Measuring How Models Mimic Human Falsehoods](https://arxiv.org/abs/2109.07958) | PR · F | Fluency and plausibility do not ensure truth. |
| 14 | [Controlling Hallucinations at Word Level in Data-to-Text Generation](https://link.springer.com/article/10.1007/s10618-021-00801-4) | PR · F | Supports claim-level fidelity checks after editing. |
| 15 | [DocNLI: A Large-scale Dataset for Document-level Natural Language Inference](https://aclanthology.org/2021.acl-long.264/) | PR · F | Long-form coherence and entailment matter. |
| 16 | [Decoding Methods in Neural Language Generation: A Survey](https://doi.org/10.3390/info12090355) | PR · E/S | Decoding choices influence fluency, diversity, and repetition. |
| 17 | [A Survey of Human Evaluation in Natural Language Processing](https://arxiv.org/abs/2107.06799) | PP · E | Catalogues methodological limits of human ratings. |
| 18 | [A Survey on Bias in Deep NLP](https://doi.org/10.3390/app11073184) | PR · H | Bias-aware revision must protect diverse language. |
| 19 | [ReproGen: Reproducibility of Human Evaluations in NLG](https://aclanthology.org/2021.inlg-1.14/) | PR · E | Demonstrates variation in human-evaluation results. |
| 20 | [The Generalizability of Text Generation Evaluation Metrics](https://aclanthology.org/2021.emnlp-main.107/) | PR · E | Metrics do not transfer cleanly across settings. |

## 2022 — multi-axis evaluation and controllable rewriting (20)

| # | Paper | Type | Why it belongs |
| --- | --- | --- | --- |
| 1 | [SentSpace: Large-Scale Benchmarking and Evaluation of Text Style Transfer](https://aclanthology.org/2022.naacl-demo.11/) | PR · S/E | Benchmarks style, content, and fluency together. |
| 2 | [Real or Fake Text? Investigating Human Ability to Detect Boundaries Between Human-Written and Machine-Generated Text](https://arxiv.org/abs/2212.12672) | PP · D/E | Human detection changes with boundaries and genre. |
| 3 | [SynSciPass: Detecting Machine-Generated Text in Scientific Papers](https://aclanthology.org/2022.sdp-1.27/) | PR · D | Domain-specific detection is not general authorship proof. |
| 4 | [Text Style Transfer via Optimal Transport](https://aclanthology.org/2022.naacl-main.182/) | PR · S/F | Combines syntactic and semantic similarity. |
| 5 | [Text Style Transferring via Adversarial Masking and Styled Filling](https://aclanthology.org/2022.emnlp-main.521/) | PR · S/F | Studies diversity and semantic consistency. |
| 6 | [A Recipe for Arbitrary Text Style Transfer with Large Language Models](https://aclanthology.org/2022.acl-short.94/) | PR · S | Shows flexible style requests need evaluation. |
| 7 | [Deep Learning for Text Style Transfer: A Survey](https://aclanthology.org/2022.cl-1.6/) | PR · S/E | Survey of methods, data, and unresolved trade-offs. |
| 8 | [Learning from Bootstrapping and Stepwise Reinforcement Reward](https://aclanthology.org/2022.findings-naacl.201/) | PR · S/F | Addresses quality degradation in transfer. |
| 9 | [So Different Yet So Alike! Constrained Unsupervised Text Style Transfer](https://aclanthology.org/2022.acl-long.32/) | PR · S/F | Preserves length, descriptiveness, and lexical constraints. |
| 10 | [GENIE: Toward a Generalizable Benchmark for Text Generation Evaluation](https://aclanthology.org/2022.emnlp-main.787/) | PR · E | Tests whether evaluators generalize across tasks. |
| 11 | [Unraveling the Mystery of Artifacts in Machine Generated Text](https://aclanthology.org/2022.lrec-1.744/) | PR · D | Investigates model and dataset artifacts. |
| 12 | [Audience-Centric Natural Language Generation via Style Infusion](https://aclanthology.org/2022.findings-emnlp.138/) | PR · S/H | Tailors language to audience, not a generic standard. |
| 13 | [CTRLEval: An Unsupervised Reference-Free Metric for Evaluating Controlled Text Generation](https://aclanthology.org/2022.acl-long.230/) | PR · E | Uses separate controls for generation quality. |
| 14 | [Dynamic Human Evaluation for Relative Model Comparisons](https://aclanthology.org/2022.lrec-1.639/) | PR · E | Improves the efficiency of comparative human judgment. |
| 15 | [Text Style Transfer: The Case of Detoxification](https://aclanthology.org/2022.humeval-1.9/) | PR · S/E | Identifies task-specific metric limitations. |
| 16 | [Towards a Unified Multi-Dimensional Evaluator for Text Generation](https://arxiv.org/abs/2210.07197) | PP · E | Encourages evaluating more than fluency. |
| 17 | [Human Evaluation of Natural Language Generation: A Survey](https://arxiv.org/abs/2203.07865) | PP · E | Synthesizes reliability and design concerns. |
| 18 | [Evaluating Generated Text in the Era of Large Language Models](https://aclanthology.org/2022.emnlp-main.401/) | PR · E | Assesses LLMs as text evaluators. |
| 19 | [FactPEGASUS: Factuality-Aware Pre-Training and Fine-Tuning for Abstractive Summarization](https://aclanthology.org/2022.naacl-main.186/) | PR · F | Reinforces factual support as a separate pass. |
| 20 | [CoAuthor: Designing a Human-AI Collaborative Writing Dataset for Exploring Language Model Capabilities](https://dl.acm.org/doi/10.1145/3491102.3517433) | PR · H | Grounds hybrid writing in human interaction data. |

## 2023 — ChatGPT-era detection, fairness, and evaluation (20)

| # | Paper | Type | Why it belongs |
| --- | --- | --- | --- |
| 1 | [AI, Write an Essay for Me: A Large-Scale Comparison of Human-Written and ChatGPT-Generated Essays](https://arxiv.org/abs/2304.14276) | PP · D/S | Compares discourse, stance, and linguistic features. |
| 2 | [Paraphrasing Evades Detectors of AI-Generated Text, but Retrieval Is an Effective Defense](https://arxiv.org/abs/2303.13408) | PR · D | Demonstrates why detector optimization is not responsible editing. |
| 3 | [GPT Detectors Are Biased Against Non-Native English Writers](https://arxiv.org/abs/2304.02819) | PR · D/H | Establishes an important fairness constraint. |
| 4 | [Can AI-Generated Text Be Reliably Detected?](https://arxiv.org/abs/2303.11156) | PR · D | Formalizes limits under distributional closeness. |
| 5 | [DetectGPT: Zero-Shot Machine-Generated Text Detection Using Probability Curvature](https://arxiv.org/abs/2301.11305) | PR · D | A major zero-shot detection approach and its assumptions. |
| 6 | [Testing of Detection Tools for AI-Generated Text](https://arxiv.org/abs/2306.15666) | PR · D/E | Tests practical detector error types. |
| 7 | [A Watermark for Large Language Models](https://arxiv.org/abs/2301.10226) | PR · D | Frames provenance as distinct from prose style. |
| 8 | [A Call for Standardization and Validation of Text Style Transfer Evaluation](https://aclanthology.org/2023.findings-acl.687/) | PR · S/E | Finds gaps in both human and automated TST evaluation. |
| 9 | [Prefix-Tuning Based Unsupervised Text Style Transfer](https://aclanthology.org/2023.findings-emnlp.990/) | PR · S/F | Tests controllability against content retention. |
| 10 | [On Text Style Transfer via Style-Aware Masked Language Models](https://aclanthology.org/2023.inlg-main.25/) | PR · S/F | Targets source-style masking without content loss. |
| 11 | [Fine-Grained Text Style Transfer with Diffusion-Based Language Models](https://aclanthology.org/2023.repl4nlp-1.21/) | PR · S | Expands style to fine-grained controllable attributes. |
| 12 | [Classification of Human- and AI-Generated Texts](https://aclanthology.org/2023.icnlsp-1.1/) | PR · D | A direct human/AI text classification study. |
| 13 | [Use Prompt to Differentiate Text Generated by ChatGPT and Humans](https://www.sciencedirect.com/science/article/pii/S2666827023000506) | PR · D | Shows prompt/context affect detection claims. |
| 14 | [Paraphrase Detection: Human vs. Machine Content](https://arxiv.org/abs/2303.13989) | PP · D/E | Questions dataset alignment with human expectations. |
| 15 | [SelfCheckGPT: Zero-Resource Black-Box Hallucination Detection for Generative Large Language Models](https://aclanthology.org/2023.emnlp-main.557/) | PR · F | Supports claim checking when source access is limited. |
| 16 | [FActScore: Fine-grained Atomic Evaluation of Factual Precision in Long Form Text Generation](https://arxiv.org/abs/2305.14251) | PR · F | Makes factual precision measurable at claim level. |
| 17 | [HaluEval: A Large-Scale Hallucination Evaluation Benchmark for Large Language Models](https://arxiv.org/abs/2305.11747) | PR · F | Separates polished text from supported text. |
| 18 | [G-Eval: NLG Evaluation Using GPT-4 with Better Human Alignment](https://arxiv.org/abs/2303.16634) | PR · E | LLM judging still needs careful criteria. |
| 19 | [MULTITuDE: Large-Scale Multilingual Machine-Generated Text Detection Benchmark](https://aclanthology.org/2023.emnlp-main.616/) | PR · D | Tests language and generator generalization. |
| 20 | [CoCo: Coherence-Enhanced Machine-Generated Text Detection Under Low Resource](https://aclanthology.org/2023.emnlp-main.1005/) | PR · D | Treats text-level coherence as a task-specific feature. |

## 2024 — stronger benchmarks and context-sensitive signals (20)

| # | Paper | Type | Why it belongs |
| --- | --- | --- | --- |
| 1 | [Differentiating Between Human and AI-Generated Text: A Rapid Review](https://www.mdpi.com/2504-2289/10/2/55) | PR · D/E | Synthesizes surface, discourse, content, and provenance cues. |
| 2 | [Exploring Limitations of AI-Generated Text Detectors](https://arxiv.org/abs/2406.11073) | PP · D | Demonstrates sensitivity to style and difficulty. |
| 3 | [Machine-Generated Text Localization](https://aclanthology.org/2024.findings-acl.495/) | PR · D | Moves from document labels to local attribution. |
| 4 | [Why Does ChatGPT “Delve” So Much?](https://arxiv.org/abs/2412.11385) | PP · S | Corpus study of post-ChatGPT lexical shifts. |
| 5 | [Empirical Evidence of Large Language Model’s Influence on Human Spoken Communication](https://arxiv.org/abs/2409.01754) | PP · H/S | Studies language diffusion rather than individual guilt. |
| 6 | [Ghostbuster: Detecting Text Ghostwritten by Large Language Models](https://aclanthology.org/2024.naacl-long.95/) | PR · D | Cross-domain detection benchmark and method. |
| 7 | [IDEATE: Detecting AI-Generated Text Using Internal and External Factual Structures](https://aclanthology.org/2024.lrec-main.751/) | PR · D/F | Relates factual structure to detection. |
| 8 | [Detecting AI-Generated Text with Pre-Trained Models Using Linguistic Features](https://aclanthology.org/2024.icon-1.21/) | PR · D | Tests stylometric features on a specific dataset. |
| 9 | [SemEval-2024 Task 8: Multidomain, Multimodel and Multilingual Machine-Generated Text Detection](https://aclanthology.org/2024.semeval-1.279/) | PR · D | Shows the problem is multilingual and multi-domain. |
| 10 | [TinyStyler: Efficient Few-Shot Text Style Transfer with Authorship Embeddings](https://aclanthology.org/2024.findings-emnlp.781/) | PR · S/F | Uses author examples and tests content/fluency. |
| 11 | [StyleFlow: Disentangle Latent Representations via Normalizing Flow for Unsupervised Text Style Transfer](https://aclanthology.org/2024.lrec-main.1336/) | PR · S/F | Treats content/style separation as difficult. |
| 12 | [Disentangled Learning with Synthetic Parallel Data for Text Style Transfer](https://aclanthology.org/2024.acl-long.811/) | PR · S/F | Addresses semantic divergence in transfer. |
| 13 | [Step-by-Step: Controlling Arbitrary Style in Text with Large Language Models](https://aclanthology.org/2024.lrec-main.1328/) | PR · S/F | Uses local edits to limit unnecessary rewriting. |
| 14 | [Distilling Text Style Transfer with Self-Explanation from LLMs](https://aclanthology.org/2024.naacl-srw.21/) | PR · S/E | Adds a transparency lens to restyling. |
| 15 | [Style-Specific Neurons for Steering LLMs in Text Style Transfer](https://aclanthology.org/2024.emnlp-main.745/) | PR · S | Studies model-level style control. |
| 16 | [Text Style Transfer Evaluation Using Large Language Models](https://aclanthology.org/2024.lrec-main.1373/) | PR · S/E | Tests LLM judges against multi-axis evaluation. |
| 17 | [Are Large Language Models Actually Good at Text Style Transfer?](https://aclanthology.org/2024.inlg-main.42/) | PR · S/E | Tests quality, fidelity, and multilingual transfer. |
| 18 | [M4GT-Bench: Evaluation Benchmark for Black-Box Machine-Generated Text Detection](https://arxiv.org/abs/2402.11175) | PP · D | Brings generator/model variation into evaluation. |
| 19 | [RAID: A Shared Benchmark for Robust Evaluation of Machine-Generated Text Detectors](https://aclanthology.org/2024.acl-long.674/) | PR · D | Evaluates robustness across domains and generators. |
| 20 | [Binoculars: Zero-Shot Detection of LLM-Generated Text](https://arxiv.org/abs/2401.12070) | PR · D | Another detector family with scope limitations. |

## 2025 — hybrid authorship, generalization, and empirical humanization (20)

| # | Paper | Type | Why it belongs |
| --- | --- | --- | --- |
| 1 | [DAMAGE: Detecting and Assessing Machine-Generated Editing](https://arxiv.org/pdf/2501.03437) | PP · H/F | Tests humanizers for fidelity, fluency, and quality harm. |
| 2 | [Beemo: Benchmarking Expert Edits for Machine-Generated Outputs](https://aclanthology.org/2025.naacl-long.357/) | PR · H/E | Expert editing is a realistic hybrid-authorship baseline. |
| 3 | [Like a Human? A Linguistic Comparison of Human and LLM Scientific Writing](https://aclanthology.org/2025.lm4dh-1.4/) | PR · S | Compares syntactic and lexical variability. |
| 4 | [Linguistic and Embedding-Based Profiling of Human and LLM-Generated Text](https://aclanthology.org/2025.emnlp-main.1163/) | PR · S/D | Compares models, domains, and feature variation. |
| 5 | [Quantifying LLM Usage in Scientific Papers](https://www.nature.com/articles/s41562-025-02273-8) | PR · H/S | Population-level language shift is not individual attribution. |
| 6 | [People Who Frequently Use ChatGPT for Writing Tasks Are Accurate and Robust Detectors of AI-Generated Text](https://aclanthology.org/2025.acl-long.267/) | PR · D/E | Human judgements use more than lexical cues. |
| 7 | [Stress-Testing Machine-Generated Text Detection in the Age of LLMs](https://aclanthology.org/2025.findings-acl.156/) | PR · D | Tests robustness under realistic shifts. |
| 8 | [Exploring Limitations of AI-Generated Text Detectors](https://aclanthology.org/2025.coling-main.288/) | PR · D | Peer-reviewed version of style/difficulty study. |
| 9 | [A Practical Examination of AI-Generated Text Detectors for Large Language Models](https://aclanthology.org/2025.findings-naacl.271/) | PR · D | Tests unseen domains, models, and false-positive targets. |
| 10 | [AIDER: A Robust and Topic-Independent Framework for Detecting AI-Generated Text](https://aclanthology.org/2025.coling-main.625/) | PR · D | Explicitly tackles topic generalization. |
| 11 | [Seeing Through the Mask: AI-Generated Text Detection with Similarity-Guided Graph Reasoning](https://aclanthology.org/2025.findings-ijcnlp.84/) | PR · D | Tests paraphrased and out-of-domain text. |
| 12 | [SenDetEX: Sentence-Level AI-Generated Text Detection for Human-AI Hybrid Content](https://aclanthology.org/2025.emnlp-main.268/) | PR · D/H | Treats mixed authorship as its own case. |
| 13 | [Profiler: Black-Box AI-Generated Text Origin Detection via Context-Aware Inference Pattern Analysis](https://aclanthology.org/2025.emnlp-main.1265/) | PR · D | Distinguishes origin attribution from quality. |
| 14 | [When Detection Fails: The Power of Fine-Tuned Models to Generate Human-Like Social Media Text](https://aclanthology.org/2025.findings-acl.695/) | PR · D | Highlights short-form and domain weaknesses. |
| 15 | [Catch Me If You Can? Not Yet: LLMs Still Struggle to Imitate the Implicit Writing Styles of Everyday Authors](https://aclanthology.org/2025.findings-emnlp.532/) | PR · S | Shows generic imitation differs from personal voice. |
| 16 | [How to Generalize the Detection of AI-Generated Text: Confounding Factors and Data Quality](https://aclanthology.org/2025.findings-emnlp.1388/) | PR · D | Examines confounds behind benchmark scores. |
| 17 | [Evaluating Text Style Transfer Evaluation: Are There Any Reliable Metrics?](https://aclanthology.org/2025.naacl-srw.41/) | PR · S/E | Meta-evaluates transfer metrics in multiple languages. |
| 18 | [ReproHum #0669-08: Reproducing Sentiment Transfer Evaluation](https://aclanthology.org/2025.gem-1.55/) | PR · S/E | Tests whether human TST evaluation reproduces. |
| 19 | [GenAI Content Detection Task 1: English and Multilingual Machine-Generated Text Detection](https://aclanthology.org/2025.genaidetect-1.0/) | PR · D | Shared-task evidence across languages. |
| 20 | [M-DAIGT: Multi-Domain Detection of AI-Generated Text Shared Task](https://aclanthology.org/2025.ranlp-mdaigt.0/) | PR · D | Tests academic and news domains separately. |

## 2026 — current evidence: context, linguistic diversity, and process (20)

| # | Paper | Type | Why it belongs |
| --- | --- | --- | --- |
| 1 | [Is Human-Like Text Liked by Humans? Multilingual Human Detection and Preference Against AI](https://aclanthology.org/2026.acl-long.639/) | PR · D/E | Separates detectability, human preference, and language. |
| 2 | [Interpretable Stylistic Variation in Human and LLM Writing](https://arxiv.org/abs/2604.14111) | PP · S/D | Finds genre often outweighs source in stylistic variation. |
| 3 | [A Systematic Analysis of Linguistic Indicators for AI-Generated Text Detection](https://arxiv.org/abs/2606.04177) | PP · D/S | Tests 284 features across models and domains. |
| 4 | [Human vs. Machine Deception: Distinguishing AI-Generated and Human-Written Fake News](https://arxiv.org/abs/2604.09960) | PP · D | Tests attribution in a high-stakes content domain. |
| 5 | [MASH: Multi-Agent Simulation for Humanization and AI-Text Detection](https://aclanthology.org/2026.findings-acl.1487/) | PR · D/H | Research evidence about a detector–rewriter arms race. |
| 6 | [AbjadStyleTransfer: Authorship Style Transfer for Arabic-Script Languages](https://aclanthology.org/2026.abjadnlp-1.70/) | PR · S | Centers literary Arabic and Urdu, not English defaults. |
| 7 | [Leveraging Human and Machine Preferences for Zero-Shot Detection of AI-Generated Text](https://aclanthology.org/2026.findings-acl.671/) | PR · D | Models human/machine prediction differences. |
| 8 | [FAID: Fine-Grained AI-Generated Text Detection Using Multi-Task Auxiliary and Multi-Level Contrastive Learning](https://aclanthology.org/2026.eacl-long.151/) | PR · D/H | Includes human–LLM collaborative text. |
| 9 | [AI Generated Text Detection](https://arxiv.org/abs/2601.03812) | PP · D | Uses topic-separated testing to reduce leakage. |
| 10 | [Why AI-Generated Text Detection Fails: Evidence from Explainable AI Beyond Benchmark Accuracy](https://arxiv.org/abs/2603.23146) | PP · D | Shows in-domain cues may fail under shift. |
| 11 | [Findings of the Counter Turing Test: AI-Generated Text Detection](https://arxiv.org/abs/2605.20761) | PP · D | Compares binary detection and model attribution. |
| 12 | [Automatic Detection of Gen-AI Texts: A Comparative Framework of Neural Models](https://arxiv.org/abs/2603.18750) | PP · D | Compares neural and commercial detectors. |
| 13 | [A Linguistic Comparison Between Human- and AI-Generated Content](https://doi.org/10.1016/j.isci.2026.114976) | PR · S | Portuguese comparison; effects vary by model and truth status. |
| 14 | [ChatGPT’s Ability to Imitate Writing Styles: An Analysis Guided by Forensic Text Comparison](https://academic.oup.com/dsh/advance-article/doi/10.1093/llc/fqag079/8703383) | PR · S | Style imitation depends on author, genre, and evaluator. |
| 15 | [Exploring Linguistic Fingerprints in Human and AI-Generated Texts: An NLP-Based Approach in Second-Language Writing](https://www.sciencedirect.com/science/article/pii/S2215039026000056) | PR · S/D | Supports fairness cautions for L2 English writing. |
| 16 | [Process-Based Authorship Assessment Across Human and LLM-Generated Writing: CRAFT](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6879243) | PP · H | Centers evidence of a writer's actual process. |
| 17 | [The Pen Is Mightier Than the Algorithm? A Multilevel Linguistic Comparison of LLM- and Human-Translated Research Article Abstracts](https://www.polyu.edu.hk/lst/research/publications/journal-papers/2026/0508-the-pen-is-mightier-than-the-algorithm/) | PR · S | Compares output profiles by discipline and translator. |
| 18 | [Stylometric Detection of AI-Generated Texts: Evidence from Human and Machine-Written Essays](https://academic.oup.com/dsh/advance-article/doi/10.1093/llc/fqag064/8714041) | PR · D/S | Tests stylometry with topic and data constraints. |
| 19 | [Stylometry Recognizes Human and LLM-Generated Texts in Short Samples](https://www.sciencedirect.com/science/article/pii/S0957417425026181) | PR · D/S | Tests short samples, summaries, and rephrasings. |
| 20 | [Stylometric Approach to AI-Generated Texts: An Analysis of Contemporary Literary Writing](https://aclanthology.org/2026.latechclfl-1.21/) | PR · D/S | Applies stylometry in a literary setting. |

## What Pantheon takes from the corpus

When the user asks for a research-grounded humanization pass, use this sequence:

1. Establish the author, audience, purpose, genre, and acceptable disclosure.
2. Protect invariants: facts, citations, quotes, claims, decisions, required terminology, and the writer's dialect.
3. Diagnose genericness as a **cluster** problem: weak causal links, ungrounded praise, template transitions, repeated paragraph roles, unearned certainty, or detail that could fit any document.
4. Rebuild the reasoning with the author's verified evidence and real trade-offs. Edit locally where possible; do not paraphrase wholesale.
5. Review reader fit, factual support, semantic preservation, and voice separately. Explain substantive changes; never claim detector safety.

## Scope and maintenance

The 2026 portion reflects sources publicly available on **12 July 2026** and includes preprints because the calendar year is still in progress. Before turning this corpus into a formal bibliography or making a high-stakes factual claim, re-check the DOI/venue and the final version. Rows marked PP are context sources, not decisive evidence.
