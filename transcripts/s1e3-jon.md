# s1e3 - jon

**Steven Hicks:** [00:00:00] In this episode of A Developer Experience Podcast, I talk with my friend Jon Allured. Jon and I were colleagues at Artsy and also BFFs, and from the start, he wowed me with his habits and discipline. As you'll see in this episode, that might be a case of someone appearing to be a natural at something because they work very, very hard at it.

Thanks for giving it a listen.

**Jon Allured:** Okay, we gotta get to it. I have a lot of stuff to say to you. 

**Steven Hicks:** Okay, cool. So, Hey Jon. 

**Jon Allured:** Hey Steve. How is it going? I'm great. Do you want me to introduce myself? 

**Steven Hicks:** I would love for you to introduce yourself. 

**Jon Allured:** Okay. I am, hi, I'm Jon. I'm, Hi. Senior engineer at Artsy . I tech lead the Grow Team, and I've been here/there since 2017.

**Steven Hicks:** What's the grow team? 

**Jon Allured:** The Grow Team is a team that many companies have that they sort of talk about as being [00:01:00] like top of funnel. So the kinds of things that that type of team gets into is like new user signups, onboarding, even like SEO. You know, stuff that like happens in the first week of your life as a user at the product shop you're working at, those kinds of things.

Sure. You're trying to like grow the audience, that kind of thing. 

Totally. I made some more notes about myself. 

**Steven Hicks:** Oh, tell me.

**Jon Allured:** I've been a professional computer programmer since 2007. How many years is that? 15. That's like a long time I didn't realize. 

**Steven Hicks:** Do you feel old? 

**Jon Allured:** Well, I always feel old. I have a six year old.

But when I wrote that down, I, and yeah, did like the math, I was like, Wow, I've been doing this a long time. I've also done both consultancies and product shops. Which I think is fun. I actually came to Artsy from a consultancy gig, and so one of the reasons why I was interested in getting at Artsy and staying at Artsy is experiencing that like... that side that consultants don't always see of like [00:02:00] writing some code and living with it for four years. And like, yeah. Do my opinions about what's maintainable code change as I work at a product shop for a long time? So anyway, that's the kind of like pendulum swinging of my career. This time I'm on the product side. 

**Steven Hicks:** Yeah, I had the same experience, similar experience where I was like, I don't have to maintain anything I do. Yeah, that's weird. And feels kind of dirty to just like hand it off and never have to deal with the problems I just created. 

**Jon Allured:** Totally. One more bit of context I'll throw in here is that I start on the web and I've mostly done web in my career.

Rails is kind of my specialty, but I've also done a lot of native iOS work in Swift, so that's kind of my corner of the world. 

**Steven Hicks:** Awesome. Super important question about your personality. Did you wordle today? ? 

**Jon Allured:** I did. Jess and I, my wife and I send each other the score or whatever you call it, the thing that you can share at the end.

And she got it or no? I, I guess I got it first. And I got it in four today. 

**Steven Hicks:** Nice job. Congratulations. Did she beat you? 

**Jon Allured:** I think [00:03:00] she also got in four. It's funny when you compare the little pictures, hers is way different than mine. Yeah. But yeah, we did it. 

**Steven Hicks:** This is not a Wordle podcast.

**Jon Allured:** Did you? 

**Steven Hicks:** I did. I worded in three today.

It was a good day.

**Jon Allured:** And there was an X in today's puzzle. That's rough. 

**Steven Hicks:** It just came to me. 

**Jon Allured:** Can I tell you one of my techniques is to, as I'm trying to construct a word as my guess, put x's for the ones I'm not sure about as placeholders basically. So I know the P is here and the thing is here, but I'm not sure what the letters in the middle.

I'll type X's there so I can like visually get, 

**Steven Hicks:** Oh, I like it. 

**Jon Allured:** You know what I'm trying to say? So, but like today, when there actually was an X in the puzzle, that was kinda hard. 

**Steven Hicks:** Yeah. I mean, let's make a wordle podcast. Another time. 

So here's the thing that I want to ask you. Well the thing that we're gonna talk about is about how you get things done.

Maybe we put a pin in this for later, but maybe now is a good time to talk about it. You mentioned that you've done both [00:04:00] consultancy and product work. Are there any distinctions, any differences for you in terms of how you think about getting your, your stuff done in those two contexts? 

**Jon Allured:** Yeah, it's a great question.

So one thing I'll say is I've worked at a couple product shops. I've only worked at one consultancy, and the one consultancy I worked at actually had two stints. So Hash Rocket was the name of the consultancy. And what's notable about Hash Rocket is they pair all the time.

And so there are a few consultancies in this class where, You sort of like show up at the beginning of your day, you're theoretically pairing for your eight hours and then off you go. And so when it came to like getting things done, organizing your day, there were some like built in structures there that just are not what you experience at a product shop.

You can pair all day at a product shop, it's just very rare. We do some intermittent pairing at Artsy. But that sort of feeling of like you, you're on a client project and when you walk in the door to when you leave, you're kind of like trying to, you know, trying to bill that client for [00:05:00] that time.

And so, yeah, like I say, it just, it has a different feel. 

