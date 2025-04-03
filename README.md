# 🏙️ Urban Explorer  

Urban Explorer is a web app with several tools for helping users navigate and understand neighborhoods. Whether you're a resident, tourist, commuter, shopper, or business owner, these tools provide insights into urban and suburban environments.

The app's first release will serve Dallas, Texas, with more cities added over time. Since each city has unique public data challenges, integrating new locations will require careful analysis, development, and testing. Rather than duplicating existing apps like Google Maps or Transit, our focus is on providing unique features that convey valuable information in easy-to-digest ways.

### Why It Matters  

Urban Explorer helps users make informed decisions about transportation and location. For example:  
- New residents can find walkable neighborhoods with convenient transit.  
- Real estate developers can plan around bike lanes, scooter parking, and transit stops.  
- Small businesses can install bike parking to attract cyclists from a nearby trail.  
- The possibilities are endless!

### How to Use
_TO-DO: publish to the domain [urbanexplorer.app](https://urbanexplorer.app/)._

### Main Features

This web app has four main features.

1. [🗺️ "How to Get Here" Shareable & Printable Guide](#%EF%B8%8F-how-to-get-here-shareable--printable-guide)
2. [🤔 "What's Around Here" Neighborhood Map of Mobility Options & Amenities](#-whats-around-here-neighborhood-map-of-mobility-options--amenities)
3. [🗓️ "Plan My Day" Route & Schedule Planner](#%EF%B8%8F-plan-my-day-route--schedule-planner)
4. [🎬 "Tell My Story" Journey Animator With Exportable Graphics](#-tell-my-story-journey-animator-with-exportable-graphics)

---

# 🗺️ "How to Get Here" Shareable & Printable Guide  

Easily create a custom travel guide by entering an address. The guide provides directions for public transit, biking, and parking, considering local factors that other apps (like Google Maps) might miss. Share it via email, social media, flyers, or embed it on a website.  

### For Local Businesses 🍔
Make it easier for customers to find you by sharing the guide on your website or social media to answer common questions like where to park, the best travel options, or whether they can bring a bike inside. Encourage repeat visits by posting a printed guide at your entrance, helping customers discover nearby train, bus, or bike routes for a more convenient return trip. Improve rideshare pickups by directing customers to safer, more efficient locations, such as side streets with smoother traffic flow. If your business serves alcohol, promote safe travel by providing a printed guide with alternatives to drunk driving, including overnight parking policies.

### For Venues & Event Promoters 🎸
Increase attendance by sharing the guide on social media to ease concerns about traffic and parking. Ensure smooth arrivals by including it in email blasts so guests know the best way to reach your event.

### For Visitors & Tourists 🚶
Plan smarter trips by using the guide to find the best travel options tailored to local conditions. Get personalized recommendations based on your preferences, whether you're biking, using public transit, or willing to walk a few blocks for cheaper parking.

# 🤔 "What's Around Here" Neighborhood Map of Mobility Options & Amenities

Input an address to generate a neighborhood guide of all the services and amenities you can reach on foot, on bike, and by public transit. The guide can be viewed online or printed as a brochure.

### For People Moving to a New Home 🏘️
Looking for a walkable place to live? Use this tool to generate a guide showing all the groceries, gyms, coffeeshops, restaurants, schools, churches, parks, and other neighborhood amenities that are walkable, bikeable, or within easy reach by public transit. Input your checklist of "neighborhood must-haves" and get a report on recommended modes (walk, bike, bus, train, microtransit, or driving) and travel times for each place on your list. Discover all the bicycle amenities and transit options available in the area. Receive localized instructions for how to use the transit options available to you; for example, if your address is in a GoLink on-demand zone, then the guide will show you how to buy a DART pass and how to book a GoLink trip. 

### For Rental Property Managers 🔑
Attract new tenants by using this tool to discover positive selling points about your property's walkability, bikeability, and transit options. Incorporate the guide into a "Welcome Home!" packet to increase satisfaction amongst your new tenants. Subscribe to receive alerts when your guide is updated with new neighborhood amenities and transportation options, which you can then forward to your existing tenants to increase retention ("Look at all the cool new stuff that came into the neighborhod!").

### For Real Estate Investors & Developers 🏗️
Use this tool to research transportation options and connected services and amenities for a site of interest. Gain valuable insight that you can incorporate into site plans and urban design in order to capitalize on the existing infrastructure around your site. For example, "Hey there's a bike trail nearby. We should design the new apartment building with ample bicycle parking!" or "Hey this land is in a GoLink zone that would connect our tenants to nearby shopping centers. We should design our building with a loading zone specifically for rideshare and microtransit vehicles!"

# 🗓️ "Plan My Day" Route & Schedule Planner
This tool is meant to work alongside navigation apps like Google Maps, Transit, or GoPass, but instead of planning just one trip at a time, it helps you organize your entire day of errands, appointments, and outings. It builds a smart schedule that adapts in real time as things change—whether you leave early, take longer at a stop, miss a bus, or get stuck in traffic. This planner ensures you stay on time, stay flexible, and make the most of your day—no matter what comes up.  

### Plan trips with multiple stops and travel modes 🚏  
Google Maps allows multiple stops but only for car trips and doesn’t account for parking. Transit and GoPass support multimodal travel (walking, transit, biking) but lack multi-stop planning. This app combines both, letting users create itineraries with multiple stops across various travel modes.

### Create a full-day schedule that handles both strict appointments and flexible arrival windows ⏰
Enter fixed appointment times, and the app will recommend departure times to maximize time at each stop while ensuring you’re never late. Need to spend an hour at the grocery store anytime before closing? The app schedules it efficiently while keeping your whole plan on track.

### Auto-arrange stops for the most efficient jourey 🚅
The app can rearrange your schedule to maximize efficiency. For instance, if you have a strict appointment at location B in the morning but flexible visits at locations A and C, each lasting about two hours, the app may adjust your itinerary from `HOME → A → B → C` to `HOME → B → C → A → HOME` to save time and improve your travel experience.

### Adjust your schedule in real time 😯
Easily adjust your schedule in real time with the press of a button—whether plans change, you need a round trip home, or you're leaving an event early, the app instantly updates your itinerary. If you miss your bus, it finds the best alternative, whether that’s the next bus, an Uber, or a scooter. You can also plan ahead with a "backup plan," such as setting up an automatic notification to inform someone if you're running late.

# 🎬 "Tell My Story" Journey Animator With Exportable Graphics

This tool combines adds options for animation and graphics export on top of this app's other features. This feature is used to visualize a journey across the city for a variety of story-telling purposes.

### Export map as a graphic file 🖼️
Generate a PNG image file showing a still map overlayed with routes, stops, and other useful details. The image file can be used on digital and print media. You can also export an animated GIF file to show the map animation of routes, stops, and other useful details. The GIF can be customized with dimensions, animation settings, and details toggled on/off.

### Export animated map as a video 🎦
Generate a video file by producing several PNG files, one for each frame of map animation. Then, using the FFmpeg.js Javascript library, combine all those PNG files into a video that users can export and download.  The video can be customized with dimensions, animation settings, and details toggled on/off. Alternatively, the PNG frames can be downloaded in a zip file so video editors can make a video their own way. 

### Embed map on external webpage 💻
Generate HTML code for embedding a map on your own website or blog. The embed can be customized with animation settings and details toggled on/off.
