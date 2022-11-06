# Optimal Crop Prediction (HackNC 2022)
## **HackNC 2022 Project Submission created by Shiva Kammala, Edward Baker, and Chloe Holleschak!**

![Alt text](/assets/alternate/hacknc.png?raw=true "HackNC 2022 Logo")

### About
Our project aims to assist farmers in predicting the best crop to be planted based on a variety of environmental variables. As the world’s population increases, one of the most pressing challenges remains ensuring that agricultural supply meets the demand for food. To alleviate this issue, our project takes advantage of existing data from the Indian Chamber of Food and Agriculture (ICFA) to output the optimal fruit or vegetable to be grown based on the provided environmental conditions.

### Technology
To construct the machine learning model for our project, we used the XGBoost software library for Python. XGBoost is an open-source implementation of the gradient boosted trees algorithm. It has been engineered for optimal performance and it is known to perform well for structured, tabular data - one of the key reasons why we selected it. The model generated for our project reached an accuracy of .9964 in prediction when using a 75-25 train-test split of the data. The project utilizes Gradio (https://gradio.app/) to provide an interactive interface for users to input environmental conditions and read the output. 

### Dataset
The dataset is taken from Kaggle (available publicly [here](https://www.kaggle.com/datasets/siddharthss/crop-recommendation-dataset)) and provides a label for the optimal crop based on the Nitrogen, Phosphorous, Potassium, temperature, humidity, pH, and rainfall levels that are observed in the environment. There are a total of 22 possible crop labels in the dataset.

![Alt text](/assets/alternate/dataset_screenshot.png?raw=true "Dataset")

### Operation
To run the project, please download the provided .ipynb file and run the tiles to generate the model. Once this is complete, you will be able to visualize the app in the provided shareable link. First-time users may need to install Python and the associated libraries/tools (Pandas, NumPy, SKLearn, Gradio). Input data in the text boxes on the left and click the submit button to generate the model prediction. The prediction as well as relevant information is displayed on the right.

![Alt text](/assets/alternate/input_screenshot.png?raw=true "Input")
![Alt text](/assets/alternate/rice_screenshot.png?raw=true "Output")

#### Sources
Information for the project was acquired from the following publicly available online resources:
- Unsplash - www.unsplash.com
- The Old Farmer’s Almanac - www.almanac.com
- NSW  Department of Primary Industries - https://www.dpi.nsw.gov.au/agriculture/broadacre-crops/summer-crops/rice-development-guides/rice-growing-guide
- Gardener’s Path - https://gardenerspath.com/plants/
- IndiaAgroNet - https://indiaagronet.com/indiaagronet/crop%20info/crop.htm
- The Spruce - www.thespruce.com
- Gardenia Organic - www.gardeniaorganic.com

**Thank you for visiting our HackNC project!!<br />-Shiva, Eddie, and Chloé**
