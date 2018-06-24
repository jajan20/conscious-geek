## Table of contents

- [About the app](#about-the-app)
- [First design decision](#first-design-decision)
- [Second design decision](#second-design-decision)
- [Third design decision](#third-design-decision)
- [Other sources](#other-sources)

## About the app
CODE.LOVE was inspired by a lecture from Titus Wormer about Git and Github which he gave at the start of my minor. He shared with us, the story of how he met his girlfriend. Which was through the use of Github.

At the start of this year, I really dived into the world of HTML, CSS, javascript, frameworks and everything else that belongs with developers and programmers. I quickly found out that everyone is really passionate about the things they do, but also that there are no middle grounds when it comes to code conventions. 

As I started a group project I learned that something as simple as using a semicolon or not can already bring a huge discussion between people. Just a few quick examples that greatly depends on the preference of the developer.

Not using any spaces or semicolons
```js 
console.log('Hello World')
```
Using spaces and double quotes
```js
console.log ( "Hello World" )
```
Not using spaces, but single quotes and a semicolon
```js
console.log ('Hello World');
```
Everyone is so different and likes to write code in their own way. How cool would it be if you found someone that does it exactly the same way?

![Silicon Valley - Tabs vs Spaces argument](https://github.com/jajan20/conscious-geek/blob/master/media/tabs-spaces-screenshot.png?raw=true)
> https://www.youtube.com/watch?v=SsoOG6ZeyUI

## First design decision
In his talk about why privacy matters Alessandro Acquisti shows us that even though a lot of people blindly accept the fact that they need to share their personal information and don't really think about what the consequences are. They shouldn't give up their right to privacy that easily. The argument is that I've got nothing to hide. But not having anything to hide doesn't mean personal information can't be sensitive information.

One of the examples that really stood out was where he presented a two photo's of the same woman but slightly altered. One picture didn't have a baby, the other did. He asked us if we would give the same job opportunities after seeing one picture and the other. His answer, no. The experiment resulted in people being biased, either consciously or unconsciously. This shows that even though you've got nothing to hide, other people can still treat you differently.

This is where I believe my dating app is different. Instead of judging someone on the way they look. You get the chance to review someone else's code. Now what users will do is read the code and decide whether or not they like the code conventions their potential match used. 

After someone likes your code back and you've been matched up you get to see a profile picture of your match. I still think it's important to know who you're talking to, so I hope by giving the option for a profile picture after you've been checking out their code it will result in a more meaningful, lasting relationship (as a partner, as a friend or as a rival.)

Biases still happen, that's something that happens naturally. But by using programming language as a base to work with. I think people sharing the same interests are less likely to judge how someone looks. But instead can support each other by giving feedback on code snippets.

> Acquisti, A. (2013, June). Why privacy matters [Video file]. Retrieved June 1, 2018, from https://www.ted.com/talks/alessandro_acquisti_why_privacy_matters?language=nl

## Second design decision
Tristan Harris talks about how our smartphones are like small slot machines. Getting us addicted, every time you pull to refresh you're left hanging for more. With a couple of steps, I tried to make my app more user-friendly by focusing the core to a specific target group. Programmers in this case.

I wanted people with a passion or hobby to find each other and create a meaningful relationship without the app being intrusive. 

My initial idea was to make a dating app for programmers which focuses solely on finding a date. After some user tests with different people, I figured out that my app wasn't just for dates. People with the love for coding could find each other and create friendships, or relationships. This meant that the fundamental of the app changed. 

The reason why users would join my app wasn't to find the perfect partner. Which adds a lot of pressure on both sides. But to find someone that helps you. Shifting this idea showed that people felt less pressure while using my app and didn't feel the need "pull the lever" of their so-called slot machine. An added benefit was that some who liked the idea of the app so much and wanted to use it more frequently found people they could actually work with. So now, instead of being distracted by your dating app. It could help you find someone that adds value in a way that works with your project.

On the flip side, this project made me realize there are a lot of things I still lack and I made everything as good as I could. I know in the future I would like to add more functions that help you stay focused on a task and still makes it fun to use my app.

For example, it is possible to send a match a message. This is done through email, which means that once you send it there's no way of knowing what the other person is doing when receiving that message. I'm a programmer myself and I always get distracted by things popping up on my screen. After I saw Tristan Harris speak I became even more aware of how this affects other people. The most important function I want to add later down the road is a messaging system which you can set to do not disturb so that the other user knows you're working but can still message you what's on his or her mind.

> Harris, T. (2016, July 14). How better tech could protect us from distraction [Video file]. Retrieved June 3, 2018, from https://www.youtube.com/watch?v=D55ctBYF3AY&feature=youtu.be

## Third design decision
Third design decision comes from Nir Eyal who inspired me to be mindful of the app I'm developing. In his TED talk, he explains the Hook principle which ensures that people continue using your app because the users get "hooked" on your app. The hook principle has 4 stages which, if followed correctly can continue over and over again.

#### 1. Trigger
This can either be an external or internal trigger. An external trigger, for example, is activated by buttons with the text "click here" or "read now". An internal one is something that can be triggered by memory.

#### 2. Action
<pre>"This can be the simplest behavior anticipating a reward" - Nir Eyal.</pre>
While he explained what we could do about this. How we could stop or unintended behavior I thought that, although he had some good tips. Company's designing these apps should be responsible for creating this behavior.

#### 3. Reward
This is the actual reward, your message getting through. Someone replying to your WhatsApp. A new article in your news feed.

#### 4. Investment
By showing you things like "name" is typing, or small notifications icons on your home screen apps keep you invested.

During his talk Nir Eyal gives a couple of tips one of them was reading your Gmail through the web browser so it is harder to get to your mail which in turn keeps you from doing this too much. Again I think this is a good tip, but I believe there is a layer above this that we're missing. Ask yourself the question, why do I keep doing this action? Getting email is important and I'm sure this example doesn't fit everyone. But I think to make it harder for yourself to use an app because otherwise, you'd spend to much time on it is something a designer/developer should be thinking about.

In my app, I decided to not add any notifications outside of the app itself. Just as an experiment. Cause I know a lot of people like receiving their notification on their home screen. This way I want to give users back control of how and when they use my app. They won't be externally triggered to keep coming back. I want developers/programmers to find someone with whom they can share their passion for code with. And if one person succeeds while using my app then I think my app has been successful.

> Eyal, N. (2015, July 11). Un-Hooked: Increasing Focus in the Age of Distraction [Video file]. Retrieved June 3, 2018, from https://www.youtube.com/watch?v=1j2Wg3kwZIk&feature=youtu.be

## Other sources
- [Stefana Broadbent: How the internet enables intimacy](https://www.ted.com/talks/stefana_broadbent_how_the_internet_enables_intimacy?language=nl)
- [Sherry Turkle: Alone together?](https://www.ted.com/talks/sherry_turkle_alone_together?language=nl)
- [Alessandro Acquisti: Why privacy matters](https://www.ted.com/talks/alessandro_acquisti_why_privacy_matters?language=nl)
- [Nir Eyal: Un-Hooked - Increasing Focus in the Age of Distraction](https://www.youtube.com/watch?v=1j2Wg3kwZIk&feature=youtu.be)
- [Tristan Harris: How better tech could protect us from distraction](https://youtu.be/D55ctBYF3AY)
