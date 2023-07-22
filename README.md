# Modern Farming Using Machine Learning🌱
Farming is one of the major sectors that influences a country’s economic growth. Farming is the backbone of our nation. This Project helps the farmers to increase their yield by taking NPK(Nitrogen, Phosphorus, and Potassium) values of soil and predicting Crop recommendation, Fertilizer recommendation, and Plant disease prediction respectively. 

- Crop Recommendation system - > By entering the corresponding nutrient values of your soil, state, and city. The NPK (Nitrogen, Phosphorous, and Pottasium) values to be entered should be the ratio between them. Refer to [this website](https://www.gardeningknowhow.com/garden-how-to/soil-fertilizers/fertilizer-numbers-npk.htm) for more information.

   Note: When you enter the city name, make sure to enter mostly common city names. Remote cities/towns may not be available in the [Weather API](https://openweathermap.org/) from where humidity and temperature data is fetched.

- Fertilizer suggestion system - > Enter the nutrient contents of your soil and the crop you want to grow. The algorithm will tell which nutrient the soil has an excess of or lacks. Accordingly, it will give suggestions for buying fertilizers.

- Disease Detection System - > Upload an image of the leaf of your plant. The algorithm will tell the crop type and whether it is diseased or healthy. If it is diseased, it will tell you the cause of the disease and suggest how to prevent/cure the disease accordingly.
  
## DEMO

- ### Crop recommendation system
  ![demo](https://media.giphy.com/media/90JbjdAa5nDq3TJh5u/giphy.gif)

     In the crop recommendation system, the user can provide the soil data from their side and the application will predict which crop should the user grow.
    
- ### Fertilizer suggestion system
   ![demo](https://media.giphy.com/media/FLftUXMFo8N2bBjAXq/giphy.gif)

     In the fertilizer suggestion system, the user can input the soil data and the type of crop they are growing, and the application will predict what the soil lacks or has an excess of and will recommend improvements. 


- ### Disease Detection system
  ![demo](https://media.giphy.com/media/NnMwEp2tGZdfnJbyjr/giphy.gif)
    
    The last application, which is the plant disease prediction application, the user can input an image of a diseased plant leaf, and the application will predict what disease it is and will also give a little background about the disease and suggestions to cure it.

## DATA SOURCE
The accuracy of the machine learning models depends on the quality and diversity of the data used for training. The Modern Farming system collects data from the following datasets taken from Kaggle
- [Crop recommendation dataset ](https://www.kaggle.com/atharvaingle/crop-recommendation-dataset) 
- [Fertilizer suggestion dataset](https://github.com/Gladiator07/Harvestify/blob/master/Data-processed/fertilizer.csv) 
- [Disease detection dataset](https://www.kaggle.com/vipoooool/new-plant-diseases-dataset)


## TECH STACK
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/python/python.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/html/html.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/css/css.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/javascript/javascript.png"></code>
<code><img height="30" src="https://github.com/tomchen/stack-icons/raw/master/logos/bootstrap.svg"></code>

<code><img height="30" src="https://raw.githubusercontent.com/numpy/numpy/7e7f4adab814b223f7f917369a72757cd28b10cb/branding/icons/numpylogo.svg"></code>
<code><img height="30" src="https://raw.githubusercontent.com/pandas-dev/pandas/761bceb77d44aa63b71dda43ca46e8fd4b9d7422/web/pandas/static/img/pandas.svg"></code>
<code><img height="30" src="https://matplotlib.org/_static/logo2.svg"></code>
<code><img height="30" src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Scikit_learn_logo_small.svg/1280px-Scikit_learn_logo_small.svg.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/pytorch/pytorch/39fa0b5d0a3b966a50dcd90b26e6c36942705d6d/docs/source/_static/img/pytorch-logo-dark.svg"></code>

## Installation

To run the Modern Farming system in your system, follow these steps:
- Clone the Repo by going to your local Git Client and pushing in the command: 

```sh
https://github.com/arunperala/Modern-Farming-using-MachineLearning
```

- Install the Packages: 
```sh
pip install -r requirements.txt
```

- At last push in the command:
```sh
python app.py
```

- Open the localhost url provided after running `app.py` and now you can use the project locally in your web browser.

  
## Contribution Guidelines
Contributions to this project are welcome! If you would like to contribute, please follow these guidelines:
- Fork the repository and create a new branch for your feature or bug fix.
- Implement your changes and ensure the code is properly formatted.
- Submit a pull request, describing your changes and their significance.



##  License
The Modern Farming using Machine Learning project is licensed under the [MIT License](https://opensource.org/licenses/MIT). Feel free to use, modify, and distribute the code according to the terms of this license.
#### Happy Farming!
