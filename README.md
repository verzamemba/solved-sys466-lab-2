Download Link: https://assignmentchef.com/product/solved-sys466-lab-2
<br>
<strong>(1%): Class Diagram Basics</strong>

<ul>

 <li>This is an individual lab and must be completed in the lab room.</li>

 <li>Using StarUML, create the required diagrams as per the instructions in this lab, then post the model you created to Blackboard under your name for example Lab2_MaryLee.uml</li>

</ul>




<strong>Setting up StarUML:</strong>

<ul>

 <li>When opening a new model select the empty approach. Name the project as “SYS466”, and then create a package “Lab2”.</li>

 <li>Under Lab2 package, create 3 new models. Name them Exercise 1, Exercise 2 and Exercise 3

  <ul>

   <li>To do this: Right click on Lab2, select Add, select Model. Do this 3 times, one for each of exercise 1, 2, and 3.</li>

  </ul></li>

 <li>To add a class diagram to a model: Right click on the model (e.g. Exercise 1), select Add Diagram, then Class Diagram.</li>

</ul>




For this Lab:

<ul>

 <li>You will be creating 3 class diagrams.</li>

 <li>For the use case described in each exercise below create a class diagram showing classes and attributes. DO NOT SHOW ASSOCIATIONS.</li>

 <li>Create the class diagram into the appropriate model in Lab2 of the uml file</li>

</ul>

<strong> </strong>

<a name="_Toc416803507"></a><strong>Exercise 1: Golf Tournament</strong><strong> Scenario</strong>




<table>

 <tbody>

  <tr>

   <td width="41"> </td>

   <td width="194">Actor (Tournament Coordinator)</td>

   <td width="374">System</td>

  </tr>

  <tr>

   <td width="41">1</td>

   <td width="194">Enters date,name of tournament and maximum number of golfers.</td>

   <td width="374">Creates the tournament and displays an entry area for 10 golfers with spaces for name, contact information—email address and/or phone number, handicap.</td>

  </tr>

  <tr>

   <td width="41">2</td>

   <td width="194">Enters golfer information and requests to add.</td>

   <td width="374">Checks that maximum number of golfers has not been exceeded and adds the golfers to the tournament.Displays an entry area for more golfers.</td>

  </tr>

  <tr>

   <td width="41">3</td>

   <td width="194">Repeats step 2 until done</td>

   <td width="374">Displays and prints a list of golfers registered for the tournament.</td>

  </tr>

 </tbody>

</table>







<a name="_Toc416803508"></a><strong>Exercise 2: Purchase tickets for a Bus Tour</strong><strong> Scenario</strong>




<table>

 <tbody>

  <tr>

   <td width="41"> </td>

   <td width="193">Actor (online customer)</td>

   <td width="366">System</td>

  </tr>

  <tr>

   <td width="41">1</td>

   <td width="193">Chooses a bus tour from a list of tours</td>

   <td width="366">Displays tour name, originating station and destination station and tour description. Also displays a list of dates on which the tour is offered.Displays tour price for each of the dates (summer tours are more expensive than spring and fall tours).</td>

  </tr>

  <tr>

   <td width="41">2</td>

   <td width="193">Selects one of the dates and requests to book a ticket for the tour</td>

   <td width="366">Displays an entry form for name, address, phone and email.</td>

  </tr>

  <tr>

   <td width="41">3</td>

   <td width="193">Enters name, address, phone, email.</td>

   <td width="366">Displays total price and all tour information for confirmation.</td>

  </tr>

  <tr>

   <td width="41">4</td>

   <td width="193">Confirms</td>

   <td width="366">Transfers to paypal and completes the payment transaction.Emails a ticket to the traveller.</td>

  </tr>

 </tbody>

</table>




<strong> </strong>

<a name="_Toc416803509"></a><strong>Exercise 3: Purchase tickets to the performance of a show</strong><strong> Scenario</strong>




<table>

 <thead>

  <tr>

   <td width="41"> </td>

   <td width="194">Actor (online customer)</td>

   <td width="365">System</td>

  </tr>

 </thead>

 <tbody>

  <tr>

   <td width="41">1</td>

   <td width="194"> </td>

   <td width="365">Displays a list of all shows (names and descriptions) for the theatre.</td>

  </tr>

  <tr>

   <td width="41">2</td>

   <td width="194">Chooses a show</td>

   <td width="365">Lists all performance dates for the show.</td>

  </tr>

  <tr>

   <td width="41">3</td>

   <td width="194">Chooses a performance date</td>

   <td width="365">Displays a list of theatre sections with prices for each section.</td>

  </tr>

  <tr>

   <td width="41">4</td>

   <td width="194">Chooses a section.</td>

   <td width="365">Searches for available seats based on the section and performance date selected.Displays available seats—shows row and seat number for each.</td>

  </tr>

  <tr>

   <td width="41">5</td>

   <td width="194">Chooses seats.</td>

   <td width="365">Displays total price and requests confirmation.</td>

  </tr>

  <tr>

   <td width="41">6</td>

   <td width="194">Confirms</td>

   <td width="365">Creates a purchase transaction and transfers control to the PAYPAL system. PAYPAL processes the request and returns control to the system being designed.The system displays ticket information for the purchased seats along with the total cost and a link to the pdf ticket file which the patron can print.The system also sends a confirmation email to the patron containing the link.</td>

  </tr>

 </tbody>

</table>


