# Transcript of interview with Jaiden Alemni, creator of Legends of Astravia

## Details

Interview took place on April 19, 2022. Interviewer is Jonas Rosland.

Full interview available at https://www.youtube.com/watch?v=tAnbwP7eHqk.

Transcription is provided by https://otter.ai. Edited by Jaiden Alemni.

## Transcript

Jonas Rosland  0:21  
Hello everyone and welcome to yet another Hit Save! indie interview. This is for the Indie Game Preservation Project that we do here at Hit Save!, where we talk to you fantastic indie developers about their marvelous games. 

So my name is Jonas Rosland. I'm here with Hit Save! and today I am joined by:

Jaiden Alemni  0:42  
Jaiden Alemni. Hello.

Jonas Rosland  0:44  
Hello, Jaiden. And you're with Studio Alemni?

Jaiden Alemni  0:48  
Yes, yes. Studio Alemni is currently just me. I am a solo developer. But I've got that official studio name, ready to present my projects under that name and hopefully expand someday into a actual game studio. 

That's like sort of the name I go by to, you know, keep things official.

Jonas Rosland  1:17  
That's awesome. So, you have your own studio, you're working on a solo project here called Legends of Astravia. Is that how you pronounce it?

Jaiden Alemni  1:28  
Yeah, yeah. "Ah-strah-vee-ah" is actually the right way to say it. I say "Ah-stray-vee-uh" a lot. But "Ah-strah-vee-ah" is kind of, I'd say, the canonical way to pronounce it because it kind of comes from "Astra", like "Astral"—like stars, you know?

Jonas Rosland  1:47  
I like it. I like it. I was playing the demo here a couple of weeks ago, and it was super fun. I had a blast playing through it. And I definitely want to see more. 

But before before we dive into the game, I want to dive into who you are a bit, Jaiden. So how did you get started with game development? How did you get here? How did you figure out "you know what, I want to start my own studio, and I want to do this." How did you get here?

Jaiden Alemni  2:19  
Well, it's perhaps a bit cliche. I've always wanted to be a game developer. When I was a kid, I liked more than just playing games. I distinctly remember playing... _The Legend of Zelda: Ocarina of Time_ was the big one. I remember playing through the games and being like, "This is so cool. How does this work?" I had this obsession with "how are these worlds made?", \[and the\] the mechanics involved.

When I was in high school, I actually got access to _RPG Maker_—an old version of _RPG Maker_—and Game Maker was another one. We had the home PC back in the 2000s hooked up by AOL internet. And I had the fortune of being able to sort of play around and I just, I was obsessed. I loved it. I loved trying to figure out how \[game engines\] worked. 

But then when it came time to go to college, I really wanted to go to game design school. And my parents weren't really into it. And a lot of people talked me out of it, because they're like, "well, everybody wants to be a game developer. And it's really hard industry to get into." And I was like, "Yeah, you know, I'll do something safe." 

So I went to school for art for a little while—I was gonna go into graphic design. And then I decided to go into IT, like, Information Yechnology, because I was pretty good with computers. So I got my Associate's Degree in IT. 

...And I just couldn't get the bug out of my brain. I just, game development kind of just kept coming up. I would on and off work on projects. Then 2017 rolls around \[and\] _RPG Maker_, one of the first engines I played around with, \[is\] having a contest called the Indie Game Making Competition. And I think it was for like, $5,000 towards your first indie game. And I was like, "oh my god, I'm gonna do it. I'm gonna try this." And I started actually making an alpha prototype of what would eventually become _Legends of Astravia_. And it was bad. The demo was not good, back then. 

But it was a good experience. People were interested in the story and I kind of just kept refining that idea. I started self teaching a little bit more, learning more theory about game design and more complex concepts. I taught myself how to program in Ruby, which is the language that _RPG Maker_ uses. And then this year I started, rather, I released the upgraded demo after all of these years of really solidifying the concept. And that's how it all happened. And now I'm going for the actual, like, game developer thing now.

Jonas Rosland  5:39  
That's amazing. So are you doing this full time right now, or...?

Jaiden Alemni  5:44  
It is only part time. I have a day job. It's hard, you know, because \[game development\]'s not really sustainable. So my goal is to finish up the first chapter of _Legends of Astravia_, have this complete game, and then once I've got something that's put together and seems like it has a lot of potential, then I might consider pitching to publishers and looking into things to actually turn it into the real deal. 

But for now, I have my my day job. Which, I like my day job, too. And it's always such a trade off, right? Because like, when you're comfortable, and you're making money doing your thing, but you want to do what you love, you got to kind of make that decision. So we'll see. But for now, yeah, it is. It is part time.

Jonas Rosland  6:39  
That's awesome. Yeah, I totally, I can totally relate, of course. I have a day job too, which allows me to do things like this. 

Jaiden Alemni 6:51  
Exactly.

Jonas Rosland 6:52  
Which I'm really grateful for. So, programming in Ruby, is that something that you do within your day job as well?

Jaiden Alemni  6:57  
I don't do... Well, actually, there's a little bit because I work in web. So there is like a little bit of Ruby, but for the most part, no, actually, I don't. I use JavaScript and whatnot in my day job. And it's kind of funny, because the the newest—I use an older version of _RPG Maker_—and the newest engines use JavaScript. And I don't like it! (Laughs) I'd rather use Ruby. 

So it's kind of funny, because I could probably use the new one and be able to use JavaScript because I use it for my job. But I like Ruby too much. I'm kind of stubborn about it. It's such a cool programming language, and I enjoy making the systems in it. So yeah. I feel like the last Ruby programmer standing.

Jonas Rosland  7:52  
There are still a lot of them out there. 

Jaiden Alemni 7:53  
There are, yeah. 

Jonas Rosland 7:55  
So for _RPG Maker_. So you're doing it in Ruby right now, the new _RPG Maker_ is JavaScript—is it possible at all to port it over to the new one? Or would you have to remake everything?

