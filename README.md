# SmartTravelPlanner
Everyone travels on vacation to get away from their hectic schedules, but organizing these getaways takes a
lot of work. One of the primary reasons for this is a lack of platforms that provide individualized vacation planning
information. Users must look for good-reviewed hotels and restaurants on their own and design an adequate itinerary
to visit top tourist attractions based on their budget. Through the travel planner proposed in this paper, we aim to
ease this process of vacation planning. To build this model, we gathered data about various tourist locations from
websites such as Holidify, and TripAdvisor using Web scraping. We applied Gaussian Mixture Model Algorithm to
group the hotels, restaurants, and tourist locations based on their geolocation. We also rank the recommendations
given to the user depending on the results of sentiment analysis performed on reviews for each location. For this
Sentiment Analysis, we used the Long Short Term Memory(LSTM) Algorithm. The reviews are scraped from the
TripAdvisor website using the Selenium library in Python. The model also sends an automated email to the user’s
email address with information about recommended clustered locations. This is done using Python’s “smtplib”
module, which employs the Simple Mail Transfer Protocol.
![image](https://github.com/VandanaVipparthi/SmartTravelPlanner/assets/79081616/e80be64d-188d-4604-b04d-aabb691c9a96)
![image](https://github.com/VandanaVipparthi/SmartTravelPlanner/assets/79081616/e40ef6e5-e8e7-4295-9e6a-dbb81f8dc60b)
![image](https://github.com/VandanaVipparthi/SmartTravelPlanner/assets/79081616/a82b9407-a509-4875-b010-edf2d28ce1f4)
![image](https://github.com/VandanaVipparthi/SmartTravelPlanner/assets/79081616/3ad9b2c3-1d4a-46c2-b3d2-cc3f3b372ca1)
![image](https://github.com/VandanaVipparthi/SmartTravelPlanner/assets/79081616/ba801eb9-daef-40bf-8da2-1a9a3fd03792)
