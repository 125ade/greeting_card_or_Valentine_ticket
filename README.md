# greeting_card_or_Valentine_ticket
single page of html / css / js to send the ticket anywhere. to change the page below I put the directions for those who are beginners




# for beginners
open the ticket.html file in a text editor and modify it following the guidelines listed below

    
### change the color of background
    [5]  body {          background-color: lightgreen;        }  in this line change the color of background
    [12] box-shadow:20px 20px 40px 10px green;                   in this line the color of the shading changes


### choiche birthday or anniversary
    [30] let choice = false;
    change for [birthday = true] or a [anniversary = false]


### set the date
    PLEASE NOTE THE MONTHS GO FROM 0 TO 11
    [31]let day_C = 1, month_C = 1, year_C = 1;// birthday
    [32]let day_A = 1, month_A = 1, year_A = 1; // anniversary


### set the message    
    write the message
    [33]  let msg_birthday = `put the text here , age `;
    [34]  let msg_anniversary = `put the text here , day `;


### set love message: [only if you have set the choice variable to false]
    you can add as many messages as you want
    [35]  let str =[`put the text here 1`,`put the text here 2`,`put the text here 3`];
    

# now save and send the html file to whoever you want



# License
This project is licensed under the MIT License - see the <a href="LICENSE.md">LICENSE.md</a> file for details
