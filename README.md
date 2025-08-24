# Mini Travel Itinerary Recommender
This is a simple Next.js app that recommends a travel itinerary based on your chosen destination. It demonstrates:
* Next.js frontend and API route usage
* Basic data handling and string search

## Working process of app
1. Enter your destination in the input field and click the submut button.
2. The API send your input(What you entered in the input field)  "/api/plan".
3. The API matches your input with a small dataset of destinations.
4. It returns up to 2 best matches with highlights and a short itinerary.
5. The frontend displays the results in a simple card format.

## Dataset 
[
  { "place": "Manali", "highlight": "Snow-capped mountains and adventure sports" },
  { "place": "Goa", "highlight": "Beaches, nightlife, and water sports" },
  { "place": "Jaipur", "highlight": "Palaces, forts, and cultural heritage" },
  { "place": "Kerala", "highlight": "Backwaters, houseboats, and Ayurveda" },
  { "place": "Ladakh", "highlight": "Mountains, monasteries, and road trips" },
  { "place": "Rishikesh", "highlight": "Yoga, river rafting, and spiritual retreats" }
]
```

## How to run  the app
1. please install Node js in your system
2. In the project folder, run:
   npm install
   npm run dev

3. Open [http://localhost:3000](http://localhost:3000) in your browser.


 Author:P.Rajesh
