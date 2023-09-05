# CupidOverflow

A Website inspired by Stackoverflow for Dummies in Love!

<h2>About</h2>
<br>
This is a internship-related project of mine where I was asked to clone Stackoverflow using Django, but I had to use my own ideas and whatnot so that I can "learn" the basics
of Django. I know the name and the website itself and the idea of the website are dumb. Hence the phrase, "Dummies in Love". Because I, myself, am a dummy who happens to be in
love and it's painful to say the least. Not the love part. The dummy part. I mean, each day I wake up and say last night was the most stupid thing that I have ever done 
and I somehow manage to top it all off... AGAIN. 
<br>
<br>
<br>
<h4>Something worth a beginner's while</h4>
<br>
The Navbar's about redirects you to the about section of the website from anywhere. Most new Django users forget that they must add a "/" before the "#" to be able to redirect the website towards 
their desired section within the html code. And for this to work you must have an ID assigned to the HTML elements. 


<br>
<h2>Some Technicalities</h2>
<br>
Django 4.2.4 is used along with Pillow 10.0.0 to integrate the users' profile picture, and Django Crispy Forms is used to integrate the Q&A part of the clone of Stackoverflow.
The database I have used is SQLite3, which I will be changing to Postgres, in a couple of days (unless I start to procrastinate on this project). The main reason behind this is that,
my seniors have given me different Django-related tasks to get me up-to-speed on the problem solving of Django with different databases as backend. So far I have used MySQL as well as SQLite3,
but I have yet to use Postgres, and for this reason my seniors at the firm for which I am interning (@LearnOBots) have given me the task to implement this "Clone" of Stackoverflow using my own
ideas but implement it using SQLite3 as well as Postgres. 
<br>
This is the part where I would like to clarify that I did not code the frontend from scratch, I instead have used Bootstrap to get the skeleton code for various items such as the Navbar.
<br>
<h2>Overall Look and Feel of the Website</h2>
<br>
<h2>Landing Page</h2>
<br>

