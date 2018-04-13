Step1: Download https://drive.google.com/file/d/1ccZSys8u4F_mqNJ97OOlSLe3fjpFLhdv/view?usp=sharing and extract it (and rename the folder to lucene_dir)
Step2: Download https://drive.google.com/file/d/1AD_7xesdcJEtth6SZdF5xTllRqPZ3E6-/view?usp=sharing and extract it (and rename the folder to transe_dir)
Step3: Download https://drive.google.com/file/d/0B7XkCwpI5KDYNlNUTTlSS21pQmM/edit?usp=sharing and put it in a folder glove_dir
Step4: Download https://drive.google.com/drive/folders/1ITcgvp4vZo1Wlb66d_SnHvVmLKIqqYbR?usp=sharing and put them in a folder wikidata_dir
Step5: Put the correct (complete) paths to wikidata_dir, lucene_dir, transe_dir, glove_dir in params.py and params_test.py
Step6: Create a folder say 'Target_Model' where you want the model to be dumped, and make two folders inside it ('dump' and 'model') (e.g. 'mkdir Target_Model/dump' and 'mkdir Target_Model/model')
Step7: Download train_preprocessed.zip from https://drive.google.com/file/d/1HmLOGTV_v18grW_hXpu_s6MdogEJDM_a/view?usp=sharing and extract and put the contents (preprocessed pickle files of the train data) into Target_Model/dump
Step8: Download valid_preprocessed.zip from https://drive.google.com/file/d/1uoBUjjidyDks0pEUehxX-ofB5B_trdpP/view?usp=sharing and extract and put the contents (preprocessed pickle files of the valid data) into Target_Model/dump
Step6: Run ./run.sh for training (the way it has been shown in the run.sh file) where the dump_dir is 'Target_Model' which you have created earlier and the data_dir is the directory containing the downloaded data
Step7: Run ./run_test.sh for training (the way it has been shown in the run_test.sh file) 
