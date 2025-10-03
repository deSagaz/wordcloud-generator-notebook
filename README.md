# Wordcloud Generator for Google Searches

A Jupyter notebook that takes a search query and generates a wordcloud visualisation based on scraped results as provided by Google Search.

For example:

<img width="3000" height="1500" alt="Wordcloud for Thalidomide" src="https://github.com/deSagaz/wordcloud-generator-notebook/blob/master/wordcloud_thalidomide.png" />

To generate this wordcloud, the English Google Search API was queried for the top 50 results for "thalidomide."
Returned URLs were consequently scraped, stripped of stop words and ranked by popularity. The size and brightness
of words in the visualisation correspond to popularity.

This notebook was commissioned by Toine Pieters (Utrecht University). In line with open science principles,
this repository contains the full pipeline that generated the published "Thalidomide" wordcloud.
