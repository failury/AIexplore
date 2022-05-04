## Instructions

- Download the data from https://drive.google.com/file/d/1R5K_2PlZ3p3RFQ1Ycgmo3TgxvYBzptQG/view?usp=sharing

-  and follow Data section in the report to setup the datafile locations. The file structure would look like this:

 ```
 ProjectRoot
 |   .gitignore
 |   main.ipynb
 |   Mini Project-1.pdf
 |   output.doc
 |   README.md
 |   
 +---.vscode
 |       settings.json
 |       
 +---DAG_ERC_CODE
 |   |   dataloader.py
 |   |   dataset.py
 |   |   evaluate.py
 |   |   LICENSE
 |   |   model.py
 |   |   model_utils.py
 |   |   ORIGINAL.md
 |   |   run.py
 |   |   trainer.py
 |   |   utils.py
 |   |   
 |   +---saved_models
 |   |   +---DailyDialog
 |   |   +---EmoryNLP
 |   |   +---IEMOCAP
 |   |   |       logging.log
 |   |   |       
 |   |   \---MELD
 |   \---__pycache__
 |           dataloader.cpython-39.pyc
 |           dataset.cpython-39.pyc
 |           model.cpython-39.pyc
 |           model_utils.cpython-39.pyc
 |           trainer.cpython-39.pyc
 |           utils.cpython-39.pyc
 |           
 +---data
 |   +---DailyDialog
 |   |       dev_data_roberta.json.feature
 |   |       label_vocab.pkl
 |   |       speaker_vocab.pkl
 |   |       test_data_roberta.json.feature
 |   |       train_data_roberta.json.feature
 |   |       
 |   +---EmoryNLP
 |   |       dev_data_roberta.json.feature
 |   |       label_vocab.pkl
 |   |       speaker_vocab.pkl
 |   |       test_data_roberta.json.feature
 |   |       train_data_roberta.json.feature
 |   |       
 |   +---IEMOCAP
 |   |       dev_data_roberta.json.feature
 |   |       label_vocab.pkl
 |   |       speaker_vocab.pkl
 |   |       test_data_roberta.json.feature
 |   |       train_data_roberta.json.feature
 |   |       
 |   \---MELD
 |           dev_data_roberta.json.feature
 |           label_vocab.pkl
 |           speaker_vocab.pkl
 |           test_data_roberta.json.feature
 |           train_data_roberta.json.feature
 |           
 \---__pycache__
         dataloader.cpython-39.pyc
         dataset.cpython-39.pyc
 ```

- Then run through the cells in main.ipynb