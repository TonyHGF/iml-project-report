### Scoring

In order to evaluate the models in terms of multiclass classification accuracy, there are mainly three approaches: macro F1-score(MF1), overall accuracy(ACC), Cohen's Kappa coefficient($\kappa$). We split the PSGs into testing set, containing 25\% of data, and the training set, containing the rest 75\%. For all the traditional machine learning models and deep learning models, we use the training set to train the models and use the testing set to check their performance. We compare the output of the models and the ground truth using MF1, ACC and $\kappa$ with the following formulas:
$$
\begin{aligned}
N&=\text{the number of testing samples}\\
k&=\text{the number of catagories}\\
CFM_{i,j}&=\text{the number of samples whose real output is j but prediction is i}\\
TP_i&=CFM_{i,i}\quad FP_j=\sum_{i\neq j}CFM_{i,j}\quad FN_i=\sum_{j\neq i}CFM_{i,j}\\
ACC&=\frac{\sum_{i=1}^{k}TP_i}{N}\\
pre&=\frac{1}{k}\sum_{i=1}^k\frac{TP_i}{TP_i+FP_i}\quad rec=\frac{1}{k}\sum_{i=1}^k\frac{TP_i}{TP_i+FN_i}\\
MF1&=\frac{2*pre*rec}{pre+rec}\\
p_o&=ACC\quad p_e=\frac{\sum_{i=1}^{k}(\sum_{j=1}^kCFM_{i,j})(\sum_{j=1}^kCFM_{j,i})}{N^2}\\
\kappa&=\frac{p_o-p_e}{1-p_e}
\end{aligned}
$$