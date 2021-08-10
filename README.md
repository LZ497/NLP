# ANLY-580 Natural Language Processing


#### Instructor: Chris Larson

#### Term: Fall 2021

#### Section 1: Mondays 6:30-9pm EST (Remote)

#### Section 2: Thursdays 3:30-6pm EST (Intercultural Center Rm.115)

#### Prerequisites: ANLY-501 Machine Learning

#
## Course Description
Natural language processing (NLP) is a critical component of modern information systems. The confluence of deep learning, massive datasets, and hardware accelerators has resulted in systems that approach and in some cases exceed human level performance on benchmark language tasks. This course explores three principal questions: 1) how do we frame language understanding as a tractable statistical inference problem, 2) what are the current state-of-the-art modeling approaches, and 3) how are NLP systems designed and evaluated. In exploring these questions the course exposes students to the foundational math, implementation methods, practical applications, and current research directions in the field. The course will focus less on task-specific feature engineering in order to provide a more complete exposition of the methods that have proven to be most successful in real world applications such as web search, recommender systems, voice and text based chatbots, and machine translation. This course assumes a basic understanding of linear algebra, probability theory, first order optimization methods, and neural networks.


## Reference Texts
1. <a href="https://github.com/jacobeisenstein/gt-nlp-class/blob/master/notes/eisenstein-nlp-notes.pdf">Jacob Eisenstein. Natural Language Processing</a>
2. <a href="https://web.stanford.edu/~jurafsky/slp3/ed3book_dec302020.pdf">Dan Jurafsky, James H. Martin. Speech and Language Processing (3rd ed. draft)</a>


