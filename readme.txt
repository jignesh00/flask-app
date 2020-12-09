Project Name: Web Deployment of Basic model

Libraries used:
1.pandas 
2.numpy
3.sklearn
4.pickle
4.flask
5.request
6.render_template

Firstly a simple model with small dataset is built then after training the model , the same model is saved as pickle file.
then a app is created using flask in which we first load the model, then using the render template model we capture data from index page entered by the user.
The stored data is passed using Post Method and prediction is performed using this data with model and then final predicted value is displayed on the final page using index.html
