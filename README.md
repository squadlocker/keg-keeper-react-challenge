# Getting Started with Create React App

At Squadlocker we have a problem with keeping our kegs full, we need a way to visualize how much beer we have left inside the kegs!

Challenge:

create a route `/kegs` this should point to a container component, the naming is up to you.
   1. Inside this container component you should make an API call to the `GET` endpoint you setup in the `Keg Keeper API`.
   2. After you make the call to the API you should create some components to display the data.
       * Note this API state maybe consumed by components further down component tree.
   3. We need a way to create some new Kegs.
      * Create a simple form based of the props the `POST` endpoint expects in the Keg Keeper API.
