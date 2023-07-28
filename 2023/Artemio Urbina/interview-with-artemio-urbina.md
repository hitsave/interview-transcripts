00:00.000 --> 00:27.640
Hello, everyone, and welcome to yet another Hit Save podcast.

00:28.000 --> 00:35.280
Today, I am here with Artemio Urbina with Junker HQ, among a bunch of other things.

00:35.640 --> 00:36.360
Hello, Artemio.

00:37.200 --> 00:39.240
Hello, it's a pleasure to be here, Jonas.

00:39.240 --> 00:39.960
Thank you very much.

00:40.840 --> 00:48.440
I have heard of you and heard about you and listened to podcasts and seen videos and things

00:48.440 --> 00:54.600
like that of you presenting some really fascinating stuff that you have created and you

00:54.600 --> 00:58.000
continue to create. So I'm honored to be talking to you today.

00:58.040 --> 00:59.840
This is going to be super fun, I think.

01:01.120 --> 01:02.840
Thank you very much. You're too kind.

01:03.280 --> 01:04.800
It's great to be here.

01:04.800 --> 01:11.360
And you taking all that time to deal with all this stuff is really, really humbling.

01:11.360 --> 01:12.120
Thank you very much.

01:13.080 --> 01:21.000
So you are the creator behind the 240p test suite MD4 year.

01:21.920 --> 01:29.640
You're a part of the team that made the CPS2 de-suicide function.

01:29.880 --> 01:32.800
And you've done a bunch of things.

01:32.800 --> 01:40.920
But the first thing that I want to dive into is you, who you are and Junker HQ and how

01:40.920 --> 01:43.400
that got started. And then we'll dive into some of the projects.

01:44.400 --> 01:52.400
Yeah, well, and from that side, Junker HQ started when I was still at college back in

01:52.400 --> 02:00.040
98, 99, it started not on its own, but as a standalone page and later got the domain

02:00.040 --> 02:05.080
name. Just between 2000, probably, it got the domain name.

02:05.480 --> 02:13.800
But it started as a site to aggregate or collect information regarding some Kojima games,

02:13.800 --> 02:19.760
mainly Snatcher and some Metal Gear and Polysnots, mainly to bring them into English to

02:19.760 --> 02:23.680
translate some of the games that weren't translated back then was one of the purposes.

02:23.680 --> 02:31.440
But the secondary purpose that I could do on my own was to document the different

02:31.480 --> 02:37.400
versions of these games, how they deferred, if the manuals had some extra information,

02:37.600 --> 02:44.760
some text dumps. I had text dumps from these games so that people or myself included would

02:45.320 --> 02:53.080
check the text of these scripts and configure it out if they had misunderstood that.

02:53.360 --> 02:58.640
So I posted that, posted scans and information on these different versions.

02:58.640 --> 03:06.720
That's how Junker HQ started as a showcase of the stuff that I could gather and share

03:06.720 --> 03:13.160
with the world. And it also contained some source code for Sega Saturn coding back in

03:13.160 --> 03:19.200
the day. So it was a mixed bag of the stuff that I was working on or that I cared about

03:19.200 --> 03:20.520
and I could share with the world.

03:21.520 --> 03:29.520
So with that, you helped with the translation, the fan translation, is that correct?

03:29.520 --> 03:36.520
Yeah, I kind of worked with them. It was interesting because it's, I believe, a perfect example

03:36.520 --> 03:43.520
of how the internet works because I extracted the text, for example, from Snatcher or

03:43.720 --> 03:52.840
Snatcher for MSX and just put it out there. I didn't know anything, but this guy, a fantastic

03:52.840 --> 04:01.120
guy called Takamichi, downloaded that script and simply translated it and put it back on

04:01.120 --> 04:08.520
the internet without letting me know. And then somebody else, a fantastic person as

04:08.520 --> 04:13.520
well, Daniel Caetano, came along, graphed that English translation and used that to

04:13.520 --> 04:18.520
translate the game itself. But we were involved in different parts of this and they were independently

04:18.520 --> 04:28.520
done. So it was interesting in every single regard. And later on, I formed part of a team

04:28.520 --> 04:33.520
that worked on Polysnotes to translate that into English for the PlayStation version back

04:34.520 --> 04:39.520
along with Mark and Sobif, amongst others, of course.

04:39.520 --> 04:46.520
I really, really appreciate everyone that puts effort into translating some of these

04:46.520 --> 04:51.520
fantastic games into more languages so more people can enjoy them. So thank you. Thank

04:51.520 --> 04:52.520
you for that.

04:52.520 --> 04:58.520
Oh, thank you. Thanks, everybody, because this is, unlike everything I've worked in,

04:58.520 --> 05:00.520
it's a community effort after all.

05:01.520 --> 05:06.520
And lately, the past few years, you've been involved in more localization efforts for

05:06.520 --> 05:07.520
other games.

05:08.520 --> 05:19.520
Have I? I've only, like, helped externally, not really, because it's a huge amount of

05:19.520 --> 05:25.520
work. And we are also engineering and, you know, the translation part is really hard

05:25.520 --> 05:33.520
because you have to change the game engine usually to deliver the English language and

05:33.520 --> 05:39.520
something that changes the font and the width of each character so that each one of the

05:39.520 --> 05:47.520
letters in the typeface has to fit because Japanese is very concise and condensed. And

05:47.520 --> 05:54.520
when you translate that, you end up with a longer verbose version. So it looks unnatural,

05:54.520 --> 05:59.520
the character width, and also the space. So there's a lot of work to be done there. I

05:59.520 --> 06:06.520
didn't work in that regard directly for those translations. I only helped. I made the text

06:06.520 --> 06:13.520
dumps, I figured stuff out, and I made the reverse engineer of the parts that overlay

06:13.520 --> 06:19.520
text over video, like placing real-time subtitles. We were really lucky that the game does that

06:19.520 --> 06:25.520
real-time with the engine, so we don't have to decode and re-encode the videos with text.

06:26.520 --> 06:34.520
So it's a lot of work. And also, even though everything's a community effort, and I really

06:34.520 --> 06:40.520
appreciate that, the other projects I've worked on, I can kind of work on the background on

06:40.520 --> 06:46.520
them and then just get feedback and rework instead of having to work intensely on something

06:47.520 --> 06:51.520
like a translation. And I respect that a lot because it's so much work.

06:53.520 --> 07:05.520
So diving into Junker HQ, because that's now a place for wikis for the OSC and a bunch of

07:05.520 --> 07:06.520
other things as well.

07:07.520 --> 07:08.520
Yes.

07:08.520 --> 07:14.520
So is that managed by you or a community? How is that handled?

07:15.520 --> 07:25.520
Basically I just give the hosting and I manage the wikis, but obviously I give the administration

07:25.520 --> 07:32.520
privileges to them as well, because I wouldn't be able to handle everything. And they just

07:32.520 --> 07:37.520
tell me I want to be a part of this, I give them an account, because otherwise the wiki

07:37.520 --> 07:43.520
was getting just spammed, right? So it's kind of restricted, but a simple mail to let me

07:43.520 --> 07:48.520
know that you want to change it brings you an account and you can change whatever you

07:48.520 --> 07:54.520
want. But that was the idea. And the wiki is very diverse because it has information

07:54.520 --> 08:00.520
on arcade PCBs and upscalers. It's mainly an upscaler thing and the RGB and video signals

08:01.520 --> 08:08.520
wiki, but it has information on some arcade boards and other interests that are around

08:08.520 --> 08:16.520
it that I have no other place to just showcase where and use that.

08:17.520 --> 08:23.520
Awesome. Awesome. Yeah, I've used it a lot. I have an OSSC here. So on the Junker HQ

08:23.520 --> 08:34.520
wiki for OSSC and figuring things out, because I also love just fine-tuning things, making

08:34.520 --> 08:41.520
it look really good and fine-tuning. I think I spend more time fine-tuning and setting

08:41.520 --> 08:46.520
things up that I'm actually using them, because it's fun tinkering.

08:47.520 --> 08:55.520
It's fun tinkering, yes. And there's a balance there that everyone should find and say, this

08:55.520 --> 09:00.520
is enough for me. I'm not having fun. Okay, you have to stop there. When that happens,

09:00.520 --> 09:07.520
stop, please. It's not intended to be an obsessive tool. It's intended to be a tool to give you

09:07.520 --> 09:13.520
a baseline to know what's going on, right? But yes, I obviously am the same way. I end

09:13.520 --> 09:20.520
up more fiddling with stuff and figuring it out and tinkering than actually playing. Yes.

09:21.520 --> 09:27.520
But it's its own kind of play, right? Exactly. It's a hobby. It's a hobby. Playing video

09:27.520 --> 09:34.520
games is a hobby and tinkering is also a hobby. And sometimes they merge. So looking at the

09:35.520 --> 09:44.520
background of your video there, you have a lot of equipment. So tell us about your education

09:44.520 --> 09:53.520
and your history in programming and electronics and things like that. How did you end up where

09:53.520 --> 10:02.520
you are right now? Well, I started at college computer science. Basically, it's an engineering

10:02.520 --> 10:09.520
here at Mexico, computer software engineering. There was no distinction between the two back

10:09.520 --> 10:19.520
in my time in that college. And it's a mixed area with computer architecture, digital design

10:19.520 --> 10:26.520
and computer software, software management. And back in the 90s when I started, you still

10:26.520 --> 10:33.520
had to deal with, I don't know, parallel ports, serial ports, that kind of thing, right?

10:33.520 --> 10:41.520
Enabling simple circuits. So I have that very, very light background in electronics. I always

10:41.520 --> 10:49.520
saw them as the same thing, obviously, because back then they were tighter. The integration

10:50.520 --> 10:55.520
between the two worlds was tighter and it wasn't such a wide area of knowledge. Of course

10:55.520 --> 11:01.520
it was, but I mean, nowadays you have specialization on every single regard because we have grown

11:01.520 --> 11:07.520
that tree impressively, right? Immensely, we have several areas and you can't be an expert

11:07.520 --> 11:13.520
on everything. You have to just work your way on the stuff that you like and be a generalist

11:13.520 --> 11:24.520
maybe in many areas, right? But I really wanted to understand how we could make something

11:24.520 --> 11:31.520
that looked alive in a way, and I don't mean like AI, I mean something that expresses something

11:31.520 --> 11:40.520
out of a rock, right? Because we grab silicon and we create these worlds. We enable video

11:40.520 --> 11:48.520
chats. We enable everything out of just inanimate matter. So I wanted to understand how that

11:48.520 --> 11:54.520
was possible. That was kind of the path that took me to learning that. And also I wanted

11:54.520 --> 12:04.520
to understand how games use that substrate to be expressive, right? Over the years I

12:04.520 --> 12:11.520
understood that I didn't want to make games. I wanted to understand what made them tick.

12:11.520 --> 12:20.520
And that's the main reason that I ended up where I am in retrospective and obviously

12:20.520 --> 12:28.520
retconning and a lot of stuff, right? But that's how I see it happening. And I don't

12:28.520 --> 12:36.520
have a formal education on electronics at all. I've only dealt with arcade repair because

12:36.520 --> 12:42.520
I started collecting arcade PCBs like, I don't know, almost 20 years ago, maybe 17, something

12:42.520 --> 12:52.520
like that. And I figured out that the only way that I could keep stuff working is because

12:52.520 --> 12:58.520
somebody else documented it. Because somebody else took the matters to their own hands,

12:58.520 --> 13:04.520
documented it in MAME. MAME source code has all this marvelous information. In the source

13:04.520 --> 13:11.520
code you just open any C file and just download the MAME source code. Open any file from any

13:11.520 --> 13:17.520
driver that you want and you'll find ASCII art of this PCB that has information on every

13:17.520 --> 13:23.520
chip, the memory map and everything. Of course MAME has its limitations in terms of arcade

13:23.520 --> 13:30.520
repair, but its main intention is that. You have the CPU, the software side of things,

13:30.520 --> 13:37.520
it's very well documented, right? And the video part is not as much because that's high

