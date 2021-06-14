# Canvassing with Google Maps
Canvassing is of a great importance in the marketing world. For simplicity, canvassing is the act of producing new leads in order to fulfill a sales target. This can be done differently for different kind of industry.

In the food delivery industry, one of the targets is to get as many merchants as possible to join the food delivery platform. This would help the platform to be more appealing to more user as they could find a wide range of options. In this case, the lead is in the form of restaurant data in a specific area that a salesman is assigned to. 

Conventionally, it is done by directly visiting the target spot or manually search on the internet, for example. However, it becomes troublesome when the target number of merchants is considerably high, let's say, 50 merchants per month. Getting 50 data manually is already no vacation, let alone the fact that not all 50 will agree to join our platform. 

Therefore, we could use Selenium to help us getting the data that we previously need to do manually. We could even get much more than 50 data as a back up. It may take time to run the script, but spending one day to retrieve hundreds of data will be worth the time since the remaining days could be spent on focusing to approach the potential merchants from the data retrieved.

<img src="food delivery.jpg" width="35%" height="35%">
Photo by cottonbro from Pexels
<br>
<br>
Here, I use Selenium to scrape information from Google Maps. 
First, we decide on the area of focus that we would like to target, then direct our browser to the Google Maps url of that location using chromedriver (as I use Chrome), and finally retrieve the information. The information needed are: name of the restaurant, its address, and its phone number. We could also add other information as long as it is available on the information card shown in Google Maps page. Dig in to the code for further details on how to do that! :)
