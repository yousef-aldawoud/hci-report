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
            <li>Web page we designed on <a target="_blank" href="https://yousef-aldawoud.github.io/booking-demo/">github</a>.</li>
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
      <br>
      <v-divider></v-divider>
      <div id="discussion">
      <br>
      <br>
      <br>
        <h1>Discussion & Findings</h1>
        <div>
          Within the 15 people that we have involved within the experiment and interview, 
<br> Table 1: Participants on Coloured Booking (Time-spent)
      <br>
      <br>
      <v-row>
        <v-flex xs12 md6>
          <h4>Colored</h4>
          <TrendChart
          class="table1"
          :min='0'
          :max='500'
          :datasets="table1.dataset"
          :grid="table1.grid"
          :labels="table1.labels"
          ></TrendChart>
          <h5 class="text-center">Participants</h5>
        </v-flex>
      </v-row>
      <br><br>
      <v-row>
        <v-flex xs12 md6>

          <h4>Non-Colored</h4>
          <TrendChart
          class="table1"
          :min='0'
          :max='500'
          :datasets="table2.dataset"
          :grid="table1.grid"
          :labels="table1.labels"
          ></TrendChart>
          <h5 class="text-center">Participants</h5>
        </v-flex>
      </v-row>
      <br><br>
      <v-row>
        <v-flex xs12 md6>

          <h4>Random-Colored</h4>
          <TrendChart
          class="table1"
          :min='0'
          :max='500'
          :datasets="table3.dataset"
          :grid="table1.grid"
          :labels="table1.labels"
          ></TrendChart>
          <h5 class="text-center">Participants</h5>
        </v-flex>
      </v-row>
      <br><br>
      <v-row>
        <v-flex xs12 md6>

          <h4>Random-Colored</h4>
          <div>
            <v-chip color="red" small dark>colored</v-chip>
            <v-chip color="orange" small dark>non-colored</v-chip>
            <v-chip color="purple" small dark>random-colored</v-chip>
          </div>
          <TrendChart
          class="table4"
          :min='0'
          :max='500'
          :datasets="table4.dataset"
          :grid="table1.grid"
          :labels="table1.labels"
          ></TrendChart>
          <h5 class="text-center">Participants</h5>
        </v-flex>
      </v-row>
        <br>
        <br>
        <br>
        <br>
        <v-row>
<v-flex xs12 md6>

        <apexchart  type="bar" :options="bar.options" :series="bar.series"></apexchart>
</v-flex>
        </v-row>
        <br>
        <br>
        The data that we have collected within 3 graphs represents the time it takes for the 3 tasks to be finished, we have asked 15 participants that had access to our Booking App to perform the given task as mentioned before where they would have to finish 6 tasks using the booking app. There are 3 variations where the first one is using coloured buttons, second would be non-coloured buttons, and the third would be randomly coloured buttons. The 3 variations are given in random order for each participant to avoid the bias that we would receive needed for our statistical evidence. We initially assumed that coloured buttons affect users by giving them a faster reaction when buttons are more familiar due to the nature of colour, but with the results of our calculation, we have found that it is not entirely the case. Within the graph that we produced, we have noticed the following.

The Coloured Results varies per participants, but we have calculated their results and received an average of 307.13 seconds or 5 minutes and 7 seconds.

The Non-coloured results have seen an average of 317.47 seconds or 5 minutes and 17 seconds which is a mere 10 seconds more than the coloured results.

The Random coloured results have an average of 285.6 seconds or 4 minutes and 47 seconds which is 32 seconds less than the Non-coloured results and 22 seconds less than the Coloured Result.

If we were to make an initial assumption, all 3 average shows variation but with a larger population size, we might not see any distinct difference so this proves that the data we are trying to gather doesn’t vary from one another, and therefore it has no significance whether the colour or the presence of text affects whether the user would perform faster within a given task.
<br/>
<br/>
<strong>NULL HYPOTHESIS, H0:</strong>
the means of the time taken do not vary significantly between the different coloured tests.
<br/>
so;
<br/>
      <div style="font-size:20pt">
      µ 1  = µ2  = µ3   = 0 
      </div>

  </div>
  <strong>ALTERNATIVE HYPOTHESIS</strong>, HA: the mean of the time taken does vary significantly between the different coloured tests.
  <div style="font-size:20pt">
    µ 1  ! = µ2  ! =  µ3   ! = 0  
  </div>
  <br/>
  <br/>
  <table style="width: 100%;">
    <tr>
      <th>#</th>
      <th>Colored</th>
      <th>NON-Colored</th>
      <th>RANDOM</th>
    </tr>
    <tr v-for="n in table" :key="n.name">
      <td>{{n.name}}</td>
      <td>{{n.colored}}</td>
      <td>{{n.noncolored}}</td>
      <td>{{n.randcolor}}</td>
    </tr>
  </table>
