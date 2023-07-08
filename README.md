# Movie-Recommendation-System
A web application that predicts top five movies for user based on the content watched by them frequently.It uses tmdb dataset from kaggle and it considers similarity scores for recommending right choices for customer.
# How to use
Firstly,Create new virtual enviornment env and activate it using following command .
```bash
pip install virtualenv
virtualenv env
env\Scripts\activate.ps1
```
Install necessary packages using following command.
```bash
pip install -r requirements.txt
```
Use this command to make pickle file
```bash
import pickle
pickle.dump(new,open('movie_list.pkl','wb'))
pickle.dump(similarity,open('similarity.pkl','wb'))
```
To start the application use this command
```bash
python app.py
```
