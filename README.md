# MBTI-Detection
## *Personality Type Detection based on BERT Language Model and Convolutional Neural Network with Ensemble Learning Technique*
Myers-Briggs Personality Indicator (MBTI) is a commonly used personality type identification tool with 4-dimension labels: 
introversion (I)/extroversion (E), sensing (S)/intuition (N), thinking (T)/feeling (F), and judging (J)/perceiving (P). 
These dimensions can be combined to identify 16 different personality
types. MBTI is widely used in various fields, such as company development. In this study, we utilize a corpus
of user-generated content from social media platforms and compute psycholinguistic features for each article
to propose a novel MBTI utilizing a BERT-based model, convolutional neural network (CNN), and ensemble
learning personality trait detection models. First, this study uses a pre-trained BERT-based model to extract
word vector information from the text and employs CNN to extract semantic features. Finally, we combine
the output of CNN with the psycholinguistic features derived from LIWC for multi-label prediction.
Additionally, we employ ensemble learning techniques to combine the BERT-based and RoBERTa-based
MBTI personality trait detection models, thereby building an ensemble model. The proposed method in this
study achieved the best results with accuracies of 86.15%, 90.59%, 85.41% and 80.30% for the four tags I/E,
S/N, T/F, and J/P, respectively. The average accuracy rate is 85.64%, resulting in an overall accuracy rate of
59.29%.
