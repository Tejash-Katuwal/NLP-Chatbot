To train a chatbot for youor own:
1. Replace the contents of new_intents.json with your desired data.
2. Open spacy_train.py to train the model using new_intents.json file as a dataset.


![image](https://github.com/user-attachments/assets/1afca348-82b7-4821-8de2-5eab0d6988d8)


Once the model has been you will have files named classes.pkl,words.pkl,final_chatbot.pth,best_chatbot.pth.

If you wanna run this inference only:
1. Install all dependencies as mentioned in requirements.txt.
2. Run python spacy_inference.py


![image](https://github.com/user-attachments/assets/fe81cfe0-b061-410c-9154-184e63d59ff5)


Note: After installing spacy install spacy english model using:
python -m spacy download en_core_web_sm

for pytorch with GPU install by going to pytorch site or by using pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118.
P.S to use pytorch with GPU you need to have proper CUDA configuration.
