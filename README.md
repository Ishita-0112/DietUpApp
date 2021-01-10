# DietUpApp
A neglect in personal health isn't an option, So Here We Present DIETUP at your service.
DIETUP provides AI DIET RECOMMENDATION solutions for helping patients remotely as telehealth solutions are the need of the hour in the current pandemic scenario.

AI DIET PLANNER

* There is a diet planner in our application.

* Helps our end-users get a customized diet plan for them. 

* There are two parts, one which takes in basic user details for profile building, which later will be utilized to connect other users with the similar likes and disliked and they can share their weekly diet plans and commencements. 

* The second part takes in all important metrics like the person’s favourite food, diet, cuisines, nutrients he/she wants their diet to be comprised of, and also about any past medical history or diseases they suffer from.

* All these inputs are fed into our ML model 

* It accurately forms a diet planner for the user, listing out all the meals with their nutrient value and ratings to the user. 

* Using celery running in the background, the diet planner refreshed weekly giving a diversified option to the users.

* The diet prediction algorithm, automatically runs every 7 days, by celery. 

* We used to host the recommendation system on the google cloud virtual machine. It made the whole process seamless!!

* It triggers an automatic notification to the users to re feed the data, if any changes are detected in their personal taste and body mass indexing. 

* It is a very powerful system, which can be extended to various domains. 

* It also amounts the total calories that will be consumed by the user for the particular recommendation, by feeding the items recommended into another Machine Learning Model. 

* Thus, this system enables a remote diet system, which predicts accurately, keeping in mind the health and well being of all our users and the entire society.
