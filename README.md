# NLP Data Augmentation

*(Augmentating Textual Data Using NLP Libraries)*

“**Augmentation**” is the process of enlarging in size or amount and here in this article, we’ll work out how we can increase the size of the data using the data augmentation techniques for textual data. Also as the neural architectures rely on large parallel corpora, synthetically generating data (which is called **data augmentation**) can be of huge help.

As mentioned in <i>“A Survey of Data Augmentation Approaches for NLP”</i>[b], some of the **Data Augmentation Techniques** are:

1. Rule-Based: Easy Data Augmentation(EDA)
2. Example Interpolation Techniques: MIXUP, SEQ2MIXUP
3. Model-Based Techniques: Seq2seq, language model, backtranslation, fine-tuning GPT-2, paraphrasing.

Under Rule-Based, the basic and most commonly used technique is **EDA**: Easy data augmentation techniques. The **EDA techniques** are:

1. Synonym Replacement
2. Random Deletion
3. Random Swap
4. Random Insertion

### **Vairous Data Augmentation Task**:

1. Summarization
2. Question Answering
3. Sequence Tagging
4. Parsing
5. Grammatical Error Correction
6. Neural Machine Translation
7. Data to Text
8. Dialogue

### **Various Libraries available:**

1. TextAugment
2. Augly
3. NLPAug
4. Parrot paraphrase
5. Pegasus paraphrase

Working Code of each libraries can be found here:

* [TextAugment](https://github.com/pemagrg1/nlp-data-augmentation/blob/main/notebooks/TextAugment_notebook.ipynb)
* [Augly](https://github.com/pemagrg1/nlp-data-augmentation/blob/main/notebooks/Augly_notebook.ipynb)
* [NLPAug](https://github.com/pemagrg1/nlp-data-augmentation/blob/main/notebooks/NLPAug_notebook.ipynb)
* [Parrot paraphrase](https://github.com/pemagrg1/nlp-data-augmentation/blob/main/notebooks/Parrot_paraphrase_notebook.ipynb)
* [Pegasus paraphrase](https://github.com/pemagrg1/nlp-data-augmentation/blob/main/notebooks/Pegasus_paraphrase_notebook.ipynb)

## Sample Output:
### TextAugment
TextAugment is a Python 3 library for augmenting text for natural language processing applications. TextAugment stands on the giant shoulders of NLTK, Gensim, and TextBlob and plays nicely with them.<br><br>
![image](https://user-images.githubusercontent.com/30492527/154437725-e220fa41-3bbf-4d74-b34a-127a32c5c446.png)


### Augly
Facebook just recently released the AugLy package to the public domain. AugLy library is divided into four sub-libraries, each for different kinds of data modalities (audio, images, videos and texts).<br>
![image](https://user-images.githubusercontent.com/30492527/154438419-0e5f2cf8-5f32-44e9-ab26-c1e105f94046.png)


### NLPAug
NLPAug is a library for textual augmentation in machine learning experiments. The goal is improving deep learning model performance by generating textual data.<br><br>
![image](https://user-images.githubusercontent.com/30492527/154438162-d563eaaa-9626-494b-9e6a-a9c863d5d8b5.png)
![image](https://user-images.githubusercontent.com/30492527/154438215-84771e31-65bb-44e9-ada4-b8b5266c0f51.png)


### Parrot paraphrase
Parrot is a paraphrase-based utterance augmentation framework purpose-built to accelerate training NLU models. A paraphrase framework is more than just a paraphrasing model.<br>
![image](https://user-images.githubusercontent.com/30492527/154438574-085d450f-144d-4077-b7c7-85e1b29f9221.png)


### Pegasus paraphrase
PEGASUS is a standard Transformer encoder-decoder. PEGASUS uses GSG to pre-train a Transformer encoder-decoder on large corpora of documents.<br>
![image](https://user-images.githubusercontent.com/30492527/154438878-d0701f27-9223-4a92-9c43-e4f1eb416e76.png)


### REF:

[a] Surangika Ranathunga, En-Shiun Annie Lee, Marjana Prifti Skenduli, Ravi Shekhar, Mehreen Alam, Rishemjit Kaur. 2021. **Neural Machine Translation for Low-Resource Languages: A Survey.

[b] Steven Y. Feng, Varun Gangal, Jason Wei, Sarath Chandar, Soroush Vosoughi, Teruko Mitamura, Eduard Hovy. 2021. A Survey of Data Augmentation Approaches for NLP.

[c] EDA from scratch: [https://jovian.ai/abdulmajee/eda-data-augmentation-techniques-for-text-nlp](https://jovian.ai/abdulmajee/eda-data-augmentation-techniques-for-text-nlp)

[d]TextAugment [https://github.com/dsfsi/textaugment](https://github.com/dsfsi/textaugment)

[e] Augly [https://analyticsarora.com/how-to-use-augly-on-image-video-audio-and-text/](https://analyticsarora.com/how-to-use-augly-on-image-video-audio-and-text/)

[f] nlpaug [https://github.com/makcedward/nlpaug](https://github.com/makcedward/nlpaug)

[g] Parrot Paraphraser [https://github.com/PrithivirajDamodaran/Parrot_Paraphraser](https://github.com/PrithivirajDamodaran/Parrot_Paraphraser)

[h] Pegasus Paraphraser [https://huggingface.co/tuner007/pegasus_paraphrase](https://huggingface.co/tuner007/pegasus_paraphrase)

[I] Improving short text classification through global augmentation methods.

[j] PEGASUS: Pre-training with Extracted Gap-sentences for Abstractive Summarization [https://arxiv.org/abs/1912.08777](https://arxiv.org/abs/1912.08777)
