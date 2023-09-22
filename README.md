# Computer Vision Unsupervised Domain Adaptation
To solve this problem i exploited the fact that the transferability of the features extracted varies depending on the depth of the layer that extracted them.

As showed by Yoshua Benjo and collegues in this paper, https://arxiv.org/abs/1411.1792, we see that features extracted at deeper layers are more general and therefore more transferable between domains, my aim is exactly to exploit this fact.

I used some of the ideas explained in the following paper as an inspiration, http://arxiv.org/abs/2004.02093v2, since this paper deals with a different problem, which is object Detection, the architecture i implemented is slightly different and uses different losses, therefore is original to me.

Check the Jupyter Notebook for more detail!
