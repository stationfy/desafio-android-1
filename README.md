# Arena - Android Challenge

## Goal

The ideal application will consist of the following workflow:

On the initial application startup, consumes a public location based rest service (Foursquare, Yelp, etc) to query a list of business near you. If the user minimizes or closes the application, this query should still continue until finished. When finished, if the user is currently viewing the application, a list should be populated with all results (i.e. an empty query should display all items). Once results are present, a menu item should be displayed to allow the user to provide a search query that will filter the list of displayed results by dispatching an additional query. As a bonus objective, we would love to see some integration/unit tests around your code.

Note: Query strings should filter on the "Name of the Business".

Feel free to use any open source project dependencies you are comfortable with. Your code should be hosted on GitHub.

## Ideal submissions

### Required

- Query the business list;
- Has a business list screen;
- Has a business detail screen;
- Has a Toolbar to receiver the user's search input;
- Has an asynchronous and on demand image loading;
- Minimum SDK version must be 14;
- Your code should be hosted on GitHub.

### Desired

- Includes a nice clean UI;
- Handles offline mode by caching requests;
- Use an REST Framework for requests;
- Has Unit Testing;
- Has Functional tests.

### You're a rockstar if...

- You use concepts of Reactive Functional Programming (RxJava + RxAndroid);
- You have used an Dependency Injection Framework like Dagger 2;
- You have used smooth and slick animations for transitions / touch events;
- The UI is beautiful.

## Submissions

Feel free to complete as much of this challenge as you feel is reasonable for your skill level.

Send relevant code source as .zip, tar.gz, or link to a git url accompanied with a signed .apk file to "email".
