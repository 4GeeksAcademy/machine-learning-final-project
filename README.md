<!-- hide -->
# Machine Learning final project
<!-- endhide -->

- Throughout this bootcamp, we have studied different models based on projects of different areas and types. Now it's time to create your own project using the agorithm that you think is best suited to your problem.
- You will have to find a suitable dataset to work with, process it, train a model and finally make it available for consumption.

> “Hard work always beats talent when talent doesn't work hard” - Tim Notke

## 🌱  How to start this project

1. Create a new repository based on [machine learning project](https://github.com/4GeeksAcademy/machine-learning-python-template/generate) by [clicking here](https://github.com/4GeeksAcademy/machine-learning-python-template).
2. Open the recently created repository on Gitpod by using the [Gitpod button extension](https://www.gitpod.io/docs/browser-extension/).
3. Once Gitpod VSCode has finished opening, start your project following the instructions below.
4. Start your project by following the instructions below.

## 🚛 How to deliver this project

Once you have finished the project, you must deliver:

- The link to your Github repository (already implemented).
- The link to your implemented Machine Learning web application.

## 📝 Instructions

### Group formation

To carry out the final project, students will be organized in teams of 2 to 3 people. The work must be collaborative.

### Project phases

#### Step 1: Problem definition

Start by defining a problem and turn it into a Machine Learning problem. This is the first step, since the data must meet a certain need and the Machine Learning process must aim at satisfying that need.

The choice of the data set must satisfy minimum requirements in terms of number of rows and predictor variables. At a minimum, it must contain:

- 10,000 instances (rows)
- 10 predictor variables, of which there must be at least 1 categorical variable.

#### Step 2: Acquiring and loading the data set

Since in the real world data does not usually arrive in a flat csv file, this data must be acquired by one of the following ways:

- Extracting data from some web page or portal using web scraping techniques.
- Exploitation of a public database using SQL language (the database must support this language).
- Exploitation of a public API to obtain data.

Once we have the data, we must store them in a CSV document and load them in Python using Pandas.

#### Step 3: Perform a complete EDA

This second step is vital to ensure that we keep the variables that are strictly necessary and eliminate those that are not relevant or do not provide information. Use the example Notebook we worked on and adapt it to this use case.

Be sure to conveniently divide the data set into `train` and `test` as we have seen in previous lessons.

#### Step 4: Build the model and optimize it

Once you have your data ready, decide which model fits best and train it. If in doubt, try using several of the models you have already studied. Select the one that best fits the data.

Remember that the hyperparameter optimization step is very important to explore and achieve the best version of the model.

#### Step 5: Deploy the model

Create a Machine Learning web application using your saved model. You can use Flask, Streamlit or any other tool you know.
Use Heroku or another cloud computing platform of your choice to deploy your web application and share it with the world.

### Presentation

The presentation will last 5 minutes per group, so be sure to use your time efficiently. The code will be reviewed, so don't waste time explaining it. Focus on the important points, as if you were trying to sell the project to your company's stakeholders or investors. Keep in mind that they probably don't have a technical background, so try to use simple words and an easy-to-understand presentation. Remember that quality trumps quantity.

Recommended important points to mention in your 5-minute presentation:

- What is the business problem you want to solve?
- How did you collect the data?
- Important patterns found in the data
- What algorithm and evaluation metrics did you use to build your final model?
- Show your web application at work and mention how it can be improved in the future.

> “The secret to getting ahead is to start.” - Mark Twain