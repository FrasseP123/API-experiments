## API Project - Randome sentences experiment

This project is based on Annyang’s API (read more about this in the “Main” README.md). In our main project, we’ve worked with simple sound outputs taken from conversations. (picture from annyang's website below)

![Skärmavbild 2021-03-12 kl  20 02 55](https://user-images.githubusercontent.com/78792592/110996811-c806bc00-837c-11eb-84f0-86ae699b8344.png)

## My project
In this experiment I’ve explored the possibilities of a more “intelligent” conversation between a person and the API, using audio outputs that give out longer sentences.
I’ve also experimented with adding different outputs to one command, making it put out random sounds from an array of sound files. With this I wanted to achieve a more "natural" conversation where the user can't predict the outcome. 
To make it easier to see what the API picked up of what the user said, I've emplimented that the words said are displayd on the page. 

## What is explored?
I wanted to make this experiment to see my ability to code an actual conversation, and also to see how the experience with talking to a non human object would feel like. I found that a lot of audio needed to be added due to me quickly learning what responses that were possible, and that more trigger words needs to be added to make the conversation more "natural". I added an array of randome "neutral" sounds that were triggerd whenever none of the trigger word were siad. This was made to simulate the noises we make when we show that we are listening, small humming noices that we put out as an reflex. 

![Skärmavbild 2021-03-12 kl  21 46 08](https://user-images.githubusercontent.com/78792592/110996764-b32a2880-837c-11eb-8ec8-895a278d6679.png)


## What you need to know
Annyang is a pretty simple API to work with. The sceleton that we built our main project on and that I experimented with was easy to ad on code to, to make it as we wated it. What the programmer needs is the programs stated in the "main README.md and ofcourse a visionis, what is going to happen and then add commands. Ether the audio files from the folder can be downloaded, or new files can be recorded that are then added to the code. To make the browser start listening, an interaction with the pages needs to be done, such as a click with the mouse. After this you start talking and you will recive feedback, at the same time as you'll se what you were saying. 
An importent thing is that the audio files that are added to the code can not contain any off the trigger words, or they will trigger another respons. Another thing to keep in mind is that audio with longer sentences vill trigger the neutral outputs.



## Contributers

The original code is taken from annyangs website (https://www.talater.com/annyang/). Frans, Yulu and I have then built a project upon that library and examples from the creators Github (https://github.com/TalAter/annyang). I have done a this separate experiment built on the same elements. All audio is done by us and all design elements as well.


