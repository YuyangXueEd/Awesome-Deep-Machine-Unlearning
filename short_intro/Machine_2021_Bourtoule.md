
[Learn to Unlearn: Insights into Machine Unlearing](https://arxiv.org/abs/2305.07512): 

> ... Bourtoule et al. introduced an alternative method referred to as SISA. This approach aims to ameliorate the universality and performance of the retrained model. The acronym SISA signifies “Sharded, Isolated, Sliced, and Aggregated training”, and it realizes machine unlearning via incremental unlearning on partitioned data. 
> 
> This technique involves the categorization of data into several isolated shards, followed by further segmenting of the data within each shard. Subsequent to this, incremental learning is implemented, and parameters are archived. Upon receiving a new unlearning request, SISA navigates back to the relevant data slice and initiates retraining from that point. Given that the remaining model parameters have already been preserved, the process of aggregation becomes straightforward and efficient.
> 
> Nonetheless, SISA could potentially experience a drop in performance in each component model when datasets are not sufficiently large, or the learning task is particularly intricate.