</div>
<div id="anova">
<br>
<br>
<br>
  <h2>One way ANOVA:</h2>
  <div>

    Anova: Single Factor
    <h4>Summary</h4>
    <table>
      <tr>
        <th>Groups</th>
        <th>Count</th>
        <th>Sum</th>
        <th>Average</th>
        <th>Variance</th>
      </tr>
      <tr>
        <td>Colored</td>
        <td>15</td>
        <td>4607</td>
        <td>307.133333</td>
        <td>5183.838095</td>
        
      </tr>
      <tr>
        <td>Non-Colored</td>
        <td>15</td>
        <td>4762</td>
        <td>317.4666667</td>
        <td>4767.409524</td>
      </tr>
      <tr>
        <td>Rand-Colored</td>
        <td>15</td>
        <td>4284</td>
        <td>285.6</td>
        <td>3696.542857</td>
      </tr>
    </table>
    <br>
    <h4>ANOVA</h4>
    <table>
      <tr>
        <th>Source of Variation</th>
        <th>SS</th>
        <th>df</th>
        <th>MS</th>
        <th>F</th>
        <th>P-value</th>
        <th>F crit</th>
      </tr>
      <tr>
        <td>Between Groups</td>
        <td>7929.73</td>
        <td>2</td>
        <td>3964.87</td>
        <td>0.87</td>
        <td><strong>0.43</strong></td>
        <td>3.22</td>
      </tr>
      <tr>
        <td>Within Groups</td>
        <td>191069.07</td>
        <td>42</td>
        <td>4549.26</td>
      </tr>
      <tr>
        <td>total</td>
        <td>198998.80</td>
        <td>44</td>
      </tr>
    </table>
    <br>
  If the P-value is insignificant (more than 0.05) it means the F stat is insignificant.
  It means no significant variance between the color sets was found, which means that we can’t disprove the null hypothesis,

  <strong>P-value = 0.43</strong> which is higher than 0.05,<strong>which means we failed to reject the null hypothesis.</strong>

  </div>
  
</div>
<br>
<v-divider></v-divider>
<div id="analysis">
  <br><br>
  <br>
  <h2>Analysis</h2>
  <div>
    The principles required for a usability test is to show how the design works to meet the purpose when testing the phenomenon. According to our data research, our perception of colour and the ability to read a button function has little to no effect whether the user would be far more adept or responsive whether the buttons look enticing, or whether the colour is random at all.
  </div>
  <br>
  <div>
    Initially, we have a sample size of 15 participants, we would not be able to get our level of confidence to a very acceptable rate so we resort into getting the initial result that the difference in colours doesn't matter. This means that we cannot prove our initial findings from our research that humans are more susceptible to colours and in extension, buttons with familiar colours of red and green should instinctively give us the idea green means good (continue) and red means bad (error or delete).
  </div>
  <br>
  <div>
    Secondly, even though we attempted to reduce the potential bias by randomizing the test that each participant would receive, we cannot escape the bias of them doing the same task 3 times in a row, which means that their 2nd and 3rd attempt would be faster. This means that we cannot get the amount of skew that we are expecting as most participants would follow a trend of getting faster and better on their subsequent attempt given that they have already done the activity beforehand.
  </div>
  <br>
  <div>
    Through this usability test that we ran through our subjects, the phenomenon of colour familiarity applied to UI/UX design has failed to deliver a conclusive evidence that colour does affect the users performance, speed, and instinctive reaction to natural colours applied to buttons. If we cannot gather more participants, then we wouldn’t be able to prove the validity of our theory.
  </div>

</div>
<br>
<v-divider></v-divider>
 <div id="further-research">
   <br>
   <br>
   <br>
   <h2>
     Further Research
   </h2>
   We have looked further into how do we eliminate performance and familiarity biases by giving the participants a random set of tasks every time they would do either of the 3 Booking Tasks. We are thinking of increasing our sample size and participant count so that we could increase the confidence level of our statistical findings. If both of these parameters could be improved in the future, then we would be able to expect a more conclusive proof whether colour does affect our performance as our P-value would be able to reach below 0.05 or 5%, so that we would be able to claim that the statistical data we got is significant to disprove the null hypothesis.
 </div>
 <br>
 <v-divider></v-divider>