Jaiden Alemni  8:07  
Yeah, it would be possible. I would have to rewrite all of my scripts and stuff. And the thought of rewriting my beautiful Ruby code in JavaScript makes me like... I don't want to do it. (Laughs) 

So yeah, I don't know, I was able to find—and maybe this is a little technical—but the old engine that I use, I use _RPG Maker XP_, which came out in like 2007, very long time ago. And it's sort of long since abandoned. It was made for old versions of Windows, and it actually ran very poorly as is. And there was this project called _MKXP_, which was originally made to port old _RPG Maker XP_ games to Linux. And one of the games that most people will probably be familiar with is _To The Moon_, which was like a very successful indie game, and it was made in _RPG Maker XP_. And they use this _MKXP_ engine to not only port it to Linux, but it made the game run a lot better. 

So I was able to use that same technology for _Legends of Astravia_. So it feels like the new _RPG Maker_ engine anyway. So people tend to be a little surprised when I tell them that I made it in _RPG Maker XP_, they're like, "How is it... I thought it was the new one! It looks like the new engines." and I'm like, "Well, this technology allows me to do it." I'm very grateful. 

I'm able to port it to macOS as well. Which is something that wasn't possible with the old version of the engine.

Jonas Rosland  9:58  
Yeah, I was looking at that and yeah, I was a little surprised that it's being made in an engine that's what, 15 years old now?

Jaiden Alemni  10:07  
Haha, yeah, XP is... it's quite old. I'm surprised the engine—the editor itself—still opens on my computer. But it's... there's just something very endearing about it. 

The like, the old fashioned sort of tiling system it has \[makes it\] a really good map making system, which is kind of why I was drawn to it over the newer makers. Because when I started on _Legends of Astravia_ the way the map making system worked in the newer ones, I didn't really like it. They've since updated it now. And I'm a little torn. But yeah, it... I don't know, there's something about it. But like, it's kind of it's like...

Jonas Rosland  10:55  
As I was playing, as I said, it definitely didn't feel like a 15-year-old engine. I definitely thought you were using a newer engine for this. So yeah, it's fantastic. What the old engine and this "MKXP" was it?

Jaiden Alemni  11:11  
Yeah, _MKXP_ is the is the name of the project that sort of made it, it's an open source project, it's perfectly okay to use by _RPG Maker_'s terms. It allows a lot more flexibility with the engine that wasn't there in that old 15-year-old version. So there's a lot of manual work to do on the side to make it work. But in my opinion, it's worth it because it let me do all of the things that I wanted to do with it. I was starting to get really bottlenecked by that in the old version of the maker, that alpha version, which well, I'm sure we'll get to a little bit later.

Jonas Rosland  11:50  
Yeah, well, we'll dive into that. So tell us a bit more about the game itself. Who are the people that we see here? Or at least some of the main characters that we see here?

Jaiden Alemni 12:02  
Yes. So in this key art, we see Oliver at the front here, which he's the main character of the game, and who the player plays as. And we don't know a whole lot about Oliver. He has amnesia, which...

Jonas Rosland 12:30  
I love that trope.

Jaiden Alemni 12:31
I think it's very funny, because some people are like, "Ugh. Amnesia trope." And some people are like, "Yes! Amnesia trope!". So I like it. It's very true to that sort of classic nostalgic, like we're getting into it with the Japanese style RPG, we're are going _Final Fantasy IV_, we're just like, you know, we get to learn more about the character as he grows and learns more about himself. And I really like that. 

So we play as Oliver, he doesn't really know a whole lot about himself except that he's rather good at using magic. And he doesn't know where he learned magic. But he wants to find that out. And he's found in the forest. At first by the woman to the right of him in this picture, which we don't know who she is, we don't know what her motives are. But she's-

Jonas Rosland 13:22  
She's mysterious.

Jaiden Alemni 13:23  
She's a bit mysterious, and she's there. And she sort of leaves him behind to be found by Azel, who is in the back. And Azel is a _mystician_, which is what we call the magic users in the world of Astravia. 

And Azel finds Oliver. And he has kind of not a lot of patience for Oliver's amnesia and his questions. He seems a bit worried about what's going on and panicky and trying to get to the temple that's in the forest that they're in. So he lets Oliver-

Jonas Rosland 13:59  
He's on a mission already.

Jaiden Alemni 14:00  
He's already on a mission! Yeah, he runs into Oliver he finds Oliver and Oliver is like, "Can I go with you? Like I don't know what I'm doing. I don't know why I'm here. Like, can I follow you?" And he's like, "Alright! Fine. I'll let you follow me. But we have to go, we need to figure out what's going on here." 

And we find out that he has a bit of a reason for being so like, short with Oliver. And that's because in the area that they're in, there are knights—which next to Oliver in this key art is in fact a knight. And Azel warns Oliver about the knights because the knights hunt mysticians, the knights don't like mysticians. And there's sort of a tension going on in Astravia—we don't really know fully why. But some people are afraid of magic users and they want to stay away from them. 

And we get kind of two different sides of this story because we get the magic users afraid of the knights and Azel warns Oliver about you know the knights hunting and killing mysticians, but then we hear about people who are afraid of mysticians, too. So it becomes sort of a like, "Who do we believe? What side of the story is the true one?" And that's kind of part of the whole plot, Oliver finds himself on both sides of the story learning about it and the history of Astravia, which is a bit muddied. It's... there's a lot of sort of dark stuff that has gone on that Oliver doesn't know about because he, you know, lost his memory.

Jonas Rosland  15:40  
Yeah. And as I was playing through the demo, I think it was Azel talking about stuff that happened, but most people have already forgotten it. So yeah, definitely, history seems a bit muddied. And I definitely want to want to see more.

Jaiden Alemni  16:01   
There's a lot to tell. I'm excited to share more.

Jonas Rosland  16:08  
Awesome. So what we see here is a fighting scene. And I was very amazed by the artwork and the thought going into the fighting mechanics here. I thought this was really, really cool. 

