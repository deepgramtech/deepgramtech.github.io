# DeepGram 

With this project we want to develop a Telegram bot to allow you running Machine Learning and Deep Learning experiments directly on your phone. 

The only requirement will be the [Telegram app](https://telegram.org/apps) (or third party alternatives) installed on your phone/laptop, or just a browser to run [Telegram Web](https://web.telegram.org/).


# ---> [Book your ticket for the next event](https://www.eventbrite.it/e/biglietti-deepgram4-creiamo-un-bot-per-il-deep-learning-79733094833) <---
## Wednesday 6th of November 2019 @[Digital Tree - Innovation Hub](https://digitaltree.ai)

## Why is it important?

_Has it ever happened to you to have an idea that you would like to prototype faster?_ I know that is wrong to answer with a question to a question. But what we want is to allow you to implement some Machine Learning algorithm very fast, _on-the-fly_.

You won't need to go home, turn your computer on, open your IDE, copy some model from [Stackoverflow](https://stackoverflow.com/), becoming mad installing packages till you give up your awesome idea and go back to your 9-5 job.

You just need to open your Telegram app and click the right buttons. 

<p align="center">
  <img width="338" height="262" src="https://github.com/deepgramtech/deepgramtech.github.io/blob/master/img/telegrambot.png?raw=true">
</p>

Jokes apart, it will look something like:

<p align="center">
  <img width="542" height="590" src="https://github.com/deepgramtech/deepgramtech.github.io/blob/master/img/telegif.gif?raw=true">
</p>

while, somewhere else, something like the following is been creating:

<p align="center">
  <img width="650" height="250" src="https://github.com/deepgramtech/deepgramtech.github.io/blob/master/img/modelgif.gif?raw=true">
</p>

## This is a community based project.

No leaders here. Just passionate people desiring to learn, and _to create_. We organize **MeetUps** to make this real. If you are around Genova (Italy), come and build with us. 

### Where?
<a href="https://digitaltree.ai"><img align="right" width="100" height="100" src="https://github.com/deepgramtech/deepgramtech.github.io/blob/master/img/dtblack.png?raw=true">

At **[Digital Tree](https://digitaltree.ai), Viale Cembrano, 2, 16147 Genova GE.**



### When?

## [The next meetup will be on *Wednesday* 6th of November 2019, from 18 to 20.](https://www.eventbrite.it/e/biglietti-deepgram4-creiamo-un-bot-per-il-deep-learning-79733094833)

 Every two weeks, usually on *Wednesday*, **from 18 to 20**. 
 
 To be up to date, sync with our [Google Calendar](https://calendar.google.com/calendar/embed?src=i8m9ckbo5l0o38bc98ocui6mp8%40group.calendar.google.com&ctz=Europe%2FRome
): [here](https://calendar.google.com/calendar/embed?src=i8m9ckbo5l0o38bc98ocui6mp8%40group.calendar.google.com&ctz=Europe%2FRome) you will find any upcoming event.

## Outline

The meetups are structured as little hackatons of two hours, where specific (but not really fixed) goals have to be achieved. 

Our goal is mostly _learning by doing_, so we won't focus strictly on the advancement of the project at each meeting, but on learning as much as we can. The following is a outline of the content of the next three meetups:

### [Meetup#0](https://github.com/deepgramtech/deepgramtech.github.io/blob/master/img/firstbotgif.gif?raw=true)
After setting the basis at Meetup#0, we went further experimenting with several Python frameworks for Telegram bots, like [Telepot](https://github.com/nickoala/telepot) (that is no longer maintained) and [PyTelegramBotAPI](https://github.com/eternnoir/pyTelegramBotAPI) (that we are currently using).
<a href="https://digitaltree.ai"><img align="center" width="438" height="510" src="https://github.com/deepgramtech/deepgramtech.github.io/blob/master/img/giffirstbot.gif?raw=true">

Several basic functions have been implemented already, to become confident with the API (QR code generator, simple image processing stuffs...) and now the goal is to go further and to dig into the real Data Science.

Currently we are at [Meetup#4](https://www.eventbrite.it/e/biglietti-deepgram4-creiamo-un-bot-per-il-deep-learning-79733094833).

### Discussion

One of the goal of this project is to have a Telegram channel with datasets that are accessible to everyone. However, Telegram allows a user to send only till around 50 MB to a bot. On the other hand, a user can upload till around 1.4 GB on a Telegram Channel. For this reason, we created a function that forward messages over a certain size to a Telegram channel, in order to store it there.

Nevertheless, 1.4GB could be not enough for a dataset (dealing with pictures or videos it is easy to occupy much more). So we thought to work in the following way:

- Command to upload a dataset
- Send it 
- If the size is more than 1.4 GB send back a script to the sender to split the original file in smaller size ones
- Send all of the resulting files.

If you have better ideas, please contact us in the [Telegram Group](https://t.me/hackademiaitaly). 


## Questions?

Feel free to ask at antonio.marsella95@gmail.com or antoniomarsella@deepgram.tech, in the [Telegram Group](https://t.me/hackademiaitaly) or privately at [@marsantonio](https://t.me/marsantonio).
