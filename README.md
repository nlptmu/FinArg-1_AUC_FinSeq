# Finarg-1_AUC_-FinSeq
<img width="967" alt="image" src="https://github.com/nlptmu/Finarg-1_ARC_-BDF4NLI/assets/113884253/2ca99174-8508-4cae-8812-876ef1d3ea01">  

The system architecture of our proposed method is shown in Figure.
First, the Preprocessing Module is crucial in readying data for subsequent steps.Tailored to model needs and the voting process, it handles tasks like padding, truncation, and adding special tokens like [CLS] and [SEP] for Transformer-based models. This module also enhances the dataset by employing techniques like text augmentation, especially beneficial for limited datasets. The Voting Mechanism boosts the prediction performance for the goal.

Given an input argumentative sentence s, the objective is to develop a model m that accurately categorizes s into either the argument unit A={claim, premise} class. 

The proposed method features four separate BERT-based language models: RoBERTa, FinBERT, Electra, and BERT-base-uncased. These models are independently trained and their predictions are combined using a hard voting strategy.

## Reference
Please cite these papers in your publications if AUC_FinSeq helps your research.

    @Article{
      author = {Hen-You Lin, Eugene Sy, Tzu-Cheng Peng, Shih-Hsuan Huang, Yung-Chung Chang},
      conference = {NTCIR-17},
      title = {TMUNLP at the NTCIR-17 FinArg-1 Task},
      year = {2023}
    }
    @Article{
      author = {Eugene L. Sy,Tzu-Cheng Peng, Shih-Hsuan Huang, Hen-You Lin, Yung-Chung Chang},
      conference = {THE 35TH CONFERENCE ON COMPUTATIONAL LINGUISTICS AND SPEECH PROCESSING},
      title = {Fine-Grained Argument Understanding with BERT Ensemble Techniques:A Deep Dive into Financial Sentiment Analysis},
      year = {2023}
    }
