About This Fork
===============

This fork extends the original `Transformer-MM-Explainability <https://github.com/hila-chefer/Transformer-MM-Explainability>`_ repository by adding an evaluation and analysis pipeline on top of their DETR-based feature visualization method.

This study compares the features learned by transformer networks on synthetic and real image data by analyzing their size, quantity, and spatial distribution using a feature visualization technique to investigate the networks' decision-making processes.

Furthermore, the study explores the impact of enhancing the realism of synthetic images using generative artificial intelligence techniques on model performance. Specifically, it investigates whether more realistic synthetic images influence the transfer of learned features to real-world applications, with the aim of addressing the domain gap between synthetic and real-world images.

It then introduces an approach to evaluate model behavior through occlusion of these significant features. Additionally, a framework is provided for comparing the features identified on test images by models trained on synthetic data and those trained on real data, enabling an assessment of the differences between the models.

Pretrained Models
========

All pretrained DETR checkpoints used in our paper are available at:

[Dropbox](https://www.dropbox.com/scl/fo/voa8orqf9ho4rpcud6x67/APGMblY-Fi8bhL1eN_Eu4Cg?rlkey=j8c59n90njebvuebz0fv7rb40&st=rtvvpxnt&dl=0)  

Associated paper: *“Paper Title”* (link coming soon)

Citation
========

If you use this code, please link to this repository.

.. code-block:: latex

   % Our paper (preprint link will be added soon)
   % @InProceedings{Citation,
   %    author    = {Trescher, Denis and Haag, Waldenar and Schröder, Enrico},
   %    title     = {Visualizing-and-Interpreting-Neural-Network-Features},
   %    booktitle = {Conference},
   %    year      = {2025},
   %    url       = {https://arxiv.org/abs/paper},
   % }

Original visualization code:

.. code-block:: latex

   @InProceedings{Chefer_2021_ICCV,
      author    = {Chefer, Hila and Gur, Shir and Wolf, Lior},
      title     = {Generic Attention-Model Explainability for Interpreting Bi-Modal and Encoder-Decoder Transformers},
      booktitle = {Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV)},
      month     = {October},
      year      = {2021},
      pages     = {397-406}
   }

We acknowledge the original authors for their foundational work on explainability for transformer models.

This project builds on their `Transformer-MM-Explainability <https://github.com/hila-chefer/Transformer-MM-Explainability>`_ repo, specifically the DETR visualization component.

The original project also credits:

- VisualBERT implementation is based on the `MMF framework <https://github.com/facebookresearch/mmf>`_
- LXMERT implementation is based on the `official LXMERT repo <https://github.com/airsplay/lxmert>`_ and `Hugging Face Transformers <https://github.com/huggingface/transformers>`_
- DETR implementation is based on the `official DETR repo <https://github.com/facebookresearch/detr>`_
- CLIP implementation is based on the `official CLIP repo <https://github.com/openai/CLIP>`_
- The CLIP Hugging Face Spaces demo was made by Paul Hilders, Danilo de Goede, and Piyush Bagad from the University of Amsterdam as part of their `final project <https://github.com/bpiyush/CLIP-grounding>`_