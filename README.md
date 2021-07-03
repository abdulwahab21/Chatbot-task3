# Chatbot-task3
This repository for chatbot. I have used Laravel 8, which is framework php, for back-end pages. There are two version for website control movement. The first one Arabic version and another English version. Inside the two versions there are two folders. First one, it is control-movement folder which has website pages. I prefer to use Visual Studio code for opening the control-movement folder because you need to use terminal and write (php artisan serve) to see the pages write URL (http://127.0.0.1:8000/)  and there are two pages index and see-settings. The second page you need add in the URL (display). Second one, it is UI folder that contains two pages UI. There is SQL file to download, or you can download by write (php artisan migrate). For chatbot, it in the main page. 
<hr>
The dialog of chatbot has 8 intents as follow: 
<hr>
1- Welcome: it shows welcome when someone open it. 
<hr>
2- Greeting: when a person send greeting like hello, good morning, etc. 
<hr>
3- Services: it provides services of chatbot when a person writes “what are services?” or similar question. Also, it has 3 entities. 
<hr>
4- Building website: it provides how I have built the website when person writes “can you tell me how you build the website?”. 
<hr>
5- Time of tournament: it provides the time of tournament when a person writes “When will the tournament begin?”.
<hr>
6- Cost of tournament: it provides the cost of tournament when a person writes “Is there any fee for the tournament?”.
<hr>
7- Thanks, it provides the pleasure when a person writes “Thanks”, “Thank you”, etc.
<hr>
8- Anything else: if the chatbot cannot recognize what a person writes.
<hr>
The pages location are control-movement -> resources -> view. For the assets is control-movement -> public.
<hr>
Note: you need to change the name of database inside .env file (DB_DATABASE) with your database name and username (DB_USERNAME) and password (DB_PASSWORD) if you have password.
<hr>
Note: if you can’t run (php artisan serve), you should download Composer.
