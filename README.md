# Mapty-App

Add Your Workouts to the Map in a Simple Customized Way.(JavaScript Training App)

1.  **Summary**

    - This Project is my 2nd practice in the JavaScript amazing World.
    - It was introduced in J.Schmedtmaan brillian JS Course.
    - For me it is just an application that I applied my knowledge up to this point in semi-real world app & I am looking forward to make it more realistic as I grow my skills.

1.  **How To Use**

    - When the user opens the app the browser will ask for location .
    - Then when clicking on the map , a form will be renderd so as to fill the fields(_cycling or running_)
      -Hit the enter button to see it on the map.
      Try it here
      [MaptyApp](https://youssuf-bakry.github.io/Mapty-App/?fbclid=IwAR23ObEVcEEqwD5tuZ9hcqnFw2xe5ENYzSqMG4tKEOKBhIcbh5u6pxAnU4U).

1.  **What I learned in this Project**

    1.  Dealing with libraries : It is my first time to deal with a library [leaflet library](https://leafletjs.com/reference.html#layer) & It was so exciting to dig deeply in the documentation for a specific feature or propety.
    1.  Using an API like those provided by the browser.

            - Geolocation :
            ```javascript

               const nav = navigator.geolocation()

            ```
            - Local storage:
            ```javascript

                _setLocalStorage() {
                  localStorage.setItem('workouts',
                  JSON.stringify(this.#workouts));

        }

            ```

    1.  Creating **ES6 classes** and controlling what to be private field which is a great convention in the JS.

    1.  As an extra Challenge I've created a button that deletes all the workouts from the UI as well as from the local storage.

1.  **To be Done**

    <quote>You 're welcome to contribute to these features</quote>

    - Making the Workouts Editable by the user.
    - Ability to delete one of the workouts individually.
    - Ability to sort workouts by a certain field.
    - More Realistic Error & Confirmation messages.
    - Abitily to position the map to show all workouts.
    - Ability to draw lines & shapes instead of just points.
    - Display weather data (_will try this after finishing the async section in the course_)
