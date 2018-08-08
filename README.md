# rmweir.github.io
hosting hackathon cms

## Technical Information
The main screen is is an adoption of a template and is meant strictly for prototyping. The details view is written using regular html 
with bootstrap. This prototype is mostly contained by the files: index.html and real_time.html

Originally we were working towards a full fledged application. If one wishes to move forward with this project I would recommend looking
at modeling after these files for the backend portion. The design involved using node (in the server.js file) for retrieving information 
using ejs (a templating language) to empower us to use html with embedded javascript. Mongodb was the database we planned on using, but
any database should be sufficient.

I think a rewritting of the full project without so many dependencies and unecessary assets would be ideal. The most important aspects of 
the project are the use of bootstrap for responsive design and chartjs for the data visualization.
