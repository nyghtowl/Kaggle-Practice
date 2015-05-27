### Summary

Description of project is at https://www.kaggle.com/c/diabetic-retinopathy-detection

---
### Ideas from Forums

Start Code approach recommends:

- boosted regression trees over the activation levels in the final layers of the NN since its an ordinal regression problem rather than a classification problem
- NN overfit for 0,1,2 vs 3,4 cases
- training NN for 5-10 iterations on the 2-class problems is generally sufficient
- ~ 5 convolution layers?
- If use graphlab keep track of disk space and change GRAPHLAB_CACHE_FILE_LOCATIONS if needed
- [Other datasets to checkout](https://www.kaggle.com/c/diabetic-retinopathy-detection/forums/t/14095/other-diabetic-retinopathy-datasets)
