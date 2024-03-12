# [M214A-Project](https://github.com/dotimothy/M214A-Project)
Final Project Repository of M214A for Winter Quarter 2024. Task: Dialect Region Classification of African American Speakers in the CORAAL Dataset <br> <br>
**Authors:** Keith Chen, [Timothy Do](https://timothydo.me), [James Shiffer](https://jshiffer.xyz), Thomas Sison

## Dependencies
The dependencies with specific versions for this project is listed under <code>requirements.txt</code>.

## Setup
1. Run <code>pip install -r requirements.txt</code> to check and install all Python dependencies.
2. Download the Project Data <code>W24 ECE M214A Project.zip</code> and unzip as <code>./W24 ECE M214A Project/</code>
3. If applying pre-trained data augmentation, the preaugmented training labels and features for the best model are in <code>./features_augmented_data_const</code> for issues with download time and compatibility. For reference the preaugmented training set can be downloaded from [UCLA Box](https://ucla.app.box.com/s/aokss65cdcssljirh3wmnml0twzescsm) into <code>./W24 ECE M214A Project/project_data/</code> and unzip as <code>augmented_data_with_adjustable_chatter</code> in the same folder to extract features and label independently with different hyperparameters, but is not required to test the hidden set.
4. Run <code>jupyter notebook</code> and open the <code>Project.ipynb</code> to perform the task progressively! For just extracting and testing the best features with the hidden set refer to section 9 of the notebook.




## Contact
For issues/questions about the code contact Timothy at [timothydo@ucla.edu](mailto:timothydo@ucla.edu).