## Course Structure
This course will consist of 14 2.5 hour classes. Each class is broken down into a lecture and lab. Both lecture and lab attendance is required. Lab participation is part of the grade, and will be assessed based on in-lab participation and submitted code. The first lab will cover [Github onboarding instructions](https://github.com/chrislarson1/GU-ANLY-580-FALL-2021/blob/main/github-setup.md).


## Course Grade

|   Component        | Weight |         Description         |
| :-----------:      | :----: | :-------------------------: |
| Course Policy Exam |    5%  |   Take home, individual     |   
| Assignment 1       |   10%  |   individual                | 
| Assignment 2       |   10%  |   individual                | 
| Assignment 3       |   10%  |   individual                |
| Assignment 4       |   10%  |   individual                |  
| Final Project      |   40%  |   Groups <= 4               | 
| Lab participation  |   15%  |   --                        | 


## Using Github
All course materials will be distributed through **this** repository: https://github.com/chrislarson1/GU-ANLY-580-FALL-2021.git.  Students will submit assignments, exams, and projects to private forks of this repository which the instructor will have access to. Setup instructions are [here](https://github.com/chrislarson1/GU-ANLY-580-FALL-2021/blob/main/github-setup.md).


## Course Schedule

|   Section I  |   Section II   | Lecture |           Description       |    Course Materials     |
| :----------: | :------------: | :-:     | :------------------------- | :---------------------- |
|    Aug 25      |     Aug 26   | 1  | **Introduction to NLP and deep learning** <br> - Course overview <br> - Math refresher <br> **Lab** <br> - Github onboarding <br> - Python environment setup <br> [<a href="https://github.com/chrislarson1/GU-ANLY-580-FALL-2021/tree/main/lectures/lecture-01">Slides</a>] [<a href="https://github.com/chrislarson1/GU-ANLY-580-FALL-2021/tree/main/labs/lab-01">Code</a>] 		| Suggested Reading: <br> [<a href="http://cs229.stanford.edu/section/cs229-linalg.pdf">Eisenstein, Appendix A, B.1, B.2</a>] <br> [<a href="http://cs229.stanford.edu/section/cs229-linalg.pdf">Linear algebra review</a>] <br> [<a href="http://www.columbia.edu/~ks20/4404-Sigman/Notes-Review-Prob.pdf">Probability theory review</a>] <br> [<a href="https://web.stanford.edu/~jurafsky/slp3/ed3book_dec302020.pdf">Jurafsky & Martin, Chp 7</a>] <br> [<a href="https://arxiv.org/pdf/2004.03705.pdf">Review of neural network architectures</a>] <br> [<a href="https://arxiv.org/pdf/1609.04747.pdf">Overview of SGD algorithms</a>] <br> [[Git+GitHub tutorial](https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners)] |
|    Aug 29      |     Sep 01   |  | Course Policy Exam Due **11:59pm EST** | [<a href="https://github.com/chrislarson1/GU-ANLY-580-FALL-2021/blob/main/exams/course-policy-exam.md">Exam link</a>] |
|    Aug 30      |     Sep 02   | 2  | **Text Classification: Part I** <br> - Bag-of-words (BOW) <br> - Naive Bayes <br> - Softmax regression <br> **Lab** <br> - Text Normalization <br> - Introduction to <a href="https://spacy.io/">Spacy</a> <br> [<a href="">Slides</a>] [<a href="">Code</a>] | Suggested Reading: <br> [<a href="https://github.com/jacobeisenstein/gt-nlp-class/blob/master/notes/eisenstein-nlp-notes.pdf">Eisenstein, Chps 2.1, 2.2, 2.5</a>] <br> [<a href="https://web.stanford.edu/~jurafsky/slp3/ed3book_dec302020.pdf">Jurafsky & Martin, Chp 2.4,4</a>] <br> [<a href="https://www.aaai.org/Papers/ICML/2003/ICML03-081.pdf">Rennie et al., ICML 2003</a>]   |
|    Sep 13      |     Sep 09   | 3 | **Text Classification: Part II** <br> - The perceptron <br> - The linear SVM <br> **Lab** <br> - Linear text classification on DBpedia dataset <br> [<a href="">Slides</a>] [<a href="">Code</a>] 	| Suggested Reading: <br> [<a href="https://github.com/jacobeisenstein/gt-nlp-class/blob/master/notes/eisenstein-nlp-notes.pdf">Eisenstein, Chps 2.3, 2.4</a>]   |
|    Sep 19      |     Sep 15   |  | Assignment 1 Due **11:59pm EST** | [<a href="https://github.com/chrislarson1/GU-ANLY-580-FALL-2021/blob/main/assignments/assignment-1.pdf">Assignment link</a>] |
|    Sep 20      |     Sep 16   | 4  | **Distributional Semantics: Part 1** <br> - Low-rank factorization methods  <br> - LSA, topic modeling <br> **Lab** <br> - Extracting topics from news feeds <br>  [<a href="">Slides</a>] [<a href="">Code</a>]  	| Suggested Reading: <br> [<a href="http://cse.msu.edu/~cse960/Papers/LSI/LSI.pdf">LSI overview</a>] <br> [<a href="https://davetang.org/file/Singular_Value_Decomposition_Tutorial.pdf">SVD tutorial</a>] <br> [<a href="https://www.jmlr.org/papers/volume3/blei03a/blei03a.pdf">Bei, et al., JMLR 2003</a>] <br> [<a href="https://radimrehurek.com/gensim/">Gensim website</a>]     |
|    Sep 27      |     Sep 23   | 5  | **Distributional Semantics: Part 2** <br> - Distributional hypothesis <br> - Skip-gram models & Word2Vec <br> **Lab** <br> - Visualizing Tweets with Word2Vec <br> [<a href="">Slides</a>] [<a href="">Code</a>]  	| Suggested Reading: <br> [<a href="https://github.com/jacobeisenstein/gt-nlp-class/blob/master/notes/eisenstein-nlp-notes.pdf">Eisenstein, Chp 14</a>] <br> [<a href="https://arxiv.org/pdf/1301.3781.pdf">Mikolov et al., 2013</a>] <br> [<a href="https://pair-code.github.io/understanding-umap/">Blogpost on tSNE, UMAP</a>]    |
|    Oct 03      |     Sep 29   |  | Assignment 2 Due **11:59pm EST** | [<a href="">Assignment link</a>] |
|    Oct 04      |     Sep 30   | 6  | **Language Modeling: Part 1** <br> - N-grams, sparse data & smoothing <br> - Markov models <br> - Viterbi algorithm <br> **Lab** <br> - Build a semantic matching service with <a href="https://github.com/facebookresearch/StarSpace">StarSpace</a> and <a href="https://github.com/chrislarson1/virtex">Virtex</a> <br> [<a href="">Slides</a>] [<a href="">Code</a>]  | Suggested Reading: <br> [<a href="https://github.com/jacobeisenstein/gt-nlp-class/blob/master/notes/eisenstein-nlp-notes.pdf">Eisenstein, Chp 6.1-6.2</a>] <br> [<a href="https://web.stanford.edu/~jurafsky/slp3/ed3book_dec302020.pdf">Jurafsky & Martin, Chps 3, 8</a>] <br> [<a href="https://arxiv.org/pdf/1607.04606.pdf">Bojanowski et al., 2017</a>] <br> [<a href="https://arxiv.org/pdf/1709.03856.pdf">Wu et al., 2017</a>] <br> [<a href="https://fasttext.cc/">FastText</a>] |
|    Oct 18      |     Oct 07   | 7  | **Language Modeling: Part 2** <br> - Introduction to neural language models <br> - Next word prediction <br> - Downstream tasks <br> - Evaluation metrics <br> **Lab** <br> - Course project kick-off <br> [<a href="">Slides</a>] [<a href="">Code</a>]  | Suggested Reading: <br> [<a href="https://github.com/jacobeisenstein/gt-nlp-class/blob/master/notes/eisenstein-nlp-notes-10-15-2018.pdf">Eisenstein, Chp 3</a>] <br> [<a href="http://nlpprogress.com/">NLP Progress website</a>] <br> [<a href="https://huggingface.co/datasets">Huggingface Datasets</a>] <br> [<a href="https://aclanthology.org/W18-5446.pdf">Wang et al., 2018</a>] <br> [<a href="">Project description</a>] |
|    Oct 24      |     Oct 13   |  | Assignment 3 Due **11:59pm EST** | [<a href="">Assignment link</a>] |
|    Oct 25      |     Oct 14   | 8  | **Neural Network Architectures for Sequences: Part I** <br> - Convolutional filtering <br> - RNNs, Seq2Seq models <br> - Bidirectionality & ELMO <br> - Siamese nets <br> **Lab** <br> - Introduction to <a href="https://huggingface.co/datasets">Huggingface</a> <br> - Train OpenNMT on en-de dataset <br> [<a href="">Slides</a>] [<a href="">Code</a>]  | Suggested Reading: <br> [<a href="https://web.stanford.edu/~jurafsky/slp3/ed3book_dec302020.pdf">Jurafsky & Martin, Chp 9</a>] <br> [<a href="https://github.com/jacobeisenstein/gt-nlp-class/blob/master/notes/eisenstein-nlp-notes-10-15-2018.pdf">Eisenstein, Chp 6.3</a>] <br> [<a href="https://arxiv.org/pdf/1508.06615.pdf">Kim et al., 2016</a>] <br> [[Minaee et al., 2020 (Sec. 2.8)](https://arxiv.org/pdf/2004.03705.pdf)] |
|    Nov 01      |     Oct 21   | 9  | **Neural Network Architectures for Sequences: Part II** <br> - Masked language model training <br> - Attention <br> - Transformers (BERT, GPT*, ...) <br> **Lab** <br> - Finetune BERT on DBpedia, CoNLL-2003, SQuADv2 <br> [<a href="">Slides</a>] [<a href="">Code</a>]   | Suggested Reading: <br> [<a href="https://arxiv.org/pdf/1609.08144v2.pdf">Wu et al., 2016</a>] <br> [<a href="https://arxiv.org/pdf/1706.03762.pdf">Vaswani et al., 2017</a>] <br> [<a href="https://arxiv.org/pdf/1810.04805.pdf">Devlin et al., 2019</a>] <br>  [<a href="https://arxiv.org/pdf/2005.14165.pdf">Brown et al., 2020</a>] <br> [<a href="https://cdn.openai.com/palms.pdf">Solaiman et al., 2021</a>] |
|    Nov 07      |     Oct 27   |  | Assignment 4 Due **11:59pm EST** | [<a href="">Assignment link</a>] |
|    Nov 08      |     Oct 28   | 10 | **Speech Processing Part I: Speech to Text (STT)** <br> - RNN Transducers, CTC <br> - Transformer based models  <br> **Lab** <br> - Finetune E2E RNNT on your own voice <br> [<a href="">Slides</a>] [<a href="">Code</a>]   | Suggested Reading: <br> [<a href="https://arxiv.org/pdf/1211.3711.pdf">Graves, 2012</a>] <br> [<a href="https://arxiv.org/pdf/1811.06621.pdf">He et al., 2018</a>]     |
|    Nov 15      |     Nov 04   | 11 | **Speech Processing Part II: Text to Speech (TTS)** <br> *Voice Synthesis using Tacotron2 & Waveglow* <br> Guest: Tarek Lahlou <br> Distinguished Data Scientist, Walmart Labs <br> **Lab** <br> - Project work <br> [<a href="">Slides</a>] [<a href="">Code</a>]  | Suggested Reading: <br> [<a href="https://deepmind.com/blog/article/wavenet-generative-model-raw-audio">Deepmind blog post</a>] <br> [<a href="https://arxiv.org/pdf/2006.03575.pdf">Donahue et al., ICLR 2021</a>] <br> [<a href="https://arxiv.org/pdf/2102.04040.pdf">Luo et al., 2021</a>]    |
|    Nov 10      |     Nov 10   |  | Project proposals due **11:59pm EST** | [<a href="">Project description link</a>] |
|    Nov 22      |     Nov 11   | 12 | **Dialogue Systems: Part I** <br> - Dialogue management <br> - Entity extraction, slot filling <br> - Policy based dialogue <br> **Lab** <br> - Introduction to Rasa <br> [<a href="">Slides</a>] [<a href="">Code</a>]    | Suggested Reading: <br> [<a href="https://web.stanford.edu/~jurafsky/slp3/ed3book_dec302020.pdf">Jurafsky & Martin, Chp 24</a>] <br> [<a href="https://arxiv.org/pdf/1712.05181.pdf">Bocklisch et al., 2017</a>]             |
|    Nov 29      |     Nov 18   | 13  | **Dialogue Systems: Part II** <br> *Introduction to Jarvis* <br> Guest: Oluwatobi Olabiyi <br> Senior Research Manager, NVIDIA <br> **Lab** <br> - Project work <br> [<a href="">Slides</a>]  	|     |
|    Dec 06      |     Dec 02   | 14 | **NLP System Design** <br> - REST, HTTP, RPCs <br> - Containerization & cloud deployment <br> - Production model serving  <br> **Lab** <br> - Deploy an embedding service on a VM<br> [<a href="">Slides</a>] [<a href="">Code</a>]     |        |
| TBD    | TBD    |  | Final project poster session & demos | |
