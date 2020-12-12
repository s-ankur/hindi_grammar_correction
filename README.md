# Grammar Correction For Hindi Using Neural Network (Deep Learning)
This repository includes the code and data used in our paper titled ["Generating Inflectional Errors for Grammatical Error Correction in
Hindi"](https://www.aclweb.org/anthology/2020.aacl-srw.24.pdf). If you are interested in using our work, please cite 
```
@inproceedings{sonawane-etal-2020-generating,
    title = "Generating Inflectional Errors for Grammatical Error Correction in {H}indi",
    author = "Sonawane, Ankur  and
      Vishwakarma, Sujeet Kumar  and
      Srivastava, Bhavana  and
      Kumar Singh, Anil",
    booktitle = "Proceedings of the 1st Conference of the Asia-Pacific Chapter of the Association for Computational Linguistics and the 10th International Joint Conference on Natural Language Processing: Student Research Workshop",
    month = dec,
    year = "2020",
    address = "Suzhou, China",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/2020.aacl-srw.24",
    pages = "165--171",
}
```
# Code and Data
A. Wikiextract --  Create a dataset of artificial Hindi errors ([IPython Notebook](https://github.com/s-ankur/hindi_grammar_correction/blob/main/Colab%20Notebooks/https_github.com_s-ankur_wikiextract.ipynb) | [Repository](https://github.com/s-ankur/wikiextract))

Data:  Artificial Dataset used as Train Dataset ([src file](https://drive.google.com/file/d/1WAPmxT10Li2pzk0iEggzWKttXgUNps5I/view?usp=sharing) | [trg file](https://drive.google.com/file/d/17rx_5M3zw0QMkCWm7YFpeJLsCkWbxV9d/view?usp=sharing))

B. Wikiedits -- Extract a dataset of real hindi errors from Wikipedia ([IPython Notebook](https://github.com/s-ankur/hindi_grammar_correction/blob/main/Colab%20Notebooks/https_github.com_s-ankur_wikiedits.ipynb) | [Repository](https://github.com/s-ankur/wikiedits/))

Data: Natural Dataset used as Test Dataset ([edits file](https://drive.google.com/file/d/1LPBA0GG82gS_H-e4Sa6ecjknLuK0rxj7/view?usp=sharing) | [src file](https://drive.google.com/file/d/1yzvHVUZ_rWKtBGPKdUrtolgohoZeTBri/view?usp=sharing) | [trg file](https://drive.google.com/file/d/1vwJpb4_czI4iNN9qczp5p6A1c_3Hm1eR/view?usp=sharing))

C. MLConvGEC -- multilayer convolutional encoder decoder Model ([IPython Notebook](https://github.com/s-ankur/hindi_grammar_correction/blob/main/Colab%20Notebooks/https_github.com_sujeetlearner_mlconvgec.ipynb))

D. Tensor2Tensor -- Base Transformer Model ([IPython Notebook](https://github.com/s-ankur/hindi_grammar_correction/blob/main/Colab%20Notebooks/https_github.com_sujeetlearner_tensor2tensor.ipynb))

E. fairseq-gec -- Copy Augmented Transformer Model  ([IPython Notebook](https://github.com/s-ankur/hindi_grammar_correction/blob/main/Colab%20Notebooks/https_github.com_s-ankur_fairseq-gec.ipynb) | [Repository](https://github.com/s-ankur/fairseq-gec))

F. ERRANT -- Error classification for Hindi as well as model evaluation ([IPython Notebook](https://github.com/s-ankur/hindi_grammar_correction/blob/main/Colab%20Notebooks/https_github.com_s-ankur_errant.ipynb) | [Repository](https://github.com/s-ankur/errant))

Data: Test Data segregated according to error classes [src, trg and m2 files](https://drive.google.com/drive/folders/1QS1wxoLMjEazxq1_DTbMgUDxLnpazTjU?usp=sharing) (Note .trg and .tgt files are identical)