**Steven Hicks:** Yeah. Just to note, you may have only done one consultancy gig, but you were there for a long time, right? 

**Jon Allured:** That's right. Good amount of time.

**Steven Hicks:** Cool. Let's see. I think you kind of answered the question that I had here about the, anything about you or your history that makes your systems of working notable, actually with what we just talked about, but is there anything that you think you might add to that one? 

**Jon Allured:** Yeah, one more thought here was just, and it's something we've casually talked about before, that it's... funny or like surprising to me to be thought of as someone who's good at getting things done because yeah, I still kind of am stuck in like thinking of myself as high school Jon, where I was absolutely not organized and like didn't get things done.

And so I guess just to say that like, I really had to work at this. This is not something that came naturally or easy. 

**Steven Hicks:** Yeah. And not only past tense, right? Just, I don't think I'm putting words into your mouth, but this isn't a past tense thing. This is like a constant thing, like a practice that you have to keep up.

Like you're almost like you're running from something or something's [00:06:00] chasing you, and you just need to outrun it every day. 

**Jon Allured:** Yeah. I mean, I, I feel like if I was left to my own devices, and didn't introspect or try to get better at these things, I would like, have terrible habits. You know, so that's what I'm always running against.

It's like I will choose the lazy, procrastinate half-ass kind of thing. And so how do I set myself up to not do that and do the thing that I really want to do? 

**Steven Hicks:** Yeah. I mean, this is a super good transition into how do you do that? Like how do you keep yourself from choosing the lazy route? 

**Jon Allured:** Yeah. I mean, it's hard to articulate some of these things in like a unified way.

So maybe some examples could be a way in here. So I'll say that you know, my systems have evolved over time, even just in the few years that we've known each other. I'm currently on paper notebooks. I'm gonna hold one up to the screen here. It's by Field Notes. So this is a firm out of Chicago, the Chicagoland area.

They make these really cute little notebooks. You can sign up for a [00:07:00] subscription. I'm also not a paid advertiser for field notes, but anyway, and they'll send you these cute, really well produced notebooks. And so I'm on them right now and I just use them as like a way to jot down my to-do list basically.

So I've alternated between. OmniFocus, Todoist, like my own to-do apps and now and then I've also like done paper in my life and I'm back to feeling like that's the right thing for me right now. 

**Steven Hicks:** Yeah, that makes sense. I think that you are also, I think you also keep notes that are not related to like a to-do list, but notes about your day or maybe like journaling, keeping track of the problems that you've been working on. I think you also keep that digitally. Is that accurate? 

**Jon Allured:** Yeah, that's right. So I have this field notes notebook on my desk with a pencil to take quick notes, whatever. But I also keep what I call, because I like read a blog post about it once, my lab notebook. And lab notebook in the sense of, you know, that scientific method, the [00:08:00] like bench notebook if you're a chemist or something like that, and you're always jotting down the notes of kind of like the experience you're working on.

You just like have a running log. And that's kind of where I look at my lab notebook as. So this is a place where I might copy and paste in, you know, a snippet of code. Maybe I need, you know, something that I do a lot is like, Hey Jon, here's a CSV file of some data, please. You know, update these records with this new data, whatever.

And so I found in my career it's really great to like jot down what you did, make even some notes for yourself. You never know when you're gonna want to get that back. 

**Steven Hicks:** Yeah, exactly. It's really nice to go back in time and read those notes. Do you, so your paper to do list, is it really just a to-do list? Is that all it is? Do you use any like bullet journaling or anything fancy with that? Is it just like a list of things you have to do and you check 'em? 

**Jon Allured:** So I make, well, there's a couple answers to this question. So if you were to flip through this book, you'd see I make a page for each day and I put it in three sections, like a [00:09:00] T almost.

So the top of the T is like, when did I get up? What's the date? What time did I go to bed, whatever. Some meta information. And then down the one side is the things I'm gonna start my day doing. And then the other column is the things I'm gonna end my day doing. This is something that is a good habit for me of like start and stop lists.

So for example, and it's a little redundant, but like literally I write a to-do list that includes things like get dressed, take a shower, take my medicine, you know, unload the dishwasher, lay out my kids' meds, whatever. Like, just those sort of things. I find it quite energizing and gets me going if I'm crossing things off, even if they're things that are not super impactful.

And then I want reminders. At the end of the day, I wanna remind myself, look, if I run the dishwasher every night before bed, boy, it's really setting myself and my family up for success. The days that I don't do it, whatever. You know, lay out my clothes in the morning so when I get outta that shower, I'm just putting my clothes on and off I go.

So those kinds of observations about how I [00:10:00] can make my life a little bit faster, a little bit easier, I try to codify in a list. So the same kind of thing for work. I want to, when I start my work day, I wanna log my hours for the day. I want to, you know, sweep notifications, but I also want to check my calendar.

Am I prepared for all of the meetings I have today? Are there any meetings I can cancel? So anyway, like all of these built up kind of like habits, I try to write them. 

**Steven Hicks:** This start stop list is definitely a thing I've heard you talk a lot about. Now that you're on paper with these things, are you writing down the same things every single day for your start stop list?