13:37.520 --> 13:43.520
level emulation. But it's the only place that you have any information about that up until

13:44.520 --> 13:52.520
recently, right? But despite this aside, talking about electronics, that's how I understood

13:52.520 --> 13:56.520
that I had to learn something about this if I wanted to keep them working, right? There

13:56.520 --> 14:02.520
was no service in Mexico to repair my PCBs when something failed. And usually when I

14:02.520 --> 14:07.520
grab something, something had been damaged by static electricity, some TTLs, I had to

14:07.520 --> 14:14.520
understand how that worked and thankfully the little things I understood about TTL design

14:14.520 --> 14:20.520
back then, back 15 years ago, helped me try to grab a pad, get an oscilloscope thanks

14:20.520 --> 14:25.520
to a friend that told me, no, it's not that hard, just go and try to deal with it, right?

14:25.520 --> 14:31.520
Of course I understand it from the software side. I usually just hack the ROM, check the

14:31.520 --> 14:36.520
ROM in MAME, change the code, place that on the PCB and use that to generate the signals

14:36.520 --> 14:41.520
to check the area that I want and then I go with a scope and probe and that's what

14:41.520 --> 14:48.520
this equipment is for. But obviously it bled, we're talking 70 years ago that I started

14:48.520 --> 14:56.520
that, but it bled into the 240p test suite because it helps me check the video signals,

14:56.520 --> 15:01.520
right? And here's the spectroscopes on this side that I use for that precise reason, right?

15:01.520 --> 15:07.520
There are spectroscopes and wafer monitors and that kind of thing because it's the same

15:07.520 --> 15:17.520
thing. It's kind of old equipment that helps me diagnose or understand signals and what's

15:17.520 --> 15:24.520
going on better. I kind of figured it out, I understood the world by measuring it. It's

15:24.520 --> 15:30.520
the way that I feel comfortable with things and make them my own. I measure stuff and

15:30.520 --> 15:36.520
go back, change, measure, and that's kind of how I figure out the stuff that's around

15:36.520 --> 15:37.520
me, right?

15:39.520 --> 15:44.520
I love that. I think that's a really good way to see the things that you're working

15:44.520 --> 15:47.520
on, measuring things and making sure that you understand what you're measuring and how

15:47.520 --> 15:50.520
you're measuring. That's really fascinating.

15:51.520 --> 15:52.520
It is.

15:53.520 --> 15:59.520
I wanted to dig into some of the projects that you've been working on. The first one

15:59.520 --> 16:14.520
that I want to talk about is the CPS2. The Capcom CPS2 had a ton of fantastic games,

16:15.520 --> 16:21.520
but there was a big issue with the Borgs. Can you please tell us about what the big

16:21.520 --> 16:24.520
issue was and how you solved it?

16:25.520 --> 16:33.520
Yes, of course. Capcom got into arcade games early in their history and there was a lot

16:33.520 --> 16:40.520
of cloning of the PCBs and they just grabbed the code and binaries, the ROMs, and used

16:40.520 --> 16:46.520
those to create clones and flood the market back in the day. This was a big problem.

16:47.520 --> 16:55.520
Capcom started changing or experimenting with security in some ways. We all have our

16:55.520 --> 17:03.520
views on how these encryption and protection systems prevent preservation as well in some

17:03.520 --> 17:10.520
ways, but I'm not going to go into those themes. The thing is that they wanted to protect

17:10.520 --> 17:16.520
their IP when Street Fighter 2 came out and everything was blown out of proportion for

17:16.520 --> 17:24.520
them. They had a huge growth period with Street Fighter 2 and they had this hardware that's

17:24.520 --> 17:30.520
called the CPS. We retrospectively called it the CPS1 because they released the CPS2

17:30.520 --> 17:40.520
later on, which is called the Capcom system. CPS has this modular architecture between

17:40.520 --> 17:46.520
several boards and they started adding some kind of protection on the video board. They

17:46.520 --> 17:54.520
have what we would call a GPU today. It's the part that generates several parts of the

17:55.520 --> 18:01.520
video signal, but in this case it dealt with sprites, priorities, backgrounds, and they

18:01.520 --> 18:11.520
made that chip kind of programmable and the protection implied that it responded in certain

18:11.520 --> 18:21.520
ways and had a battery that kept that configuration in RAM. But that was hacked easily and there

18:21.520 --> 18:27.520
were a lot of clones, so they released this new version, the CPS2, just right after they

18:27.520 --> 18:32.520
released something that was called CPS1.5, the DASH version. Very few games were released

18:32.520 --> 18:38.520
there, but they evolved rapidly into CPS2 that has this different protection scheme

18:38.520 --> 18:45.520
that has encryption keys and the whole code of the game, the code, not the data, is protected.

18:45.520 --> 18:55.520
It's encrypted in a way, in layman terms, because it's encoded, right? And you have

18:55.520 --> 19:04.520
to decode it. They made this custom CPU, a 68000, that has the chip itself has inside

19:04.520 --> 19:11.520
this 68000 has some RAM and has some extra hardware that's used to decode the code that

19:11.520 --> 19:18.520
arrives to the CPU and execute it in the CPU, in the 68000. So the data comes from

19:18.520 --> 19:24.520
the ROMs, it's decoded by this extra layer of hardware that has a RAM and the RAM has

19:24.520 --> 19:31.520
the decryption keys. Imagine that it has a password and it uses that password to decode

19:31.520 --> 19:36.520
the information that's arriving to the CPU and then it's only executed if it makes sense

19:36.520 --> 19:42.520
to the CPU, because it's scrambled, basically, right? And the thing is that this was kept,

19:42.520 --> 19:49.520
these keys, this password was kept by a battery. It's SRAM, it's static RAM that's kept

19:49.520 --> 19:58.520
by a battery alive. So if the battery failed, if there was a short, whatever, the keys were

19:58.520 --> 20:04.520
lost. And if the keys were lost, the game wouldn't boot anymore. It would be just an

20:04.520 --> 20:09.520
expensive piece of hardware laying at your office.

20:09.520 --> 20:12.520
An expensive paperweight, yeah.

20:12.520 --> 20:17.520
Exactly, that was exactly what I was looking for, an expensive paperweight. And Capcom

20:17.520 --> 20:24.520
had a service to de-suicide these boards back in the day, or change them to a different

20:24.520 --> 20:31.520
game. You brought them in, they swapped the, it's a two-layer PCB that has this kind of

20:31.520 --> 20:37.520
cartridge, but the cartridge that we are used to only contain the data has also the CPU

20:37.520 --> 20:44.520
and these keys. So the board that's at the bottom has all the video and audio hardware

20:44.520 --> 20:50.520
and common stuff, all glue stuff and controllers. And the top board has the CPU and has all

20:50.520 --> 20:56.520
graphics and data, and audio data as well. And obviously the encryption part and some

20:56.520 --> 21:01.520
extra chips that are used for PD as well.

21:01.520 --> 21:12.520
And this protection was very, very successful for Capcom and it prevented any clones during

21:12.520 --> 21:20.520
its active or commercially viable period. However, main people and math people, there's an

21:20.520 --> 21:26.520
incredible story back there. If somebody's interested in this, I would advise to look it up,

21:26.520 --> 21:33.520
because there's this Spanish mathematician that was working on decoding the data and figuring

21:33.520 --> 21:39.520
out the keys, right? And they did succeed, along with main people, to decode the keys and

21:39.520 --> 21:45.520
figure out what the keys would be based solely on the data, okay? This was a process that

21:45.520 --> 21:53.520
took some time to do, but they could just, like, grab the data. If you dumped a game that

21:53.520 --> 21:59.520
wasn't documented, which happened to me back in the day because I started collecting like 15 years

21:59.520 --> 22:05.520
or 17 years ago. Here in Mexico, I have the privilege of being one part of a dumping union

22:05.520 --> 22:14.520
that's an organization that documents, they simply, we understand that collecting this stuff is useless

22:14.520 --> 22:21.520
if you don't document it so it could be recovered, right? There's no way to have a collection of

22:21.520 --> 22:30.520
video games that's able to be projected into the future if you don't have them documented.

22:30.520 --> 22:35.520
If you have a piece of hardware that's unique in the world and it's not documented and you don't know

22:35.520 --> 22:42.520
how it works, it's going to be lost forever, eventually. So it's better to have it documented

22:42.520 --> 22:49.520
so that somebody could just, like, rework it and keep it, like, functional. I believe in this.

22:49.520 --> 22:57.520
I call it functional preservation. You change parts and re-enable processes to get things working

22:57.520 --> 23:05.520
for the future, right? So the thing is that they worked on this. I submitted several of these dumps

23:05.520 --> 23:12.520
that were not available, not documented, because there was something called Capcom Mexico

23:12.520 --> 23:20.520
that they had specific versions for this region and they also have some games like the Street Fighter

23:20.520 --> 23:27.520
15th Anniversary Edition for Street Fighter 2. It's quite similar to what you have in the picture.

23:27.520 --> 23:34.520
It's a blue PCB that was only released in Japan or believed to be only released in Japan.

23:34.520 --> 23:41.520
And here in Mexico we were able to find and document American, US versions of the PCB.

23:41.520 --> 23:43.520
That's fantastic.

23:43.520 --> 23:50.520
Yeah, and Capcom Mexico had these pieces and they did sell that in the southern part of the US

23:50.520 --> 23:58.520
as a distributor, I believe, or it was stocked from the US that was sent over here. I don't know the specifics.

23:58.520 --> 24:04.520
But we found these PCBs and I was able to dump it and they were able to decode these keys and document that.

24:04.520 --> 24:12.520
Right, but there was this particular version of the PCB and if you look for this thread in forums

24:12.520 --> 24:18.520
you'll find it. There is a black PCB that's a monolithic piece that doesn't have the two boards

24:18.520 --> 24:25.520
and it uses parts of what CPS-3 was commercially in terms of memory.

24:25.520 --> 24:35.520
But it's compact and everything's stored in those... they look like RAM DIMMs but they are actually flash pieces

24:35.520 --> 24:41.520
that... flash memory that can only be reached into by specialized hardware, right?

24:41.520 --> 24:52.520
And you couldn't desuicide them by the methods available in the early 2000s or late... or early 2010s even.

24:52.520 --> 24:59.520
Because you'd need to rewrite those to decrypt the game and re-enable that.

24:59.520 --> 25:03.520
And that was a method that was used, the Phoenix method back in the day.

25:03.520 --> 25:13.520
You have a dead PCB, you couldn't restore the keys, so you grab the ROMs, you dump them, decode them

25:13.520 --> 25:18.520
or use a decoded set and install that in the PCB, but it was a hack after all, right?

25:18.520 --> 25:26.520
It's very useful, it enabled several things like changing region, changing languages, having sound tests, that kind of thing.

25:26.520 --> 25:33.520
Which is awesome by itself, but it was prone to errors and corrections.

25:33.520 --> 25:40.520
There were several versions that were changing because they needed to detect what was data and what was code

25:40.520 --> 25:45.520
and decode only those parts and it was not an easy task and that was done by hand, right?

25:45.520 --> 25:51.520
It was not an automated process, so I had one of these PCBs.

25:51.520 --> 25:54.520
One of those black PCBs, a Marble vs. Capcom PCB.

25:54.520 --> 26:06.520
I bought it, I was really happy with it, I changed the battery and it was notorious for being very sensitive in terms of the battery change.

26:06.520 --> 26:13.520
And after the battery change it worked, but half an hour later, probably bad solder on my part 15 years ago

26:13.520 --> 26:16.520
not that I'm any better, but I was worse.

26:16.520 --> 26:25.520
Or maybe something I did, not discharging the capacitor or whatever, it died, right?

26:25.520 --> 26:31.520
It died like half an hour later and I only had a pink screen, magenta.

26:31.520 --> 26:33.520
That's not good, that's not good at all.

26:33.520 --> 26:35.520
No, no good. It was completely dead.

26:35.520 --> 26:41.520
So I posted and I said, hey, can somebody else help me?

