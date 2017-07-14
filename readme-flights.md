Project Name: Wanderlust

Problem: User has an idea of what they would like to do when traveling, but may be overwhelmed by options.  There may be ideal places to travel that match their interest that they are not aware of or they are not considering.

UX: input box on home screen.  user is prompted to type in the airport they will be leaving from.
second input box.  user is prompted to type in where they would like to go.  Hit "go" button.

using google flights API, the cheapest flight is found.
using TripAdvisor API, the top three destinations for the city are found.
using custom credit card API, the dollar amount of the cheapest flight is converted into points needed to take the flight for free.

User has option of clicking 'wanderlust' button which will generate a destination at random.

The tripAdvisor, flight, and recommended CC can appear in bootstrapped cards.  Clicking on each will lead to the tripadvisor link, google flight to book, and bank, respectively.

*PROBLEM*: Southwest, Delta, and American Airlines info would not be available in this API. Delta and AA only share under special circumstances and SW not at all.  United only shares partial information.
This issue alone might make the project un-doable.

"As a user, I want a one-stop-shop to find affordable flights and recommended destinations."
"As a user, I want destinations and activities recommended to me when I dont have any idea where to go."