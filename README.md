# AnimalTrack

![logo1xSmall](https://user-images.githubusercontent.com/80968217/118900329-aaa32080-b8de-11eb-92cd-c5c61b174833.png)
<br><br>
We believe that it is everyone's responsibility to care for the Earth, raise public awareness, and help make the planet sustainable. We did this by allowing us to notice whenever a species of animals/insects drop or rise. This provides people with information that can help us respond much faster to changes. The AnimalTrack app allows users to upload different animal/insect photos taken, and also helping the environment by tracking the sightings of each species. When users upload pictures of animals/insects to AnimalTrack, a graph will be formed that displays the trend of the uploaded species each year. For example, if someone sees a squirrel in their backyard, they would press the camera button and take a photo of it. After that, a screen will show up that displays what type of species it is through the AI identifier, information about that animal such as diet and habitat, and any comments that the uploader wants to tell other users when they look at their post. When they post the image, a thumbnail will show up on the home page, displaying a map of their community and the image taken. The purpose of AnimalTrack is that animal/insect/environment organizations can determine the reasons behind the rise and fall of each species and also accelerate the speed in which they find out when a species decreases or increases, and react much quicker when changes occur. AnimalTrack is helping to protect these organisms by getting people's attention towards protecting the animals and insects. When more and more people join, the data formed will be more accurate.

## Our Story
2 years ago, ash trees in my backyard were destroyed by emerald ash borers. From that point on, I was thinking how we can quickly realize decreases like this and respond to them without delay. Plant infection might be hard to catch and stop, but tracking animals and insects could be achieved. If we had the knowledge that a particular animal species were down in an area, we would pay more attention and try to avoid causing more harm. This accumulates more notice in preserving wildlife.

## Functionality

### Map
On the home page of AnimalTrack, it displays a map of the area you are in, and the image posts from other users. Thumbnails will appear the moment you post an image, and other users are able to open your image and explore on furture details such as the time, location, and species.

### Forum
People can create and talk in forums about animal protection, their current location biodiversity, bugs with the app, etc. Only people in the same area as the creator of the forum can fully participate in discussions and commenting, while if someone is outside the limit, they can only view what other people are saying, and not be able to comment.

### Community leaders
Community leaders are people that have access to hide users' posts if they contain inappropriate, offensive, or not related to AnimalTrack content. Not everyone can become a community leader. The following states the standards that must be met to become one:

- Be in the top 10% of their community.
- Have more than 500 [contribution points].
- Upload at least 3 photos per week.

Note: The community leader function is unavailable during the first few months of deployment.

### Contribution points
Contributions are points calculated to visually show how much a user has put into AnimalTrack. Factors that affect the score of a contribution is stated below:

- Number of observations: __2 points__ per photo.
-	Number of species: __4 points__ per different species that you upload
-	Number of people invited: __20 points__ per invited guest
-	Number of posts or other elements that you shared through other social media platforms: __8 points__ per share
-	Number of likes obtained: __1 point__ per like
-	Number of likes sent: __1 point__ per like
-	Number of comments obtained: __1 point__ per comment
-	Number of comments sent: __1 point__ per comment

### Refer code
When a current user of AnimalTrack wants to invite one of their friends to join, they can do so within the app and send an invitation that includes a string of text to the specified friend. This way, matching the contribution points system, the invitation sender would be able to receive points when the receiver enters in the code when signing up.

### AI
When users wish to upload a photo of an animal/insect that they have taken, AnimalTrack will automatically recognize the species with the AWS Rekognition API. When the recognition fails, you have the choice to manually type in the species if you already know it. The AI functionality is using the [AWS Rekognition API].

<br><br>
If you have any questions, contact `animaltracksendemail@gmail.com`.
<br><br><br><br>

[AWS Rekognition API]: https://aws.amazon.com/rekognition/?blog-cards.sort-by=item.additionalFields.createdDate&blog-cards.sort-order=desc
[contribution points]: https://github.com/animaltrackapp/AnimalTrack#contribution-points
![allthree](https://user-images.githubusercontent.com/80968217/118900410-e8a04480-b8de-11eb-87e9-7e486da26280.png)
