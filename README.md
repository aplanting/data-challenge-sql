## Looking for real world SQL challenge ?
If you want to test your SQL skills you can try to complete this challenge. But you can use only SQL, preferably T-SQL to complete this.

### The challenge
A media company has send out an email to 10.000 customers asking them to participate in an online survey. If they complete the survey they are eligible for an giftcard for an online shop, see it as an discount card. The survey was requested by an third party. Amongst the participants 150 giftcards will be awarded with an valua of 5 euro's.

Every email has an unique link to the online survey, what makes is unique is an identifier in the link. 

In order for the media company to send the email an data export was made containing the IDs and the unique links and loaded into the email platform.

#### The winners
The winners are selected by the third party and IDs are delivered to the media company. 

#### The giftcards
The giftcards are delivered to the media company by another third party

#### The files
There are 3 files in this challenge.

- file containing the original selection made by the media company containing the user IDs and the unique link to the survey. (customer_ids_links.csv)
- file containing the selected winners by the third party containing an ID that is found in the unique link. (winners.csv)
- file with unique card numbers, pin numbers and the value of the card. (giftcards.csv)


### Your task
The media company have asked you to make an export of the winners and assigned to it the card numbers and pin codes. The export should be an CSV file so that it can be used in the email platform where it will send an email to the winners. The correct customers should be selected by ID in the links. 

You should use only SQL to accomplish this task.

##### Notes
If you want to complete this and share your solution, please upload the SQL script that you used to export the final CSV file. You can also share an notebook file for instance. You can do so in the ***issue*** section

*But be carefull, maybe there is something wrong with the data.........*
