# Kalmann Filter
The project was made possible by the following resources: <br />
https://www.youtube.com/playlist?list=PLX2gX-ftPVXU3oUFNATxGXY90AULiqnWT <br />
https://www.kalmanfilter.net/default.aspx<br />
<br />
In python notebooks, I attempted to explain the project as thoroughly as possible. The Kalmann filter is used in this project to predict data from measurement values and process (Newton's equation) values.
<br /> ->First, I read the dataframe with Panda and classified it as px, py, vx, vy and considered time frame as 1 second
<br /> ->Plotted velocity and position value and time value against time
<br /> ->The updated state matrix has been used for new predicted vx ,vy,px,py
<br /> finally px is plotted with py
<br /> in book without acceleration a is considered as 0 while in considering acceleration a= (v2-v1)/t