26:41.520 --> 26:43.520
Razula, can you help me with this?

26:43.520 --> 26:48.520
And it was, I don't have the equipment to write that and well, it's that.

26:48.520 --> 26:50.520
Just deal with it, okay?

26:50.520 --> 26:58.520
And I was sad, but we worked on that with some other impressive individuals.

26:59.520 --> 27:06.520
Our kid hacker did reverse engineering in Europe, Eduardo Cruz, in Spain.

27:06.520 --> 27:11.520
And he has this amazing blog with all the detailed data.

27:11.520 --> 27:20.520
And IAN has access to many things and a lot of people, of course, in the main community, in the CPS2 community.

27:20.520 --> 27:28.520
And he made this reverse engineering and by decapping the chips, you basically grab one of these chips,

27:28.520 --> 27:33.520
just remove the upper layer of the chip with lasers, with assets,

27:33.520 --> 27:40.520
and then use metallurgic microscopes to check out how the transistors are connected.

27:40.520 --> 27:49.520
You create that map and understand how that works, reverse engineer it and use that to reinsert the key.

27:49.520 --> 27:55.520
And I was happy to work since I have a decent CPS2 collection

27:55.520 --> 28:07.520
and I also helped developing software tools to test this and create some of the code to insert the keys and make it easier.

28:07.520 --> 28:16.520
So I was part of that team in certain layers and I had access to certain hardware here in Mexico as well.

28:16.520 --> 28:26.520
I was part of that and thankfully I could help revive CPS2 boards by injecting the original keys back into the PCB

28:26.520 --> 28:29.520
and have them functional again using Arduinos.

28:29.520 --> 28:34.520
Originally, we have methods that are PIC based and several others today.

28:34.520 --> 28:40.520
But what you usually do is you have a dead board, you place a new battery,

28:40.520 --> 28:46.520
you connect the Swiss side hardware, upload the keys and you're done.

28:46.520 --> 28:52.520
It's basically back to how it was factory original in that time.

28:52.520 --> 29:03.520
I just think it's fantastic that this global group of people working together to make sure that this specific piece of hardware,

29:03.520 --> 29:09.520
which was conceptualized and created to essentially die.

29:09.520 --> 29:16.520
You made it so that they can live on forever, essentially, thanks to this.

29:16.520 --> 29:28.520
I just think it's fantastic just being able to modify them and making sure that they continue to function even after the batteries have died or something has happened.

29:28.520 --> 29:31.520
It's just stellar work. I love it.

29:31.520 --> 29:41.520
I was really honored to be a part of it and also that we shared the same values because we didn't want to make a profit out of this.

29:41.520 --> 29:45.520
We understood several things.

29:45.520 --> 29:49.520
Firstly, we had the privilege to not need to do it as a business.

29:49.520 --> 29:52.520
That's one side of it, right?

29:53.520 --> 30:03.520
We also understood that when we released this, even if it was a commercial product, it would be backwards engineered, reverse engineered.

30:04.520 --> 30:10.520
Since we understood and we believed in open source, we open sourced this immediately.

30:10.520 --> 30:29.520
It wasn't released until we have everything detailed for not user friendly, but end user capable, slightly technically inclined person to be able to just grab off the shelf parts and just grab an Arduino, grab some DuPont cables and you're set.

30:29.520 --> 30:32.520
You just upload this code and it's open source.

30:32.520 --> 30:50.520
That was part of the reason so that when we released it, we hoped for this to be as public and general as possible, as much noise as possible, so the people wouldn't be scammed out by keeping this gatekept.

30:50.520 --> 30:52.520
I love that.

30:52.520 --> 30:58.520
We tried to do as much as possible in public as well.

30:58.520 --> 31:01.520
We obviously support open source projects.

31:01.520 --> 31:05.520
I work within open source outside of the organization.

31:05.520 --> 31:07.520
That's my day job.

31:07.520 --> 31:10.520
Open source is incredibly valuable.

31:10.520 --> 31:18.520
Again, thank you to everyone on the team that made this possible and made it open source because then everyone benefits from it.

31:18.520 --> 31:21.520
It's just so valuable.

31:22.520 --> 31:39.520
It's so important that there are organizations like yours that are working on that because it's usually decentralized individuals and it doesn't have the punch when it comes to individuals scattered around the globe.

31:39.520 --> 31:41.520
Thank you.

31:41.520 --> 31:42.520
Sure thing.

31:43.520 --> 31:47.520
The game preservation community is just fantastic in general.

31:47.520 --> 31:50.520
Fantastic individuals.

31:50.520 --> 32:00.520
It's not easy working globally as a team because you are still individuals, you have your day jobs, you need to do that as well.

32:00.520 --> 32:10.520
Being able to actually create this project and make it successful, I'm just amazed.

32:10.520 --> 32:13.520
Thank you again.

32:13.520 --> 32:18.520
I wanted to dive into two other projects that you're focused on right now.

32:18.520 --> 32:24.520
The first one is, of course, the 240p test suite.

32:24.520 --> 32:27.520
Can you tell us a bit about how this started?

32:27.520 --> 32:32.520
I think you started this for the Sega Genesis and Mega Drive, right?

32:32.520 --> 32:35.520
Yes, you're right.

32:35.520 --> 32:38.520
It's interesting how this got started.

32:39.520 --> 32:45.520
I was into video and audio on from an early age.

32:45.520 --> 32:56.520
Of course, not up to the point that was allowed or permitted by economics in Mexico when I was a kid, but I was impressed in that area.

32:56.520 --> 33:04.520
When we grew up in my generation, when we grew up in the 80s, it was the era of high fidelity, right?

33:04.520 --> 33:13.520
There was this trend to have as much fidelity from equipment as was possible, right?

33:13.520 --> 33:23.520
It was floor speakers, subwoofers, and woofers and tweeters, crossovers, and videotape devices.

33:23.520 --> 33:32.520
You just entered technology and offering as much fidelity as possible at home, right?

33:33.520 --> 33:36.520
That kind of had an impact on me.

33:36.520 --> 33:43.520
Today, it's quite different because we all consume, everyone is in the living room checking their own phone, right?

33:43.520 --> 33:47.520
It's not about quality.

33:47.520 --> 33:50.520
I mean in general terms, I don't say that people don't care.

33:50.520 --> 34:02.520
I'm saying the general consensus is based around more content and faster instead of higher quality and more of a curated experience, right?

34:02.520 --> 34:05.520
Just a general trend, but that left an impression on me.

34:05.520 --> 34:19.520
Professionally, I dedicated myself almost two decades to video processing and video broadcast on TV stations, okay?

34:19.520 --> 34:29.520
Satellite and analog video and the transition from analog to digital video and the transition from SZTV to HDTV.

34:30.520 --> 34:44.520
In actuality, even though I started professionally working with SZ television for ADI and NTSC, I transitioned fastly into HDTV professionally.

34:44.520 --> 34:56.520
But as that transition happened, I was in love with CRTs and I wanted to change to an HDTV.

34:56.520 --> 35:02.520
But several things happened at the same time period.

35:02.520 --> 35:12.520
I bought my first home theater back in the early 2000s and also LUVA television from Europe, right?

35:12.520 --> 35:21.520
This amazing HDCRTs that were huge, like 36 inches, 16 by 9.

35:21.520 --> 35:26.520
And I didn't want to change to LCDs, right?

35:26.520 --> 35:29.520
I didn't like the contrast.

35:29.520 --> 35:36.520
I didn't like how the levels of darkness were not precisely profound.

35:36.520 --> 35:39.520
They looked like browns back in the day.

35:40.520 --> 35:43.520
Sometimes you get that nowadays, but it's less often, right?

35:43.520 --> 35:45.520
Yeah, they were not good.

35:45.520 --> 35:47.520
No, they were not good.

35:47.520 --> 35:55.520
And I was too much into like DVD, progressive video, aspect ratios and audio calibration.

35:55.520 --> 36:06.520
And when I started calibrating my home theater, I got my SPL meter, I measured, I checked the resonance in the room, that kind of thing.

36:06.520 --> 36:09.520
And I got into Room also, which is an amazing software.

36:09.520 --> 36:16.520
If you are into home audio and don't know the Room Equalization Wizard software, just go.

36:16.520 --> 36:24.520
It's an amazing piece of software that allows you to measure what are the resonant frequencies in a room, graphs everything,

36:24.520 --> 36:36.520
and even does the equalization for you so you can equalize the subwoofer and attenuate any rumbling and extra booming frequencies that you have in your room.

36:36.520 --> 36:38.520
So it's amazing.

36:38.520 --> 36:41.520
So that influenced me for the future, certainly.

36:41.520 --> 36:50.520
Because it resonated with me that I could just measure something with a computer and get actual feedback and correct reality.

36:51.520 --> 36:55.520
It was this kind of power that makes you love engineering.

36:55.520 --> 37:05.520
Because understanding that you can modify your environment is something that I believe that exact sciences gives you.

37:05.520 --> 37:08.520
Not to say that we can control the world.

37:08.520 --> 37:09.520
No, no, no.

37:10.520 --> 37:14.520
It's impressive how good math and physics are.

37:14.520 --> 37:32.520
And it's obviously dumb that I'm saying this, but it's certainly a point of interest that when you use these things to try and measure and predict stuff and better something, and it works, it changes you in a way.

37:32.520 --> 37:38.520
Changes you in ways that people that haven't done that maybe have a hard time to understand.

37:38.520 --> 37:41.520
So, that.

37:41.520 --> 37:47.520
And as a hardware platform, I have it at hand here.

37:47.520 --> 37:53.520
The Framemeister came out back in 2010.

37:53.520 --> 37:58.520
I came from using an XRGB2 and XRGB3.

37:58.520 --> 37:59.520
Here they are.

37:59.520 --> 38:03.520
And these things are upscalers that we used in the analog world.

38:03.520 --> 38:04.520
This is an XRGB2.

38:04.520 --> 38:07.520
I'm not going to show you the other ones, but this one came out.

38:07.520 --> 38:08.520
Okay.

38:08.520 --> 38:12.520
And this one was the first HDMI upscaler that was out there.

38:12.520 --> 38:13.520
Okay.

38:13.520 --> 38:15.520
DBI we have.

38:15.520 --> 38:17.520
With the XRGB3, we have DBI.

38:17.520 --> 38:18.520
Okay.

38:18.520 --> 38:19.520
Here it is.

38:19.520 --> 38:26.520
But this one was the first HDMI one and intended for HDMI directly.

38:26.520 --> 38:38.520
So, I was worried that the aspect ratio and the pixel aspect ratio, which is a whole kind of worms, was probably not being processed correctly.

38:38.520 --> 38:41.520
And I worried about lag, right?

38:41.520 --> 38:51.520
So, we have information on how these things worked and that we had certain promises, but I didn't have a way to measure them.

38:51.520 --> 38:54.520
So, I had some time.

38:54.520 --> 38:57.520
The SGDK that came out, which is amazing.

38:57.520 --> 39:05.520
If you don't know the software development kit for the Sega Genesis, it's an amazing piece of development kit that's done by Stefan.

39:05.520 --> 39:12.520
And the SGDK came out and it was C-based for the Sega Genesis.

39:12.520 --> 39:17.520
I wasn't particularly good at assembly back then.

39:17.520 --> 39:21.520
I'm way better now, yes, but I'm terrible in general.

39:21.520 --> 39:24.520
But that was really attractive.

39:24.520 --> 39:28.520
Several things just clashed at that moment.

39:28.520 --> 39:31.520
I got an SDK in C for the Sega Genesis.

39:31.520 --> 39:35.520
The Sega Genesis was my favorite console while growing up.

39:35.520 --> 39:41.520
And I had an XRGB Framemeister and I knew I didn't want to make games.

39:41.520 --> 39:47.520
I knew that I like tools, I like measuring, and I wanted to understand consoles better.

39:47.520 --> 39:52.520
So, I said, okay, I can understand how the Sega Genesis works.

39:52.520 --> 39:57.520
I can understand how this old hardware made this magic happen.

