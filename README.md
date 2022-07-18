# runelite-live-friend-locations-api
This API is used in combination with the live friend locations plugin in runelite: https://github.com/TiboDeMunck/runelite-live-friend-locations-plugin

# Setup
- Deploy somewhere 
- After build returns shared key and creates .env file

## Heroku Setup
Example of setup using Heroku

1) Fork this repository to your own GitHub account
2) Create a new heroku app
3) Under "deploy" connect with your GitHub account
4) Search of the forked repository under App connected to GitHub
5) Manually Deploy
![image](https://user-images.githubusercontent.com/46536105/137190410-595425a5-a7b2-4925-978e-740d4a30b252.png)

6) When the application is deployed go to "View Logs" under "More" and copy the Shared Key
![image](https://user-images.githubusercontent.com/46536105/137190865-ce1508e3-b2f1-46ec-a640-e620260aca06.png)

7) Go to settings and add a config var named "SHARED_KEY" with the copied shared key as value
![image](https://user-images.githubusercontent.com/46536105/137191099-44ebc769-9d5e-47a5-8b0d-3796b0f61e70.png)

note: under settings you will also find your url
![image](https://user-images.githubusercontent.com/46536105/137191199-8dfa2572-f0b2-42ee-aee3-e1248d67f110.png)

8) Enter your base url and the shared key into the runelite plugin

! Only share this link and Url and Key with people you trust, it's not my fault if your api gets leaked and PK'ers know your every move in the wilderness

## Updating Fork
1) Click the "Fetch Upstream" in your forked repository
![image](https://user-images.githubusercontent.com/46536105/175146130-8537604b-6af6-4ad0-a48a-c5b8ac93e347.png)

2) If Heroku is setup correctly, the updated repository should automatically deploy on Heroku

!If this doesn't work, manually deploy the "master" branch

# Youtube Tutorial
https://www.youtube.com/embed/eMgULNYfU1k
