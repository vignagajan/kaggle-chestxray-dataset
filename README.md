# Kaggle Pneumonia Chest Xrays dataset

 This dataset is orginaly published in, https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia
 
 ## Directory Structure
 
 > 
    ├── train                    
    │   ├── NORMAL          
    │   └── PNEUMONIA
    ├── test                    
    │   ├── NORMAL          
    │   └── PNEUMONIA             
    └── val
        ├── NORMAL          
        └── PNEUMONIA
 * There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal).

## Data description
>Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care.

![alt text](https://i.imgur.com/jZqpV51.png)

**Illustrative Examples of Chest X-Rays in Patients with Pneumonia.**

> The normal chest X-ray (left panel) depicts clear lungs without any areas of abnormal opacification in the image. Bacterial pneumonia (middle) typically exhibits a focal lobar consolidation, in this case in the right upper lobe (white arrows), whereas viral pneumonia (right) manifests with a more diffuse ‘‘interstitial’’ pattern in both lungs.

## Preparation

>For the analysis of chest x-ray images, all chest radiographs were initially screened for quality control by removing all low quality or unreadable scans. The diagnoses for the images were then graded by two expert physicians before being cleared for training the AI system. In order to account for any grading errors, the evaluation set was also checked by a third expert.

## Next Steps

This image dataset can be used for many bioscopy analysis and feast for beginners in image classification to play around. Happy coding!

## License
[MIT](https://choosealicense.com/licenses/mit/)