It's time based, but also you need to, it's not instant, but you can make things that speed up your attacks. And it had a lot of depth that I was not expecting when I started playing here. I was like, "Oh, I need to pay attention" pretty much immediately. Even with the basic enemies, I needed to pay attention. 

So can you tell us a bit more about the the game mechanics here, and the fighting mechanics?

Jaiden Alemni  16:51  
Yes. So the battle system, it takes a bit of influence from \[something\] some folks might be familiar with—the "Active Time Battle" system, which was in the old _Final Fantasy_ games and _Chrono Trigger_, where you wait for a bar to fill up, and then your character gets their turn. And if you took too long other enemies could attack you. 

This idea was further refined in a PlayStation RPG called Grandia. And it showed that bar. And I thought that bar was super cool—where you see each character in relation to each other as they're moving in time, and you can plan your actions around that. 

But you still had to wait. You had to wait till your character got to the end of the bar, then you would choose your action. And then they would move on the bar \[again\]. And it was kind of like this race to get your turn in first. And I wanted to expand on that. 

And I was like, "Well, what if you can just pick your action right away? Like, what if you don't have to wait, what if it's completely fluid?" So I, you know, refined that system so you can choose your action right away. And the quicker you choose your action, you kind of get an advantage. But you still have enough time to sort of decide and  be a little strategic with it. 

And that system was really cool. And then I had some help from some colleagues, and I had a colleague suggest to me to let you speed up or slow down battle. And that you can use the trigger buttons on your controller to speed up battle. So if you've picked your actions, you don't have to wait, you can just fast forward to the end and get your action in and start it over again. But if you need a little more time to think you can slow things down. 

So it's kind of a weird hybrid between a turn-based system and a completely active system. And then I had that going on, and it was going really well. And then in the demo, I had somebody—I had a lot of feedback in the demo where folks when they went into the menus to pick skills, they were getting frustrated because the system was always active, they would get interrupted while they were picking items from a list. 

So I further refined it with another colleague's suggestion to slow time down a lot when you're in a list. Very similar to _Final Fantasy VII Remake_ \[which\] did a similar thing. So time almost slows down to a stop, but not quite. It's still pressuring you a little bit, but you have time to think and then keep things going. 

It's very fluid. It makes you like, I don't know, it's pretty exciting to play cuz you're always doing something—you don't have to sit and wait. You don't have to, you know, button mash, either. Like there's this nice balance, I think, between the two systems.

Jonas Rosland  20:06  
Yeah, I definitely thought the combat there was very fluid. There was no, as you said, it wasn't really a waiting game and there was always something that you could do. You could also pause to make sure that you were ready to block when the enemies attack and everything like that. 

It has a lot of depth. And I had a lot of fun just figuring out what I should do \[and\] when, because some enemies are of course faster than others. Some enemies hit harder than others. And yeah, it was a lot of fun to figure out.

And the constant time—the constant passing of time, that's the word I was looking for The constant passing of time, even when you're choosing things, it kind of reminded me of the the Fallout VATS system as well. 

Jaiden Alemni 21:06  
Yeah, yeah!

Jonas Rosland 21:07  
Now I'm focused on something. But your enemies still move. And you still have to actually make a decision. We haven't paused the game, we've just slowed it down enough so you can make a calculated choice. 

And I really like that. I really like it. So yeah, I had a lot of fun. I searched out all the enemies that I could find. I battled every enemy that I could find, because I had a blast playing through this. So this was super, super fun.

Jaiden Alemni  21:34  
I'm glad, yeah, that was a funny thing I had noticed with people who were playing it. I put the enemies on the map screen, I made it so that you can avoid enemies. Because that's something that I didn't like about old games, \[that\] the random encounters sort of just interrupt you while you're playing. But I found that even though I made battles optional, most people enjoyed the battles so much that they were seeking out enemies to fight like, I wasn't anticipating that. So I was like, "Oh, cool."

Jonas Rosland  22:10  
Yeah, it was just really, really fun. So yeah, I absolutely do not enjoy random encounters either. It's a thing of a bygone era, I think. But giving the player the choice of actively seeking out enemies and putting them on the map, as you said there, I think it's brilliant.

Jaiden Alemni  22:36  
Thank you.

Jonas Rosland  22:37  
So this is the beginning of the game here. This is where you start out, and this is where you're found. The intro, we're not going to show the pictures of the intro the paper cut intro. 

Jaiden Alemni  22:56  
Yes, yes.

Jonas Rosland  23:57
But I really, really liked that I highly recommend anyone that's interested in this go play the demo. The intro is just fantastic. It's a really cool demo—a really cool intro.

Jaiden Alemni  23:13  
Thank you. Yeah, I had done it all sort of manually, like the paper cut drawings, and then moved them individually to get that sort of... It was very inspired by _The Legend of Zelda: The Wind Waker_, like that beginning opening scene where you see the paper graphics. I just like that style of storytelling, because it brings you back to that era of really long ago. And it really sets the tone. 

It was a lot of fun to do, too. I had a lot of fun making that scene. And I hope to make a couple more throughout the game and make use of that system. Because it's cool. It's really cool to do.

Jonas Rosland  24:03  
Yeah, it was super, super cool to see. Again, I was not expecting that from an early demo like this. So it was really cool to see. One thing that I really-

Jaiden Alemni  24:15  
I think there's a screenshot? In the press kit actually, of it. If you wanted to showcase it a little bit.

Jonas Rosland  24:24  
This one?

Jaiden Alemni  24:27  
Yeah. So that's a good like, example of what like the what it looks like.

Jonas Rosland  24:43  
The world itself is very colorful. You have very bright colors. Very bright and it's easy to see where you should go. And items that are important. Was that a choice that you made? You wanted more colors in the world? Because a lot of games are very bleak otherwise. Especially when we look at ruins, because we have a lot of ruins here, but it's very colorful.

Jaiden Alemni  25:08  
Yeah, that was a conscious decision. And it actually, especially with the opening area. It's a swamp, and people often associate swamps with this darkness and this bleakness. And I actually wanted it to be colorful and sort of have this whimsical, positive element to it. 

