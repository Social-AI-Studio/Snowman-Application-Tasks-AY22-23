## Welcome Note

First of all, thank you for applying to be my graduate student! I am glad that you have made the decision to explore graduate studies at this phase of your life, and I hope that I can be part of your research journey. However, I have received quite many applications every year, and it is impossible for me to accept all of you. Therefore, I have created two tasks to help me understand your strength and suitability to join my research team. The two tasks also give you a flavor of my research interests and what you will be doing as my graduate student. As I was also once a graduate student, I know doing graduate studies is a major decision as you will be spending a good 3-5 years of your life on this graduate program. So it is very important that you like what you do or at least have an idea of what you will be doing in the program.

Do note that completing the two tasks does not guarantee your acceptance into the SUTD PhD program! Officially, you can submit your application through the school's [website](https://istd.sutd.edu.sg/education/phd/phd-application-process/). You may also want refer to this [website](https://www.sutd.edu.sg/Admissions/Graduate/Scholarships) to find out the scholarship and fellowship available to support your graduate studies.

Should you have any questions on the following two tasks, please drop me an email: roy_lee@sutd.edu.sg.

## Task 1a: Hateful Meme Classification
Hateful and offensive content detection has been extensively explored in a single modality such as text. However, such toxic information could also be communicated via multimodal content such as online memes. Therefore, detecting multimodal hateful content has recently garnered much attention in academic and industry research communities. In this task, you are required to perform hateful meme classification, i.e., predict if a given meme is hateful or non-hateful.

You can download the dataset from the [Facebook Hateful Meme Challenge](https://hatefulmemeschallenge.com). You may also refer to the [Facebook MMF solutions](https://mmf.readthedocs.io/en/website/notes/hateful_memes_challenge.html#). You can also refer to the [Facebook's research paper](https://arxiv.org/abs/2005.04790) on the hateful meme challenge.

You are required to report the Accuracy and AUROC on the validation dataset (as the unseen has no labels provided)

**Deliverable**: Submit your Jupyter Notebook/Python codes with your implementation and arrange a date where we can skype to discuss your solution.

Note that I am not just looking at the best performance. I am more interested in your thinking process. Specifically, I will like to know the following:

*  How do you approach this problem?
*  How you decide which text summarization models to implement?
*  How you interpret your results?

This task gives you a sneak preview on what you will be working on after joining my research team. You will be building novel machine learning algorithms, writing codes, designing experiments to evaluate your models, analyzing results, etc. If you find this task fun, then yes, you are the right student, and I am your right supervisor :)


## Task 1b: Text Summarization

