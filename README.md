Hello, my name is Raehan Nasir Ahmed and this is my project for CS210 - Introduction to Data Science. 

My poject is about my music interests and listening statistics, namely; my favourtite artists, my favourtite songs, the language of music I listen to most and the days when i listen to music the most. I believe that I listen to music more on the weekends than weekdays because I feel like I have more time to relax on the weekends. I love listening to music alot whether I am studying, playing games or doing nothing at all which is why I chose to do this project.

I got my data from requesting my personal information in the spotify application which they sent to me via email in the following week. The data consisted of some account details, my playlists and streaming history from approximately the past year. I used the pandas library in python to read the json files and stored the data by creating a database in pandas.Each file was read into a single database and then I used the concat method to merge the two databases into a single comprehensive one. This database consisted mainly of my streaming history. I checked this data for missing values and punctuation but I did not have to clean it because it was already in a very good state. 

I then began my analysis of the data. I began by grouping the data by artist name and minutes played so that I could find the artists that I listened to the most. Since there were many artists in the list, I arranged this data in descending order and used the first 5 values and plotted them in a bar graph to better visualise my findings. I found out that the artist that i listened to the most was 'Anuv Jain' who is an Indian singer very popular in Pakistan as well because of the similarity in Hindu and Urdu languages. I listened to 'Anuv Jain' almost 4 times more than any other artist and I believe the reason is his soothing voice and the heart warmingly beautiful lyrics in his songs. 


