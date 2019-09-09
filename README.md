# Purple

Brief
------

Purple is a location scoring site that allows users to receive an evaluation of an address based on factors that are important to them.

At Purple, we believe every person should be able to live by the places that are important to them. If living by restaurants and bars makes a person happy, they should live by restaurants and bars! If having bus stops and grocery stores nearby is more important to them, they should find a place where there are a few nearby. We know that nearby places are critical to deciding where people live, and we want to make the process easy for them. With Purple, users simply enter an address, select the places that are important to them, and receive an address score.

View Demo:
[![Watch the video](readmeImages/purplevimeo.jpg)](https://vimeo.com/357981076)


Concept 
------ 

Existing sites like Zillow and Apartments.com have general walkability and transportation scores, but nothing more specific, and no way for users to specify what's important to them. With Purple, a user can specify exactly which nearby places they care about, and how important each nearby place is to them. They can even set default preferences so they can apply the same preferences to multiple addresses with ease.

Purple was founded on the belief that different nearby places are important to different people, and that nearby places are critical to deciding where people live. However, the core principle that underlies this belief is that nearby places are important to any location-based decision. This core principle is not limited to home and apartment searches. It can just as easily be applied to finding a hotel or airbnb while traveling, choosing a venue for an event, etc. Purple was developed with flexibility and scalability in mind, and it can easily expand into new markets.

Purple's existing functionality also has great potential for growth. Purple's functionality can be broken down into two core components: retrieving nearby place information, and calculating a score based on user-specific criteria. Retrieval of nearby place information could be expanded to utilize a variable search radius, be based on time and method of transportation instead of distance, allow increased specificity (eg. Trader Joe's), allow factors like crime statistics, etc. Calculation of a score based on what's important to user could be expanded to utilize existing walkability indexes, account for various properties such as commute time and customer ratings, etc.


Technologies 
------ 

Purple's core functionality, the use of nearby location data to determine a score, is driven by integration with Google Maps APIs and a JavaScript algorithm developed by our team. Purple's design was developed using raw HTML, Sass, and JavaScript, without the use of CSS frameworks.

* HTML
* Sass
* Javascript
* [Google Maps API](https://cloud.google.com/maps-platform/places/)
* Firebase Cloud Firestore (NoSQL database)


Launch
------

Purple can be accessed at the following url: [http://purplemap.surge.sh](http://purplemap.surge.sh)


Authors
------

* [Kelsey Gaetjens](https://github.com/kjgaetjens/)
* [Elizabeth Vasquez](https://github.com/elizabethsv)
* [Eric Snover](https://github.com/ersnover)
* [Taliaa Tuatolo](https://github.com/taliaa10)