**Jon Allured:** Yeah. 

**Steven Hicks:** How do you keep track of 'em? Like, do you have a template that you use? Do you just off the top of your head, write 'em down every single day? 

**Jon Allured:** I'll say this is kind of a new habit. Maybe in the last month or so, so I'm still kind of trying to figure it out. I think so far it's just been enough to just kinda like page back, look at the last day's list and kind of take it from there.

So I take that page to kind of have the snapshot of the day. But like, if you were to flip through, you also just see like, random lists, random notes. You know, one thing I [00:11:00] do, I like to have a paper notebook when I'm talking with a candidate, you know, if I'm doing any kind of interviewing and I literally just write down whatever comes to mind that stands out of what that person says, just to kind of help remember what they're saying, Feel engaged with that conversation. Do more active listening. So anyway, there's like a lot of,... I don't hold myself to any kind of like, only one kind of note can go in this notebook, all kinds of things. My kid likes to pick it up occasionally and draw a Pokemon that he's excited about.

So, you know, it's kind of like anything goes in there. 

**Steven Hicks:** Cool. Do you, do you have any sort of, I don't know, rules. Boundaries around how things move from one list to to the other? Like whether it's from your personal start/ stop list, your work start/ stop list or either of your start stop lists to your digital lab notebook, that kind of thing? Or vice versa? 

**Jon Allured:** Yeah, it's a good question. I mean, there are times when I pick up my physical notebook and I write my standup notes in there, but I do have a place in my [00:12:00] lab notebook for it. And I just try to like, not be concerned about that. 

**Steven Hicks:** Yeah. It doesn't bother you. 

**Jon Allured:** It's not that it doesn't bother me, it's that it would bother me if I don't work to like, try to not let it bother me.

The completionist in me or like the, it's,... I could very easily go down the rabbit hole of like, Oh, I can't, I can't do it. It's not in the right medium or something.

Okay. One more thing I wanted to say here in terms of tools. I used to use Todoist. I think I mentioned that. And one of the things I miss from Todoist is recurring items to do. 

**Steven Hicks:** Yeah. Yeah. So I witnessed you experience this. This was like a bad time for you. 

**Jon Allured:** Yeah, so right now I'm just using Apple Calendar app and going in there and making recurring meetings basically. I don't love this, but I'm trying it out. I haven't quite, I haven't quite figured out recurring things. 

**Steven Hicks:** Do you think it's better so far than when you were trying Todoist, does it feel like an improvement?

**Jon Allured:** It felt like recurring things were the only thing I was going to Todoist for.[00:13:00] 

And so in that sense, I just didn't open the app enough. You know, like I, when it comes to recurring things, it has to be built into your existing tools that you're using every day, or you could easily miss it. 

**Steven Hicks:** Got it. I think I maybe misunderstood. When you were trying out Todoist, and I think you mentioned Omni...

**Jon Allured:** Omni Focus.

**Steven Hicks:** Omni Focus, yes. Thank you. I was gonna say omni auth. I'm like, no, this doesn't have anything to do with authentication.

So when you were doing, when you were trying to use those tools, were you still also using your paper notebook? 

**Jon Allured:** No, this is when I was all digital. 

**Steven Hicks:** Okay. You were all digital. Okay. 

**Jon Allured:** When I made the move to go to paper, I pretty quickly was like, well, I'm just never gonna open Todoist again. But again, so then what am I gonna do with recurring things?

And the calendar was the only thing I could think of. It was like already kind of built into my systems. Cause I'm already having to look at that calendar all the time. 

**Steven Hicks:** Yeah, for sure. So it sounds like you spend a lot of time refining things and like, and making changes. How do you build in that [00:14:00] time, or how do you think about that time?

**Jon Allured:** I'm smiling because this is a habit that I shared with you after you started working at Artsy. And I don't think it ever really landed for you, but, so this is another one, like bumped into it on the internet, this idea of you should be sharpening your tools as a software engineering craftsman.

And I mostly think that that craftsman stuff is a bunch of horse shit. But on this one point, I agree with that movement that like, it's important to be good at the sort of, almost like the meta, So I'm talking about like being good at git, being good in your text editor. And for me that that includes setting aside, like literally going to my work calendar and putting an hour aside every Monday.

For an appointment called sharpening. So what this sharpen hour is for me is a couple things. One thing that's just routine, which is I run a few commands in my terminal to do things like upgrade my package manager. So for me, that's brew upgrade. Some other command line tools [00:15:00] to upgrade vim and all my vim plugins.

I do things like, I empty my screenshots folder. I clean up my desktop. I empty my trash can, you know, in the dock. It's like some file management. I check for free disk space on my machine to make sure I'm not almost running outta disk space. 

**Steven Hicks:** It's like hygiene stuff.

**Jon Allured:** Hygiene stuff. Totally. Yeah. And then also I have a list of like tasks. Have them maybe collecting or picking up. So if I observe something that could be improved about the way I work and I don't have time in that moment to address it, what I'll likely do is go to my dot files repo on GitHub and open an issue, and then I'll sweep those issues during my sharpen time looking for things to improve.

