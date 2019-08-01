# Ted-Talks-Descriptive-Analysis

TED Talks have gone to become hugely popular conferences. Regarded as a mecca of ideas, they have attracted the most high-level speakers such as Bill Gates, Al Gore or Stephen Hawking. Founded in 1984 by Rochard Saulman as a nonprofit organisation aiming at bringing experts from the fields of Technology, Entertainment and Design together, TED and its sister TEDx chapters have, as of 2015, published more than 2000 talks of 18 minutes length available for free on the Internet.  

I decided to exploit the availability of these incredibly rich and insightful talks. I rely on the dataset obtained from Rounak Banik and hosted on Kaggle containing the transcripts of all audio-video recordings of TED Talks uploaded to the official TED.com website until September 21st, 2017. I have merged the transcript dataset with a second dataset provided by Rounak Banik containing more metadata information on the TED Talks themselves such as the number of views, speakers, titles etc. The datasets can be downloaded from the Kaggle website via the following link: https://www.kaggle.com/rounakbanik/ted-talks. I have chosen to keep only the variables that I deemed relevant and cleaned the dataset from any blanks or missing values. Additionally, I kept only the TED Conferences or TEDx formal events and removed any external or special conferences. As a result, my final dataset countains 2342 observations from 2002 until 2017. 

I have 6 variables, describing the following columns in our dataset: 
- "Event": the name of the TED talk event 
- "main_speaker": the first and family name of the speaker 
- "speaker_occupation": the job title of the speaker 
- "title": the title of the TED talk 
- "views": the number of views for the TED talk 
- "transcript": the transcript for the TED talk
