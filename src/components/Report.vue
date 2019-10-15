<template>
  <v-layout class="mx-2 px-2">
      <v-flex xs12 class="text-left">

      <div id="intro">
        <br>
        <br>
        <br>
        <h1>Introduction</h1>
        <p>
          Colors and their use in UX design of websites and mobile apps have been a topic of debate between UX designers for long.
Most, if not all, designers agree that colors have their own psychological effect on human behavior. Between making decisions whether to buy an item, add it to cart, stay longer on a website or an app, or how fast we learn to use apps all relates to the overall design of that app and how the colors are arranged and used.

When designing an app there are 2 main types of colors that need to be considered: Brand colors; which are fixed, a UX designer can’t change them or not use them as they define the brand and remind users of their experience with that brand, and colors that are chosen by the designer for general use like button color and text color.
Our work is going to target the second group of colors, and to be specific button colors and how they relate to the speed of performance and achieving goals in an app.

        </p>
        <p>
<strong>There are things to consider when picking colors for an app, some of them are: </strong>
<ul>
  <li>
    <strong>Brand colors</strong>: as we don’t want buttons that represent negative things, like deleting an account or error messages to be of the same color of the brand.</li>
  <li>
    <strong>Color psychology</strong> colors have their own effect on how we make decisions, an example of that is the studies that were conducted at at one U.S. Naval correctional facility, two California county correctional centers, and two state and federal psychiatric hospitals that confirm that pink color had a calming effect on inmates. (Schauss, 1985)
It is also believed that social media apps use certain shades of blue as it is a calming color as well. And many believe that red is associated with errors and warnings.
However, those rules are not always the case.
For example, red is used for sales, “add to cart’ buttons on some websites as it is a color that gets our attention.
  </li>
  <li>
    <strong>Cognitive overhead:</strong> is the amount of connections or logical jumps our brain has to take in order to understand or get the hang of a process.
In simpler terms, it represents how hard it is for humans to learn about the tool, or in our case, the app they are using.

  </li>
</ul>
        </p>
        <p>
What we’re really trying to test is the speed of performance of participants when given a task to accomplish on a web page. 
Our goal of this experiment is to understand whether button colors can affect the speed of our performance.
It is a test of whether we actually have expectations when it comes to button colors and whether our test subjects will have less cognitive overhead when the buttons colors are common, uncommon, or not colored.
        </p>
      </div>
      <div id="material">
        <br>
        <v-divider></v-divider>
        <br>
        <br>
        <h1>Material</h1>
        <p>
          <ul>
            <li>Web page we designed on <a href="https://yousef-aldawoud.github.io/booking-demo/">github</a>.</li>
            <li>Task sheet made by us.</li>
            <li>Timer.</li>
          </ul>
        </p>
      </div>
      <div id="methodology">
        <br>
        <v-divider></v-divider>
        <br>
        <br>
        <h1>Methodology</h1>
        <h2>Experimental observation:</h2>
        <p>
For the sake of our experiment, we designed 3 web pages, each of them have the very same design except for buttons colors. These pages allow you to add a booking, delete a booking, and edit a booking.
The experiment is composed of three parts. Each part has a certain set of colors.
We gave those sets of colors names to label them.

First set of colors is called ‘common colors set’; where a shade of blue called ‘Primary’ in bootstrap is used for the ‘edit’ button, a shade of red called ‘Danger’ in bootstrap is used for the ‘delete’ button, and a shade of green called ‘Success’ in bootstrap is used for the ‘add new booking’ button.

Second set of colors is called ‘uncommon colors set’; where a shade of blue called ‘Primary’ in bootstrap is used for the ‘delete’ button, a shade of red called ‘Danger’ in bootstrap is used for both the ‘add new booking’, and the ‘edit’ button.

The last set of colors is called the ‘uncolored set’; where a shade of grey is used for all of the buttons regardless of their purpose.


Those color sets and their given names do not carry any scientific meaning, they were picked by the three of us according to our understanding of what is common in web design. The names were given to make it easier for us to refer to them and to test if our understanding of what is common is going to have an effect on the performance of our participants.

In order to eliminate the effects of order bias, we decided to randomize the order of the three pages while carrying the experiment on each participant.

We designed a task list for participants to go through. What matters to us is one variable, which is how fast they can finish the tasks for each set of button colors. Accuracy and errors are to be ignored in this experiment.
The timer starts when the participant starts working on the first page and stops when the participant finishes working on that set. Same thing is repeated for each set.
The tasks given are shown below.

        </p>
      </div>
      <div id="insruction">
        <br>
        <v-divider></v-divider>
        <br>
        <br>

        <h1>Software instruction</h1>
      <v-sheet color="green lighten-3">
        <ol>
          <li>Create 5 new bookings with the following information:
            <ul>
              <li>
              Customer name: <strong>Adam David</strong>
              <br>Date: <strong>11/05/2019 </strong>
              <br>Room: <strong>SH18</strong>
              </li>
              <li>
                Customer name: <strong>Dimitri Klashinkov </strong>
                <br>Date: <strong>15/02/2018</strong>
                <br>Room: <strong>GF55</strong> 
              </li>
              <li>
                Customer name: <strong>Captain Price</strong> <br>
                Date: <strong>24/04/2011</strong> <br>
                Room: <strong>MW141 </strong>
              </li>
              <li>
                Customer name: <strong>Geralt of Rivia</strong> <br>
                Date: <strong>18/07/2016</strong> <br>
                Room: <strong>KF54</strong>
              </li>
              <li>
                Customer name: <strong> Anatoli Abdul</strong> <br>
Date: <strong>02/06/2017</strong> <br>
Room: <strong> ST47</strong>
              </li>
              <li>
                Customer name: <strong>Rick Sanchez</strong> <br>
Date: <strong>05/11/1850</strong> <br>
Room: <strong>SJ45</strong>
              </li>
            </ul>
          </li>
          
          <li>Edit room <strong>GF55</strong>, change the date to <strong>14/02/2018</strong>.</li>

          <li>Delete the booking for <strong> Geralt of Rivia</strong>.</li>
          <li>Delete Rooms <strong>ST47</strong>, and <strong>SH18</strong>.</li>
          <li>
            Create a new room with: <br>
                Customer name: <strong>Alex French</strong> <br>
    Date: <strong>17/04/2007</strong><br>
    Room: <strong>FT85</strong>



          </li>
          <li>Edit the booking for <strong>Rick Sanchez</strong>, change the name to <strong> Morty Sanchez</strong>.</li>
          <li>Tell us that you’re done.</li>
        </ol>
          Thank you for your time:)
      </v-sheet>
      </div>
      <br>
      <v-divider></v-divider>
      <div id="refs">
        <h2>Refs</h2>
        Schauss, A. .G. . (1985). The Physiological Effect of Color on the Suppression of Human Aggression: Research on Baker-Miller Pink. : Alexander G Schauss.
      </div>
      </v-flex>
  </v-layout>
</template>

<script>
export default {

}
</script>

<style>

</style>