![1](https://github.com/Xcel2k/CupidOverflow/assets/79083282/8c4dd8f5-f55b-4b0b-bd15-38572884e2cc)


<br>
The landing page presents a very simple design featuring three clickable buttons that take you(the user) to the pages where the good stuff(questions) are at!
<h2>User Interface of the Website</h2>
<br>


![1](https://github.com/Xcel2k/CupidOverflow/assets/79083282/7b2ac608-8aca-4d4c-b295-d01a105d7d65)


![2](https://github.com/Xcel2k/CupidOverflow/assets/79083282/be28911b-7012-48ce-8233-510d4d94fa45)


![3](https://github.com/Xcel2k/CupidOverflow/assets/79083282/5a9d5e50-9f28-4203-9e6b-411b437feb88)

![4](https://github.com/Xcel2k/CupidOverflow/assets/79083282/72746ed0-56fc-4055-81b8-d29e720e2748)


![5](https://github.com/Xcel2k/CupidOverflow/assets/79083282/d4283c8e-3ce8-4282-a4fe-c3c6deeb4a54)


![6](https://github.com/Xcel2k/CupidOverflow/assets/79083282/5d49c907-d944-4f6d-931a-f41c999999fd)


![7](https://github.com/Xcel2k/CupidOverflow/assets/79083282/143ebe3c-9b35-4e82-960e-bd69159a949d)


<br>

<h2>Register/Sing up view</h2>
<br>


![register](https://github.com/Xcel2k/CupidOverflow/assets/79083282/5f402524-b31a-4fe0-b874-15101ae11ab8)



<br>
<h2>Login/Sign in view</h2>
<br>

![login](https://github.com/Xcel2k/CupidOverflow/assets/79083282/1ccd31b4-ebda-4ce9-8066-22943467ed86)


<br>

<h2>Profile view</h2>
Upon registering as a user, you will be redirected to the homepage of the website, where you will find that the buttons that were previously "login" and "signup" have now been changed to 
"Profile" and "Logout", respectively.
<br>


![profileview](https://github.com/Xcel2k/CupidOverflow/assets/79083282/85fb67e6-2594-4d31-8f2d-8a15cf4e551a)


<br>
<h2>Profile update view</h2>
Upon clicking on the profile, you will see that you can update the info on your profile and change your username, bio, and profile picture as well
<br>


![profileupdate](https://github.com/Xcel2k/CupidOverflow/assets/79083282/e7e0b4b4-529e-48f2-83f4-8f7239253fd2)



<br>
Completion of this update dialog will lead to a prompt that says you have successfully updated your profile and it will display the changes that you have just made

![successfulupdateprofile](https://github.com/Xcel2k/CupidOverflow/assets/79083282/0025e5c3-55b7-4046-9904-a4f08ad499b4)


<br>
<h2>Questions and Answers</h2>
<br>

If you click on any of the three buttons provided on the Landing page, you will be redirected to the appropriate page of the questions where all of the top questions will be displayed (these are
displayed using the formatting of the latest question asked). I have used the latest question asked formatting since that is the one which Stackoverflow follows, and since this website was 
originally meant to be a clone of stackoverflow and I was later asked to change it according to my own creativity, this is a feature that I felt would be better if left unchanged.
<br>
The top questions will be displayed as under:
<br>

![topquestions](https://github.com/Xcel2k/CupidOverflow/assets/79083282/ce6e6bf4-b4e9-4642-acba-7a03a93f25b7)

<br>

<h2>New Question</h2>
You can ask a new question by clicking the "Ask a question" button, which will redirect you to the following screen:
<br>

![newquestion](https://github.com/Xcel2k/CupidOverflow/assets/79083282/52a067e4-8570-4ae8-bc8c-fbfa1206f5d7)


<br>




<h2>Question upon being asked</h2>
When you ask a quesiton, this is how it will be displayed, if there doesn't exist an answer to the question:
<br>

![questions](https://github.com/Xcel2k/CupidOverflow/assets/79083282/dd48654f-e538-4c47-b1e4-27ff9f635002)


<br>

<h2>Answering a question</h2>
Suppose, you are an expert (loveguru as per the terminology of the website :3), and you want to guide a newbie about something that they want answers/guidance for. 
You simply click on the question and click the answer this question button located under the question form. This will take you to the following display:

<br>


![answer](https://github.com/Xcel2k/CupidOverflow/assets/79083282/42b88b25-25ad-4225-8526-923957181989)




<br>



<h2>Question upon being answered</h2>
If you were to click on any of the questions given in the "Top Questions" bit, you will be redirected to a page which shows the same display as the one shown above... but... 
if there exists an answer, the following will be displayed:
<br>

![qnaview](https://github.com/Xcel2k/CupidOverflow/assets/79083282/234311fd-e19e-4ce0-82fb-327c58e861b9)


<br>

<h2>About the author</h2>

<br>
Hello everyone! I'm glad you made it this far. My name's Muhammad Osama, Xcel is my gaming name and i'm an ex-professional of Counter-Strike and Counter-Strike Global Offensive for my country, Pakistan. I'm also a hobbyist photographer 
and I love nothing more than to just sit on the rooftop, watching the moon illuminate whatever is in its wake. What do the cool kids call it? Selenophile? I could never get this word right tbh since I always just write selena gomez instead 🥰
<br> 
I want to thank https://github.com/desphixs for the amazing youtube tutorial that helped me get this Website up and running (at least on my localhost) 😜
<br>
You can clone this repo using the following command:
<br>
git clone https://github.com/Xcel2k/CupidOverflow.git 
<br>
If you find any bugs/improvements, do let me know ❤️
Check out more of my projects over at https://www.github.com/Xcel2k
Alternatively, you can find me over at
<!-- display the social media buttons in your README -->

[![facebook](https://github.com/shikhar1020jais1/Git-Social/blob/master/Icons/Facebook.png (Facebook))][1]
[![instagram](https://github.com/shikhar1020jais1/Git-Social/blob/master/Icons/Instagram.png (Instagram))][2]
[![twitter](https://github.com/shikhar1020jais1/Git-Social/blob/master/Icons/Twitter.png (Twitter))][3]
[![linkedin](https://github.com/shikhar1020jais1/Git-Social/blob/master/Icons/LinkedIn.png (LinkedIn))][4]
[![github](https://github.com/shikhar1020jais1/Git-Social/blob/master/Icons/Github.png (Github))][5]


<!-- To Link your profile to the media buttons -->

[1]: https://www.facebook.com/mohammad.osama1257
[2]: https://www.instagram.com/mohammad_xcel_osama
[3]: https://www.twitter.com/Xcel2k
[4]: https://www.linkedin.com/in/Xcel2k
[5]: https://www.github.com/Xcel2k

























