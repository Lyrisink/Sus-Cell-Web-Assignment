# Tools to use:
For building this platform, I’ll use the following tools:
* React, using Vite, for frontend and building the user interface.
* Open street map to get the required map layout. Also use CSS to apply required effects to it.
* Leaflet.js for map engine.
* Firebase Firestore for backend database.
* Vercel for deployment and hosting.

I also researched on alternative applications and compared pros and cons too finalize this list of tools.
Alternatives like Vue, Angular, Google maps API, etc exist but these provide the better optimized tool for building our platform.

# Structure of the Platform:
* Firebase will store location points of the places we want to mark on the map in its database.
* Every location will consist of data like – name, category (Plant, Waste collection spot, Main buildings, etc.), coordinates, description.
* React will provide a dynamic user interface, and it will also fetch these location data, and pass to react-leaflet.
* React-leaflet will render the map and plot the respective markers on it.

# Steps Involved:
1. We first use vite and initialize a react environment.
2. We then make a raw database of all initiatives, and their details like coordinates, category and brief description.
3. On firebase, we make a new firebase datastore. On this database we add the details mentioned in step 2, and then connect it to react.
4. We then use open street map to get the base map.
5. Then we use CSS on the map-container to customize it accordingly.
6. We provide a green/blue color theme to main locations we want to mark, while adding a grayscale effect to side objects.
7. Use leaflet for map integration, and add popup markers on important locations.
8. Add buttons and tabs for user interaction. When clicked, it will update a react state and highlight the appropriate locations.
9. Finally use vercel to deploy it to the web by linking the github repository to it.

# Main Features:
* The map will be on a grayish background, while the important locations will be highlighted using green/blue color (theme of sustainability cell).
* Clicking on these locations will provide a detailed description of the location, different policies put into place etc.On top it will have different tabs to categorize the spots.Another thing I wish to add is a sidebar, which will have a list of different sustainability cycles.
* For example, the food waste management cycle, when clicked on, it specially highlights different places involved in the process, and connect them with green arrow, also providing a detailed description of what takes place where.
* Another thing I wish to add, is to place QR codes or such on the locations, when scanned they will take to this map, and might even have some hidden easter eggs which will make it more engaging.

# AI Use:
* Not much AI was used in this. I researched on some tools that can be used. I already knew about React, Vite, Firebase because of a current chat-app project I am doing under "Seasons of Code" program in this summers.
* Because I am still yet to actually use these tools myself, as still the project is in starting phase, I used AI to learn more about the tools and their uses in brief.
* Any idea I have mentioned in the answer is solely mine and no AI is used for ideation.