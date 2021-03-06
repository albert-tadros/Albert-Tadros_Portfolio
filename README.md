# Albert Tadros Projects

## Click on each project's title for the project github code

# Software Development Projects


# [Project 1: Flix ](https://github.com/albert-tadros/Codepath-iOS-Flix)

# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

### User Stories
- [x] User can tap a cell to see more details about a particular movie.
- [x] User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.
- [x] User can tap a poster in the collection view to see a detail screen of that movie.
- [x] In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthrough GIF

![part2](https://user-images.githubusercontent.com/78925894/156969046-62c38b66-ad48-4457-a233-2adf51e665f6.gif)

# [Project 2: LOOK UP | Social Interaction Mobile App](https://github.com/tpandos/lookup)

***Our mobile application promotes and facilitates connection between people that are in near proximity. Consider someone who has a great idea but needs help from someone with a particular skill set. What if this person can find exactly who they are looking for at the Cafe ́ they always visit? Lookup provide an interface that can connect people more locally, allowing them to find the people that fit the criteria of their search within a limited distance relative to their location.
We want the user to have access to other individual who are at walking distance from them, who can spare a few minutes to meet in person and establish the beginning of a real interpersonal relationship.
Closing the distance gap can promote not only a more reliable interaction but also a literary closer one. Our mobile application LOOK UP is a social media app that helps promote more face-to-face interaction.***

 **MVP**
- User can register
- User can Login
- User can update profile
- User can upload profile picture
- User can allow access Location
- User can search for others around them, based on 1 keyword skill and filter by distance or
ranking
- User can view other profiles
- User can send connection(friend) request to other users
- User will receive a notification if so one wants to connect with them, they can either accept or deny the request
 
 **App Development Tools:**
 - React Native using expo(for front end)
 - Node.js, express ( for backend)
 - MongoDB ( to save user information)
 - Cloudinary ( to store user profile pictures)
 - Herokuapp (API)
 
 **Demo: the following Gifs are two-part demos of all the functionalities of the app**
 
 ***Part 1:***
 
 ![lookup_demo_part1](https://user-images.githubusercontent.com/78925894/153927990-02591a94-5d00-4679-9b46-95c65ae1eeec.gif)

 ***Part 2:***
 
 ![lookup_demo_part2](https://user-images.githubusercontent.com/78925894/153928248-d83d0e48-454f-47c3-acc8-be0acc7f7018.gif)

# [Project 3: Personal Website](https://albert-tadros.github.io/albert-tadros-site/) 

**Developed this personal website using HTML5 and CSS.** 

**Deployed the app on Github Pages**

![website gif](https://user-images.githubusercontent.com/78925894/175169320-e5fb3092-2e1f-4303-b3c7-c15939fcb0f2.gif)

---


# Data Science and Machine Learning Projects

# [Project 1: Piano Chords Recognition Using CNN](https://github.com/albert-tadros/Piano-Chords-Recognition-Using-CNN)
**Motivation Behind Project:**
- Beginner music producers may find it difficult to identify chords in a song A chord: is at least 3 music notes played simultaneously to create harmony
- What if there is way to give a program the chords, and program returns what chord it is! This what the project is about
- In this project, a CNN model was trained to recognize piano triads ( 3-note chords). 
- This project is helpful in: Song chord recognition and Melody notes recognition

**Dataset**
- Piano Triad Waveset on Kaggle: Dataset consists of 362 Wav files of piano triads (3 sec length)
   - https://www.kaggle.com/datasets/davidbroberts/piano-triads-wavset

**Implemtation**
- Processing Audio Data: The goal of data processing is to represent audio waveforms (with features) as numerical data that can be used in training model.
   * In this project, librosa, which is a python package for music and audio analysis, was used to process the audio wave files.
   
   
* Training the CNN using Tensorflow: CNN created using the following layers: 3 Conv2D layers, 5 flatten, 1 dense, 1 dense (output layer)

   * For training:
     * 75% of data allocated for training and 25% for testing
     * 20% of the testing data used to evaluate accuracy and error in training

**Results**
* High accuracy and minimized loss were obtained at:
     * Learning rate = 0.001
     * Epochs = 30 

<img width="837" alt="10 seg, 30 epochs, accuracy" src="https://user-images.githubusercontent.com/78925894/175131753-3eec4400-92ba-4ae2-a8fc-0eedcf83ca53.png">


<img width="879" alt="10 seg, 30 epochs, error" src="https://user-images.githubusercontent.com/78925894/175131825-0f80ffbb-839f-4dc9-8268-037a550a635d.png">

**Using the trained model to make a prediction**

<img width="1401" alt="predicted" src="https://user-images.githubusercontent.com/78925894/175131912-05634a08-e55b-4702-a70f-2c93feca9f3a.png">

# [Project 2: The impact of COVID19 on the NYC Public High School Enrollment](https://github.com/albert-tadros/NYC-High-School-Studnet-enrollment)
***This python data analysis project aims to investigate any change in the enrollment number of high school students in NYC public school during COVID19 pandemic. The data used for the analysis was secondary data sourced from [the New York State Education Department Data website](https://data.nysed.gov/). The analysis was implemented using Python on Jupyter notebooks. The following python's data analysis libraries: Numpy, Pandas, Matplotlib, and Seaborn, were mainly used in the project.***

**Problem Statement**

Overall, college enrollments in the U.S. declined by 4% during the year 2020 due to the pandemic. Given that high school education is just as important as college education, the goal of this analysis is to gain insights on effect of the pandemic on the NYC public high school enrollment numbers during the first year of the pandemic (2020 and early 2021).

**Guiding Analysis Questions**

- Has public high school enrollment fallen like college enrollment?
- Do public high school enrollments vary by student ethnicity and gender in 2020?
- Do public high school enrollments vary between student of different economic advantage in 2020?
- What has been the trend of public high school enrollment before the pandemic?
- If an enrollment trend is recognized, can there be an explanation to change in the enrollment ?

![](./images/total%20enrollment%20trend.png)

# [Project 3: Maven Toyes Profit Margin](https://github.com/albert-tadros/Maven-Toyes-Profit-Margin-Project)

***This python data analysis project aims to improve the profit margin of the company Maven Toys using the company's products, sales, stores, and inventory data. The analysis was implemented using Python on Jupyter notebooks. The following python's data analysis libraries: Numpy, Pandas, Matplotlib, and Seaborn, were mainly used in the project.***

**Question:** The executive at Maven Toys is interested in how they can strategically improve their margins. 

**Reframing the Question:** Analyzing the data, the goal was to determine: 

- Which products should Maven Toys focus on while utilizing what methods to improve overall sales margin. 
- Which products are of interest company wide.
- which products are of interest at individual stores.

**Executive Summary:** This project provides an analysis and strategic recommendations for improving sales margins at Maven Toys by analyzing company wide and individual store data to identify specific products that can improve sales margin and by association sales revenue. The project will also identify products that hinder sales margin through analysis of low sales revenue and products with long shelf lifes. The method of our analysis consists of calculating average cost, generated sale revenue, product margin, variable correlation and age of inventory.

![](./images/Top%20Selling%20Products.png)
