<h1>Purpose of the project</h1>

<p>The purpose of the project is to help Sparkify to analyze the user activity on their music stream app. With this insight into their data, they should be able to make informed decisions on popularity of songs, who their most active users are, and be able to develop a plan to bring in new users.</p>
    
<p>In order to do this, I used the JSON data that was given to create a fact table called songplays, and along with it 4 dimension tables called artists, songs, time, and users. Each table element is listed below. These tables create a star schema. One of the things Sparkify would like with this project is simple queries, and this is a benefit of star schema.</p>

<h3>Songplays</h3>
<ul>
    <li>songplay_id</li>
    <li>start_time</li>
    <li>user_id</li>
    <li>level</li>
    <li>song_id</li>
    <li>artist_id</li>
    <li>session_id</li>
    <li>location</li>
    <li>user_agent</li>
</ul>
<h3>Users</h3>
<ul>
    <li>user_id</li>
    <li>first_name</li>
    <li>last_name</li>
    <li>gender</li>
    <li>level</li>
</ul>
<h3>Songs</h3>
<ul>
    <li>song_id</li>
    <li>title</li>
    <li>artist_id</li>
    <li>year</li>
    <li>duration</li>
</ul>
<h3>Artists</h3>
<ul>
    <li>artist_id</li>
    <li>name</li>
    <li>location</li>
    <li>latitude</li>
    <li>longitude</li>
</ul>
<h3>Time</h3>
<ul>
    <li>start_time</li>
    <li>hour</li>
    <li>day</li>
    <li>week</li>
    <li>month</li>
    <li>year</li>
    <li>weekday</li>   
</ul>

<h2>The data used</h2>

<p>In our data repository there are two sets of data, log data and song data. Song data contains information on a particular song including a song ID, title, and duration of the song. Log data contains information on activity in Sparkify including basic information about the user, if they're a paid subscriber, and what song they're listening to. </p>

<h2>Running the scripts</h2>

<p>To begin running to scripts for this project, first open test.ipynb, then choose "kernal", "restart kernal". From there you should be able to run the first 4 boxes of code. This will run the sql_queries.py and etl.py scripts as well as connect to the sparkify database.</p>

<p>After that, switch to etl.ipynb and run through all of that code. This will get data from the repository and insert that data into the correct tables.</p>

<p>Finally, go back to test.ipynb and continue running the rest of the code and you will see the populated tables.</p>

