The raw dataset can be found in the zip file, FakeNewsNet-master

Data preparation was run in the Preprocessing.ipynb file which filters the raw dataset into the useable dataset. 
The cleaned dataset is found in df_gosscop.xls. The extracted images are also provided in the images folder.
From this cleaned dataset, the text and image features were extracted. The feature extraction files are found in:
Text-BERT_Features, Text-RoBERTa_Features, Text-XLNET_Features, Image Features-VGG16, Image Features-VGG19, and Image Features-Xception.

The feature extraction files with fine-tuning are found in: Transfer Learning - Xception-Block13, Transfer Learning - Xception-Block12, and Transfer Learning - Xception-Block9.

Experiment 1 results for the text only model results are in Gosscop_BERT_Only_FINAL, Gosscop_RoBERTa_Only_FINAL, and Gosscop_XLNET_Only_FINAL.
Experiment 2 results image only model results without finetuning are in Gosscop_VGG16_Only_FINAL, Gosscop_VGG19_Only_FINAL, Gosscop_Xception_Only_FINAL.
Experiment 3 results for the source task datasets are in Gosscop_VGG16_Only_FINAL and Gosscop_VGGFace_NoFineTuning.
Experiment 4 results for different fine-tuning levels are in Gosscop_Xception_Only_FINAL, Gosscop_Xception_Block13_Tuned, Gosscop_Xception_Block12_Tuned, and Gosscop_Xception_Block9_Tuned.
The multi-modal model results are in the XLNET_Xception file.

The statistical test results are in the statistical_tests file.