The spritework for the tiles, like the maps, are actually, some of them are, default assets from _RPG Maker XP_, and the originals were a lot more desaturated. I actually colorized them more and made the colors pop more, because I liked that. That's something I really like about older games, especially like on the Nintendo 64 and stuff. Some of them were almost comically colorful, and I miss that. I like that sort of just really, really saturated look on things. 

_Golden Sun_ is obviously another big inspiration for the game. And that was another, rather, that was the thing that they did in the game. Everything was just super colorful. It's clear to see where you can go, all of the characters pop out and are distinct. I'm a big fan of that. Yeah.

Jonas Rosland  26:33  
Yeah, it was really cool. And there's also, when you start the game, you had a kind of a new type of control scheme, as well.

Jaiden Alemni  26:47  
Yes, yes. And it trips some folks up a little bit.

Jonas Rosland  26:53  
Yeah it did for me for the first few minutes before I got used to it.

Jaiden Alemni  27:00 
Yeah, I actually had added a prompt to the demo after getting some feedback from some players. Because I was a little adamant on on having that new control style be the default one because I felt like it worked really well with that like, fast paced battle system. But I still like to give people options, especially for accessibility reasons. And let people change the key bindings and stuff if they want.

But I actually directly referenced _Super Mario RPG_, because I noticed it had that same system where you can quickly switch between actions just by pressing the face buttons on the controller. And that's kind of why I had designed it that way. 

So like if you're actively attacking an enemy, and an enemy does something because it's real time and you're like, "Oh, no, I don't want to attack them. Now I want to defend or I want to use an item or I want to switch to a skill," it's one button press instead of two. And that doesn't seem like a lot, but when you're in it and you're like doing it. It's like, suddenly you're like, "Whoa, this is so much faster". 

But I saw some folks get tripped up by it too. Some people still prefer the other control scheme even after getting used to it. And that's a-okay, too. But yeah, I wanted to try something new and interesting to go with the new and interesting system, I suppose.

Jonas Rosland  28:30  
Yeah, no, I definitely liked it. And once I got used to it after the first few battles, like this makes sense. So I'm definitely on the train for the new control scheme. I really like it. It works really well. It tripped me up a few times throughout the demo as well. But I understand it and I like it and it's yeah, it's very... Again, I'm going to use the word "fluid" because it's easy to understand.

One of the enemies and we see this here on the screen, one of the enemies that I hate in the game, are the bees. I went in thinking "Oh it's just bees", but they kicked my ass for a bit! I was not expecting this.

Jaiden Alemni 29:28  
They're very fast!

Jonas Rosland 29:29  
Yeah, they're very very fast.

Jaiden Alemni  29:31  
They're very fast and they have poison and everybody loves poison mechanics in RPGs. I know it's everybody's favorite so I had to put it in, you know?

Jonas Rosland  29:37  
The best. Yeah, sure. No, it's the best. Yeah, I think I died the first time I encountered them like, "Oh yeah? Okay". But having multiple saves definitely helped. Yeah, those bees those bees definitely got the best of me there for a bit.

Jaiden Alemni  29:59  
They were worse than the alpha build of the game. They were even scarier in early versions of the game. Those are actually toned down in the demo, which means I should have like a bee final boss at the rate I'm going. Because they seem to be very intimidating.

Jonas Rosland  30:21  
I love it. So the characters here, I want to dive into the characters a bit more. So let's let's dive into them. So we got the different characters here. Let me see. 

I'm gonna start with Oliver. So this is Oliver, you already talked about him a bit, but the main character?

Jaiden Alemni  30:48  
Yes, yeah. So this is the main character of the game. I actually did do this artwork, it was kind of like an experimental thing, it came out pretty good. But the thing in his design here that you'll see is he has the sword in one hand, he has a magic and the other hand and that's like a really key part of his character throughout the game.  He's sort of like the bridge between, you know, the Knights of the world and the mysticians of the world. Because he, he kind of gets a side of both stories. 

And also, because he's the main character, and you can't really swap him out in battle—you'll get new characters throughout the game that you can use in battle, but I don't think I'm going to make it so that you can take Oliver out of battle. So I wanted to have him be kind of well rounded, like you can get some physical affinity out of him and you can get some magic affinity out of him. 

So you have this sort of this spellsword motif going on with his design. Which I have, you can see here, in the key art. And his clothes are otherwise simple. I wanted something kind of not too complex, in contrast with Azel, which we'll get to later. (Laughs) But yeah,

Jonas Rosland  32:14  
Yeah, let's dive into Azel a bit.

Jaiden Alemni  32:17  
His design's a little more complex. (Laughs) The very classic, I'm gonna say wizard, I know they're not—they're mysticians in this world—but sort of the adorned robes show his like "class" you know. He's obviously a powerful magic user, he comes from a place that is not nearby, it sort of shows this like fanciness to his character. And yeah, he was he was a fun design to come up with. With all of like, the different robes and the contrasting colors and stuff. 

And you'll see the jewelry, the gold jewelry is actually like a thing among mysticians, and I have a little bit on each character that is a magic user. And then of course, the blue hair is something that we see across the magic users too. So there is actually a lore reason for that.

Jonas Rosland  33:21  
Yeah, and I also believe, I also see black fingernails?

Jaiden Alemni  33:26  
Yes. That was...it's funny, I was working on—I think it was this art piece—because the artist that helped me with this or that I had commissioned for this, they also helped me with the key art, which I know we'll go over later. 

But basically, I gave \[the artist\] a sketch, \[and\] they sent me some the beautiful linework of the character, and then I colored the linework in after the fact. And yeah, when I was going through coloring, I was like, "You know what," I'm like, "We're gonna paint his fingernails" like there's something about it, "We're gonna give him black fingernails." It was just an in-the-moment thing and like, I love it. And you don't notice it, really, unless you're like paying attention. And if you do you're like, "Cool, distinguished gentleman \[that\] paints his nails on Sundays."

