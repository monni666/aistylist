<!-- This is the markdown template for the final project of the Building AI course,
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# AI Stylist

Final project for the Building AI course

## Summary

AI Stylist is an AI‑powered personal stylist that helps people pick clothes based on weather, body type, and personal style preferences. It aims to make outfit selection easier, faster, and more confident for people who struggle with choosing what to wear.

## Background

Many people — including me — find it difficult to pick clothes for daily life, special events or changing weather. This leads to wasted time, stress, unnecessary purchases, and lower confidence.

This project aims to solve:

* indecision when choosing daily outfits  
* difficulty matching clothes into coherent combinations  
* uncertainty about what suits one’s body type  
* choosing weather‑appropriate clothing  

My personal motivation is simple: **I often have a hard time picking clothes** and would love to have intelligent, personalized guidance.

## How is it used?

The solution would be used as a:

* **mobile app** that allows users to photograph and upload their wardrobe  
* **virtual closet** that organizes clothes into categories  
* **smart stylist** that suggests outfits  
* **weather‑aware tool** that adapts recommendations  
* **body‑type advisor** that suggests flattering cuts and styles  

Example usage:

1. User opens the app in the morning.  
2. AI checks local weather.  
3. AI analyzes available wardrobe items.  
4. User selects the activity (school, work, gym, date, party).  
5. The app generates 2–4 personalized outfit options.  

## Data sources and AI methods

Possible data sources:

* user-uploaded wardrobe photos  
* publicly available fashion datasets (e.g., DeepFashion, Fashion‑MNIST)  
* weather data via APIs (e.g., OpenWeatherMap)  
* user preferences (colors, favorite items, comfort level)  

AI methods:

* image classification (to identify clothing items)  
* recommender systems (to create outfit combinations)  
* similarity algorithms (to match colors and styles)  
* rule-based filters (weather, season, context)  
* optional computer vision for body shape estimation (with consent)  

## Challenges

This project does **not** solve:

* fully understanding unique personal taste  
* differences across cultures, fashion norms or trends  
* ensuring perfect outfit choices every time  
* privacy risks related to uploading personal wardrobe photos  
* high‑accuracy body-shape analysis without advanced modeling  

Ethical considerations:

* user images must remain private and secure  
* avoid reinforcing beauty stereotypes or biased fashion norms  
* ensure fair and inclusive style recommendations for all body types  

## What next?

Future development ideas:

* adding a 3D virtual try-on  
* sustainability guidance (second-hand options, eco-friendly materials)  
* integration with online stores for additional suggestions  
* AI‑generated outfit previews  
* community features like sharing and rating outfits  

To move forward, I would need:

* access to diverse fashion datasets  
* collaboration with designers or AI developers  
* user testing to improve recommendations  
* better outfit-matching algorithms  

## Acknowledgments

* Inspired by fashion recommendation apps and virtual wardrobe tools  
* DeepFashion and Fashion‑MNIST datasets (if used)  
* Weather data providers such as OpenWeather  
* Building AI course by Reaktor & University of Helsinki