<div id="usability-testing">
  <br>
  <br>
  <br>
  <h2>
    Usability Testing
  </h2>
  <div>
    Usability testing is a way of letting users test a hardware, software, or a phenomenon in order to see how easy it is to use.  (Barnum, 2010)
  </div>
</div>
<div id="usability-eval">
  <br>
  <br>
  <br>
  <h2>
    Usability Evaluation
  </h2>
  <div>
    <div>
      The use of a usability evaluation is to test a service which introduces the users to the new design which guarantees that it is user-friendly and it is instinctual irregardless of the user. This is able to provide a positive user experience as this links the existing knowledge the users have into a service that they are about to use which guarantees that any possible issues can be evaluated before releasing the product.
    </div>
    <br>
    <div>
      Since we are testing a phenomenon and not the usability of the booking app, we are more inclined to find the group’s result to prove that the phenomenon does exist and is prevalent on a lot of application that is currently out in the market.
    </div>

  </div>
</div>
<br>
<v-divider></v-divider>
<div id="conclusion">
  <br>
  <br>
  <br>
  <h1>Conclusion</h1>
  <p>
    In conclusion, we failed to prove that there’s a significant variance between the means of the speeds for different color sets. This can be explained by the lack of enough participants. Although we succeeded in doing further research that could further prove the phenomenon as long as we keep our data collection bias-free and the task to be varied to reduce familiarity bias and to be able to reduce the variance in between the data sets.
  </p>
  <p>
    Due to having a very limited number of participants, we decided to have each participant try the three color sets and switch the sequence of the three of them every time we conducted the experiment. This was to reduce the effect of order bias.
However, we noticed that participants had the tendency to become faster at the second trial than the first, and faster at the third than the second. The difference was very significant that we had to make sure each 5 of the 15 participants start with a sequence of the same first color set, and even those had to be divided into 2 types where half of them have a different second color set than the other half.
Although we tried all those complicated methods of controlled randomisation, data was still not enough and the order bias still had a slight effect. 
  </p>
  <p>
    What could’ve solved this problem is having more participants where we can have each participant try one single color set so they won’t have the effect of getting used to the software. 
  </p>
  <p>
    Another factor that may have contributed to this failure is that we tested button colors on a webpage with a white background. Having a different background color can affect the numbers. This is because background color can change how we see the colors of the buttons.
  </p>
</div>
<v-divider></v-divider>
<div id="ref">
  <br>
  <br>
  <br>
  <h2>Reference</h2>
  Barnum, C.M. (2010). Retrieved from 
  <a
  target="_blank" 
  href="https://books.google.co.nz/books?hl=en&lr=&id=tzX3J81MAAMC&oi=fnd&pg=PP1&dq=Usability+Testing+Essentials:+Ready,+Set...Test!&ots=uV5-ozYqbo&sig=t_cBPPdfZ1ZNMiVT8zxA_u4Y_rI&redir_esc=y#v=onepage&q=Usability%20Testing%20Essentials%3A%20Ready%2C%20Set...Test!&f=false">
  https://books.google.co.nz/books?hl=en&lr=&id=tzX3J81MAAMC&oi=fnd&pg=PP1&dq=Usability+Testing+Essentials:+Ready,+Set...Test!&ots=uV5-ozYqbo&sig=t_cBPPdfZ1ZNMiVT8zxA_u4Y_rI&redir_esc=y#v=onepage&q=Usability%20Testing%20Essentials%3A%20Ready%2C%20Set...Test!&f=false
  </a>
  <br>
  <br>
Schauss, A. .G. . (1985). The Physiological Effect of Color on the Suppression of Human Aggression: Research on Baker-Miller Pink. : Alexander G Schauss.


