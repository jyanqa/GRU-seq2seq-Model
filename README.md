# GRU-seq2seq-Model
*A course project for [Natural Language Processing class, Fall 2021](https://rycolab.io/classes/intro-nlp-f21/) at ETH Zurich.*

**Do noises break GRU Seq2Seq Translation Model?**
<p align="justify">
 
- The project aims to assess the robustness of the Seq2Seq neural machine translation by testing trained model on data which had been added different types of noises. The research is thus focused on presenting these features in the setting of French-English translation. 

- Two big general categories of noises including character-level and word-level are added to the clean texts. 

- Built model is tested on the 'dirty' data. BLEU-4 is the metric used to evaluate the performance NMT model. 

- The experiment reveals that word-level noises have less ability to break seq2seq model meanwhile randomizing character noises including Fully Random and Middle Random are two character-level noises whose the most negative affect to the model.  
</p>

[Data](https://drive.google.com/drive/folders/1RItIHESxFAYdWY2DQ-kmnRz2soOQh7zE?usp=sharing) |
 [Code](https://github.com/jyanqa/GRU-seq2seq-Model/blob/main/final%20copy/code_seq2seq/seq2seq_RNN.ipynb) | [Report](https://github.com/jyanqa/GRU-seq2seq-Model/blob/main/final%20copy/Noises_and_Seq2seqRNN_NMT.pdf)
