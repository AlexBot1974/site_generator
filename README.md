# site_generator
Code that generats web-site automatically. You need just type short description of the future site.

This repository contains Python notebook with machine learning model that classifies input text into 4 labels
(business web-site, personal web-site, site of online school and site of hackathon or HR agency).
Model is saved using pickle libraty an wraped by Flask. So you can start web-server that use saved pickle model.
At the end server generats code of desired web-site and put it into docker-container(in the future) and client 
has web-site in several seconds after he click the botton GENERATE.
AUTHER IS ALEX BOCHAROV, skype bam271074
The project is open source.
Technology stack^ Python, Flask, Random Forest, HTML, Java.