39:57.520 --> 40:04.520
And at the same time, I could try to create something that could have some value for somebody else.

40:04.520 --> 40:10.520
Much more value than what I could do with a game from my own perspective.

40:10.520 --> 40:14.520
And at the same time, solve several problems.

40:14.520 --> 40:19.520
Have an example of how something is coded for the Sega Genesis in C.

40:19.520 --> 40:23.520
Have test patterns like the ones I used to calibrate my home theater.

40:23.520 --> 40:30.520
But coming out from a Sega Genesis and checking them out on the console itself and the upscaler.

40:30.520 --> 40:33.520
And learn how these things work.

40:33.520 --> 40:35.520
So, it was a no-brainer.

40:36.520 --> 40:42.520
I just dived in and contacted the people that were into upscalers back in the day.

40:42.520 --> 40:47.520
And got some feedback on which patterns would work, which ones would be interesting.

40:47.520 --> 40:49.520
And that's the way it started.

40:49.520 --> 40:54.520
I just posted this and told people, hey, I'm making this.

40:54.520 --> 41:04.520
Is there something that could be made to it or included in it to make it easier to use?

41:04.520 --> 41:06.520
And for your purpose.

41:06.520 --> 41:07.520
And we can integrate that.

41:07.520 --> 41:09.520
And that's how the ball started rolling.

41:12.520 --> 41:15.520
And this was the first test pattern you did.

41:15.520 --> 41:16.520
Is that correct?

41:16.520 --> 41:19.520
Yes, this was the first pattern that I did.

41:19.520 --> 41:21.520
And you have a coincidence as well.

41:21.520 --> 41:27.520
Because that test pattern is the grid as the CPS2 hardware does.

41:27.520 --> 41:29.520
So, that's why.

41:29.520 --> 41:31.520
That's the grid that I used.

41:32.520 --> 41:35.520
It simply was the grid that I had on CPS2.

41:35.520 --> 41:38.520
And I ported that to Sega Genesis.

41:38.520 --> 41:39.520
Easy.

41:39.520 --> 41:41.520
And it's super useful.

41:41.520 --> 41:43.520
It's super useful.

41:43.520 --> 41:46.520
Yeah, it's really cool.

41:46.520 --> 41:52.520
I actually have a copy here of the 240p test suite as well for the Dreamcast.

41:52.520 --> 41:57.520
That was sent over to us by our friends over at Video Games New York Soft.

41:57.520 --> 41:59.520
So, VG&I Soft.

42:00.520 --> 42:03.520
So, get your own copies there as well.

42:03.520 --> 42:05.520
Everyone is listening.

42:05.520 --> 42:07.520
And it was great that they did that.

42:07.520 --> 42:11.520
Because we made an agreement that they have...

42:11.520 --> 42:15.520
If you notice, it has a lower value than most of the things they publish.

42:15.520 --> 42:19.520
And the deal was to have it as low as possible.

42:19.520 --> 42:21.520
That was my only condition.

42:21.520 --> 42:24.520
Because it's open source.

42:24.520 --> 42:26.520
They could publish it without asking, right?

42:26.520 --> 42:28.520
And they did that.

42:28.520 --> 42:29.520
And they did an amazing job.

42:29.520 --> 42:33.520
They didn't want to do anything halfway.

42:33.520 --> 42:35.520
They made this manual.

42:35.520 --> 42:38.520
They commissioned the cover.

42:38.520 --> 42:40.520
And they made a great work.

42:40.520 --> 42:42.520
I love it.

42:42.520 --> 42:43.520
Thank you.

42:43.520 --> 42:44.520
Yeah.

42:44.520 --> 42:48.520
Can you tell us a bit about the other test patterns we have here?

42:48.520 --> 42:51.520
And what they can be used for?

42:51.520 --> 42:52.520
Sure thing.

42:52.520 --> 42:56.520
And every test pattern has its own use, purpose.

42:56.520 --> 43:01.520
And it's grown out of community need.

43:01.520 --> 43:05.520
Or something that I thought would be useful.

43:05.520 --> 43:09.520
All patterns have, on all versions of the suite, have interactive...

43:09.520 --> 43:10.520
Well, not interactive.

43:10.520 --> 43:12.520
It has online help inside the suite.

43:12.520 --> 43:14.520
Inside the same...

43:14.520 --> 43:20.520
You usually press start or the sign button that's shown in the main screen.

43:20.520 --> 43:25.520
That brings you up a help screen that tries to give you information on how things work.

43:25.520 --> 43:30.520
But this one, for example, is also a CPS2 version.

43:30.520 --> 43:34.520
Well, a CPS pattern that's been backported into consoles.

43:34.520 --> 43:45.520
But the idea here is to have the basic colors and the full range of amplitudes of intensity of each one of them.

43:45.520 --> 43:48.520
So, at the top you have red, right?

43:48.520 --> 43:55.520
And red goes all the way from black, that's zero, all the way to the reddest red that the Sega Genesis could draw.

43:55.520 --> 43:58.520
That's an E internally, okay?

43:58.520 --> 44:05.520
What you do with this is you calibrate your display, your stream, whatever you're doing.

44:05.520 --> 44:08.520
Because the 240p test suite is not only intended for CRTs.

44:08.520 --> 44:13.520
It was born in the digital world, after all.

44:14.520 --> 44:21.520
It helps CRTs, which was a feature that was added later on.

44:21.520 --> 44:24.520
This was made originally for scalers, right?

44:24.520 --> 44:26.520
To test scalers.

44:26.520 --> 44:33.520
But I understood that I could use it also to calibrate CRTs and later on to prepare streams, right?

44:33.520 --> 44:35.520
Or recordings.

44:35.520 --> 44:44.520
If you want to have a recording that's going to be for preservation purposes and you want to have levels proper for what you're doing.

44:44.520 --> 44:50.520
You calibrate white to that white and you calibrate black to that black.

44:50.520 --> 44:54.520
So that they match the domain that you're translating it to.

44:54.520 --> 44:58.520
Be it an HDTV, a CRT or a stream.

44:58.520 --> 45:02.520
And you have to be able to see all the gradings of color.

45:02.520 --> 45:07.520
In this specific case with the Sega Genesis, it's very few primary colors that can be displayed.

45:07.520 --> 45:11.520
This is the full range of primaries that the Genesis can display.

45:11.520 --> 45:15.520
And you have to be able to see the last two divisions.

45:15.520 --> 45:18.520
For example, in this case, you have C and E.

45:18.520 --> 45:24.520
You have to be able to see a different hue of red between C and E.

45:24.520 --> 45:27.520
And same thing for green, same thing for blue.

45:27.520 --> 45:30.520
And the white has to be white, balanced between those.

45:30.520 --> 45:33.520
So that's all the purposes that this pattern serves.

45:33.520 --> 45:38.520
And obviously it changes between versions because you have different gradings.

45:38.520 --> 45:42.520
But it kind of offers the same kind of service for everything.

45:42.520 --> 45:45.520
And when you open an oscilloscope and have a different version.

45:45.520 --> 45:52.520
Like running this Sega Genesis implementation on a MrFPGA and you want to see if the levels are proper.

45:52.520 --> 46:00.520
You open this in a scope and it immediately gives you a ramp of how it goes and if it reaches every single value.

46:00.520 --> 46:05.520
That's kind of the purpose of this in general terms.

46:05.520 --> 46:08.520
That's really, really cool.

46:08.520 --> 46:14.520
I'm looking forward to trying out this on my CRT that's back here.

46:14.520 --> 46:16.520
Panasonic Tau.

46:16.520 --> 46:19.520
I want to try it out as well.

46:19.520 --> 46:21.520
This is going to be super fun.

46:21.520 --> 46:26.520
For testing this, I would recommend the Dreamcast version mainly for that pattern.

46:26.520 --> 46:28.520
For general use, right?

46:30.520 --> 46:33.520
Sounds good. Yeah, I'll definitely try that out.

46:33.520 --> 46:37.520
This one I found and I'm not really sure what I'm looking at here.

46:37.520 --> 46:40.520
Yeah, this is a recent pattern.

46:40.520 --> 46:44.520
Thanks to Keith, Keith Rainey brought it to my attention.

46:44.520 --> 46:53.520
Because I have originally and naively done a pattern on the Sega Genesis and later on the Super Nintendo and every version ever since.

46:53.520 --> 46:56.520
That showed some circles, right?

46:56.520 --> 46:59.520
And you had to measure that the circle was a circle.

46:59.520 --> 47:05.520
That was really hard because even designing it was really hard to use.

47:06.520 --> 47:14.520
Because you have things that pixels on a game console are not square.

47:14.520 --> 47:16.520
That's one side of it.

47:16.520 --> 47:18.520
CRTs have no pixels.

47:18.520 --> 47:20.520
That doesn't exist.

47:20.520 --> 47:24.520
There's no concept of resolution of pixels in a CRT.

47:24.520 --> 47:26.520
And not in the signal.

47:26.520 --> 47:32.520
When you are sending the signal from the console to the CRT, there are no pixels.

47:32.520 --> 47:35.520
It's just a signal that changes with time.

47:35.520 --> 47:40.520
The game console internally has a representation and a limit in resolution in pixels.

47:40.520 --> 47:41.520
Yes.

47:41.520 --> 47:45.520
But that gets translated to the analog domain.

47:45.520 --> 47:54.520
And when it does, and when we digitize it, it not necessarily matches the pixels in our displays.

47:54.520 --> 47:55.520
Right?

47:55.520 --> 47:58.520
It won't, as a matter of fact.

47:58.520 --> 48:05.520
Because these pixels are most of the time wider than taller.

48:05.520 --> 48:08.520
They are basically rectangles.

48:08.520 --> 48:15.520
And these stripes that are being drawn on the signal have to be used to create circles.

48:15.520 --> 48:23.520
And that circle, even though I did reach pixel aspiration when I could create circles on a perfect scene,

48:23.520 --> 48:25.520
it was really hard to measure.

48:25.520 --> 48:31.520
Because you had to measure the diameter and rotate and have the diameter the other way.

48:31.520 --> 48:35.520
And Keith suggested that we should use squares.

48:35.520 --> 48:38.520
And it was so simple that I felt dumb.

48:38.520 --> 48:43.520
Yes, we should use squares to measure linearity instead of circles.

48:43.520 --> 48:47.520
So it was a way of squaring the circle in some ways.

48:47.520 --> 48:58.520
The thing is that he calculates for every single game console and capabilities of the video signal of the system, its clock, etc.

48:58.520 --> 49:07.520
And using perfectly calibrated PBMs, because he is obsessive in this, and I don't mean it in a bad way.

49:07.520 --> 49:13.520
He checks the service manual, follows it to the point.

49:14.520 --> 49:21.520
And recaps everything, follows the thing to the point, uses a real signal generator, not the 2-4-EP test suite.

49:21.520 --> 49:26.520
Like this is the signal generators, well, the one that I use, thanks to him.

49:26.520 --> 49:40.520
And he uses fancier ones so that we can match the 2-4-EP test suite output the best we can to an NTS signal and have a proper pattern being generated.

49:40.520 --> 49:44.520
So this thing that you're seeing has these red squares.

49:44.520 --> 49:52.520
You can use some buttons in the 2-4-EP test suite and that's good that we have an interactive version instead of flat patterns.

49:52.520 --> 50:04.520
And you can darken the white part and you can measure those red squares so they can match and be the same width as the same height when they are upscaled or shown on a CRT.

50:04.520 --> 50:07.520
And that tells you that you have proper aspect ratio.

50:08.520 --> 50:17.520
And it serves obviously other ends, other means, like the ends of the signal, the squares tell you where the signal ends,

50:17.520 --> 50:27.520
and you have these detailed point patterns or pixel patterns that help you check linearity and convergence on a CRT.

50:27.520 --> 50:34.520
But it also helps check that aspect ratio has been properly upscaled.

50:34.520 --> 50:43.520
And when this was done, I was also at a crossroads because I don't only serve CRT user or upscaler users.

