# Google-My-Business-Reviews
Showing customer reviews on the website is becoming a vital part of business. As customers are the biggest asset of any business, one should show number of happy customers. This project shows Google My Business reviews on the website.

The task is not much difficult, if you are familiar with Javascript you can implement it in your website in few hours.
Before starting you have to get placeId and Google api key/ server key. for that follow below instructions.
1. Go to https://console.developers.google.com/apis
2. Create Project.
3. Click on Enable API Library.
4. Click On Maps Javascript API.
5. Enable it.
6. Click on Credentials.
7. Create credentials for your project and note down <b>Server Key<b>.

Now you have to find PlaceId for your Google My Business.
1. click on below link
https://developers.google.com/places/place-id

2. enter your business address
3. you will get PlaceId with popup showing on Map
4. Note Down your PlaceId.

Now open index.html file 
Replace PlaceId with your placeId in script
it will look like
placeId: 'Your Place Id'

Now enter the server key in below line.
https://maps.googleapis.com/maps/api/js?v=3.exp&key=YourKey&signed_in=true&libraries=places

Congratulations!
Now you can show Google My Business Reviews.
We have implemented it in a website which is a <a href='https://www.lonavalacab.com'>Car Rental In Lonavala</a>
