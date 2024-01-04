
[Learn to Unlearn: Insights into Machine Unlearing](https://arxiv.org/abs/2305.07512): 

> Their research illustrates a mechanism to ex- punge data points from 𝐿2-regularized linear models, provided these models have been trained using a differentiable convex loss function. 
> 
> The approach deployed by them utilizes a Newton step on the model parameters, which proficiently eradicates the influence of the data point under deletion. Additionally, the residual is obscured by introducing random perturbations into the training loss, thereby preventing potential privacy violations. 
> 
> Despite its groundbreaking nature, the proposed methodology has certain restrictions. Firstly, implementing Newton’s optimization method requires the inversion of the Hessian matrix, a task that can pose considerable challenges. Secondly, the technique is not adaptable to models with nonconvex losses. Lastly, the data-dependent bound does not quite succeed in accurately estimating the gradient residual norm, which underlines the need for further enhancements and rigorous scrutiny.