**Steven Hicks:** What is your dot files repo? Can you just give like a quick summary of what that is. 

**Jon Allured:** Yeah, so dot files is a, I don't even know how it's, it's like a mechanism..., what would you call it? It's like a, it's like a thing that a lot of Unix tools use. 

**Steven Hicks:** Kind of a standard. 

**Jon Allured:** It's a standard. That's a great way of saying it.[00:16:00] 

It's a standard that many Unix tools use to set aside your configuration. So for example, if you were to open up your Apple laptop and, and look into your home folder, you'd find a file that that starts with a dot that's like .bashrc for example. So bash the Shell can be configured using this file and you can put all kinds of little goodies in there.

Git is another common one. So there's a git config file and in there you can add aliases and tweak its settings any way you want. So a dot files repo is a collection of these kinds of dot files all in one place. So that were you to throw your laptop out the window, get another one, you could have it configured just to your specifications pretty quickly.

And so that's just kinda like the home for my ideas around like sharpening my tools. It's already where I'm thinking about tinkering with them. And so it's pretty natural to go there and add some kind of like, Hey, see if you can figure out how to, I don't know, like do this kind of thing and get, you know, I'm like observing that I'm always, [00:17:00] ...or like a good one was when we switched, so we had a new engineer start and advocate for different kinds of formatting in our pull requests on GitHub. And I was like, I know I can skip this for myself so I don't have to do a lot of typing like in the GitHub dot com interface, but instead all at the command line. So like, wrote myself some tools around starting pull requests, opening them with certain templates. Certain bits filled in. 

**Steven Hicks:** So you definitely use this sharpening time to do the technical types of refinement to your tools and processes. Do you also use that sharpening time to do something like, say this isn't working for me, I'm gonna scrap this and start with like a notebook and what would that look like?

Or how do you just make that decision to just like not do it anymore? And when do you figure out how, what you're gonna do next? 

**Jon Allured:** Yeah. That I mean, I think that would be fine things to occur during sharpened time. That's not how I've used it, but yeah. Like these kind of happened a little more organically than that.

I [00:18:00] wanted... one barrier for Todoist was, it wasn't helping me organize my personal life cuz I was only using it for work. And so what I wanted to move towards was something that was like, just organize myself all over the place. Stop trying to have any kind of separation between church and state in that regard.

So this has kinda helped me achieve that. I guess I had another thought here. Another way I kind of keep this all organized for myself is this thing I like to say where I only work in my office and I only work in my office, so to say. I don't work anywhere else in my house. And when I'm in my office, I don't play video games.

You know what I mean? So it's like I try to only work in my office and when I'm in my office, only do work.

**Steven Hicks:** Yeah. You work remotely. You have worked remotely at Artsy for I don't know how many years. 

**Jon Allured:** Since the beginning. Five years. Yeah. 

**Steven Hicks:** So five years? Is that what you said? 

**Jon Allured:** I've been working remotely since 2015.

**Steven Hicks:** Okay. So is that, I imagine that that's an [00:19:00] important part. Like, you know, in the last couple years we've all read millions of articles about what are the most important things about being remote if you've never done it before. Is that really important to you having that distinction, that separation between work and home?

**Jon Allured:** It's key. 

It's sort of like the habit that makes it all work for me. I mentioned some things in my personal life, including I have, you know, a wife and a kid and I just like, it would be irresponsible for me to do anything other than what I just described because it's just too easy for me to make poor choices that would impact their seeing their dad or seeing their husband.

And so one other thing I'll call out here is that I actually made a little app to help myself track my time and keep track of it. So this is like, I call up the app, I put in when I start, when I stop, and then I'll track PTO and whatever else. And my goal is to hit 40 hours even every week.

And so, Again, I'm building up some more habits around, okay, I'm only gonna work when I'm, when I'm in my [00:20:00] office and I'm trying to hit 40 hours a week. And kind of having those constraints just be like habits that make me feel good, like I feel good when I accomplish those things, has been a good foundation to build some of this stuff on top of.

**Steven Hicks:** So Jon, like when you say that you were surprised that people think of you as being very on top of your shit, I don't know how you can be surprised. I mean obviously whatever but that's why people think that you're on top of your shit is because you are so structured and so organized with that stuff and you're like the only person that maybe has those structures in place and sticks.

**Jon Allured:** Yeah, this is one that I, I might want to touch on a little bit with you. Just that like, you know, I really do a very good job with, with 40 and literally sticking to 40 hours a week. I have some passion there for a reason. I'm not quite sure I can articulate, but even this notebook, like I skipped a few days recently, I just like didn't feel like doing that thing at [00:21:00] the beginning of the day where I make the thing.

I didn't really do sharpening this week. I mean, we had yesterday off, whatever. And I have no guilt about it. Like I just don't, I just let it bounce right off of me that I set up systems, I set up all this stuff and I have some things that I'm just, for whatever reason, really click with me and I do consistently and others that I don't, and I just like do not give myself a hard time about it.

