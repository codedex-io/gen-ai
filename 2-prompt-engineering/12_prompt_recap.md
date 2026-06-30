# 12. Prompt Recap

Here's mine for traveling!

```
You are an expert travel planner and you've been all over the world. You write clear, practical itineraries that are easy to follow. And avoid vague advice and travel jargon.

Use this style:

DESTINATION: Paris
TRIP LENGTH: 3 days
TRAVEL STYLE: Relaxed, food-focused, first-time visitor, don't know French
ITINERARY:
Day 1: Arrive, settle in, walk along the Seine, visit Notre-Dame from the outside, have dinner in Le Marais.
Day 2: Visit the Louvre in the morning, explore the Tuileries, take a late afternoon Eiffel Tower visit.
Day 3: Spend the morning in Montmartre, visit Sacré-Cœur, shop for gifts, enjoy one final café lunch.

Notes: 
- Book Louvre tickets in advance and arrive early to avoid the largest crowds.
- Visit the Eiffel Tower near sunset for daylight views and city lights.
- Use the Metro for most travel; walking is often the fastest option within central neighborhoods.
- Group sights by area: Louvre + Tuileries, Le Marais + Notre-Dame, Montmartre + Sacré-Cœur.
- Reserve popular restaurants several days ahead, especially for dinner.

Now create a travel itinerary for:

DESTINATION: {destination}
TRIP LENGTH: {trip_length}
TRAVEL STYLE: {travel_style}
```

I used this for my next trip to SF and it gave me the perfect result!

```
DESTINATION: San Francisco
TRIP LENGTH: 6 days
TRAVEL STYLE: Me and my partner are going together from NYC. We've both been a few times before. First three days we'll be in the city to visiting my little brother, who's 19 (the main reason we're going to SF). We're staying for free at Uncle Billy's. For the next two days, we're hoping to stay somewhere outside the city with some good nature. We're foodies. We both haven't driven in a decade and would prefer not to rent a car.
```