</div>
<br>
<v-divider></v-divider>
<div id="reflection">
  <br>
  <br>
  <br>
  <h2>Individual Reflection</h2>
  <h3>
    Jeson Dijamco
  </h3>
  <p>
    Our lives have integrated with technology for a long time from our work to our home lives, it is intertwined with our daily lives as much as technology is made smart to catch up to our fast pace of life. Our interaction with computers is bound strong that it affects the motion of our society, business, lifestyle and future. As IT students, we are driven to push this status quo forward, and with AHCI I have learned that our biological constructs or our 5 main senses are connected like two hands locked as if in prayer. AHCI through BCIS allowed me to understand the major factors that let technology affect us and how can we utilize technology efficiently.
  </p>
  <p>
    During this specific group assignment, I developed my ability to research information necessary to form an analysis report. With the help of this assignment, I have learned how to back my research with statistical evidence required in order to prove an aspect within the research that we are currently working on.
  </p>
  <p>
    My main responsibility is to set the Discussion and Findings of this experiment and to show enough statistical evidence of the phenomenon that we are trying to prove. I have also performed gathering data by locating participants and timing their results in order to meet my quota. I am certain that I have successfully done my part even though the results that we received didn’t match my initial expectations of what the phenomenon would be.
  </p>
  <p>
    After the finalization of the findings that we have laid out, I learned how to improve my methods of gathering data, and providing controlled tests as bias could affect the collected data that I would be using to prove a phenomenon. So as a future Software developer, I am on the mindset that I should be proactively thinking if I am collecting the right set of data and if the data that I am collecting is worthy of being tabulated.
  </p>
  <p>
    Team wise, the main issues where there wasn’t any initial contact on the first few weeks of the assignment, so we were left to prove a theory on a short amount of time. During the first readings of the assignment, I got stuck on how do I relate usability testing on proving a phenomenon. Due to the strain that I have on time and schedule and other papers, I am afraid that I am not producing a good quality report that would have sufficient evidence, research, and analysis.
  </p>
  <v-divider></v-divider>
  <br>
  <br>
  <h3>
    Yousef Aldawoud
  </h3>
  <p>
    When I finished this paper I had learned a lot about how humans interact with different devices and what design aspects should be looked after to ensure the usability of that device.
  </p>
  <p>
    In the first lecture, we had examples of previous devices that had different shapes and forms and we were taught about the two important aspects when looking at the artefacts presented
  </p>
  <ul>
    <li>Context of use </li>
    <li>Culture </li>
  </ul>
  <p>
    The fact that some devices are designed in a specific way due to culture preferences at a time is interesting and raises a lot of questions in mind.
  </p>
  <p>
    As we progressed through the lectures we came across the process of designing and the importance of prototypes. We learned how prototypes serves a big role in making a device or a software easier to use for users.
  </p>
  <p>
    When were introduced to the second assignment, We started to learn topics regarding experiments and UI quality over features.
  </p>
  <p>
    In this assignment I was responsible for designing the experiment software and in managing the report layout on the web version.
  </p>
  <p>
    I learned how to test usability on a software and how to control the variables in the experiment
  </p>
  <div>
    Lots of what I learned in the first half of the semester helped when making the software
    <br>
I had to learn a bit of HTML, CSS and Javascript to make the software.
<br>
It was a simple software for booking rooms.
<br>
The software contained three different versions colored non-colored and randomly colored.

  </div>
  <p>
    In the second half of the semester we started learning about topics related to our second assignment. One of the topics that picked my interest is conducting experiments. We learned how some experiments can result in insufficient data for a study and how we can avoid those types of experiments. Furthermore, we learned how to observe people when they are part of that experiment 
  </p>
  <p>When the people started testing my software and speaking about it I started to understand what UI elements the software lacked and what can be improved</p>
  <p>
    I learned how experiments should have constants and variables. 
We also learned how to collect data from people and how to write questionnaires.
What types of questions that can be useful for one topic and useless for the other.

  </p>
<p>
After finishing the second assignment, I feel more confident in my skills as a web developer.
Due to learning the key values of UX/UI and exploring topics such as how humans’ mind learns to use different tools.
I believe that my skills as a designer and a UI developer has improved after I took this class
  </p>
  <v-divider></v-divider>
  <br>
  <br>
  <h3>Ahmed Aldawoud</h3>
  <p>
    Web apps, and mobile apps have become a huge part of our daily lives. We almost don’t pass a day without being on at least one or probably more Web applications. 
In the last few years, we changed the way we browse the internet in the sense of we started using phones more often than a laptop of a PC. This meant that UIs need to be flexible to satisfy a large range of screen sizes.  

  </p>
  <p>
    As a web developer and a colorblind person, I always had a problem picking colors for my website. I did some research about this topic and most UX designers were suggesting to start with the brand colors. However, I have noticed that when it comes to button colors, there is a lot of theories to what you should use for what. This assignment gave me and my friends the opportunity to experiment with different button color sets. Although we did not have enough participants to have a meaningful significant difference, we learned how to conduct that experiment, and how to make sense of data using data analysis tools.
  </p>
  <p>
    If we had the time to do things differently, we would have been better off having each participant try one color set only, and to as many participants as we can. Having many participants will make it better as the effect of participants having different levels of skills in doing tasks online ( which we can’t control).
  </p>
  <p>
    My responsibilities for this assignment were to design the task sheet, find participants to conduct the experiment, analyse the data, be part of writing the report, and help design the experiment UI hosted on github. The most part I enjoyed was the data analyses because I got to try some of the statistical methods I learned in the past, and make conclusions based on numbers.
  </p>
  <p>
    This research taught me about how details must be considered when designing an experiment and that some variables can’t be fully controlled but their effect can be minimised with having more samples and randomisation. It also made me understand the strength and importance of few statistical methods that I learned before.
  </p>
  <p>
    In the end, although we failed to disprove the null hypothesis, we learned a lot about what could have been done better to improve our results. I learned more about the concept of experimenting than whether colors make a difference on buttons. Although I am still interested in knowing what would the results be if the experiment was done on a larger sample, I now at least know what the next step should be to redo such experiment and get better, more reliable results.
  </p>
