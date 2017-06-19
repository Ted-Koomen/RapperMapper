# README

* The intent of RapperMapper is to map all locations referenced in rap songs.
The api's that will be used are the Musicxmatch API for lyrics, the Google Maps API
for showing the location of the references, and the WIKI api for rapper biographical information.
* This app is currently in the devlopment stage and is not functional.

# Technoligies used:
 * Materialize for front end.
 * Rails for backend.
 *  This app will use either the Stanford NLP through the Ruby-Java-Bridge, or use Linneaus, and train the app to understand what a location is through machine learning. Later versions of this app will be written in Python to optimize data mining of a large lyric database, also optimizing the use of the Stanford NLP.


# Problems
* The major issue that I am working through right now is using the Ruby-Java Bridge ('rjb'). Currently the 'rjb' gem is not compatable with the most recent stable build of Ruby or Rails. Currently I am reseraching alternetive Named Entity Recognition libraries.