Summarization is the process of condensing a piece of text into a shorter version in order to reduce the size of the original text while retaining key informational elements and content meaning. As text summarization is a time-consuming and laborious task, automating the task is gaining popularity and serves as a strong motivator for researchers. In this task, you are required to summarize the text from a sampled publicly available text summarization news article dataset collected for the [notable work by Hermann et al (2015)](http://papers.nips.cc/paper/5945-teaching-machines-to-readand-comprehend.pdf)


You can download the sampled dataset [here](https://drive.google.com/file/d/1EDACA02DFkELXuzMg6pH53MMynrRzitJ/view?usp=sharing). In the folder you will find the following files:
*  **train.txt.src**: News articles used for training.
*  **train.txt.tgt.tagged**:  Summary of the training artciles.
*  **val.txt.src**: News articles used for validation.
*  **val.txt.tgt.tagged**:  Summaries of the validation artciles.
*  **test.txt.src**: News articles used for testing.
*  **test.txt.tgt.tagged**:  Summaries of the testing artciles.

You are required to report your models' BLEU and ROGUE scores on the test dataset.

**Deliverable**: Submit your Jupyter Notebook/Python codes with your implementation and arrange a date where we can skype to discuss your solution.

Note that I am not just looking at the best performance. I am more interested in your thinking process. Specifically, I will like to know the following:

*  How do you approach this problem?
*  How you decide which text summarization models to implement?
*  How you interpret your results?

This task gives you a sneak preview on what you will be working on after joining my research team. You will be building novel machine learning algorithms, writing codes, designing experiments to evaluate your models, analyzing results, etc. If you find this task fun, then yes, you are the right student, and I am your right supervisor :)


## Task 2: Reading Presentation

You would be invited to work on task 2 if you had performed task 1 well! I will send an email to invite you to perform task 2 and coordinate a Skype meeting for you to present the deliverables.

Pick one of the following research papers an present it to me. You are welcome to create slides to aid you in this presentation.

-  [Don't Stop Pretraining: Adapt Language Models to Domains and Tasks](https://arxiv.org/pdf/2004.10964.pdf) (ACL'20)
-  [GCAN: Graph-aware Co-Attention Networks for Explainable Fake News Detection on Social Media](https://arxiv.org/pdf/2004.11648.pdf) (ACL'20)
-  [What Was Written vs. Who Read It: News Media Profiling Using Text Analysis and Social Media Context](https://arxiv.org/pdf/2005.04518.pdf) (ACL'20)
-  [Topic-aware neural keyphrase generation for social media language](https://arxiv.org/pdf/1906.03889.pdf) (ACL'19)
-  [Encoding social information with graph convolutional networks forPolitical perspective detection in news media](https://www.aclweb.org/anthology/P19-1247.pdf) (ACL'19)
-  [Tree LSTMs with Convolution Units to Predict Stance and Rumor Veracity in Social Media Conversations](https://www.aclweb.org/anthology/P19-1498.pdf) (ACL'19)
-  [JNET: Learning User Representations via Joint Network Embedding and Topic Embedding](https://dl.acm.org/doi/pdf/10.1145/3336191.3371770?casa_token=qtyXSQMtu10AAAAA:pLo_HKPiuVHZD4yHb4XOW7P833UwnMC88D1uIKIrOgwb3KEz7R4QRBlIx3-mpGE2eAcLDgo461Am6Q) (WSDM'20)
-  [Beyond News Contents: The Role of Social Context for Fake News Detection](https://dl.acm.org/doi/pdf/10.1145/3289600.3290994?casa_token=_k9_O4y_jBwAAAAA:mGJirrhOGqE_cXaHnGpmEPGAt8fI4ywrEGaC60H3kBF_JdHUWqjcybe7x5rWyaPicWdplvnw_beTbw) (WSDM'19)
-  [Neural Based Statement Classification for Biased Language](https://arxiv.org/pdf/1811.05740.pdf) (WSDM'19)
-  [Homogeneity-based transmissive process to model true and false news in social networks](https://dl.acm.org/doi/pdf/10.1145/3289600.3291009?casa_token=lSeBX2mv46QAAAAA:n3V5L4wxLnb3oRGaWvKVgiVHHcmJ143cKxbZDcI-BN0u3wDcR_TB3wT0YJ4hoAhb-V-TV_OdO6E7Ww) (WSDM'19)
-  [DETERRENT: Knowledge Guided Graph Attention Network for Detecting Healthcare Misinformation](https://dl.acm.org/doi/pdf/10.1145/3394486.3403092?casa_token=wrcnanj1mI0AAAAA:Nj1Xib12nP0JcGj6NFHaAdVq_rworHV64gfMNkpXJ_6hGZEtJpP9n2scRaFSEMWJaoNbCstrsldg_A) (KDD'20)
-  [Cascade-LSTM: A Tree-Structured Neural Classifier for Detecting Misinformation Cascades](https://dl.acm.org/doi/pdf/10.1145/3394486.3403317?casa_token=Mzk8tjHKz30AAAAA:8e90siCm3rH8EFYMTmzaq7uEdw3i9K5cooaSY9Bn7n7pqw5yZFXpdIbPE_DB83Cb4kj5cgPKcID5bw) (KDD'20)
-  [dEFEND: Explainable Fake News Detection](https://dl.acm.org/doi/pdf/10.1145/3292500.3330935?casa_token=uSFWKwPgSgcAAAAA:z1QcUl5sEiXSE4U4wT5KcC6i_E-79Bo1vLSzDjTsctaSuRCIUr3yHbmWvMRmI-lwIc6LVBt2Ye6LVg) (KDD'19)
-  [Neural Based Statement Classification for Biased Language](https://arxiv.org/pdf/1811.05740.pdf) (WSDM'19)
-  [Hate Speech Detection is Not as Easy as You May Think: A Closer Look at Model Validation](https://users.dcc.uchile.cl/~jperez/papers/sigir2019.pdf) (SIGIR'19)
-  [Multilingual and Multi-Aspect Hate Speech Analysis](https://www.aclweb.org/anthology/D19-1474.pdf)(EMNLP'19)
-  [Generating Counter Narratives against Online Hate Speech: Data and Strategies](https://arxiv.org/pdf/2004.04216.pdf) (ACL'20)
-  [Contextualizing Hate Speech Classifiers with Post-hoc Explanation](https://arxiv.org/pdf/2005.02439.pdf) (ACL'20)
-  [Gated Multi-Task Network for Text Classification](https://www.aclweb.org/anthology/N18-2114.pdf) (NAACL'18)
-  [Learning What to Share: Leaky Multi-Task Network for Text Classification](https://www.aclweb.org/anthology/C18-1175.pdf) (ACL'18)

**Deliverable**: Present the paper during the coordinated Skype meeting. Note that you might be asked questions on Task 1 in this interview. 

The purpose of this task is to let you know that as my graduate student, you are required to do tons of readings like this. There will be times where you have absolutely no clue what the paper is talking about as it gets very technical, and this exercise challenges you to think of ways to overcome this problem. Don't worry, I will teach you how to overcome this when you enroll in the program, but before that, I will leave you to think of creative solutions to complete this task :)
