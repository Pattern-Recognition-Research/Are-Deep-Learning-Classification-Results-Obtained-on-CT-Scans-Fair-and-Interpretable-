# Are-Deep-Learning-Classification-Results-Obtained-on-CT-Scans-Fair-and-Interpretable-

Following the great success of various deep learning methods in image and object classification, the biomedical image processing society is also overwhelmed with their applications to various automatic diagnosis cases. Unfortunately, most of the deep learning-based classification attempts in the literature solely focus on the aim of extreme accuracy scores, without considering interpretability, or patient-wise separation of training and test data. For example, most lung nodule classification papers using deep learning randomly shuffle data and split it into training, validation, and test sets, causing certain images from the CT scan of a person to be in the training set, while other images of the exact same person to be in the validation or testing image sets. This can result in reporting misleading accuracy rates and the learning of irrelevant features, ultimately reducing the real-life usability of these models. When the deep neural networks trained on the traditional, unfair data shuffling method are challenged with new patient images, it is observed that the trained models perform poorly. In contrast, deep neural networks trained with strict patient-level separation maintain their accuracy rates even when new patient images are tested. Heat-map visualizations of the activations of the deep neural networks trained with strict patient-level separation indicate a higher degree of focus on the relevant nodules. We argue that the research question posed in the title has a positive answer only if the deep neural networks are trained with images of patients that are strictly isolated from the validation and testing patient sets.

https://arxiv.org/abs/2309.12632




![image](https://github.com/Pattern-Recognition-Research/Are-Deep-Learning-Classification-Results-Obtained-on-CT-Scans-Fair-and-Interpretable-/assets/152629804/4efc2606-d81c-46ad-858b-cc52101b1def)
