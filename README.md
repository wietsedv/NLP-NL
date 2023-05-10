# NLP-NL: Dutch Natural Language Processing Datasets

Dutch variants of (English) Natural Language Processing datasets.

> ⚠️ **Warning:** Work in progress.

## Datasets

### 📁 [WiC-NL](WiC-NL) [recreated [WiC](https://pilehvar.github.io/wic/)] <small>(Word Sense Disambiguation)</small>

Recreation of [Words in Context (WiC)](https://pilehvar.github.io/wic/) based on [DutchSemCor](http://wordpress.let.vupr.nl/dutchsemcor/).

WIP

### 📁 [WSC-NL](WSC-NL) [recreated [WSC](https://cs.nyu.edu/~davise/papers/WinogradSchemas/WS.html)] <small>(Coreference Resolution)</small>

Recreation of [The Winograd Schema Challenge (WSC)](https://cs.nyu.edu/~davise/papers/WinogradSchemas/WS.html) based on [SemEval-2010 Task 1](https://semeval2.fbk.eu/semeval2.php?location=tasks&area=Coreference).

WIP

### 📁 [COPA-NL](COPA-NL) [translated [COPA](https://people.ict.usc.edu/~gordon/copa.html)] <small>(Causal Reasoning)</small>

Translation of [Choice of Plausible Alternatives (COPA)](https://people.ict.usc.edu/~gordon/copa.html).

| Split | Source                | Procedure                | English | Dutch |
| ----- | --------------------- | ------------------------ | ------: | ----: |
| train | COPA-dev (first 400)¹ | Google Translate + Human |     400 |   400 |
| dev   | COPA-dev (last 100)¹  | Google Translate + Human |     100 |   100 |
| test  | COPA-test             | Google Translate + Human |     500 |   500 |

¹ These splits are the same as in [SuperGLUE](https://super.gluebenchmark.com/).

### 📁 [SQuAD-NL](QuAD-NL) [translated [SQuAD](https://rajpurkar.github.io/SQuAD-explorer/) / [XQuAD](https://github.com/deepmind/xquad)] <small>(Question Answering)</small>

Translation of [The Stanford Question Answering Dataset (SQuAD)](https://rajpurkar.github.io/SQuAD-explorer/).

#### v1.1

| Split | Source                 | Procedure                | English | Dutch  |
| ----- | ---------------------- | ------------------------ | ------: | -----: |
| train | SQuAD-train-v1.1       | Google Translate         |  87,599 | 87,599 |
| dev   | SQuAD-dev-v1.1 \ XQuAD | Google Translate         |   9,380 |  9,380 |
| test  | SQuAD-dev-v1.1 & XQuAD | Google Translate + Human |   1,190 |  1,183 |

#### v2.0
| Split | Source                 | Procedure                | English | Dutch   |
| ----- | ---------------------- | ------------------------ | ------: | ------: |
| train | SQuAD-train-v2.0       | Google Translate         | 130,319 | 130,319 |
| dev   | SQuAD-dev-v2.0 \ XQuAD | Google Translate         |  10,174 |  10,174 |
| test  | SQuAD-dev-v2.0 & XQuAD | Google Translate + Human |   1,699 |   1,699 |

## Other Similar Datasets (External)

### 📁 [SICK-NL](https://github.com/gijswijnholds/sick_nl) [translated [SICK](https://marcobaroni.org/composes/sick.html)] <small>(Natural Language Inference)</small>

Translation of [Sentences Involving Compositional Knowledge (SICK)](https://marcobaroni.org/composes/sick.html).

| Split | Source     | Procedure     | English | Dutch |
| ----- | ---------- | ------------- | ------: | ----: |
| train | SICK-train | DeepL + Human |   4,439 | 4,439 |
| dev   | SICK-trial | DeepL + Human |     495 |   495 |
| test  | SICK-test  | DeepL + Human |   4,906 | 4,906 |