**Steven Hicks:** I love the idea of the guilt there or the lack of guilt. And you and I have talked many times about guilt and how it tends torule the things that we do. But I think the part that's more impressive to me than the fact that you don't have guilt about it is that you just get back on the wagon so quickly and easily, you know what I mean?

For me personally, if I go about three days without doing something that I know is important to, you know, my mental health and the processes that keep me from falling apart, it tends to snowball . And day four is worse, [00:22:00] and day five is really bad. And by like day seven, I'm like, I don't know what's going on in my life.

And it's awful. Everything's awful and I hate this and I don't know why. And I have to do some... you know, I've kind of changed. I'm, I'm a little up and down with how much I follow this, but I've tried to give myself a guidebook for getting myself out of these situations. And if I don't actually take some intentional time to consciously think about what are the things that I'm not doing that I should be doing, it's really hard for me to get back to them.

**Jon Allured:** Yeah. I don't have a good antidote for this and I definitely empathize with it. I think for me it's, Those times when I maybe don't follow my patterns or my systems the way I would like to, it's like, oh, that's the real me shining through. And like I just don't feel bad about it. It's just like, well, he got through a little bit like, you know, he's gonna do that , He's one of those little fuckers and you just gotta try to... [00:23:00] 

and then, you know, honestly, like a good night's sleep, waking up taking a shower, you know what I mean? Like just the,... so one of my wife's books talked about keystone events. Like, there are things you can do during your day that if you do them, it just sets you up to kind of keep making the right choices, to keep doing the things you know, that are good for yourself.

So I just can, if I can just hit a few of those keystones, then I find that it all, it all kind of starts lining up. 

**Steven Hicks:** Sure. Couple things. What Keystone events? It sounds like showering is one of them for you. 

**Jon Allured:** It's, it's such a, like a, maybe it's such an oddball thing to say, but Yeah.

Literally if I wake up and roll outta bed and then hit the shower immediately, it just sets the tone of my whole day. 

**Steven Hicks:** Yeah, that makes sense. I wonder, is this where I've heard people say and read things about like, if you make your bed every morning, it sets the tone for your day, or it's a win, or whatever.

I wonder if that's kind, if that's the same thing, if that's just saying, making the bed is [00:24:00] your keystone event.

**Jon Allured:** I think there's something there. 

Yeah, it's something has gotten internalized here, where if I do that one habit, I see myself just starting to kind of like, Okay, then I will probably eat breakfast at the right time.

I'll make my coffee, and then the dominoes of just like, Okay, I'm falling into the pattern of the things that are familiar and the things that work best for me. So if the prior day I didn't do some of those things and I got myself kind of off track you know, hopefully I can go to bed at a decent hour and then wake up at a decent hour and get back back on track.

**Steven Hicks:** Yeah. Yeah. I'm just in my head trying to think about what my keystone events would be in. I don't have much other than, other than getting a workout in and like that's, I feel like that's maybe some of it is a keystone event and some of it is also... I don't know. The effects of the workout are so important, so valuable and important to me that [00:25:00] maybe that just is what a keystone event is.

But I feel like there's an energy that 

**Jon Allured:** It's a keystone plus plus. 

**Steven Hicks:** Yeah. Yeah, for sure. It's got like some sort of modifier on it. 

The other thing I wanted to just say is back to the guilt conversation I was having trouble seeing this guilt as part of starting things back up.

But I don't know the way that you described it, it does make sense that whenever I do get in that situation, I am starting to snowball a little bit and things are getting a little bit bad. There is, it's not like I'm just saying to myself, Oh, I need to get back on the wagon. It's like, Oh, I need to get back on. I'm falling off. I always do this. I'm awful. So, yeah. Yeah, so that's interesting. 

**Jon Allured:** It comes so quick. 

**Steven Hicks:** That's gonna be something for me to think about. Yeah. Yeah. That's cool. 

**Jon Allured:** You know, again, like thinking about how we get things [00:26:00] done. I'm just very interested in being fast. So this impacts how I work and how I organize my day in a couple ways.

One of the things I think about when I think about speed is I've really tuned my dev environment, so I've been a loyal Vim user since 2011. I'm really all in on it. I hope I'll be able to continue to just use Vim forever. I think there's a big value in picking an editor.

It doesn't matter if it's vim or whatever you love, I'm just really getting expertly, expertly good at it. The other tool that I would categorize this way is tmux. So this is like a, a tool that makes a terminal session just the way you want. You can disconnect and reconnect.

So it's persistent in a way that you could actually even quit your terminal program and it would still be hanging out there for you to resume. So anyway, getting extremely good at some of those tools, I have found really pays off so that when I'm. You know, maybe someone's having experiencing a bug or there's an incident that's being experienced.

I can be interrupted. I can switch [00:27:00] into a different kind of problem space. Cause I maybe have that already booted up in tmux and I'm right back where I was. I can help that person and then return to my work. So it's actually, actually helps with interruption for me. Yeah, it's like the world stopped on this train of thought and I was able to just like move to this other train of.

Work on that and come right back to that first train of thought. Anyway, it's not that my tools are the only tools that allow this, but you should strive for tools that help you do that. 

**Steven Hicks:** Yeah, definitely. Is that a thing that happens to you often, those interruptions? 

