# Collaborative Decoupling Knowledge Learning for Semantic Segmentation of Hazy Remote Sensing Images

Remote sensing images (RSIs) often suffer from degradation caused by haze, leading to challenges in accurate semantic segmentation. The objects in hazy RSIs tend to have blurry boundaries and indistinguishable appearance, which poses significant difficulties for semantic segmentation tasks. To address this, we introduce a novel collaborative decoupling knowledge learning (CDKL) model specifically tailored for semantic segmentation in hazy RSIs. CDKL comprises three key components: a teacher subnetwork (T-Net), a decoupled subnetwork (D-Net), and collaborative knowledge transfer (CKT). This integrated framework effectively optimizes both dehazing and segmentation tasks, elevating segmentation accuracy in hazy RSIs. Specifically, at first, the T-Net undergoes pre-training using clear RSIs to generate accurate semantic segmentation results. Subsequently, D-Net is developed to simultaneously handle RSI dehazing and semantic segmentation. During D-Net training, T-Net guides feature transfer, facilitating the adaptation of features between clear and hazy images. Additionally, a novel CKT mechanism is introduced to learn intrinsic feature associations between hazy RSIs and clear images, further enhancing dehazing and segmentation performance. Quantitative and qualitative experiments validate the efficacy of CDKL, demonstrating substantial improvements in semantic segmentation accuracy for hazy RSIs. We hope this newly proposed approach can serve as a base research for the community to solve the segmentation problem of hazy RSIs.

# Key words

Remote sensing, segmentation, dehazing, knowledge learning

# Code 
The code will be available after this paper is accepted.