Jonas Rosland  34:17  
I like it. We have a few other characters here as well. So let's check out some of the character profiles.

Jaiden Alemni  34:30  
Yes, so this is Minerva. I actually just revealed her on Twitter the other day, which we'll learn more about her later on. 

Oh, now we're on Oliver. So yeah, this is the key art for Oliver. 

This is Sarina who is on that that main key art. She's a knight who Oliver is going to meet. 

This is Arlyn who we haven't really heard much about yet, but he's also a knight you can see a bit more... decorated. But we'll learn more about him later on in the game. 

And this is obviously Azel's profile art. 

This is Baldric who was featured in the original alpha demo. He was actually... There's something a little interesting about him—he was in the role of Azel. Like he was what Azel currently is in the demo. He was in that role in the alpha version. 

So Oliver in the alpha version, which we'll we'll kind of talk about later, but he wakes up in town and Baldric actually goes with him to the dungeon. I reworked the story a little bit and so we get Baldric a little bit later and his story arc has changed a little bit, but you see, he also has the knight motif, but it's a little bit different for him. 

So we get to learn a little bit more about him as the game goes on, and his association with the knights. All of the knights have that sort of sweater like turtleneck type thing going on. And his is a little bit more worn with age so we can tell he's got somewhat of a past there.

Jonas Rosland  36:21  
Very cool. Very cool. So all these characters, of course, these are the profiles for them. 

Jaiden Alemni 36:34  
Yes.

Jonas Rosland 36:35  
But then you for the game. You created some fantastic character sprites as well.

Jaiden Alemni  36:39  
Yes, well, the character sprites are a paid commission. The artists name is Burt. He did an incredible job. Like, I still look at the sprites and I'm like, kind of floored by how fantastic they look. And how they really, like, every design aspect, important design aspect of the characters is captured in the sprite. 

Which is incredible to me, because the sprites are small, you don't really have a lot of room to work. But all of these really key aspects are visible and make them look really distinct in that battle scene. So it's just great to see them come to life, so to speak, in that way.

Jonas Rosland  37:27  
Yeah, I think the sprite work here is just stellar. It looks so darn good.

Jaiden Alemni  37:35  
It does. It's very good.

Jonas Rosland  37:37  
It's just fantastic sprite artwork here. So yeah, that's fantastic. 

Jaiden Alemni 37:38  
Thank you, thank you.

Jonas Rosland  37:40  
And this one, the big tree, what do you what did you call it?

Jaiden Alemni  37:48  
So "Soulich" was the the name for it, and I actually don't remember how I came up with the name. Like, I know that it's "Sou" and then "Lich" like the monster. I forgot where I got "Sou" from but yeah, it's like this big tree monster basically, that you encounter in the first dungeon. Which has this... It's Earth themed, but throughout the dungeon, you sort of see the vegetation, and you see the rocks like intertwined with the vegetation. So with this boss, when I came up with a design, I wanted that same motif in its design. And so this is what I came up with. And then of course the sprite artist executed it. Amazing. Like, it looks so great. And it looks super cool in game. And it swings down is giant rock hammer fist. It's really neat.

Jonas Rosland  38:52  
Yeah, it's fantastic. I think we want to move into the key art process that we've alluded to a few times here, because this is really, really cool, I think. So I'll start with the first picture that you sent over here.

Jaiden Alemni  39:10  
This was a lot of a lot of fun to do, too. 

So this was my sketch of the key art. I had talked to the artist, her name is Ryuuen. They're very good at what they do. I sent them—I came up with a sketch, you know, and kind of got like the idea. I actually spent quite a lot of time thinking about sort of the composition of how all of the characters were going to fit and where the logo was gonna go before I gave it to them. 

So this was the sketch that I had, you know, completed for them. And I was like, "Feel free to make changes," \[and\] she was like, "Is it okay if I make a few changes?" And I'm like, "Of course, yeah, like whatever works." And then she sends me back a sketch and I was like, "Oh my god, this is amazing!" Like, I couldn't believe it. It was so professional, it looks so cool. Really brought the characters to life. And captured, like, the essence of kind of what I'm going for with the game. 

And yeah, so I gave them the okay on the sketch. And then they sent me back, well, this was like, I placed the logo a little bit and sort of arranged it to see how the composition would look. And it was good. And then of course, they sent back this gorgeous lineart, which was the commission that I had commissioned them to do. 

So they sent me back this lovely lineart, and then I started coloring it. And I have a background in graphic arts, but it took, oh, it took me some time. I think it took me about an entire month to get through this thing and really make it something that I was happy with. 

And it was just kind of layering and playing with different lighting. You'll actually see this first example, the background is dark and the foreground was light. And I was like, "That looks really weird." So as I reworked it, I sort of reversed that. So the characters in the foreground are darker and the characters in the background are lighter, and that like really pulled it together. And it was just adding layer after layer and just changing the colors around and stuff. Until I could make it what it is. Yeah. 

So there was a couple more. This was like another pass with the shadows. This was the pre-final pass, all of the colors were done, and then I move the sliders around, yeah, and evened it out and made it look more cinematic, I guess. And yeah, so that was the process. A lot of fun. A lot of work.

Jonas Rosland  42:15  
I bet, but it looks amazing. 

Jaiden Alemni 42:20  
Thank you.

Jonas Rosland 42:21  
I think, yeah, it looks fantastic. And it's really cool to see it from the original art that you sent over the like, "Hey, here's what I think," and then seeing this here.

Jaiden Alemni  42:33  
Yeah it's very, very cool to see it imagined the way I was picturing it in my head. Because that's a very frustrating process, right? Like, we get this image in our head, and then we sort of make a sketch. And it's not quite what we were imagining in our head. \[But\] then going through this process I was able to make it happen, and it's... I'm super glad.

Jonas Rosland  42:58  
Yeah. Yeah, I think it's super. It's beautiful. You did a fantastic job, coloring and shading and everything here. It looks absolutely amazing. 

Jaiden Alemni  43:14  
Thank you. 