**Jon Allured:** Yeah, I mean, definitely. My days as a tech lead include lots of meetings, so if nothing else, I'm often being interrupted by meetings.

But if you add in, you know, pairing requests or you know, just the normal activities that occur during the day, you know, maybe dipping into Slack. And so that's, yeah. Interruptions are part of. 

**Steven Hicks:** You're a tech lead. That's the job is being interrupted. 

**Jon Allured:** But so that's [00:28:00] one way you can think about fast.

Other things include, like, I'm pretty hooked on a task launcher called Alfred. There are many such tools. Maybe the first thing you learn about these kinds of tools is that you can hit hotkey, get a prompt, and then you can launch an application by typing its name. But they are often quite a bit more customizable.

For instance, you probably know, there are like plugins often and you maybe can get a plugin for Jira, so you can summon your Jira ticket a little faster, or you can get a plugin for GitHub and get to a GitHub issue faster. So I'm always thinking about like, how can I set myself up to be able to do those kind of, you know, those tasks we do all day, every day, but do 'em with fewer keystrokes, which is I think kind of a vim mentality applied to other tools. 

**Steven Hicks:** Definitely. But I don't think it's wrong. I mean, that's obviously not whatever, whatever editor is fine, but I think that there is value in the key strokes versus dragging your mouse across the [00:29:00] screen. And, I think, you know the amount of time that it takes to your point about speed, the amount of time it takes you to remember the command, like command option C or whatever it is that you're trying to do and hit those on your keyboard versus, Oh, I need to move my mouse cursor over to this part and click on this thing and click on this other thing.

I mean, that's like, not only is it an amount of time that it takes you to do that thing, but it's more of a distraction, and you're now thinking about where is my mouse going instead of what is the activity that I'm trying to do? 

**Jon Allured:** Yeah. So I mean, another way of saying this is closing the gap between thought and action .

So some people talk about this experience of using vim as like being able to move. Through your code, like at the speed of thought. And so that's maybe, No, that's definitely hyperbolic . But like striving for that kind of workflow again, whether it's Vim or your preferred editor or whatever the tool is.

I mean, Figma, sketch, doesn't matter what the tool is. What matters, it's like kinda having that [00:30:00] mindset. How can I get to a point where the gap between my thoughts and the thing I'm trying to accomplish, how can I close that gap? 

**Steven Hicks:** Yeah, for sure. It's reminded me of the conversation about Oh, I'm not gonna remember the phrases.

There's, there's like the two types of code. HTML is... declarative versus imperative. Declarative versus imperative code. So like you know, the declarative way of just saying, I wanna copy this line. Versus the imperative of like, I'm gonna drag the cursor over here, click on this thing, copy the line.

Which is kind of, I don't know, maybe a stretch, but it always comes back to code. 

**Jon Allured:** So another couple of thoughts on this topic are like don't repeat yourself as it applies to, like, shell commands. So for example, there's a very long command we issue to run a production rails console on some of our apps.

It includes a couple different flags. There's a lot of to remember. You [00:31:00] should, I think, notice that it's a awkward command to type and then probably try to figure out how to type it in fewer keystrokes or at the very least, get good at control-r. So this is like in command prompt, you can hit control-r and it'll search your history as you start typing keystrokes for a command that matches.

There's even an improved experience called fzf that I would encourage people to check out where it'll do fuzzy finding through your history. So anyway, the same idea of like, what can I do to move myself closer to, I know I've typed a command recently that would accomplish this goal. I'm not gonna type it again.

I'm not gonna try to futz with remembering it. I'm gonna try to summon it from my history. I do the same thing with Alfred cuz Alfred has a clipboard history manager. I would encourage everyone to get yourself into clipboard history management, because it's such a superpower. [00:32:00] Every time I copy anything, it's going into this queue.

And the password managers work, so you're not gonna have anything sensitive in there. But anyway everything from like IDs of users that I'm investigating and an artist's id, the slug, you know, a URL to a doc site, whatever, all that's in my history. And with a few simple keystrokes I can probably find it again. 

**Steven Hicks:** And your sharpening is like the time that you would notice that you're doing these things over and over and there's improvements that you can make to it. 

**Jon Allured:** Exactly. 

**Steven Hicks:** I wanna jump back a little bit. When we were talking about interruptions and you talked about how your tools enable you to, Basically jump away from what you're doing and then jump back to it more quickly and easily. How do you keep breadcrumbs to know where you were? You know what I mean? Like aside from just the editor comes up. You were in a train of thought. Is there anything that you do there? 

**Jon Allured:** Yeah, I mean, you know, for the case where it was really like, Stop the [00:33:00] world, I need to switch gears and do something. You don't necessarily have the benefit of leaving yourself those breadcrumbs. So sometimes you're just gonna have to kind of reboot your brain and there's may be some tricks there, but.

When I do have an opportunity to leave myself breadcrumbs, I do have a couple tricks. One of them is leaving yourself a red test. One of the best ways you can boot yourself back up when you return to a topic or a task or whatever you wanna call it, is by typing out what the next step would be in a test.