</div>
      </v-flex>
  </v-layout>
</template>

<script>
export default {
  data(){
    return{
      table1:{
        dataset:[
          {
            data: [380, 290, 345, 205, 306, 280, 370, 290, 310, 470, 200, 206, 216, 380, 320],
            smooth: false,
            fill: true
          }
        ]
        ,grid:{
          verticalLines: true,
          horizontalLines: true
        }
        ,labels:{
          xLabels:[],
          yLabels: 6
        }
      },
      table2:{
        dataset:[

          {
            data: [320, 260, 365, 225, 374, 380, 250, 350, 285, 370, 410, 210, 227, 410, 330],
            smooth: false,
            fill: true
          }
        ],
      },
      table3:{
        dataset:[

          {
            data: [280, 204, 360, 280, 265, 335, 220, 325, 265, 305, 370, 180, 260, 380, 360],
            smooth: false,
            fill: true
          }
        ],
      },
      table4:{
        dataset:[
          {
            data: [280, 204, 360, 280, 265, 335, 220, 325, 265, 305, 370, 180, 260, 380, 360],
            smooth: false,
            fill: false,
            className: "curve1"

          },
          {
            className: "curve2",
            data: [320, 260, 365, 225, 374, 380, 250, 350, 285, 370, 410, 210, 227, 410, 330],
            smooth: false,
            fill: false
          },
          {
            className: "curve3",
            data: [380, 290, 345, 205, 306, 280, 370, 290, 310, 470, 200, 206, 216, 380, 320],
            smooth: false,
            fill: false
          }
        ]
      },
      bar:{
        options:{
          chart: {
          id: 'vuechart-example'
        },
        xaxis: {
          categories: ["Participants"]
        },

        },
        series: [
            {
              name: 'non-colored',
              data: [4800]
            },
              {
                name: 'random colored',
                data: [4200]
              },
          {
            name: 'colored',
            data: [4500]
          },
        ]
      },table:[
        {name:"Mean",colored:"307.133333",noncolored:'317.4666667',randcolor:"285.5"},
        {name:"Standard Error",colored:"18.5900298",noncolored:'17.82771162',randcolor:"15.6982862"},
        {name:"Median",colored:"310",noncolored:'341',randcolor:"282"},
        {name:"Mode",colored:"N/A",noncolored:'364',randcolor:"N/A"},
        {name:"Standard Deviation",colored:"71.9988757",noncolored:'69.0464302',randcolor:"60.7992011"},
        {name:"Sample Variance",colored:"5183.8381",noncolored:'4767.409524',randcolor:"3696.54286"},
        {name:"Kurtosis",colored:"-0.2280125",noncolored:'-1.557960357',randcolor:"-0.7341369"},
        {name:"Skewness",colored:"0.2946202",noncolored:'-0.184069337',randcolor:"0.02084649"},
        {name:"Range",colored:"255",noncolored:'193',randcolor:"209"},
        {name:"Minimum",colored:"201",noncolored:'217',randcolor:"179"},
        {name:"Maximum",colored:"456",noncolored:'410',randcolor:"388"},
        {name:"Sum",colored:"4607",noncolored:'4762',randcolor:"4284"},
        {name:"Count",colored:"15",noncolored:'15',randcolor:"15"},
        {name:"Confidence Level(95.0%)",colored:"39.8716483",noncolored:'38.23663856',randcolor:"33.6694753"},
      ]

    }
  }
}
</script>

<style lang="scss">
.table1{
    .stroke{
      stroke:blue;
    }
}
.table4{
  .curve1{
    .stroke{
      stroke: red;
      stroke-width: 2px;
    }
  }

  .curve2{
    .stroke{
      stroke-width: 2px;
      stroke: purple;
    }
  }
  .curve3{
    .stroke{
      stroke-width: 2px;
      stroke: orange;
    }
  }
}
table {
  border-collapse: collapse;
  
}

th, td {
  padding: 8px;
  text-align: left;
  border-bottom: 1px solid #ddd;
}
</style>