# PastesAnalyser
Paste Analyser inspired by AIL-Framework.

# Feeding
The idea is to feed pastes either from pystemon or the CIRCL feed and searching for keywords using the existing ELK Suite.

Pystemon can be found at https://github.com/cvandeplas/pystemon

I however recommend trying to contact the CIRCL about getting access to their superior feed. This is done over ZMQ, which logstash supports through an external app.


# Visualisation
You will have to customize the ELK dashboards visualisations to show the desired keywords. 

As provided the following graphs are given:
- total count graph (used for count the amount of pastes (Making sure it runs))
- Windows keyword graph (purpose is to change the keyword to the desired keywords)

Simply reuse the windows keywords graph and modify the keyword to get the desired keyword match.

Furthermore you can create the desired graphs as long as you have the source of data.
