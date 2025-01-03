# Korean-English Context-Aware Translation Challenge Dataset

This repository contains the dataset associated with the COLING 2025 accepted paper:

**"A Testset for Context-Aware LLM Translation in Korean-to-English Discourse Level Translation"**  
*Minjae Lee¹, Youngbin Noh², Seung-Jin Lee²*  
¹ Korea University  
² NCSOFT

---

## 📊 **Dataset Overview**

This dataset is designed to evaluate Korean-to-English **discourse-level** translation capabilities of Large Language Models (LLMs) and Neural Machine Translation (NMT) systems. It consists of **600 manually constructed text instances** that highlight six linguistic phenomena requiring **contextual inference beyond the sentence level**.

Unlike sentence-level datasets, this dataset emphasizes **inter-sentential (cross-sentence) context** that is necessary to resolve ambiguities and accurately translate challenging linguistic phenomena.

---

## 🧩 **Linguistic Phenomena Covered**

1. **Lexical Ambiguity**  
   Words with multiple meanings that need context across sentences to resolve correctly.

2. **Zero Anaphora**  
   Omitted subjects, objects, or complements that require inference from preceding or following sentences.

3. **Slang**  
   Informal expressions where inter-sentential context helps in understanding the tone and meaning.

4. **Idiom**  
   Phrases with non-literal meanings that can only be accurately translated by considering the broader discourse.

5. **Figurative Language**  
   Metaphors or expressions requiring context from surrounding sentences to be properly interpreted.

6. **Implicature**  
   Implied meanings where the intention becomes clear only when considering the entire conversation.

---

## 📂 **File Structure**
```
korean-english-context-aware-translation-dataset/
│-- README.md                       
│-- LICENSE                         
│-- dataset/                        # Dataset files for each linguistic phenomenon 
│   ├── lexical_ambiguity.jsonl
│   ├── zero_anaphora.jsonl
│   ├── slang.jsonl
│   ├── idiom.jsonl
│   ├── figurative_language.jsonl
│   └── implicature.jsonl
```

## License

This dataset is licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). 

### Copyright
Copyright (c) 2025 NCSOFT. All rights reserved.
