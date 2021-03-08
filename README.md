# causal_profit
Causal cost-sensitive decision-making. 

Classification and causal models are commonly used to identify and subsequently apply customized organizational interventions. The targeting decision, however, entails various benefits and costs. For example, failing to detect a disease has different consequences than diagnosing a disease to a healthy patient. As a result, cost-sensitive methods have been proposed to associate unequal benefits and misclassification costs to different prediction types. 

This repository builds on the foundations of cost-sensitive classification as introduced by Elkan et al. (2001) and the foundations of causal cost-sensitive learning as presented in Verbeke et al. (2020). We formulate a causal cost-sensitive decision-boundary for treatment prescription based on the estimation of the Individual Treatment Effect (ITE), the positive outcome probability of treatment, and cost and benefit parameters of the problem setting. Moreover, a novel causal cost-sensitive ranking based on the formulation of the decision-boundary is proposed. The cost-sensitive ranker maximizes the expected profit across all possible thresholds and facilitates the identification of instances that should be targeted. Unlike conventional causal learning methods, our approach acknowledges the benefit that results of targeting instances for whom the treatment is expected to have a positive effect, as well as its associated costs, e.g., the value of discounts, or losses associated to triggering negative reactions from subjects. Taken together, we aim to increase the effectiveness and profitability of causal models by considering three elements: benefits, costs and ITEs.

We present the application of the proposed ranking method on synthetic and marketing campaign data to illustrate its potential to boost the profitability of causal models. The logistic regression and extreme gradient boosting machine learning algorithms are chosen to estimate treatment effects based on three different causal learning techniques. Subsequently, we report model performance based on the Qini coefficient and profit metrics.

Related paper:

[Olaya, D., Verbeke, W., Van Belle, J., & Guerry, M. A. (2021). To do or not to do: cost-sensitive causal decision-making. arXiv preprint arXiv:2101.01407.](https://arxiv.org/abs/2101.0140).

References:

Elkan, C. (2001, August). The foundations of cost-sensitive learning. In International joint conference on artificial intelligence (Vol. 17, No. 1, pp. 973-978). Lawrence Erlbaum Associates Ltd.

Verbeke, W., Olaya, D., Berrevoets, J., & Maldonado, S. (2020). The foundations of cost-sensitive causal classification. arXiv preprint arXiv:2007.12582.


