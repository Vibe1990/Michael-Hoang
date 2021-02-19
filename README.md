# Michael Hoang's Portfolio 

A collection of various data science projects that I've done. 


## PROJECT 1: [Membership Analysis of a Downtown Toronto Gym](https://github.com/Vibe1990/Bang_Membership_Analysis)

A look at the membership history of past and current clients from a boutique training studio in downtown Toronto from 2017 to 2020.  Using data collected from various sources (i.e., internal CSM (via [AirTable](www.airtable.com)), emails, and billing & scheduling software ([wellnessliving.com](www.wellnessliving.com))), I've performed an analysis of  membership survival as well as build predictive models on key membership milestones.  

**Key Factors**: 
    
   * Sociodemographic: age, employment sector
   * Membership history: membership type, monthly rates, attendance/cancellation rates 
   * Types of email interactions

**Notable Outcome Measure**:
    
   * Membership status at 3-months, 6-months and 12-months (via random forest and logistic regression)
   * Length of membership (via Cox-regression)



## PROJECT 2: [Analysis of Audio/Track Features of Songs on Spotify](https://github.com/Vibe1990/Spotify_Data_Analysis)

A two-part project looking at some data scrapped from the Spotify Web API available on [Kaggle](https://www.kaggle.com/yamaerenay/spotify-dataset-19212020-160k-tracks) containing data on the various audio/track features of songs released from 1921-2020.

Stemming from a 10-minute judgmental rant during a car ride from my dad about my playlist choice, the first part examined the audio qualities of tracks across the years to see if he's right about today's music.

   * Explored changes in audio and track features of songs based on year of release.
   * Comparison of these features from tracks of Yesterday's Greats with Today's current top artists.
   * A quick look at some of the artists whose content we are consuming today.

The write-up of the findings can be found in this [article](https://community.dataquest.io/t/using-data-analysis-to-see-if-my-dad-is-right-about-today-s-music/551251/1)


The second project looked to provide an opportunity to flex some of my supervised learning muscle by building predictive models for popularity scores of tracks on Spotify using these audio/track features.  The approaches that were taken included: 
   
   (a) Generalized Linear Models
   (b) Regression Trees
   (c) Generalized Additive Models 
   (d) k-Nearest Neighbours 
