Use Anaconda to setup the environment 
Setup
Open Anaconda command prompt
Run the following command
1. conda create -n rasa-nlp python=3.8
2. conda activate rasa-nlp

Put my codes into one folder
Change directory to your folder
3. cd (..........)  

4. pip install rasa
5. pip install spacy
6. python -m spacy download zh_core_web_lg
7. rasa train
8. rasa run -m models --enable-api --cors “*” --debug

Then, click the index.html file.

To open it after setup
Run
1. conda activate rasa-nlp

Change directory to your folder
2. cd (..........) 

3. rasa run -m models --enable-api --cors “*” --debug

Then, click the index.html file.