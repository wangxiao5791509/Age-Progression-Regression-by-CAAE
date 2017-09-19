# Age-Progression-Regression-by-CAAE
the repaired code of paper "Age Progression/Regression by Conditional Adversarial Autoencoder---CVPR 2017"
the original link is: https://github.com/ZZUTK/Face-Aging-CAAE 
the paper of this code: http://openaccess.thecvf.com/content_cvpr_2017/papers/Zhang_Age_ProgressionRegression_by_CVPR_2017_paper.pdf 
the dataset for training this network can be found in: https://drive.google.com/file/d/0BxYys69jI14kYVM3aVhKS1VhRUk/view?usp=sharing

#### Environment: 
I have tested this code on Tensorflow 1.2.1, it does not have problem. 
The following issues have repaired under tensorflow version 1.2.1: 
  1. TypeError: Expected int32, got list containing Tensors of type '_Message' instead. 
  2. ValueError: Only call 'sigmoid_cross_entropy_with_logits' with named arguments (labels=..., logits=..., ...) 
  3. ValueError: Variable E_conv0/w/Adam/ does not exist, or was not created with tf.get_variable(). Did you mean to set reuse=None in VarScope ? 

  Detailed information could be found in my blog: http://www.cnblogs.com/wangxiaocvpr/p/6646546.html 

Finally, this is a very interesting work. Thanks for the authors. 