**Steven Hicks:** That test is failing at that point, right? Because you haven't actually made that part pass. 

**Jon Allured:** Yeah, and it can even be kind of a horse shit test, but if I see some red, my brain just starts wanting to complete it, wants to get it to go green. And so it kind of puts me back right into that problem solving mode.

And so if I can articulate the problem, even if again, the test isn't perfect, that's often a great way to kind of jumpstart the rebooting of the context into my brain. 

For other [00:34:00] things we can do to kind of get ourselves back into the frame of mind. Go back to the ticket you're working on and like read it again.

If there's like a slack thread that caused you to do the thing, go back and just start from the top and read that slack thread. These are great ways to just like, use reading as a way to... and so, because that's such a great thing to do, I often try to leave myself notes again in my lab notebook.

So hopefully when I was interrupted, I had a note maybe from a couple minutes ago giving myself some idea of what I was just thinking or what I was just doing. 

**Steven Hicks:** Yeah, kind of mixing that with the failing test approach, a thing that I often find myself doing, and I don't even think about it at all, is like literally just in my code, just writing a sentence, plain English, &quot;Steve, you are going to do this next.&quot;

And it totally doesn't compile, it's garbage, but it tells me exactly what I was gonna do, which is kind of nice. 

**Jon Allured:** Sometimes I'll write some pseudo code, and then write some English words, just as a way to kind of, again, get myself back into some kind of head space. 

**Steven Hicks:** For sure. I definitely think it's important to be [00:35:00] intentional when you do have to jump over to something else so that you do get back in there.

Cuz that's the hardest part for me is yeah, the spin up time. Ramp up time is always like, it kills me in everything. 

How are we doing? Is there any, are there other things that you wanna cover? 

**Jon Allured:** Let's keep going on interruptions and distractions. So there's one more thing, and it's something that actually Artsy does for us.

So, on Wednesdays at Artsy in the afternoon, we have something that we kind of call, like heads down time. And so the permission that we give ourselves is on Wednesday afternoons, you should quit Slack, you should quit email and you should work on something heads down and not, and... there's no expectation even hopefully of ourselves, that we're gonna be like super responsive. So another technique that I'm using to keep myself on task is trying to, even on a Monday, I'll start thinking of like, okay, what am I gonna work on Wednesday afternoon?

I'll start trying to collect tasks. I'll try to start thinking about like, what's the hardest thing I need to think about with [00:36:00] uninterrupted focus, you know, and kind of try to tee it up for a Wednesday. So if I think, Oh, this problem is a good problem for me to think about on this Wednesday, and really try to work on do I have any blockers, is there any questions I have, try to ask those Monday, Tuesday.

So when it comes time for Wednesday, I've kind of got all the things I need and I can just really start digging. 

**Steven Hicks:** Yeah, that makes a lot of sense. It's interesting. I hadn't really thought of it as a time where it was okay to turn off Slack. I've never done that on a Wednesday. I tend to ignore it, but I tend to ignore Slack pretty easily anyways, I set my notifications such that they don't really... It's not a push, it's a pull. Like when I have time to be updated, I'll go be updated. But for the most part, there aren't a lot of notifications that make their way through where I'm going to be interrupted with whatever it is that I'm doing. 

**Jon Allured:** That's great. And I wish I had more discipline there. I definitely am, am susceptible to Slack taking over. 

**Steven Hicks:** Yeah. Yeah, it's pretty easy to do, for sure. Yeah. 

**Jon Allured:** That's what I wanna say about [00:37:00] that one. 

**Steven Hicks:** Are there any other things that you wanted to touch on that we haven't touched? 

**Jon Allured:** Looking. I do have a timer on my desk that I use in a Pomodoro sense. Like literally having a physical object and it's kind of cool cuz it has like, as you spin, like a red pie chart timer. So there's like a physical red thing that I see in kind of the corner of my eye that shrinks as my timer is about to expire. And then, Just gonna silence it so it doesn't go off...

i don't always do Pomodoro. It's not always right for what I'm working on or whatever, but I, I do reach for that. 

**Steven Hicks:** Sure. When you do the Pomodoro, do you pretty much just do the time boxes, 25 minutes on, five minutes off? Or do you also start to look at it more holistically like tracking interruptions and trying to figure out you know, making changes to your flow or whatever to minimize those interruptions?

**Jon Allured:** That's a good question. I. Now [00:38:00] that you're forcing me to think about it, I think what I would do is put on do not disturb in Mac Os where like all the notifications be turned off so that,... I'm trying to basically say I'm, you know, basically quitting everything and focusing on a task for those minutes.

And then I would look back if I need to. When the timer goes off. 

**Steven Hicks:** One of the people that I've talked to for this show already talked about how he's pretty deep into Pomodoro, where he breaks his day down in terms of Pomodoros and thinks, I have these things, it's gonna take me three Pomodoros to do this.

And I'm gonna plan it for these three Pomodoros in the morning. Is that anything that you do? 

**Jon Allured:** No, I, like most engineers, I have a complicated relationship with the tasks I have and time and how much time they should take. And I guess what I mean by that is like, it's done when I say it's done a little bit, you know? I hold myself to a pretty high standard in terms of quality. I try to have good discipline around knowing when the refactoring is complete. We've talked about this a ton of times, but I don't give myself deadlines like that, like that would be [00:39:00] something I would never be able to tolerate.

