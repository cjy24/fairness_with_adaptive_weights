# fairness_with_adaptive_weights
 We propose a novel adaptive reweighing method to address representation bias. The goal of our method is to achieve group-level balance among different demographic groups by learning adaptive weights for each sample. Our approach emphasizes more on error-prone samples in prediction and enhances adequate representation of minority groups for fairness. We derive a closed-form solution for adaptive weight assignment and propose an efficient algorithm with theoretical convergence guarantees. We theoretically analyze the fairness of our model and empirically verify that our method strikes a balance between fairness and accuracy. In experiments, our method achieves comparable or better performance than state-of-the-art methods in both classification and regression tasks. Furthermore, our method exhibits robustness to label noise on various benchmark datasets. Paper available at: https://proceedings.mlr.press/v162/chai22a/chai22a.pdf

# Configuration
 Please install all necessary packages via: pip install -r requirements.txt
  

# Usage
 To run the experiments, please change the file directory to current directory. The hyperparameter a can be determined by cross validation, and the constant c can be set as the number of samples in major group.


# Citation
 @inproceedings{chai2022fairness,
  title={Fairness with adaptive weights},
  author={Chai, Junyi and Wang, Xiaoqian},
  booktitle={International Conference on Machine Learning},
  pages={2853--2866},
  year={2022},
  organization={PMLR}
}
