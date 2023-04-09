# Query-a-Digital-Music-Store-Database 

I have used Chinook Database . The Chinook Database holds information about a music store. For this project, i will be assisting the Chinook team with understanding the media in their store, their customers and employees, and their invoice information.
<img width="652" alt="001" src="https://user-images.githubusercontent.com/70021800/230799313-8ea08f04-d66c-4cf2-bb81-b56b727dff45.png">

# My Projec:
 
 ## - Presentation
 ![Screenshot (1631)](https://user-images.githubusercontent.com/70021800/230799393-3a4fb138-8036-4bf7-a2e0-4979f332387b.png)
 ![Screenshot (1633)](https://user-images.githubusercontent.com/70021800/230799436-e214b67b-2fce-4fab-a1a2-ca62fa017162.png)
![Screenshot (1636)](https://user-images.githubusercontent.com/70021800/230799519-2f11cad7-d1dc-4cb7-aa1e-b57678500d3f.png)
![Screenshot (1637)](https://user-images.githubusercontent.com/70021800/230799523-05cb8611-f0fe-48ee-905c-c59878fa94d4.png)

# - Queries I used for my Project:

*/First Query */
SELECT art.name,COUNT(al.ArtistId) "Albums"
 FROM  Artist art
 JOIN Album al
 ON art.ArtistId = al.ArtistId
 GROUP BY art.name ORDER BY 2 DESC LIMIT 10;