50:43.520 --> 50:57.520
One of the other and generally disregarded aspect of the suite that I try to do is this software tries to document what the console does.

50:58.520 --> 51:06.520
For example, the NES or the Super NES, they don't necessarily adhere to broadcast video standards.

51:06.520 --> 51:17.520
That was not their intention. Their intention was that they could display a signal on a commercial TV screen and do that as cheaply as possible.

51:17.520 --> 51:22.520
And I don't mean that Sega did that as well. Everybody did that as well.

51:23.520 --> 51:31.520
And these game consoles have their own quirks and unique signals and they are out of spec most of the time.

51:31.520 --> 51:36.520
So I have to document that and the 240p test suite tries to document that.

51:36.520 --> 51:44.520
For example, the colors that we were showing at the last pattern, they are not the colors to calibrate your CRT for.

51:44.520 --> 51:47.520
They are the colors of the Sega Genesis.

51:48.520 --> 51:56.520
If you calibrate to these colors, it will work perfectly for your Sega Genesis, but it wouldn't be ideal for your DVDs.

51:57.520 --> 51:59.520
You will be missing something.

52:00.520 --> 52:06.520
But if you calibrate for your DVD, you will get decent Sega Genesis values.

52:07.520 --> 52:16.520
That's why I recommended the Dreamcast because the Dreamcast's range is way wider and it will allow you to have a calibration that's general.

52:16.520 --> 52:21.520
But every single console has a different enough spec configuration.

52:21.520 --> 52:31.520
So if you calibrate with a grid and are obsessive with it and calibrate it with the Genesis, the Super Nintendo will be off by 1 pixel to the top.

52:31.520 --> 52:35.520
And the TurboGrafx would be off by 5 pixels to the right.

52:36.520 --> 52:38.520
So you have to deal with it.

52:39.520 --> 52:42.520
It's never ending tinkering, essentially.

52:43.520 --> 52:49.520
But you have to understand this and live with it.

52:49.520 --> 52:58.520
But the thing that I deal with on the other side is I have to output the things as wrongly or as properly as a console does.

52:59.520 --> 53:05.520
And Keith is trying to manage to keep our pattern as close to NTSC standard as possible.

53:05.520 --> 53:10.520
That's why the grid is still there because that offers a value for the game console.

53:11.520 --> 53:18.520
When you're documented, if your emulator is doing things as a Sega Genesis would, then you go here.

53:18.520 --> 53:26.520
And if you want to check if the video signal is being represented and upscaled and the proper aspect ratio in your emulator, then you go to the monoscope.

53:27.520 --> 53:29.520
Depending on what kind of work you're doing.

53:29.520 --> 53:35.520
I understand that the suite in general terms is mostly used by people that have the video signals.

53:35.520 --> 53:46.520
But it's also used by emulator authors, by MrFPGA core developers, by people that are documenting or recording video for archival purposes.

53:46.520 --> 53:54.520
And that purpose is not indirect clash with proper signals, but they are not the same thing.

53:54.520 --> 53:58.520
There are certain nuances that have to be preserved.

54:00.520 --> 54:03.520
Yeah, this is fantastic.

54:05.520 --> 54:07.520
You're hitting a really good point there.

54:07.520 --> 54:11.520
Recording live footage as well.

54:11.520 --> 54:19.520
Because preserving gameplay is just as important as preserving the games themselves as well.

54:19.520 --> 54:21.520
How do you actually play a game?

54:21.520 --> 54:23.520
And what should it look like?

54:24.520 --> 54:31.520
So people can look back and say, yeah, oh, yeah, maybe we made an error 10 years ago and we can go back and fix that.

54:31.520 --> 54:34.520
So, yeah, I think that's really, really important.

54:34.520 --> 54:47.520
The 240p test suite has some great artwork with it as well, as can be seen here on this one.

54:47.520 --> 54:49.520
And the image here.

54:50.520 --> 54:51.520
And this.

54:51.520 --> 54:53.520
Yes, there too.

54:53.520 --> 54:54.520
Oh, I love that.

54:54.520 --> 54:55.520
I love that.

54:55.520 --> 54:58.520
And this is Donna.

54:58.520 --> 54:59.520
Yes.

54:59.520 --> 55:01.520
Yes, I was really, really lucky.

55:01.520 --> 55:06.520
And this is this awesome artist called Pepe Salo.

55:06.520 --> 55:15.520
He, out of the blue completely, just tweeted one day, this is my fan art for the 240p test suite.

55:16.520 --> 55:17.520
I made this poster.

55:17.520 --> 55:20.520
It includes my original character Donna.

55:20.520 --> 55:24.520
So it's not a character related to the 240p test suite.

55:24.520 --> 55:27.520
It's as she is his character.

55:27.520 --> 55:31.520
And he made this poster, right?

55:31.520 --> 55:36.520
That's an amazing promotional piece for the suite.

55:36.520 --> 55:38.520
And I was amazed.

55:38.520 --> 55:40.520
I was in a pool.

55:40.520 --> 55:41.520
Imagine that.

55:41.520 --> 55:42.520
On vacation.

55:43.520 --> 55:46.520
And I received that tweet and I tried.

55:46.520 --> 55:49.520
I had very bad internet access.

55:49.520 --> 55:51.520
I tried to contact him.

55:51.520 --> 56:04.520
And just that same night I was talking with him by Zoom and thanking him for the work and figuring out if I could use hair to change the pattern.

56:04.520 --> 56:08.520
There's a pattern that's been there in the suite from the beginning.

56:08.520 --> 56:10.520
That it's interactive.

56:10.520 --> 56:12.520
You can't show it as a still.

56:12.520 --> 56:20.520
But it's, you know, when you get hit, like, for example, in Final Fight or in a shoot-em-up, your ship or your character blinks.

56:20.520 --> 56:21.520
Right?

56:21.520 --> 56:24.520
It turns one frame on, one frame off, one frame.

56:24.520 --> 56:28.520
And that creates an image of transparency on a CRT.

56:28.520 --> 56:31.520
On LCD it's due to image permanence.

56:31.520 --> 56:35.520
On LCD it's notorious as well, but it's kind of slightly different.

56:35.520 --> 56:41.520
But that's something that upscalers back in the day got completely wrong.

56:41.520 --> 56:50.520
And this 240p signal, that's a complete violation of video television standards, used it.

56:50.520 --> 56:57.520
And since it was a complete violation of standards, there's no standard way to process it.

56:57.520 --> 56:58.520
There was.

56:59.520 --> 57:04.520
So when a video processor wore a signal with something blinking that way, it didn't show as transparency.

57:04.520 --> 57:08.520
It showed as a completely black slate.

57:08.520 --> 57:10.520
Or it didn't show at all.

57:10.520 --> 57:12.520
It simply disappeared.

57:12.520 --> 57:15.520
Or, in even worse cases, it got feathered.

57:15.520 --> 57:18.520
One line black, one line white.

57:18.520 --> 57:24.520
Yeah, depending on the way that it was interlacing the signal to convert it to a progressive display.

57:24.520 --> 57:31.520
So we have this test where Fudo told me to use some complex pattern in the background.

57:31.520 --> 57:33.520
And I could flash a sprite on top of it.

57:33.520 --> 57:38.520
And it was one of the first tests that was included in the 240p test suite.

57:38.520 --> 57:40.520
So I didn't know what to add.

57:40.520 --> 57:42.520
I'm a terrible pixel artist.

57:42.520 --> 57:50.520
So I just scanned an image that I had at hand from an animation cell from Ghost in the Shell.

57:50.520 --> 57:53.520
I'm lucky to have one of the original animation cells of the movie.

57:53.520 --> 57:55.520
And I had that just scanned.

57:55.520 --> 57:58.520
And I said, okay, this is awesome.

57:58.520 --> 58:00.520
This is just a test pattern on my software.

58:00.520 --> 58:02.520
I'm just going to put it there.

58:02.520 --> 58:03.520
Not thinking much about it.

58:03.520 --> 58:09.520
But several years ago when this happened, I was looking into removing Motoko from Ghost in the Shell.

58:09.520 --> 58:13.520
And I asked Pepe if I could use Donna instead.

58:13.520 --> 58:16.520
And he was pleased and agreed.

58:16.520 --> 58:20.520
So he allowed me to use Donna.

58:21.520 --> 58:24.520
And we started creating the pixel art for this.

58:24.520 --> 58:30.520
Converting this awesome artwork into the color palette of the Sega Genesis and the Super Nintendo.

58:30.520 --> 58:39.520
And use her instead of Donna to have that background to contrast the pattern, the flashing pattern against.

58:39.520 --> 58:42.520
But, yeah, he's been doing art for the suite.

58:42.520 --> 58:47.520
We commissioned this new version for Neo Geo.

58:47.520 --> 58:53.520
This was a request from our side instead of him doing it just because he wanted to.

58:53.520 --> 58:56.520
And it's been great.

58:56.520 --> 59:00.520
I mean, his artwork is amazing.

59:00.520 --> 59:03.520
Yeah, I definitely love this one.

59:03.520 --> 59:07.520
The latest version here for the Neo Geo.

59:07.520 --> 59:13.520
Where she's fixing the monitor, the screen in the cabinet there.

59:13.520 --> 59:16.520
Making sure, fine tuning it.

59:16.520 --> 59:19.520
I think it's fantastic. It's really, really cool.

59:19.520 --> 59:24.520
When is that coming out? Do you know yet?

59:24.520 --> 59:26.520
That's already out.

59:26.520 --> 59:28.520
Stonish Gamer has the exclusive.

59:28.520 --> 59:31.520
These were made by hand.

59:31.520 --> 59:36.520
We tried our best to have the price as low as possible.

59:36.520 --> 59:38.520
And kind of as a service.

59:38.520 --> 59:42.520
I was kind of against trying to tackle something like this.

59:42.520 --> 59:47.520
Because costs and demand, I believe it's very low.

59:47.520 --> 59:51.520
But a friend of mine here in Mexico custom designed the PCBs.

59:51.520 --> 59:56.520
These are the first homebrew PCBs that are going to release as open hardware.

59:56.520 --> 59:59.520
We are preparing all the documentation to have that.

59:59.520 --> 01:00:03.520
And since flashcards are so expensive.

01:00:04.520 --> 01:00:08.520
We figured that there might be certain very small section of the community.

01:00:08.520 --> 01:00:12.520
That might want to do 3P test with the Neo Geo as a card.

01:00:12.520 --> 01:00:15.520
And well, this project was born.

01:00:15.520 --> 01:00:18.520
80 units were made.

01:00:18.520 --> 01:00:21.520
And they are all at Stonish Gamer.

01:00:21.520 --> 01:00:23.520
I don't think there will be more.

01:00:23.520 --> 01:00:25.520
I'm not saying this to say.

01:00:25.520 --> 01:00:27.520
It's being promoted as a limited edition.

01:00:27.520 --> 01:00:29.520
Because it kind of is.

01:00:29.520 --> 01:00:31.520
We won't do this because it's not a business.

01:00:31.520 --> 01:00:35.520
We are making like $5 on each.

01:00:35.520 --> 01:00:37.520
That's it.

01:00:37.520 --> 01:00:40.520
I just try to be open about it.

01:00:40.520 --> 01:00:46.520
It's not something to try and make money and support the project.

01:00:46.520 --> 01:00:49.520
Well, of course you support the project.

01:00:49.520 --> 01:00:51.520
Because we are making $5 out of it.

01:00:51.520 --> 01:00:53.520
If you buy it.

01:00:53.520 --> 01:00:56.520
But it's mostly a service for those that really want it and have it.

01:00:56.520 --> 01:01:02.520
And Stonish Gamer was generous enough to distribute it and publish it.

01:01:02.520 --> 01:01:06.520
So they have the stock in their store.

01:01:06.520 --> 01:01:08.520
That's fantastic.

01:01:08.520 --> 01:01:10.520
And it looks amazing.

01:01:10.520 --> 01:01:13.520
Yeah, I'm impressed of the quality of it.