Jonas Rosland  43:15  
Really, really cool. So I want to dive into the alpha a bit so people can see like, we've already shown what the game looks like right now, people can try the demo as well. 

But I want to show people what the alpha look like. And then I want to dive a little deeper into your dungeons and how they're created. But let's start with the alphas here.

Jaiden Alemni  43:46  
This is so nostalgic. Yeah, so, this was when I started in. This was, I think the screenshots from 2018. So this was even after refining this sort of 2017 demo that I had for that contest. But yeah, it was in this locked resolution. This was sort of more true to the default _RPG Maker_ design. You can see some of the core ideas are here. Oh my gosh, that old Oliver design is so funny. (Laughs)

It was, yeah. Oh my goodness, it's really come a long way. This is the "Essence" system, which I actually changed a bit, after thinking about the system and how it worked. It changed through to the new demo, which I know we'll get into sort of the mechanics later but yeah, and then of course that battle system. It's changed so much you can barely see that time bar at the bottom. 

So yeah, it's been a long time of refining it.

Jonas Rosland  45:00  
I think it's wonderful to see the how far it's come. So seeing the alpha here and then playing the demo as well. And contrasting the the two. You can definitely see how far it's come.

Jaiden Alemni  45:13  
Yeah, it certainly has. The old alpha was also like, the movement was gridlocked. So you only moved like one tile at a time. And one of the big changes I made that took me a really long time to do with the new demo was that sort of "gridless" movement. That like smooth, all eight directions, free movement. 

And it makes such a world of difference. If I ever go back to the alpha just to, like, every now and again, I'll go back just to remind myself how far I've come. And it's like, "Oh, my goodness, this is so uncomfortable. How did it work like this for so long?" Because it feels so good to move freely without that restriction. So yeah.

Jonas Rosland  45:59  
Yeah, this is awesome. So within the game, of course, we got multiple different venues, so to speak, we got dungeons, we got overworlds, we have a castle or a ruin.

How do you build these out? And how do you think about \[it\]? What do you think about when you're building these out?

Jaiden Alemni  46:19  
So um, I have sort of a process. So what I'll do is I'll usually, kind of, I'll do a document first, I'll actually type out what my plans are for an area, \[and\] I'll summarize what the area is about, like the purpose it serves for the game, the key aspects of the area, and then the mechanics of that area. And I do this for all of the areas in the game, not just the dungeons. 

So like, when the player starts the game, in the like the demo in particular, they go through this area, Mordin Forest and Mordin Swamp. And in my mind, it's still kind of the dungeon. And even the towns are still kind of a dungeon, right, they all sort of serve this purpose, and you have a path that you want the player to go through.

So I start on paper first, and then I'll open up the editor--sometimes before I even do something like this image we have on screen--and I'll kind of rough out some map tiles to get the spacing and stuff. And then I'll do something like this picture, at least specifically for dungeons, where I plan out the structure and the path. So I have a good idea of what I'm getting into, so I don't get lost in it as I'm designing. Because it's very easy to sort of start designing and then get lost in the details and not have this big picture on top. 

And I got a lot of these sort of ideas from studying like, how _The Legend of Zelda_ did their dungeons. There's this series on YouTube called "Boss Keys" that's really good that talks about it, \[and\] I had a colleague who actually like went to school for game design, and he's very good at level design. And he gave me some pointers on  this kind of level design as well. 

And I've also really liked level design. When I originally wanted to go to school for game design, I wanted that to be my specialty. I just like the sort of environment that the player has to traverse the most. Like, it's the most important part of the game. 

So yeah, so I make something like this that's very primitive just give me this idea of where they're going to progress and how they're going to get to the goal of the dungeon, which in this case, we've got the beautiful skull that I drew and MS Paint for the boss. (Laughs)

And then once that's done, I do the actual map in game. This is a screenshot of the whole map in game--there's actually a couple rooms missing from this. So I map it all out in game first, and then I actually took this giant screenshot, and I threw it in Photoshop, and I dimmed it and then I put these icons here and I sort of plan out where I was going to place enemies and the items and stuff the player gets. 

Which is funny because you look at something like this and it reminds me of the old gaming magazines back in the day that would tell you where to find secrets and stuff. It's kind of like the same idea. And I found it's really useful for designing as well.

Jonas Rosland  49:54  
So are you going to sell a guidebook for the game?

Jaiden Alemni  49:58  
I would love to, I mean, there's one that's already for free that goes with the demo, but it's not fancy or anything. I'd love to do the classic game manual, like the old games. \[That\] would be so cool.

So yeah, this is this is kind of what my process looks like, you actually can see to on this screenshot all of the colored tiles that are used, like in debug mode, for all of those spots that you jump on. That's kind of like a little side thing. Because I have to place all of those in the the map editor first, and then they're not visible in the game, because well, yeah. Obvious reasons. 

Jonas Rosland 50:02  
Yeah.

Jaiden Alemni  50:05   
And then this is the full layout of the demo, actually spoiling a little bit of a later area--the bottom half of the map is not in the game yet. But yeah, you see this sort of Mordin Forest starting area that the player progresses through, and I wanted it to just be a straight shot, to kind of just give you an idea of like, \[to\] pace you into the more twisty paths of the swamp area. So relatively simple, straight path, though, because it's the introduction.I just wanted it to be really simple and gentle introduction to the world and its mechanics. 

And then of course, I think later areas, I'm looking forward to doing more complicated designs. You can see the bottom map is kind of more of an example, it's like almost a maze.

Jonas Rosland  51:53  
Almost looks a little like a dragon down to the left.

Jaiden Alemni  51:57  
Yeah, a little bit a little bit. It's got those like, yeah, the twists and turns.

Jonas Rosland  52:05  
Yeah, I think it looks really cool \[and\] plays really well. I like the straight shot, as you said, just to get you used to the game. But while it looks like on the over overhead map here, it looks like a straight shot, and then up to the temple. But there's a lot of nooks and crannies, where you can find things and find enemies and find extra items and things like that. So it's definitely worth exploring that initial map to its full extent. 

