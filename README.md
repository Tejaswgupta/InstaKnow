# InstaKnow

Flutter application that allows user to analyze sentiments of other users based on their captions. This application uses a Machine Learning NLP approach to analyze captions and provide positive, negative and neutral scores as the output.

The flutter application uses ```Provider``` + ```Get_it``` for State Management.

 MVVM(Model-View-(View)Model) Architecture has been used.


## Screenshots

### HomeScreen

![Home_Screen](https://github.com/ketanchoyal/InstaKnow/raw/master/Screenshots/homeScreenDemo.gif)

### App UI Demo

![App_UI](https://github.com/ketanchoyal/InstaKnow/raw/master/Screenshots/UIDemo.gif)

### Public Profile Analyzer

![Analyzer](https://github.com/ketanchoyal/InstaKnow/raw/master/Screenshots/public.png)

### Private Profile Analyzer

![PAnalyzer](https://github.com/ketanchoyal/InstaKnow/raw/master/Screenshots/private.png)

### Example 

![Example](https://github.com/ketanchoyal/InstaKnow/raw/master/Screenshots/example.png)



## Installation and Execution

Download or clone the repository in a directory and cd into folder containing the file ```app.py```.

* Set the FLASK environment variable FLASK_APP to the name of the python file as follows in the terminal (for Windows):

  
```python
set FLASK_APP=app.py 
```

* Run the flask app using the following command:

```python
flask run 
```


