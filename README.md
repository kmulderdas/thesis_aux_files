# Auxiliary thesis materials 
Listed auxiliary materials for "Adversarial training to improve robustness of deep neutrino classifier in the NOvA experiment".

## Network architecture graphs
The AdCVN framework contains the base architectures for both the ResNet18(Res18) and ModifiedMobileNet(MMNet) CVN models as well as the custom components required for the implementation of the domain adaptation techniques such as the gradient reversal layer and the loss penalization with or without memory structures. Other components such as the incorporation of event weights for training with weighted data are also supported in the framework.


To give a clearer picture of how these various components are incorporated into the model architectures the full network graphs are provided here. 

- [ResNet18](https://github.com/kmulderdas/thesis_aux_files/blob/main/model_GvG_res18_inc_no_weight_viewmodel.png) - Network graph of the ResNet18 CVN architecture.

- [ModifiedMobileNet](https://github.com/kmulderdas/thesis_aux_files/blob/main/model_LL_FHC_mmnet_inc_viewmodel.png) - Network graph of the ModifiedMobileNet CVN architecture.

- [Eventweights](https://github.com/kmulderdas/thesis_aux_files/blob/main/model_GvG_mmnet_inc_weight_viewmodel.png) - Network graph of the ModifiedMobileNet CVN architecture with eventweighting.

- [Gradient Reversal](https://github.com/kmulderdas/thesis_aux_files/blob/main/model_LL_FHC_mmnet_ad_100_x_viewmodel.png) - Network graph of the ModifiedMobileNet CVN architecture with gradient reversal.

- [Loss Penalization without Memory](https://github.com/kmulderdas/thesis_aux_files/blob/main/model_LL_FHC_mmnet_lp_cs_viewmodel.png) - Network graph of the ModifiedMobileNet CVN architecture with loss penalization.

- [Loss Penalization with Memory](https://github.com/kmulderdas/thesis_aux_files/blob/main/model_LL_FHC_mmnet_lpmem_cs_viewmodel.png) - Network graph of the ModifiedMobileNet CVN architecture with memory inclusive loss penalization.
