-----------
A Modern Approach to Adverse Event Detection in Biomedical Corpora: [Collins, 2024]
------------
**Abstract**
In the pursuit of advancing patient care and medical safety, we present a novel approach
to Adverse Event (AE) detection in biomedical corpora, leveraging the latest advancements in Artificial Intelligence. We compare highly optimized classical deep learning techniques using both general
and domain-specific BERT-based architectures with the modern approaches of instruction fine-tuning,
zero-shot and few-shot prompting. Moreover, we make this comparison across varied biomedical corpora
and explore and compare both open-source and closed-source models. We employ Quantized Low Rank
Adaptation (QLoRA) for parameter-efficient fine-tuning to address practical considerations such as cost
and ethical implications. We conclude by analysing whether these modern techniques do indeed offer
improvements that are reproducible in the classical Natural Language Processing problems of Classification and Named Entity Recognition for the task of AE detection. Our results clearly demonstrate
that the latest generative biomedical models indeed offer a significant advantage over classical BERT
implementations for the detection of adverse events, when they are fine-tuned to specific AE corpora.

-----
All finetuned HF models available at: https://huggingface.co/collij22

Example1 - BioMistral-7B Sequence Classification model finetuned on ADE corpus: collij22/seq-adesplit_FT_BioMistral-7B
Example2 - BioMedGPT-LM-7B Causal LM finetuned on PsyTAR corpus: collij22/jcpsytar_FT_BioMedGPT-LM-7B 
Example 3 - BioLinkBERT-base NER Token classification model finetuned on CADEC corpus: collij22/ner_preprocessed_cadec_michiyasunaga_BioLinkBERT-base_2.0