01:01:13.520 --> 01:01:16.520
And of course you can also download the ROM for free.

01:01:16.520 --> 01:01:18.520
That's as always.

01:01:18.520 --> 01:01:20.520
I didn't mention it.

01:01:20.520 --> 01:01:24.520
But the 2 for 3P test suite is completely open source on their GPL.

01:01:24.520 --> 01:01:27.520
And the ROMs are all free.

01:01:27.520 --> 01:01:29.520
Yeah.

01:01:29.520 --> 01:01:31.520
And I love that.

01:01:31.520 --> 01:01:34.520
Again, we talked about open source earlier in the podcast here.

01:01:34.520 --> 01:01:36.520
So same thing here.

01:01:36.520 --> 01:01:43.520
Making this available for everyone to utilize is really important.

01:01:43.520 --> 01:01:46.520
And very, very nice to do as well.

01:01:46.520 --> 01:01:48.520
It's a very kind thing to do.

01:01:48.520 --> 01:01:50.520
To share this with the world.

01:01:51.520 --> 01:01:54.520
At least I could do it since I learned from Linux.

01:01:54.520 --> 01:01:56.520
And I learned from GCC.

01:01:56.520 --> 01:02:01.520
And I believe it's the way for things to grow.

01:02:01.520 --> 01:02:06.520
I understood early on that if it was to be a community project, I had to open source it.

01:02:06.520 --> 01:02:12.520
But it would simply be cloned and suppressed by something that was better.

01:02:12.520 --> 01:02:15.520
So by somebody that knew more.

01:02:15.520 --> 01:02:19.520
So I'd rather try and have it work for a community.

01:02:20.520 --> 01:02:22.520
I love that.

01:02:22.520 --> 01:02:29.520
I want to dive into the other open source project that you are currently working on.

01:02:29.520 --> 01:02:31.520
MD4 here.

01:02:31.520 --> 01:02:34.520
So tell us a bit about this.

01:02:34.520 --> 01:02:36.520
Because this is different.

01:02:36.520 --> 01:02:38.520
This is not a visual project.

01:02:38.520 --> 01:02:40.520
Well, it is visual.

01:02:40.520 --> 01:02:42.520
But it's not for video.

01:02:42.520 --> 01:02:44.520
Indeed.

01:02:44.520 --> 01:02:46.520
This is for audio.

01:02:46.520 --> 01:02:50.520
And again, inspired by Ryu.

01:02:50.520 --> 01:02:53.520
It's what retcons everything and works.

01:02:53.520 --> 01:03:01.520
This is a project that tries to document the audio signatures of game consoles.

01:03:01.520 --> 01:03:04.520
You can expand that and say of synthesizers.

01:03:04.520 --> 01:03:09.520
You can expand that and say audio cards or audio equipment in general.

01:03:09.520 --> 01:03:17.520
So the idea is to have a signal and generate it from the hardware that you want.

01:03:17.520 --> 01:03:20.520
And then compare it to something else.

01:03:20.520 --> 01:03:22.520
Okay?

01:03:22.520 --> 01:03:30.520
What this software allows you to or software tool set allows you to do is contrast two signals.

01:03:30.520 --> 01:03:33.520
And gives you the difference visually.

01:03:33.520 --> 01:03:40.520
So, for example, you have a Sega Genesis and you have a software emulator.

01:03:40.520 --> 01:03:42.520
Okay?

01:03:42.520 --> 01:03:47.520
You can record a tone generator signal from both of those.

01:03:47.520 --> 01:03:49.520
And contrast them with the computer.

01:03:49.520 --> 01:03:51.520
And it will tell you how they differ.

01:03:51.520 --> 01:03:53.520
If they are slower, if they are faster.

01:03:53.520 --> 01:03:55.520
If the pitch is different.

01:03:55.520 --> 01:03:57.520
Which is the same thing.

01:03:57.520 --> 01:04:02.520
And if the amplitudes are at different levels at different frequencies.

01:04:02.520 --> 01:04:10.520
So when it gets, I don't know, up to the higher tones, it's louder maybe.

01:04:10.520 --> 01:04:13.520
Or it's not properly reproducing that.

01:04:13.520 --> 01:04:20.520
But this term properly is against this reference that you put.

01:04:20.520 --> 01:04:22.520
The software is relative.

01:04:22.520 --> 01:04:25.520
And that's an important part to mention.

01:04:25.520 --> 01:04:27.520
There is no absolute thing here.

01:04:27.520 --> 01:04:32.520
You place what you want to compare to and what you want to compare against.

01:04:32.520 --> 01:04:33.520
Okay?

01:04:33.520 --> 01:04:36.520
So, it's completely objective.

01:04:36.520 --> 01:04:41.520
But it's relative in the terms of what you place as a reference standard.

01:04:41.520 --> 01:04:45.520
You can place a real Sega Genesis model 1 as a reference standard.

01:04:45.520 --> 01:04:48.520
Or you can place a software emulator as your reference standard.

01:04:48.520 --> 01:04:50.520
It's completely up to the user.

01:04:50.520 --> 01:04:51.520
Okay?

01:04:51.520 --> 01:04:54.520
Or you can place a model 2 with a Sega CD attached.

01:04:54.520 --> 01:04:57.520
And you want to contrast against that.

01:04:57.520 --> 01:04:58.520
Okay?

01:04:58.520 --> 01:05:01.520
And, again, that's up to you.

01:05:01.520 --> 01:05:05.520
As part of the design and as part of the philosophy.

01:05:05.520 --> 01:05:10.520
Because in the same way, we have tools inside Amphifuria.

01:05:10.520 --> 01:05:13.520
Where you have a perfect digital reference signal.

01:05:13.520 --> 01:05:16.520
And you can contrast an audio card recording to that.

01:05:16.520 --> 01:05:20.520
So you can tell how good the audio card is.

01:05:21.520 --> 01:05:27.520
Originally, I thought that was too presumptuous to really measure.

01:05:27.520 --> 01:05:29.520
But it's measurable.

01:05:29.520 --> 01:05:32.520
And we've detected differences in audio cards.

01:05:32.520 --> 01:05:36.520
And certain manufacturers have even changed their drivers.

01:05:36.520 --> 01:05:38.520
Thanks to this feedback.

01:05:38.520 --> 01:05:39.520
For our purposes.

01:05:39.520 --> 01:05:44.520
To get a proper audio card in a low budget scenario.

01:05:44.520 --> 01:05:47.520
It's not as easy as one would imagine nowadays.

01:05:47.520 --> 01:05:50.520
And the thing is, we found cards that were almost perfect.

01:05:50.520 --> 01:05:52.520
We submitted.

01:05:52.520 --> 01:05:54.520
We've tested with our custom software desk.

01:05:54.520 --> 01:05:57.520
And they changed the drivers and fixed that stuff.

01:05:57.520 --> 01:05:59.520
So it's been great as well.

01:05:59.520 --> 01:06:01.520
That's cool.

01:06:01.520 --> 01:06:03.520
Yeah, it's been really cool.

01:06:03.520 --> 01:06:09.520
The idea is to try and characterize audio signals from game consoles.

01:06:09.520 --> 01:06:13.520
So that emulators, FPGA implementations, what you have.

01:06:14.520 --> 01:06:16.520
Can properly, if they want to.

01:06:16.520 --> 01:06:21.520
Properly, again, imitate the audio signals of an original.

01:06:21.520 --> 01:06:26.520
So, again, this is intended to contrast the signals.

01:06:26.520 --> 01:06:28.520
So if somebody in an emulator.

01:06:28.520 --> 01:06:33.520
For example, I don't know, Mr. FPGA.

01:06:33.520 --> 01:06:37.520
Wants to imitate the Sega Genesis signal.

01:06:38.520 --> 01:06:43.520
They contrast the signal that's been generated by the Mr.

01:06:43.520 --> 01:06:47.520
When playing this Genesis Stones to a Genesis reference.

01:06:47.520 --> 01:06:49.520
In this case, a Model 1 or a Model 2.

01:06:49.520 --> 01:06:51.520
And they can check how they differ.

01:06:51.520 --> 01:06:52.520
Correct.

01:06:52.520 --> 01:06:53.520
Apply proper filters.

01:06:53.520 --> 01:06:56.520
And get that audio out.

01:06:56.520 --> 01:06:57.520
Okay.

01:06:57.520 --> 01:07:02.520
There are differences in philosophy here that can be argued, of course.

01:07:03.520 --> 01:07:08.520
For example, Mr. and Provenance MU have this idea or extremes.

01:07:08.520 --> 01:07:10.520
That they should simulate the full change.

01:07:10.520 --> 01:07:12.520
Like, if you have a Sega Genesis.

01:07:12.520 --> 01:07:14.520
Like, I don't know, this one.

01:07:14.520 --> 01:07:21.520
And you believe that the audio that comes out of this is your reference.

01:07:21.520 --> 01:07:26.520
Then you change, check against that.

01:07:26.520 --> 01:07:30.520
But that implies that there's a whole change inside the Sega Genesis.

01:07:30.520 --> 01:07:33.520
You have the audio chip, the Yamaha chip inside of it.

01:07:33.520 --> 01:07:35.520
That generates the pulses.

01:07:35.520 --> 01:07:38.520
It then passes through an amplifier and certain filtering.

01:07:38.520 --> 01:07:40.520
And goes out to that port.

01:07:40.520 --> 01:07:42.520
And there's analog filtering there.

01:07:42.520 --> 01:07:45.520
That analog filter serves different purposes.

01:07:45.520 --> 01:07:46.520
Right.

01:07:46.520 --> 01:07:51.520
There might be very high frequencies that are bothersome to some people.

01:07:51.520 --> 01:07:53.520
And they wanted to filter that out.

01:07:53.520 --> 01:07:54.520
And they did.

01:07:54.520 --> 01:07:55.520
Okay.

01:07:55.520 --> 01:07:57.520
And that might have been intentional.

01:07:57.520 --> 01:07:59.520
And you want to replicate that.

01:07:59.520 --> 01:08:00.520
Okay.

01:08:00.520 --> 01:08:04.520
That's why I believe some people think that Genesis simulation was so harsh.

01:08:04.520 --> 01:08:06.520
Back in the early 2000s.

01:08:06.520 --> 01:08:08.520
Because they were emulating those frequencies.

01:08:08.520 --> 01:08:11.520
And not filtering them out as the game console did.

01:08:11.520 --> 01:08:13.520
That makes sense.

01:08:13.520 --> 01:08:14.520
Yeah.

01:08:14.520 --> 01:08:18.520
And some people argue the other side.

01:08:18.520 --> 01:08:19.520
They say, no.

01:08:19.520 --> 01:08:22.520
I want to emulate what the chip does.

01:08:22.520 --> 01:08:26.520
And not filter out those frequencies that the game hardware does.

01:08:26.520 --> 01:08:27.520
I respect that.

01:08:28.520 --> 01:08:30.520
And we can also compare against that.

01:08:30.520 --> 01:08:33.520
You make a recording without the filtering.

01:08:33.520 --> 01:08:35.520
And contrast to your emulator.

01:08:35.520 --> 01:08:36.520
And you get that.

01:08:36.520 --> 01:08:37.520
Right.

01:08:37.520 --> 01:08:39.520
So, it serves both purposes.

01:08:39.520 --> 01:08:42.520
But there are different tendencies or philosophies inside of this.

01:08:42.520 --> 01:08:45.520
Right.

01:08:45.520 --> 01:08:53.520
Could this also be used to identify if there are any issues with older

01:08:53.520 --> 01:08:55.520
capacitors or stuff like that as well?

01:08:55.520 --> 01:08:56.520
Yes, of course.

01:08:56.520 --> 01:08:58.520
It's really interesting.

01:08:58.520 --> 01:09:03.520
If the capacitors are bad, there's going to be a difference in filtering.

01:09:03.520 --> 01:09:10.520
So, the thing is, of course, that you need a reference that models what you

01:09:10.520 --> 01:09:11.520
want to compare against.

01:09:11.520 --> 01:09:12.520
Right.

