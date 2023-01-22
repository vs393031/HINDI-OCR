# Hindi-Character-Recognition

Install the requirements: `pip install -r requirements.txt`

1. Hindi Character Recognition

    ![App](https://user-images.githubusercontent.com/54038552/210263132-2e95ad65-5049-4a8c-b453-2616cbc4df20.gif)

    Getting the data:
    - Download the data from [here](https://www.kaggle.com/datasets/suvooo/hindi-character-recognition)
    - Unzip it. You need to split the data into 4 different directories, since we are training for Hindi digits & letters separately.
    ![image](https://user-images.githubusercontent.com/54038552/209815855-cd629bdd-5a9a-474e-8ad6-1d4df1954fdc.png)
    
    How to run ?
    - You can create your custom model in the `model.py` file or can go with the `HNet` already present. For custom models created, you need to import them to `train.py`, for them to to use. Remember we are training different models for Hindi Digit & Characters.
    - Now to train the model with default params do, `python train.py`. You can also specify epochs and lr. Most important, is the `model_type`
    - To train do, `python train.py --epochs <num-epochs> --lr <learning-rate> --model_type <type-of-model>`
    
    Running the app:
    - Just so, `streamlit run app.py`
