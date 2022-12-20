# Self-Assessment

When we were brainstorming ideas for this project, we decided we wanted to do something music 
related. We were scouring the internet, trying to find a datasource. There were many options
to consider, and the Spotify features API was the strongest candidate. However, we ran into
paywall problems and with getting the API set up. There was another dataset that was supposedly free 
and located on Amazon Web Services, however we struggled to figure out how to connect.

I made use of my Google-Fu and searched until we found the source we needed on Kaggle. It turns
out it was a user that tapped into the Spotify API and pulled all the related features into
an easy to use CSV. We finally found our dataset! I quickly downloaded and set about the task
of moving it into the SQL database on Zach E's personal server. These tasks put me into the
database management role - a role I am very familiar with. It took some finagling to get the 1.2+M 
songs into pgAdmin, but, again with Google-Fu, I was able to figure it out.

From then on, I continued my role as all things database related. Making sure our data was complete, 
breaking tables into smaller, manageable sizes, and preparing for the tables to be uploaded into
the machine learning model.

In addition, I became the pseudo leader of the group. I made sure the README was always up to
date according to the rubric, people were committing to the GitHub page, tried to keep us 
all communicating, and led a lot of discussions. Although this was the role I played, it was 
very difficult for me. I am usually not a leader. I like to quietly do my job and let other 
people lead. But I ended up in the role because our group needed some help to come together in
order to finish the project. 

# Team Assessment

Our biggest challenge was life. We all have different schedules and different problems. One of 
us had personal health problems and I was dealing with health problems of loved ones. One
of us was even trying to move during this time. One had connectivity issues whenever there was a 
storm. We mostly communicated during class time and kept up to date using Slack. Next time, 
I would use another app, such as Telegram or WhatsApp and keep in better communication that way. 
We are all on our phones but not always on Slack or our computers.

Our strength as a team was our ability to problem solve. We all did our own parts to complete
the projects and we ended up coming together in the end. Everyone has their own strengths to
bring to the table, and its great to find those strengths and utilize them. 

# Summary of Project

We used a set of song features provided by Spotify to plug into an unsupervised machine learning
model. We determined the data groups well in 6 clusters, however since mood is subjective, we were
unable to determine a specific mood for each cluster of songs. We created a lookup function to 
see the ML cluster of any song within the dataset. 