01:09:12.520 --> 01:09:14.520
What I mean.

01:09:14.520 --> 01:09:16.520
I mean that back when this project started,

01:09:16.520 --> 01:09:20.520
I was worried that every single Sega Genesis or Super Nintendo or NES out

01:09:20.520 --> 01:09:22.520
there would sound differently.

01:09:22.520 --> 01:09:24.520
And this project would be completely useless.

01:09:24.520 --> 01:09:25.520
Right.

01:09:25.520 --> 01:09:28.520
That the sensitivity of the tool was too much.

01:09:28.520 --> 01:09:32.520
And we ended up calibrating a way to get.

01:09:32.520 --> 01:09:36.520
And every single Sega Genesis in the world or Super.

01:09:36.520 --> 01:09:39.520
Well, let's get into the Super Nintendo thing later on.

01:09:39.520 --> 01:09:46.520
But every single Sega Genesis model 1 BA3 in the world sounds basically 99%

01:09:46.520 --> 01:09:48.520
identical to every single other one.

01:09:48.520 --> 01:09:53.520
So, when we understood that, measured several systems around the world.

01:09:53.520 --> 01:09:55.520
And they measured the same.

01:09:55.520 --> 01:09:56.520
Well, I was relieved.

01:09:56.520 --> 01:10:01.520
But we could also place a baseline that you can measure your Genesis against

01:10:01.520 --> 01:10:03.520
the records that we have that are out there.

01:10:03.520 --> 01:10:07.520
And you can tell if it needs a capacitor change.

01:10:07.520 --> 01:10:09.520
You can easily tell that.

01:10:09.520 --> 01:10:15.520
Also, while I was developing, I had this issue during summer where certain

01:10:15.520 --> 01:10:17.520
recordings started making no sense.

01:10:17.520 --> 01:10:18.520
And you know what it was?

01:10:18.520 --> 01:10:19.520
No.

01:10:19.520 --> 01:10:20.520
Temperature.

01:10:20.520 --> 01:10:22.520
Oh, that's interesting.

01:10:23.520 --> 01:10:28.520
It reached the point of 80 degrees Celsius that was above what the

01:10:28.520 --> 01:10:31.520
capacitors were rated for.

01:10:31.520 --> 01:10:34.520
I placed a fan and recordings matched.

01:10:34.520 --> 01:10:38.520
I removed the fan and recordings were a mess.

01:10:38.520 --> 01:10:40.520
That's really interesting.

01:10:40.520 --> 01:10:41.520
Yeah.

01:10:41.520 --> 01:10:45.520
And these 80 degrees were inside the console, right?

01:10:45.520 --> 01:10:47.520
When my room was at 30.

01:10:49.520 --> 01:10:51.520
That's pretty hot.

01:10:51.520 --> 01:10:59.520
So, having a fan on it helped and made it sound correct again.

01:10:59.520 --> 01:11:01.520
Not better, but correct.

01:11:01.520 --> 01:11:02.520
Exactly.

01:11:02.520 --> 01:11:04.520
That's really cool.

01:11:04.520 --> 01:11:05.520
Right.

01:11:05.520 --> 01:11:08.520
And, well, I mentioned the Super Nintendo.

01:11:08.520 --> 01:11:11.520
And Super Nintendo has a particular issue.

01:11:11.520 --> 01:11:15.520
And that's the reason it hasn't been released to the public, the Super

01:11:15.520 --> 01:11:16.520
Nintendo files.

01:11:16.520 --> 01:11:21.520
I've been slow on that because it's a mess explaining it.

01:11:21.520 --> 01:11:28.520
The thing is that, and let me share with you maybe a file about this that

01:11:28.520 --> 01:11:31.520
might be interesting for you.

01:11:31.520 --> 01:11:39.520
And this file shows how a Super Nintendo changes pitch when temperature

01:11:39.520 --> 01:11:41.520
changes.

01:11:41.520 --> 01:11:42.520
Oh.

01:11:42.520 --> 01:11:44.520
And I don't mean like 80 degrees, no.

01:11:44.520 --> 01:11:50.520
I mean very, very low temperatures, like 30 degrees, and it changes pitch

01:11:50.520 --> 01:11:53.520
very slightly, but measurably and demonstrably so.

01:11:53.520 --> 01:11:58.520
You can just raise and lower the temperature and the ceramic resonator

01:11:58.520 --> 01:12:01.520
that's in the Super Nintendo changes pitch with temperature.

01:12:01.520 --> 01:12:05.520
I'll share this file in the show notes.

01:12:05.520 --> 01:12:07.520
Yeah, sure.

01:12:07.520 --> 01:12:11.520
And this makes that every single Super Nintendo out there is going to

01:12:11.520 --> 01:12:14.520
sound slightly, very, very slightly different.

01:12:14.520 --> 01:12:20.520
And it will depend on temperature and probably pressure, of course, and how

01:12:20.520 --> 01:12:24.520
much time it's been on and what's the temperature of your room.

01:12:24.520 --> 01:12:29.520
And also, when we discovered this with MDFuria, we were like, wow, this is a

01:12:29.520 --> 01:12:30.520
huge discovery.

01:12:30.520 --> 01:12:33.520
And no, it was discovered like 20 years ago, the emulation community.

01:12:33.520 --> 01:12:35.520
We went into the notes.

01:12:35.520 --> 01:12:36.520
We figured it out.

01:12:36.520 --> 01:12:41.520
And they figured that they had to emulate the Super Nintendo like 40 hertz above

01:12:41.520 --> 01:12:46.520
what Spec mentioned because if they didn't, games crashed.

01:12:46.520 --> 01:12:51.520
And games crashed because games never ran at the stock speed because the

01:12:51.520 --> 01:12:55.520
ceramic resonator always was hotter than zero degrees.

01:12:55.520 --> 01:12:58.520
It never ran at 32 kilohertz.

01:12:58.520 --> 01:13:00.520
It always ran above.

01:13:00.520 --> 01:13:03.520
That's fascinating.

01:13:03.520 --> 01:13:09.520
And all emulators out there run at slightly higher speeds than what's spec'd,

01:13:09.520 --> 01:13:10.520
okay?

01:13:10.520 --> 01:13:14.520
Like 32 and 45 hertz, okay?

01:13:14.520 --> 01:13:17.520
32,045, that kind of thing.

01:13:17.520 --> 01:13:22.520
They agreed upon a number and that works.

01:13:22.520 --> 01:13:28.520
But the reality is that you could, I don't know, if somebody wanted to

01:13:28.520 --> 01:13:33.520
implement a proper Super Nintendo emulator with sound, which I know it makes

01:13:33.520 --> 01:13:34.520
no sense.

01:13:34.520 --> 01:13:35.520
It's just cool.

01:13:35.520 --> 01:13:39.520
You could place a slide bar that changes the temperature and with that model,

01:13:39.520 --> 01:13:41.520
the change in pitch of your Super Nintendo.

01:13:41.520 --> 01:13:46.520
So you could just have a thermometer in your mystery and register that and

01:13:46.520 --> 01:13:48.520
emulate the Super Nintendo at that temperature.

01:13:48.520 --> 01:13:50.520
That would be awesome.

01:13:50.520 --> 01:13:54.520
That is a completely unnecessary and amazing idea.

01:13:54.520 --> 01:13:56.520
I love it.

01:13:56.520 --> 01:13:59.520
It's like, yeah, what temperature is my Super Nintendo at right now?

01:13:59.520 --> 01:14:04.520
Let's emulate it at 40 degrees or 15 and it will sound differently.

01:14:04.520 --> 01:14:05.520
That's hilarious.

01:14:05.520 --> 01:14:07.520
I love it.

01:14:07.520 --> 01:14:08.520
Yeah.

01:14:08.520 --> 01:14:13.520
So I had to implement something in MD4EA to compensate for this, okay?

01:14:13.520 --> 01:14:17.520
Because no Super Nintendo that we ever recorded matched it, not even against

01:14:17.520 --> 01:14:19.520
itself.

01:14:19.520 --> 01:14:22.520
Because how do you keep temperature constant?

01:14:22.520 --> 01:14:30.520
So you would need to have a specific like temperature controlled environment

01:14:30.520 --> 01:14:31.520
essentially.

01:14:31.520 --> 01:14:32.520
You would.

01:14:32.520 --> 01:14:33.520
Yeah.

01:14:33.520 --> 01:14:34.520
Yes.

01:14:34.520 --> 01:14:36.520
What I did instead is play an eight kilohertz tone in the part of the

01:14:36.520 --> 01:14:42.520
signal and measure with Fourier transforms how off eight kilohertz that is.

01:14:42.520 --> 01:14:48.520
And based on that, I could guess the mate, approximate the speed at which that

01:14:48.520 --> 01:14:56.520
Super Nintendo is running and just lower the speed of that recorded in so much

01:14:56.520 --> 01:15:02.520
milliseconds so that they do match in pitch and I could compare them and it

01:15:02.520 --> 01:15:04.520
works.

01:15:04.520 --> 01:15:06.520
To a certain degree, of course.

01:15:06.520 --> 01:15:15.520
So then you get results like this that we're showing on screen here right now.

01:15:15.520 --> 01:15:17.520
Really pretty graphs.

01:15:17.520 --> 01:15:19.520
Can you tell us what we're looking at here?

01:15:19.520 --> 01:15:21.520
Yeah, sure.

01:15:21.520 --> 01:15:23.520
On the X axis, that's horizontally.

01:15:23.520 --> 01:15:27.520
You have a slightly greener line that says zero, okay?

01:15:27.520 --> 01:15:29.520
And in the vertical.

01:15:29.520 --> 01:15:31.520
But I mean, that's your axis, the zero.

01:15:31.520 --> 01:15:33.520
And that shows you frequency.

01:15:33.520 --> 01:15:38.520
On the left, you have low frequency like your base, like 20 hertz, subwoofer

01:15:38.520 --> 01:15:40.520
stuff.

01:15:40.520 --> 01:15:43.520
And on your right side, you have high frequency stuff.

01:15:43.520 --> 01:15:45.520
This is tweeter range.

01:15:45.520 --> 01:15:53.520
This is very high frequency signals or sounds like bell, that kind of thing.

01:15:53.520 --> 01:15:57.520
But on the mid, it's obviously the middle of that.

01:15:57.520 --> 01:16:01.520
But you have here around 100, 1 kilohertz.

01:16:01.520 --> 01:16:07.520
Human voice is on the center right part of that graph.

01:16:07.520 --> 01:16:10.520
So you have an idea of frequency range.

01:16:10.520 --> 01:16:16.520
And the default of MD4E is to graph based on standard or normalized human

01:16:16.520 --> 01:16:18.520
hearing.

01:16:18.520 --> 01:16:20.520
That's between 1 hertz and 20 kilohertz.

01:16:20.520 --> 01:16:25.520
That's what the average human can listen to.

01:16:25.520 --> 01:16:30.520
Most of us adults cut at 16, 17, maybe 14 kilohertz.

01:16:30.520 --> 01:16:33.520
That's up to how well you've treated on genetics.

01:16:33.520 --> 01:16:41.520
But the idea is to show standard view that has the human center of what you hear.

01:16:41.520 --> 01:16:49.520
And on the y-axis, you get amplitude, you get volume, you get how much they differ.

01:16:49.520 --> 01:16:51.520
It's not the volume of one console.

01:16:51.520 --> 01:16:57.520
It's the volume of the difference between those two recordings that you put in.

01:16:57.520 --> 01:16:58.520
Okay?

01:16:58.520 --> 01:17:00.520
So you're seeing here the difference between them.

01:17:00.520 --> 01:17:07.520
If there's no difference and there's a perfect match, the graph will be completely empty.

01:17:07.520 --> 01:17:08.520
Okay?

01:17:08.520 --> 01:17:10.520
Oh, interesting.

01:17:10.520 --> 01:17:12.520
That never happens, of course.

01:17:12.520 --> 01:17:15.520
There's always going to be a difference, even though it's light.

01:17:15.520 --> 01:17:17.520
So that's why it's kind of hazy.

