# Awesome-Buddhist-Open-Sourse Data
### (AI Claude) 
#### Phase 1-3 Phase 1-3: Source Materials & Digitized Collections
- [BUDA (Buddhist Digital Archive)](https://library.bdrc.io/): Description: World's largest collection of digitized Buddhist texts Bdrc +3. IIIF images, OCR texts, Linked Open Data Bdrc. 28+ million pages, 26,000+ works, 72,000 volumes Bdrc +3. Tibetan, Sanskrit, Chinese, Pali, Burmese, Khmer, Newari. Source collection, high-resolution imaging, metadata
- [Göttingen Register of Electronic Texts](https://gretil.sub.uni-goettingen.de/): omprehensive Sanskrit and Indian language e-text repository. Plain text, UTF-8, minimal encoding. Sanskrit, Pali, Prakrit, Hindi, Marathi, Tamil, Malayalam, Tibetan. Text collection, format standardization, academic access.
- [Chinese Buddhist Electronic Text Association](https://cbetaonline.dila.edu.tw/): Digitized Taishō Tripiṭaka and Chinese Buddhist canons. XML with comprehensive markup, searchable database. Text markup, cross-referencing, scholarly annotation.  

#### Phase 5-7: OCR Training Data & Models
- BDRC OCR Datasets (via HuggingFace): Uchan datasets (~1.46M samples), manuscript corrections, modern print collections. Available Models are Multi-script classification, line detection, character recognition. Tibetan (multiple scripts), Bdrc +3 Sanskrit, Chinese. OCR training, script classification, model development. Research datasets, some publicly available. 
- [tibetan-voice-benchmark](https://huggingface.co/MonlamAI/tibetan-voice-benchmark):Speech-to-text benchmark dataset for Tibetan. Audio transcriptions reviewed by multiple transcribers Hugging Face. Multimodal processing, speech recognition integration.
- [sanskrit-verses-gretil](https://huggingface.co/paws/sanskrit-verses-gretil): Sanskrit verses from GRETIL repository. Structured verse data, Derived from GRETIL, stable. Text collection, poetic structure analysis.
#### Phase 8-10: Processed Corpora & Linguistic Resources
- [OpenPecha-Data organization](https://github.com/OpenPecha-Data): 4,000+ works, 10,000+ volumes, 80,000+ individual texts, PF (OpenPecha Format) with YAML annotations Openpecha, Primarily Tibetan, some Sanskrit and Chinese. Continuously updated, community contributions. Text markup, annotation, collaborative editing.
- [ACTib v2.0]( https://doi.org/10.5281/zenodo.3951486): POS-tagged Classical Tibetan corpus, Segmented and annotated text, 185 million tokens, Linguistic analysis, NLP training, morphological annotation.
- [BDRC Corpus (Wallman et al.)](https://doi.org/10.5281/zenodo.821218): Base corpus for multiple derivative projects, Plain text, various encodings, Text collection, corpus development, research foundation.
- [Tibetan FastText Embeddings](https://doi.org/10.5281/zenodo.6782247): 100-dimensional FastText embeddings for Classical Tibetan, Vector embeddings, NLP applications, semantic analysis, computational linguistics.
- [Buddhist Sanskrit Corpus (proof of concept)](https://doi.org/10.5281/zenodo.6686472): Lemmatized Buddhist Sanskrit texts with reference corpus, Romanized Sanskrit (UTF-8), Sanskrit linguistic analysis, lemmatization, corpus linguistics. Partially proofread, ongoing improvements.
- [Taishō and Xuzangjing Corpus](https://doi.org/10.5281/zenodo.6798320): CBETA digitized Chinese Buddhist texts processed for analysis , Processed for TACL text analysis tool, Chinese text analysis, computational philology.

#### Phase 11-12: Machine Learning Models & Applications
- [Buddhist-NLP models](https://huggingface.co/buddhist-nlp): Berkeley AI Research Buddhist NLP models, gemma-2-mitra-e (9B parameters), huggingface english-tibetan embeddings, Research-grade, actively developed, Translation, text generation, semantic analysis.
- [Monlam_Melong_preview](https://huggingface.co/TenzinGayche/Monlam_Melong_preview): Large language model for Tibetan, 200+ language translation, NER, QA, text generation, Translation, language modeling, text generation.
- [tibetan-phonetic-transliteration]( https://huggingface.co/billingsmoore/tibetan-phonetic-transliteration): 98,597 pairs of Tibetan text with phonetic transliterations, Lotsawa House, Literary Tibetan from Buddhist canon, Phonetic analysis, pronunciation modeling.
- [Tibetan-PLM](https://github.com/Dslab-NLP/Tibetan-PLM): BERT and Tibetan-BERT-wwm pre-trained models , PyTorch and TensorFlow versions , Research models, available for download, Advanced NLP, semantic understanding, language modeling.

#### Specialized Language Resources
- [Various Pāli dictionaries and texts](https://github.com/digitalpalitools): Enhanced Digital Pāli Dictionary and study resources GitHub, Multiple dictionary formats, structured data, Dictionary integration, linguistic analysis, educational tools. Actively maintained. 
- [Old Tibetan Corpus and Normalization Grammar](https://doi.org/10.5281/zenodo.4727552): Old Tibetan Annals and Chronicle with linguistic annotation, CoNLL-U files with POS tags, dependency relations, English alignment. Historical linguistics, comparative analysis, grammatical research.
- [Khmer Palm Leaf Manuscript Dataset](https://github.com/donavaly/SleukRith-Set): 657 pages of annotated digitized Khmer manuscripts. XML-based character and word-level annotations. OCR training, manuscript analysis, Southeast Asian Buddhist texts.