It comes back to the guilt of you know, the self-induced guilt of just feeling bad because something's taking long. 

And I mean, I'm certainly not immune to that. I definitely feel, you know, I'm on the third day of that gravity PR refactor that I'm working on. Like, I don't feel great about it, but I know it's the right thing to do, and I try to include people, like bring people into my head.

So I'm not, you know, in the cave and I will bring back the code finished. So that I'm checking my assumptions. I'm hearing people say to me, Yeah, no, I see why you're choosing this and I agree with you, or whatever. 

**Steven Hicks:** Yeah. I think the longer it goes on, the more important it becomes to verbalize and socialize your status and what you're doing and where you're at. But also the harder it becomes to socialize and verbalize that stuff because you're like I feel like an idiot. 

**Jon Allured:** And like, honestly, this is the exception that, for me anyway, what I'm describing is the exception. Most of the time my tasks are on the hour to half [00:40:00] a day kind of timeline.

It's rare I work on a thing for multiple days. That's just where I'm at these days. 

**Steven Hicks:** Yep. If there's anything that you would add in regards to like the emotional, psychological effects of this kind of stuff, that would be great to hear. Anything you have there?

If you haven't already, I mean, like that's been sprinkled in all over the place. But if there was anything specific. 

**Jon Allured:** Yeah, I mean, I feel like, when the system is working well, when I feel like I'm being efficient and effective, I just feel happy. Like it makes me feel self actualized, you know?

And so that can be a good motivator to keep doing it. And I just try to not beat myself up when I'm not, you know, it's like, I try to not let the opposite get to me. I try to just get back to that that that good feeling. And this is something that I've struggled with throughout my career, that kind of holding the two in your head simultaneously, of I'm not a bad person if I don't [00:41:00] do this, but when I do this, I'm a good person. You know? It's like, trying to hold those two together is sometimes challenging.

I had two more points. One, and they're both maybe a little minor. One is I have to have, so Steve knows that I'm a Rubik's Cube fan and it's not actually cause I like solving the rubs cube, it's that I need something in my hands to take away my physical fidgety-ness.

So that I can focus on you, so you know that I'm actually really listening to you when you hear that Rubik's Cube going. Because then that means that I'm occupying my physical form and my mental energy can be directed towards what you're saying. So for those of you that find that that's true try to find something physical to do.

Steve, you've shared a habit about coloring. 

**Steven Hicks:** Yeah, that was working for me for a while. I currently don't have a coloring book here, but this topic keeps coming up this week. I mean, we, I've talked about it with my daughter who has talked about bringing a fidget cube to the school so that she can [00:42:00] focus on the teacher more.

I had this exact conversation yesterday, or maybe it was, it might have been Friday, with a couple other engineers about, what I've been doing lately is just like especially when I'm in a meeting that I have a hard time focusing on, and I'm not doing a lot of talking, I'm mostly listening, is just getting up, walking around and doing things around the house with my hands. Whether that's washing dishes or like you know, working on my bike or putting stuff away. And listening. And I find myself actually listening better in those cases. The people I was talking to, like they were talking about playing guitar with their fingers or you know, just all sorts of things.

I fidget like crazy, but if I'm not fidgeting, I'm not listening. 

**Jon Allured:** Right. I'm barely hanging on. 

I purchased a standing desk during the pandemic and that's been actually pretty helpful too. I find that I can do a lot better paying attention when I'm not like slouching and sitting. I don't know. Something about standing. It just, it doesn't seem like it'd be that much of a difference. I'm telling you, it's a big difference. 

One more thing I wanna plug here is a [00:43:00] book called Tiny Habits. This is just another one of those self health books. This one really landed for me though.

It takes a pretty cool approach where you're like designing your life. That really landed for me. If you're interested, you should check it out. 

**Steven Hicks:** Cool. Yeah, I'll definitely dig that one up and put it in notes. This is Awesome. 

**Jon Allured:** Thanks.

**Steven Hicks:** Thanks for listening to this episode of A Developer Experience Podcast, and thanks to my guest, Jon Allured. Love you buddy. Jon's website is jonallured.com. That's J O N A L L U R E d. If you like the show, support it at the podcast home, anchor.fm/a- developer- experience. I'm Steve Hicks.

Check stevenhicks.me/where to find me on the internet. Take care friends.[00:44:00] 

**Jon Allured:** Always be recording. How's my gain? 

**Steven Hicks:** I don't know. Say something loud. 

**Jon Allured:** Hello? Hello. Hello. 

**Steven Hicks:** You're great. I don't know how you do that. 

**Jon Allured:** Huh? 

**Steven Hicks:** I don't know how you do that. 

**Jon Allured:** Have good gain? 

**Steven Hicks:** Yeah. 

**Jon Allured:** Josh told me to turn this knob down, and so I just did it, And I had good gain. 

**Steven Hicks:** Sick gain. 

**Jon Allured:** Sick gain. Yep.

