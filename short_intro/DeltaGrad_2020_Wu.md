
[Learn to Unlearn: Insights into Machine Unlearing](https://arxiv.org/abs/2305.07512): 

> DeltaGrad, an exact machine unlearning methodology, emphasizes expedited retraining ... It accomplishes this by training the data designated for deletion in a counteractive manner – that is, by maximizing the loss rather than minimizing it, as is typical in traditional ML scenarios. 
> 
> The resulting reversed model is subsequently integrated with the original model, which is preserved beforehand. Through the application of DeltaGrad, the performance of the model can be well-sustained, given certain constraints on the proportion of data to be removed (1% as suggested in the DeltaGrad publication). 
> 
> Nevertheless, although DeltaGrad is compatible with stochastic gradient descent ML algorithms, it lacks the capability to manage mini-batch sizes.