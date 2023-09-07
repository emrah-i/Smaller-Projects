<h1 align="center">Smaller Projects</h1>

<br/>
<br/>

<h2>About the Projects</h2>

<h4>Pomodoro:</h4>
<p>This Pomodoro application was created exclusively using <ins>Python's TKinter module</ins>, without incorporating any web components. It was developed independently as part of my journey through the Udemy course <ins>"100 Days of Code: The Complete Python Pro Bootcamp,"</ins> however, I built it entirely from the ground up. The most challenging aspect of this undertaking was undoubtedly the user interface, as TKinter's limited customization options posed a significant hurdle. Nonetheless, the remainder of the project mainly entailed establishing loops and managing code to ensure UI updates.</p>

<p>The functionality of the application is quite simple. Clicking the start button starts a timer for 25 minutes. Once it reaches zero, you hear a beep noise and the break starts. This continues for a total of 5 cycles before it allows the user to take a longer 25 minute break. These cycles can be tracked with green check marks shown under the tomato. The timer can be stopped using the 'stop' button. Once stopped, the user must click the 'start' button to begin where they left off. The 'reset' button completely resets the timer and the cycle progress.</p>
<br/>

<h4>Flashcards:</h4>
<p>I developed this Flashcard application as part of my journey through the Udemy course <ins>"100 Days of Code: The Complete Python Pro Bootcamp,"</ins> once again, starting from scratch and use <ins>Python's TKinter module</ins>. The only resources I utilized from external sources were the flashcard images and a list of the 1000 most commonly used Turkish words.</p>

<p>Upon launching the application, the screen will display a flashcard featuring a Turkish word, indicated by the 'Turkish' label. Clicking on the flashcard triggers it to flip, revealing the English definition on the reverse side, indicated by the 'English' label. At the top, the application displays statistics on the learned words with current launch, total learned words, and those remaining in the deck. Additionally, there is a red and green buttons that enables users to categorize a word as either 'learned' or 'not learned,' with this information being automatically saved to a JSON file. Upon reloading the application, words from the JSON file are removed from the deck, preserving your progress and allowing you to seamlessly resume where you left off during your next session.</p>
<br/>

<h4>Pong:</h4>
<p>This is a straightforward rendition of the classic Pong game, created using <ins>Python's Turtle module</ins> and a series of classes. The primary goal behind its development was to gain hands-on experience with <ins>Object-Oriented Programming</ins> principles. In essence, there are four key classes at play: ball, paddles, score, and center line.
<ul>
  <li>The ball class handles various aspects of the ball's behavior, such as its speed and functionality, including movement, acceleration, resetting, and collision interactions with both paddles and walls.</li>
  <li>The paddle class defines the dimensions of the paddles and their movement speed.</li>
  <li>The score class takes charge of displaying and continually updating the game score whenever a player scores a point.</li>
  <li>Lastly, the center line class is responsible for drawing the central dividing line.</li>
</ul>
To get the game up and running, all that's required is configuring the ball's attributes and assigning the movement keys for the paddles.</p>
<br/>

<h4>Snake:</h4>
<p>Similar to my Pong game, this is another remake of a classic game using <ins>Python's Turtle module</ins> in order to practice <ins>Object Oriented Programming.</ins> There are four key classes for this game: food, scoreboard, and snake.
<ul>
  <li>The food is the red dot that gets randomly placed around the gameboard. Once it touches the snake, it automatically moves to a new location. </li>
  <li>The scoreboard keeps track of how many pieces of food the snake has consumed and updates the scoreboard with each new point.</li>
  <li>Lastly, the snake starts with a length of three segments and grows with each new piece of food. The most difficult part was making sure that each segment follows the segment before it. Also, the snake has to be moving fast enough so the gaps between the segments weren't visible.</li>
</ul>
</p>
<br/>

<h4>Twitter Bot:</h4>
<p>This bot was crafted exclusively using the <ins>Selenium</ins> module for Python. Its primary function conduct an internet speed test and tweet at the provider if the actual speed is lower than the promised speed. The bot's first action is to conduct a speed test by navigating to the website www.speedtest.net. Once the speed test completes, it captures the speed measurement. At this juncture, an "if" statement could be integrated to evaluate whether this recorded speed falls below the promised speed threshold. However, as this project was undertaken for recreational purposes, I opted not to include this feature to test it's full functionality.</p>

<p>If the test results indicate that the speed falls short of the promised value, the bot logs into Twitter and promptly tweets at the provider before exiting. If it is above or equal to the promised value, it would simply exit instead of tweeting. This bot can be executed multiple times throughout the day, utilizing a platform like PythonAnywhere to automate the process.</p>
<br/>

<h4>Spotify Playlist Maker:</h4>

<p>This application was built using the <ins>BeautifulSoup module and Spotipy API</ins>. The process begins by requesting the user's input for a specific date they desire a playlist for. Following that, BeautifulSoup is employed to navigate to the Billboard Charts on the provided date and fetch a comprehensive list of the top 100 songs. A for loop is then employed to iterate through this list, enabling each song to be added to a newly created Spotify playlist through the Spotipy API. Once all the songs are successfully added, the playlist can be accessed and shared via its unique, shareable link. Because there are multiple versions of some songs, the API struggles to find every song in the list. On average, it can find around 90 songs out of 100. This depends heavily on the date. Older songs generally have more releases or have the chance of not being lsited on Spotify at all.</p>
<br/>

<h4>Automated Birthday Messager:</h4>
<p>This tool has been developed using <ins>Python's SMTP module</ins>. It simplifies the process of sending birthday wishes by requiring the user to configure a JSON file containing entries with the following keys: name, birthday, year, subject, body, and email. The birthday is specified in MM-DD format, while the year is represented as a standard 4-digit integer.</p>

<p>These date values are then converted into datetime objects and compared to the current date. When the tool detects that it's someone's birthday based on the provided list, it proceeds to send them a pre-configured email with the specified subject and message body. As an additional enhancement, you can also configure the tool to send you an email as a confirmation that the birthday message has been successfully dispatched.</p>

<p>To automate this process, you can utilize a service like PythonAnywhere to schedule the tool to run at a designated time every day, checking the list for upcoming birthdays. While it may seem like a simple project, it can be a valuable tool for maintaining and nurturing friendships, especially when it runs automatically on a daily basis.</p>
