READ ME

In order to run the code in this project, you must follow the following steps
1. recreate the following directory in your google drive: /content/drive/MyDrive/Classes/Intro ML/Project/
2. in the Project folder, add 2 subfolders titled 'Dataset' and 'Models'
3. copy all 5 files into the main Project folder
4. download the .csv version of the dataset (approx. 3.7 Gb) from this link: https://www.kaggle.com/datasets/dennisho/blackjack-hands
5. place the dataset file in the Dataset subfolder and rename it to 'raw'

Then, run the files in this order:
1. Run '0 File Management'. This notebook will reduce the dataset to 25k samples
2. Run '1 Data Preprocessing'. This notebook will perform all the data preprocessing tasks outlined in the report for both returns based and strategic labelling
3. Run 'Model_training_1' and 'Model_training_2'. These will train all the models, save the models to the 'Models' folder, and automatically calculate all metrics discussed in the report
4. Run 'Winrate'. This notebook will perform the blackjack simulation and generate the results discussed in the report