01:17:17.520 --> 01:17:21.520
What you're seeing is the differences, not the matches.

01:17:21.520 --> 01:17:22.520
Okay?

01:17:22.520 --> 01:17:26.520
And also, you can see there's a scale to the left.

01:17:26.520 --> 01:17:39.520
And that scale, instead of going 3D, I figured that the color would represent how loud it was in the original signal.

01:17:39.520 --> 01:17:40.520
Okay?

01:17:40.520 --> 01:17:42.520
So how relevant it is.

01:17:42.520 --> 01:17:48.520
So the brighter spot is, it was more relevant in the signal that you placed as a reference.

01:17:48.520 --> 01:17:50.520
And there are different traces.

01:17:50.520 --> 01:17:53.520
You have a greenish one, a cyan one, and a yellow one.

01:17:53.520 --> 01:17:56.520
Each one of these is one of the synthesizers on the Sega Genesis.

01:17:56.520 --> 01:17:58.520
The green one is FM.

01:17:58.520 --> 01:18:02.520
The cyan one is, I believe, yeah, it's the noise.

01:18:02.520 --> 01:18:09.520
And the yellow one is the SPSG, the Sega Master System component of the synthesizer.

01:18:09.520 --> 01:18:18.520
So what it's telling us here, as you can see, the cyan and the yellow lines are around 3 dBs below the FM.

01:18:18.520 --> 01:18:32.520
That means that on that game console that was measured, the FM and the SPSG and noise on the reference one, they matched at the same level or a certain level.

01:18:32.520 --> 01:18:40.520
And on the comparison signal that you introduced, you're getting them lower by 3 dBs everywhere.

01:18:40.520 --> 01:18:41.520
Okay?

01:18:41.520 --> 01:18:49.520
So they have a different balance on that other game console or emulator than on the reference one that you placed.

01:18:49.520 --> 01:18:51.520
And the curve is also different.

01:18:51.520 --> 01:18:54.520
There's different filtering for SPSG than there's for FM.

01:18:56.520 --> 01:18:58.520
This is really fascinating.

01:18:58.520 --> 01:19:00.520
I need to play around with this as well.

01:19:00.520 --> 01:19:03.520
I haven't tried it yet, but this is really fascinating.

01:19:03.520 --> 01:19:05.520
It's fun.

01:19:05.520 --> 01:19:06.520
Yeah.

01:19:06.520 --> 01:19:07.520
It's really fun.

01:19:07.520 --> 01:19:09.520
Again, more tinkering.

01:19:09.520 --> 01:19:12.520
This is really interesting.

01:19:12.520 --> 01:19:14.520
Yeah, just measuring.

01:19:14.520 --> 01:19:21.520
So I have, obviously, a bunch of various systems here that I could try things out on.

01:19:21.520 --> 01:19:25.520
It's out right now for the Sega Genesis and the PC Engine.

01:19:25.520 --> 01:19:26.520
Is that right?

01:19:26.520 --> 01:19:30.520
In public terms, yes, but it's a lot more systems.

01:19:30.520 --> 01:19:34.520
It's out for even...

01:19:34.520 --> 01:19:36.520
Well, it's available for NES.

01:19:36.520 --> 01:19:39.520
It's available for Game Boy, Sega Master System.

01:19:39.520 --> 01:19:45.520
It's available for Genesis, Sega CD, PC Engine, Super CD-ROM, Super Nintendo, Sega Dreamcast.

01:19:45.520 --> 01:19:47.520
GameCube is not published yet.

01:19:47.520 --> 01:19:48.520
Either we...

01:19:48.520 --> 01:19:51.520
I do have it now, but I've not published it.

01:19:51.520 --> 01:19:54.520
Neo Geo, this version of the suite, does have MD4A.

01:19:54.520 --> 01:19:57.520
Every version of the suite includes MD4A.

01:19:57.520 --> 01:20:05.520
Yeah, so we have it for MBS, AES, Neo Geo CD, X68000, and the Irem M92 arcade PCB.

01:20:05.520 --> 01:20:06.520
Oh, wow.

01:20:06.520 --> 01:20:08.520
And the Dreamcast BMU, of course.

01:20:10.520 --> 01:20:16.520
Okay, so quite a few more than what's listed on the site right now.

01:20:16.520 --> 01:20:18.520
Yeah, yeah.

01:20:18.520 --> 01:20:21.520
These versions are available in the suite.

01:20:21.520 --> 01:20:25.520
What's not available is reference recordings.

01:20:26.520 --> 01:20:32.520
I don't have as much systems to have an analysis as deep as I did with the Genesis and PC Engine.

01:20:32.520 --> 01:20:34.520
That's basically the difference.

01:20:34.520 --> 01:20:36.520
So it's public. You can use it.

01:20:36.520 --> 01:20:45.520
But we don't have hundreds of recordings, maybe tens of recordings, to compare systems against and have a proper analysis.

01:20:45.520 --> 01:20:55.520
In the original MD4A documentation, I tried to use the Sega Genesis as a test case scenario of what you can do, right?

01:20:55.520 --> 01:21:12.520
And since I have like 20 systems, I could compare and change and contrast how a Model 2 changes, how a Model 1 version 6 changes, how placing a Sega CD changes the signal or not, how a CDX does things different, mixes channels different.

01:21:12.520 --> 01:21:15.520
But we kind of get an idea on how variations change.

01:21:15.520 --> 01:21:17.520
Same thing with the PC Engine.

01:21:17.520 --> 01:21:21.520
I have access to a lot of hardware, but not the same as Super Nintendo.

01:21:21.520 --> 01:21:28.520
We do have a basis of how Super Nintendo changes between revisions and the Mini, right?

01:21:28.520 --> 01:21:31.520
The Mini does change the curve a little.

01:21:31.520 --> 01:21:35.520
It has a different equalization and filtering.

01:21:36.520 --> 01:21:42.520
But it's very slightly different, and it's just a single synthesizer, so it's not as complex as the other scenarios, right?

01:21:42.520 --> 01:21:46.520
Same with the Dreamcast or the BMU.

01:21:46.520 --> 01:21:50.520
But the Neo Geo, I only have two AS systems, right?

01:21:50.520 --> 01:21:52.520
So what kind of data is that?

01:21:52.520 --> 01:21:56.520
I cannot publish like 100 recordings of things.

01:21:56.520 --> 01:22:00.520
That's why it's not in the same status as the others.

01:22:01.520 --> 01:22:03.520
Not because the software is not there.

01:22:03.520 --> 01:22:05.520
Software is there. Analysis is there.

01:22:05.520 --> 01:22:12.520
But we don't have as much recordings and an effort by the community to document every single system and contrast differences, right?

01:22:12.520 --> 01:22:17.520
Because getting audio capture equipment implies an investment.

01:22:17.520 --> 01:22:22.520
Not as big as one might think, but we're talking like $200, right?

01:22:22.520 --> 01:22:29.520
The lowest right now for a very good audio card that won't introduce its own filtering.

01:22:29.520 --> 01:22:34.520
So that's a big hurdle to make this bigger.

01:22:34.520 --> 01:22:42.520
And honestly, when I published this, I thought that the end user would be the most interested in having this and having these tools

01:22:42.520 --> 01:22:46.520
and measuring stuff and contrast and check how emulation is being done.

01:22:46.520 --> 01:22:48.520
But not. That didn't happen at all.

01:22:48.520 --> 01:22:50.520
I was too naive.

01:22:51.520 --> 01:23:00.520
What did happen was that emulator authors and FPGA core developers were the ones that were interested in this, right?

01:23:00.520 --> 01:23:05.520
To match it so that users won't want to go into it.

01:23:05.520 --> 01:23:08.520
I also wanted hardware manufacturers to use it.

01:23:08.520 --> 01:23:10.520
And it's been used to different extents.

01:23:10.520 --> 01:23:15.520
Like the triple bypass filter that's out for the Sega Genesis used to match it.

01:23:15.520 --> 01:23:17.520
The Sega Nomad triple bypass.

01:23:17.520 --> 01:23:19.520
The Mega Everdrive Pro, right?

01:23:19.520 --> 01:23:21.520
This hardware by Krikzz.

01:23:21.520 --> 01:23:23.520
I had it right here.

01:23:23.520 --> 01:23:25.520
Just when I got this.

01:23:25.520 --> 01:23:27.520
Again, not sponsored at all.

01:23:27.520 --> 01:23:34.520
Krikzz just got it and used it to match the Sega CD.

01:23:34.520 --> 01:23:36.520
And when he finished, he contacted us.

01:23:36.520 --> 01:23:40.520
It was not like, hey, help me model this.

01:23:40.520 --> 01:23:41.520
No.

01:23:41.520 --> 01:23:42.520
He did it all on his own.

01:23:42.520 --> 01:23:45.520
He released it and published the information, right?

01:23:45.520 --> 01:23:47.520
That's awesome.

01:23:47.520 --> 01:23:48.520
Yeah, that's awesome.

01:23:48.520 --> 01:23:50.520
He didn't need any support.

01:23:50.520 --> 01:23:52.520
He figured everything out.

01:23:52.520 --> 01:23:57.520
Xtrems also wanted to test different audio cables for the GameCube and the Wii.

01:23:57.520 --> 01:24:06.520
And he published a very expensive wiki that has all this information on contrasting differences and variations of GameCube cables,

01:24:06.520 --> 01:24:14.520
hardware, and HDMI encoders, and how they filter and change the audio in great differences.

01:24:14.520 --> 01:24:22.520
And, well, that's kind of how it ended up being used, even though I thought the users would provide their own recordings.

01:24:22.520 --> 01:24:29.520
But main showstopper is an audio interface to digitize audio, right?

01:24:29.520 --> 01:24:32.520
But we have now ways to check it.

01:24:32.520 --> 01:24:40.520
We have a test to check if your audio equipment is flat enough, transparent enough.

01:24:40.520 --> 01:24:46.520
And then providing that, we can take your recordings as valid hours, right?

01:24:46.520 --> 01:24:48.520
This has been super, super interesting.

01:24:48.520 --> 01:25:01.520
Thank you so much, Artemio, for coming here and talking on our podcast and showcasing the projects that you have been working on and what they can help us with.

01:25:01.520 --> 01:25:13.520
Both as a preservation organization, but also as an end user, making sure that our hardware is working correctly and that it looks as it should.

01:25:13.520 --> 01:25:17.520
So thank you so much for everything here.

01:25:17.520 --> 01:25:28.520
Do you have... I would like to invite you to share where people can find you and talk to you and find out more about your projects and also how they can support you.

01:25:29.520 --> 01:25:38.520
Oh, yeah. Well, first of all, thank you very much for the space and dedication to my work, the interest, because I know it's not easy.

01:25:38.520 --> 01:25:44.520
And I really, really appreciate and thank your time and interest in these areas.

01:25:44.520 --> 01:25:50.520
And even though I can't pronounce your name as well as you can pronounce mine, thank you, Jonas.

01:25:50.520 --> 01:25:56.520
And, well, people can find me on Twitter. That's Artemio.

01:25:56.520 --> 01:26:01.520
And Patreon, the Patreon of the 240p Test Suite is the main way to support us.

01:26:01.520 --> 01:26:05.520
You can also support these projects by donating while you download.

01:26:05.520 --> 01:26:12.520
The download is available at itch.io and you can use that and you can download it without any donation.

01:26:12.520 --> 01:26:17.520
But if you want to support, you can support on itch.io directly as well.

01:26:17.520 --> 01:26:22.520
And those are the main ways to contact me. And thank you very much.

01:26:22.520 --> 01:26:27.520
Fantastic. Thank you so much, Artemio. It's been a pleasure having you on today.

01:26:27.520 --> 01:26:33.520
And thank you, everyone, who's been listening and watching and hope to see you soon again.

01:26:33.520 --> 01:26:34.520
Have a great time. Bye.

01:26:34.520 --> 01:26:35.520
Have a great time.

01:26:47.520 --> 01:26:48.520
Bye.


