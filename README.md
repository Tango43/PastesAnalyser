# PastesAnalyser
Paste Analyser inspired by AIL-Framework.

# Feeding
The idea is to feed pastes either from pystemon or the CIRCL feed and searching for keywords using the existing ELK Suite.

Pystemon can be found at https://github.com/cvandeplas/pystemon

I however recommend trying to contact the CIRCL about getting access to their superior feed. This is done over ZMQ, which logstash supports through an external app.


# Visualisation
You will have to customize the ELK dashboards visualisations to show the desired keywords. 

As provided the following graphs are given:
- Total count graph (used to count the amount of incoming pastes)
- Windows keyword graph (purpose is to change the keyword to the desired keywords for alerting)

Simply reuse the windows keywords graph and modify the keyword to get the desired keyword match.

Furthermore you can create the more advanced graphs on the existing data source. These graphs are just given as examples.

# Importing Template Dashboard Guide:
- Click in Management In Kibana
- Click on Saved Objects
- Use the import button to import the export.json file.

