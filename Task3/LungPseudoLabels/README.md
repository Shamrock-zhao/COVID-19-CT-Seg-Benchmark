We provide lung pseudo labels for public COVID-19 CT datasets, which are generated by the pretrained models.

### COVID-19 Lung CT Lesion Segmentation Challenge - 2020 [(COVID-19-20)](https://covid-segmentation.grand-challenge.org/COVID-19-20/)

- `Task300-Infer-COVID-19-20-Training.zip`: lung pseudo labels of the training set
- `Task300-Infer-COVID-19-20-Validation.zip`: lung pseudo labels of the validation set

**Please keep in mind that these labels are pseudo labels rather than ground truth.** Thus, the product between the images and the pseudo labels is not the complete lung tissue.
One possible usage of the pseudo labels is to extract the bounding box information of the lungs.