Jaiden Alemni  52:42  
Yeah, there's a lot of goodies. There's a lot of goodies in both this map, and in the dungeon. There's a secret in the dungeon that not everybody has found, like there's a secret room in there. So it's fun. I love making secrets, like that's my favorite part of level design; things that the player is like, "Is this... Is this something?" and then they check it out and it is and they're like, "Whoa! This is cool."

Jonas Rosland  53:10  
Now I need to try it again.

Jaiden Alemni  53:17  
(Laughs) The secret room, yes.

Jonas Rosland  53:18  
Yeah, I definitely want to find those things. That's awesome. 

So I want to dig into the game a bit again, here. You said earlier, you're looking at releasing the first complete chapter later this year. 

Jaiden Alemni 53:29  
Yes.

Jaiden Alemni 53:30  
So how do you envision the chapters working? And how many chapters are you thinking?

Jaiden Alemni  53:47  
So there are going to be exactly three chapters. The chapters kind of came--like, I have had the full game in mind, and it's just too big for one person. It's just that this thing is such a behemoth of a project. 

And I was like, well, I had a couple different options. I could have gone the route of trying to get the whole thing done all at once, but it would take me a really long time to do it and I would have to seek funding. And I was like, or I can just split it into the three parts, you know, finish the first chapter, get an idea for what my production and release process is like. And then the second and third chapter.

It's almost like splitting it into three smaller games instead of doing this one giant project. But the story is planned in such a way that like the three chapters actually make a lot of sense. I want them to feel very complete. So like, you play the first chapter, it's still going to be--I'm ballparking--about 10 hours, maybe more right now,  for the first chapter. So it's going to be a sizable game still on its own. And you have this sort of complete story. But obviously, you want to know more, \[and\] there's more that's gonna happen. 

And then the second and third chapter will be kind of similar in length, the same idea. And, yeah, they all kind of work together with each other. I wanted it to be something that is like, everything works together. It's not like, "Oh, I'm just making up chapters as I go." Like, it's all planned out, basically. I'm just splitting it to make the production and work a lot easier for me. And \[to\] just \[make it\] a better experience, I think, for people who want to play the game too. Like there are people who have been waiting since 2018, since I started this thing. So I was like, "I gotta give them something," you know?

Jonas Rosland  56:01  
I think a 10 hour chapter is nice as well. Especially when you compare with these silly large RPGs that take over 100 hours to complete and you're like, "I don't know where I am. I'm 70 hours in, am I even at the halfway point?"

Jaiden Alemni  56:20  
Yeah, that was another sort of factor, I think, too. I love Japanese RPGs. I love RPGs in general, but like, I feel like nowadays, they're just all so big. And they're so long, and a lot of us don't have the time. So I like the idea of like, giving it in these sort of sizable chunks. So you play it and you're like, "Oh, that was a good experience. And that was like manageable, and I could finish it." And then when Chapter 2 comes out, you know, you can either replay Chapter 1 or you get a nice reminder of what happened and you can just continue on. 

I want it to be a really seamless experience. When I do come out with it. Like, your saves are going to carry across.

I'm left thinking about _Golden Sun_, like _Golden Sun_ kind of did the same thing. Right, like you had the first game on the GameBoy, and then you had the second game on the GameBoy. And they just cut off! The first game just cut off and and it was like a super crazy cliffhanger! You're like, "Oh, no!" But you had to type in a code to transfer your save over to the second game. So I was like, "if they can do it, I can do it too!"

Jonas Rosland  57:33  
Yeah, like that. I think that's smart. And yeah, a total of 30 to 40 hours, or something like that. That's way more manageable. 

I'm a full time worker. And then full time dad. Yes, I do this nonprofit on the side, and I also want to play games. Making time for a game that's 100 plus hours is very, very hard. 30 to 40 hours I can manage. So definitely looking forward to those three chapters to come out. 

So when do you—I know in the demo, and release dates are always floating, of course—but in the demo, when you within the demo, you mentioned that Chapter 1 of 3 is due to release late this year. Is that still the plan?

Jaiden Alemni  58:29  
That is the plan, I really want to get it out by the end of this year. You know, I've just been dying to release this thing, especially given when I had worked on the alpha, you know, I basically dropped everything to rework the game at its core. 

So now that I've got this good foundation, I want to move forward with everything. So I'm really shooting for the end of this year. 

I mean, I'm a part time developer, life happens, you know. I keep it very loose. I have regular developers logs every month where I sort of let people know what my progress is and if I'm still on track But I'm not gonna officially announce a date or anything like that until I'm certain. 

It also depends on like, what other games and stuff are coming out. I know _Breath of the Wild 2_ is due to come out and if _Breath of the Wild 2_ comes out \[around\] the same time that I'm planning on releasing Chapter 1, like I'm gonna wait a little bit! Because I'm gonna get drowned out by those kinds of things.

So, it all kind of depends on on how my process goes. How, you know, when I sit down and actually start making maps and stuff. It will go a lot faster I think than the past couple of years, which is just raw programming and planning.

