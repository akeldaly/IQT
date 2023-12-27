# IQT
# Alternative Learning Paradigms for Image Quality Transfer

**Abstract:**
Image Quality Transfer (IQT) aims to enhance the contrast and resolution of low-quality medical images, e.g. obtained from low-power devices, with rich information learned from higher quality images. In contrast to existing IQT methods in the literature which adopt supervised learning frameworks, in this work, we propose two novel formulations to the IQT problem. The first approach uses an unsupervised learning framework, whereas the second is a blend of both supervised and unsupervised learning. The unsupervised learning approach considers a sparse representation (SRep) and dictionary learning model, that we call IQT-SRep, whereas the blend of supervised and unsupervised learning approach is based on deep dictionary learning (DDL), that we call IQT-DDL. The IQT-SRep approach trains two dictionaries using a sparse representation model using pairs of low- and high-quality volumes. Subsequently, the sparse representation of a low-quality block, in terms of the low-quality dictionary, can be directly used to recover the corresponding high-quality block using the high-quality dictionary. On the other hand, the IQT-DDL approach explicitly learns a high-resolution dictionary to upscale the input volume, while the entire network, including high dictionary generator, is simultaneously optimised to take full advantage of deep learning methods. The two models are evaluated using a low-field magnetic resonance imaging (MRI) application aiming to recover high-quality images akin to those obtained from high-field scanners. Experiments comparing the proposed approaches against state-of-the-art supervised deep learning IQT method (IQT-DL) identify that the two novel formulations to the IQT problem can avoid bias associated with supervised methods when tested using out-of-distribution data that differs from the distribution of the data the model was trained on. This highlights the potential benefit of these novel paradigms for IQT.

This respiratory provides codes used in the paper 
Ahmed Karam Eldaly, Matteo Figini, and Daniel C. Alexander ''Alternative Learning Paradigms for Image Quality Transfer'', submitted to Imaging Neuroscience 2024.

**Citation:**
If you find this work useful, please consider citing it.

@InProceedings{Eldaly2024Alternative,
  author={Eldaly, Ahmed Karam and Figini, Matteo and Alexander, Daniel C.},
  title={Alternative Learning Paradigms for Image Quality Transfer},
  booktitle = {Submitted to Imaging Neuroscience},
  year = {2024}
}