\[I'm\] seeing how that goes, and really, I'm hoping--I would love to get Chapter 1 out by the end of this year. And then the goal would be like, maybe a chapter a year? But, you know, I gotta give myself a little time. 

The other reason why I wanted to do the chapters method is because it also gives me a little time to like, rest and recover before doing it, you know, as opposed to doing this like massive game release, and spending all this time and burning myself out. So give myself a little bit of time to like, relax, see how the release goes. And then, you know, come out with the next chapter. And then the chapter after that.

Jonas Rosland  1:00:41  
You mentioned earlier that _MKXP_ makes it easier to pour to other systems as well, or other operating systems like Mac and Linux. 

Does that also mean that you can port the game to say \[Nintendo\] Switch or something like that? Or how does that work?

Jaiden Alemni  1:00:59  
Unfortunately not. And it's because _MKXP_ is open source, which doesn't play nice with other--the licensing is a little bit gray, and doesn't play nice with consoles. 

So I'm definitely not guaranteeing a console port. I know, everybody wants to put the game--like I want to put the game on the \[Nintendo\] Switch so bad. 

But I don't want to guarantee it unless I'm sure I know. Even the other folks that had used _MKXP_, I think they had had the whole game moved over to like Unity in order to port it to the \[Nintendo\] Switch because it's just, it's this whole thing. 

So at the moment, no. The framework isn't there. So it would be something that I think I'd consider after all three chapters are out. Because then it's like, then I can just put it all together, you know, and then have that on consoles as  one thing. As opposed to each individual chapter, I think, on a console, would not work out very well. So I have to admit, I have to manage my expectations a little bit here. 

So unfortunately not. I can't guarantee any consoles. But if it does well, you know, if people like support the game and stuff, you know, it could certainly happen in the future. I want it to happen in the future. I'd love to see it on a console.

Jonas Rosland  1:02:27  
Yeah, yeah, no, I was playing in here on my my gaming rig here behind me. And it's just beautiful. I need to hook it up to the CRT as well to see how it looks.

Jaiden Alemni  1:02:37  
Oh, yeah. That would be so cool. I bet it looks super cool on a CRT, I think that makes the pixel art look like very smooth.

Jonas Rosland  1:02:45  
Yeah, exactly. So I'm gonna finish up here. But before we finish up, I want to talk a little about your review of the indie game scene. 

So we met at the Boston Festival of Indie Games, the virtual festival. That happened a couple of months ago. The Boston scene is pretty well established. I'd say there's a lot of game developers around here. 

What are you? Are you involved in any groups? Or meetups? Or what do you think about the local Boston scene and then the global one?

Jaiden Alemni  1:03:26  
Well, I actually am very much like a game development hermit. I'm actually not from Boston. I live in Connecticut. But Boston is like the closest sort of area to me where there is game development stuff. 

Given BostonFIG is the only thing that I actually have like direct familiarity with and I've gone to a couple of years. Given the pandemic, it's been kind of hard to go to other stuff. 

So I don't really have an opinion on on the local scene, because I'm like, not super involved in it. Most of the things I do are online, I'm very intertwined in the _RPG Maker_ community which is its own little thing. 

But globally, I see--I'm very much on Twitter and stuff, trying to show off the game. And I see other games that people are working on. And I think it's really cool. Like how accessible indie gaming is right now. 

Like I see games from everywhere. I see games being made from developers all over the world. And it's just really nice to see that because I know that historically, a lot of games have only come from the US and Europe and Japan and stuff. And now we're seeing all of these other countries making games, and young developers like me and just people getting to do their own independent thing and bring their ideas to life is like, I don't know, it's super cool. It's super cool.

So I have a lot of hope for it. I think it's just gonna keep getting better and like, more cool ideas are going to keep appearing. And I'm looking forward to it. 

I'm super grateful for the opportunity that I've had to make this game. Like if it wasn't for the internet and all of the free resources available for people to learn game development, I wouldn't have been able to even do this. And of course, all the people I know that I met through Discord. And who helped me and gave me both advice and feedback has had a huge impact too.

Jonas Rosland  1:05:49  
Yeah, I think the indie scene is special. Everyone is super helpful, and just trying to make something fun. Something that people can enjoy. 

And yeah, like, you were putting your heart and soul into something that you hope people will enjoy. Even though you're a hermit. You have this community of people who are testing your game, downloading the demo and providing feedback, helping you become better and learn. 

And as you said, online learning resources and online, just resources for game making as well like the open source projects that augment existing existing products and things like that. 

I'm very, very grateful that we have a fantastic indie scene right now. I think it's really cool to see. 

Jaiden Alemni  1:06:54  
Yeah, absolutely.

Jonas Rosland  1:06:58  
So to wrap things up, where can people find you, information about the game, and download the demo?

Jaiden Alemni  1:07:06  
So I have my website, studioalemni.com. From there is kind of where you can find everything. 

The game is available on different platforms, the demo, it's on Steam, it's on Itch.io and it's on GameJolt. And it's on rpgmaker.net. So it's on a few different places that you can download it. If you don't want to download the Steam launcher, you know, you can get it on Itch.io or one of the other platforms. 

It's available for both Windows and macOS, \[and\] Linux soon. Working on that with the next update. The capabilities are there, it's just something that I had to sort of put aside because it was just a lot of extra work to do on top of already making the demo. 

I have a Discord server for the game. It's only for the game; I don't really do much extra community stuff. I keep it kind of focused on the game, again, because I'm so into development. Just trying to keep it going, you know? 

And I am on Twitter, I have the Studio Alemni Twitter, which is the official one and I do have a personal Twitter. It's not like super professional but if people want to see like me, the things that I'm interested in, and they can find me there as well. Or of course you can find me on my Discord via Discord as well. These are all the places. 

But yeah, my Twitter is @JaidenAlemni, @StudioAlemni is the studio, @AstraviaGame is the handle for Astravia... it's all very obvious, I think.

Jonas Rosland  1:08:57  
Yeah, awesome. Yeah, this has been super, super fun. I want to thank you Jaiden for for volunteering to be interviewed here. This has been super fun. And I had a blast. As I said, I had a blast playing through the game.

I highly recommend everyone to try out the demo and give feedback after the demo. It's super easy to do; short Google form. So please do that. Play through the demo. Super, super fun. Very colorful. Stupid bees. It's just a super fun game. And I'm really looking forward to seeing more of Legends of Astravia here. It's going to be a great game and I'm looking forward to Chapter 1 here.

Jaiden Alemni  1:09:56  
Thank you.

Jonas Rosland  1:09:59    
Thank you again, Jaiden. It's been fantastic. 

And for everyone listening or watching, you can find us at hitsave.org on the interwebs. You can find us at @hitsaveorg on Twitter and I'm @JonasRosland everywhere as well. 

Thank you everyone for watching or listening. Have a fantastic rest of the week and catch you next time!