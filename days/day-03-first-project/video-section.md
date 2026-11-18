# Day 3 — Your First Project: Make Claude Do Real Work

**Video slice:** `00:09:57` → `00:23:04`  
_(source: `transcripts /full transcript.md`)_

---

## Transcript

**[00:09:57,423 → 00:10:00,043]**
Alright, our initial setup is done. Now

**[00:10:00,063 → 00:10:02,893]**
let's go through and learn what Alex has to do.

**[00:10:03,033 → 00:10:05,033]**
So let's say Alex runs marketing

**[00:10:05,053 → 00:10:07,093]**
at a SaaS company. It's a small team,

**[00:10:07,113 → 00:10:08,373]**
so Alex has to do a lot of

**[00:10:08,393 → 00:10:10,573]**
different things in the company. And the

**[00:10:10,593 → 00:10:13,213]**
problem is that the CEO just told Alex,

**[00:10:13,233 → 00:10:15,833]**
hey, we're spending too much on paid ads. Pull

**[00:10:15,853 → 00:10:17,993]**
together the profit and loss and marketing

**[00:10:18,013 → 00:10:20,263]**
spend and come back tomorrow morning with a

**[00:10:20,283 → 00:10:22,343]**
presentation on where to allocate the

**[00:10:22,363 → 00:10:24,343]**
money. also find out how we can make more

**[00:10:24,363 → 00:10:26,263]**
money. Alright, so tomorrow morning

**[00:10:26,283 → 00:10:30,303]**
is not a lot of time. And there's data all over
the place. There's credit card statements,

**[00:10:30,323 → 00:10:32,733]**
there's platform receipts, there's revenue

**[00:10:32,753 → 00:10:34,803]**
coming in from five different places.

**[00:10:34,823 → 00:10:37,063]**
Subscriptions, annual plans, one off

**[00:10:37,083 → 00:10:38,553]**
setups, all these.

**[00:10:38,573 → 00:10:40,893]**
And the CEO expects a deck to match the brand

**[00:10:40,913 → 00:10:44,333]**
guidelines, probably. Alex needs

**[00:10:44,353 → 00:10:48,903]**
to pull all of this together, find where the
money is going, figure out what's actually

**[00:10:48,923 → 00:10:52,923]**
working, and build a presentation by
tomorrow morning. The end goal is clear.

**[00:10:53,103 → 00:10:55,533]**
A clear profit and loss breakdown.

**[00:10:55,553 → 00:10:57,843]**
Probably like a pie chart or something, to

**[00:10:57,863 → 00:10:59,793]**
show where the money is going,

**[00:10:59,813 → 00:11:01,823]**
and build a presentation and a deck to

**[00:11:01,843 → 00:11:03,783]**
recommend what to do next. Cool.

**[00:11:04,713 → 00:11:07,593]**
Now, Alex is gonna do this the right way.

**[00:11:07,613 → 00:11:09,953]**
And to do that, what he's gonna do is set up a

**[00:11:09,973 → 00:11:12,343]**
project, and then load in the context and then

**[00:11:12,363 → 00:11:14,879]**
start working from there.
So let's start doing that.

**[00:11:14,899 → 00:11:16,169]**
So now to set up project,

**[00:11:16,189 → 00:11:20,399]**
what I'm going to do is I'm going to open the
sidebar and then hit project right here.

**[00:11:20,699 → 00:11:23,189]**
And then I'm going to hit new project. Cool.

**[00:11:23,209 → 00:11:27,419]**
Let's call this PL for boss.

**[00:11:29,099 → 00:11:31,869]**
And let's say I'm trying

**[00:11:31,889 → 00:11:34,589]**
to create a PL and see where we should

**[00:11:34,609 → 00:11:37,149]**
allocate our bud budget for let's say the next

**[00:11:37,169 → 00:11:40,139]**
quarter. And simply we're going

**[00:11:40,159 → 00:11:42,519]**
to create the project. So there's a couple of

**[00:11:42,539 → 00:11:46,379]**
things I'm going to show you here, so you
understand what's happening. Alright?

**[00:11:48,025 → 00:11:49,945]**
And first of all, if you look here,

**[00:11:50,425 → 00:11:52,765]**
there is an instructions field.

**[00:11:52,785 → 00:11:55,375]**
So if I open that up, right now,

**[00:11:55,395 → 00:11:59,035]**
what we're gonna do is Include the right

**[00:11:59,055 → 00:12:01,495]**
instructions so Claude has the context.

**[00:12:01,515 → 00:12:05,295]**
Right. And every project has
a custom instructions field.

**[00:12:05,595 → 00:12:08,655]**
This is what Claude calls a system prompt.

**[00:12:08,865 → 00:12:11,345]**
And a quick explanation is a system

**[00:12:11,365 → 00:12:14,295]**
prompt is a set of instructions that gets

**[00:12:14,315 → 00:12:16,835]**
inserted before every single message we're

**[00:12:16,855 → 00:12:19,225]**
going to be sending to Claude. Every time

**[00:12:19,245 → 00:12:21,545]**
we type something into Claude inside the

**[00:12:21,565 → 00:12:24,795]**
project, this system prompt will go first

**[00:12:25,215 → 00:12:26,825]**
before Claude even sees what

**[00:12:26,845 → 00:12:29,395]**
we're sending it. Alright. This basically is

**[00:12:29,415 → 00:12:31,785]**
there to set the tone, the rules,

**[00:12:31,805 → 00:12:33,825]**
and the role before anything happens.

**[00:12:33,845 → 00:12:36,645]**
So when Alex types a question, Claude

**[00:12:36,665 → 00:12:39,195]**
actually sees the system prompt first.

**[00:12:39,285 → 00:12:41,475]**
Then Alice's message. This is why this

**[00:12:41,495 → 00:12:43,545]**
is so powerful. You write it once, and it

**[00:12:43,565 → 00:12:45,825]**
shapes every conversation automatically.

**[00:12:45,845 → 00:12:48,215]**
You don't have to keep saying be direct or use

**[00:12:48,235 → 00:12:50,235]**
bullet points. It's already there.

**[00:12:50,255 → 00:12:52,725]**
So for Alyx, let's write one.

**[00:12:53,685 → 00:12:56,185]**
Hey, I'm the marketing manager at

**[00:12:56,205 → 00:12:58,545]**
a B2B SaaS Company.

**[00:12:58,565 → 00:13:01,515]**
I need sharp data first answers,

**[00:13:02,985 → 00:13:05,895]**
lead with number the the number of findings,

**[00:13:06,585 → 00:13:08,715]**
and then the reasoning

**[00:13:08,985 → 00:13:11,265]**
in your response is use bullet points,

**[00:13:11,295 → 00:13:13,805]**
not long paragraphs, and when you give

**[00:13:13,825 → 00:13:15,885]**
me recommendations, give me the one you

**[00:13:15,905 → 00:13:18,565]**
actually believe, and do not hedge. Make

**[00:13:18,585 → 00:13:21,605]**
visualizations as much as you can to explain

**[00:13:21,625 → 00:13:24,435]**
what you need to match our brand voice,

**[00:13:24,455 → 00:13:26,865]**
be direct, confident, and don't add any flaw.

**[00:13:27,285 → 00:13:30,645]**
So this was just a basic one that I added.

**[00:13:30,665 → 00:13:33,435]**
Now every conversation

**[00:13:33,465 → 00:13:35,535]**
Alex starts inside this project,

**[00:13:35,775 → 00:13:37,845]**
Claude is going to see this,

**[00:13:37,865 → 00:13:40,275]**
and have this context loaded,

**[00:13:40,505 → 00:13:42,855]**
and it'll know how I like my responses.

**[00:13:42,875 → 00:13:44,165]**
So I encourage you to

**[00:13:44,185 → 00:13:46,635]**
go try it out for yourself, and then come back.

**[00:13:46,898 → 00:13:49,378]**
Okay, to make this a bit easier for the early

**[00:13:49,398 → 00:13:51,618]**
levels, what I'm gonna show you is let's

**[00:13:51,638 → 00:13:53,698]**
imagine Alex has compiled all

**[00:13:53,718 → 00:13:55,858]**
these documents that he may or may

**[00:13:55,878 → 00:13:58,178]**
not need to compile his report.

**[00:13:58,268 → 00:14:00,238]**
So I'm gonna take all these

**[00:14:00,258 → 00:14:02,408]**
documents and drag it here.

**[00:14:02,618 → 00:14:05,698]**
And you can see over time all these different

**[00:14:05,718 → 00:14:08,528]**
types of files are being ingested by Claude.

**[00:14:08,768 → 00:14:11,408]**
Great. So Claude now

**[00:14:11,738 → 00:14:13,958]**
has access to use these

**[00:14:13,978 → 00:14:16,058]**
files when I'm gonna be talking to it.

**[00:14:16,078 → 00:14:17,968]**
Okay, so now that the project

**[00:14:17,988 → 00:14:20,218]**
is created, and the instructions have been

**[00:14:20,238 → 00:14:22,418]**
loaded and the files have been uploaded, and

**[00:14:22,438 → 00:14:24,398]**
our memory has also been turned on,

**[00:14:24,548 → 00:14:26,478]**
Claude now knows our company,

**[00:14:26,498 → 00:14:27,918]**
the voice, the numbers,

**[00:14:27,938 → 00:14:30,768]**
and what we probably want. Now Alix would be

**[00:14:30,788 → 00:14:33,548]**
ready to build a thing like that PNL document.

**[00:14:33,568 → 00:14:36,378]**
So let's try and do that. Hey, I just

**[00:14:36,398 → 00:14:38,698]**
uploaded all of our credit card statements,

**[00:14:38,718 → 00:14:41,228]**
app platform receipts, revenue data.

**[00:14:41,588 → 00:14:43,618]**
What I want you to do is break

**[00:14:43,638 → 00:14:45,878]**
down the profit and loss for me, please.

**[00:14:45,968 → 00:14:48,108]**
Show me two pie charts, maybe,

**[00:14:48,128 → 00:14:50,028]**
one for revenue by source and one

**[00:14:50,048 → 00:14:52,238]**
for expenses by our channels, please.

**[00:14:55,028 → 00:14:57,378]**
And one thing I want to show you is you see

**[00:14:57,398 → 00:14:59,588]**
right here, it's selected as Opus.

**[00:14:59,918 → 00:15:01,388]**
But I know that I don't need

**[00:15:01,408 → 00:15:05,388]**
Opus right now. So I'm gonna hit Sonic
and I'm gonna hit go. And then I will wait.

**[00:15:05,472 → 00:15:07,312]**
And you can see Claude just working,

**[00:15:07,332 → 00:15:08,992]**
it's reading the ad spend data,

**[00:15:09,012 → 00:15:10,272]**
reading the meta ads,

**[00:15:10,292 → 00:15:12,822]**
all this stuff. And I'll just let us do a thing.

**[00:15:13,973 → 00:15:17,143]**
Okay, look at that. Now I can see two

**[00:15:17,163 → 00:15:19,663]**
interactive pie charts.

**[00:15:19,683 → 00:15:21,823]**
This is really cool, and this is what a new

**[00:15:21,843 → 00:15:24,063]**
feature Claude just introduced in their

**[00:15:24,083 → 00:15:26,383]**
chat function, where it can actually build

**[00:15:26,403 → 00:15:28,613]**
these visualizations in for you, right?

**[00:15:28,633 → 00:15:32,133]**
So anything you need to visualize or
understand, Claude Chat is a really

**[00:15:32,153 → 00:15:34,373]**
good place that you can be using, and I use

**[00:15:34,393 → 00:15:36,523]**
these in my YouTube videos a lot.

**[00:15:36,755 → 00:15:39,575]**
Great, so now just visualizing this data,

**[00:15:39,595 → 00:15:41,735]**
we can see that most of our money is

**[00:15:41,755 → 00:15:44,105]**
being spent on meta ads.

**[00:15:44,255 → 00:15:46,535]**
And most of our money is being made from

**[00:15:46,555 → 00:15:48,785]**
this monthly subscriptions. Cool.

**[00:15:49,025 → 00:15:53,015]**
So now I'd assume the next logical question

**[00:15:53,255 → 00:15:55,595]**
is to see if, hey,

**[00:15:56,555 → 00:15:59,015]**
are these meta ads really worth it?

**[00:15:59,645 → 00:16:02,175]**
Like the money we're spending. And what

**[00:16:02,195 → 00:16:04,415]**
are we getting per lead? So if I ask it,

**[00:16:04,925 → 00:16:09,635]**
hey, based on all this data, where are we right
now? What's actually working and what's not.

**[00:16:09,805 → 00:16:13,045]**
I want to know which channels per marketing

**[00:16:13,065 → 00:16:15,605]**
spend is bringing in the most lead, so we can

**[00:16:15,625 → 00:16:17,665]**
double down on that channel. Can you build

**[00:16:17,685 → 00:16:21,995]**
me some visualizations for that? Great, so I
just asked it to do that, and I'll let it load.

**[00:16:22,235 → 00:16:24,405]**
And what I want you to understand is

**[00:16:24,425 → 00:16:26,795]**
to get in this mode of thinking,

**[00:16:26,815 → 00:16:28,985]**
when you're just in level one or two,

**[00:16:29,165 → 00:16:31,525]**
of how you can just interact with the chat,

**[00:16:31,545 → 00:16:33,995]**
make it quickly inside the chat,

**[00:16:34,085 → 00:16:36,065]**
make visualizations for you,

**[00:16:36,085 → 00:16:38,565]**
read a lot of data, synthesizing it,

**[00:16:38,585 → 00:16:41,415]**
give you insights to save you a bunch of time.

**[00:16:41,548 → 00:16:44,588]**
So just spin it back out, and I can very clearly

**[00:16:44,608 → 00:16:48,118]**
see now how we're spending so much on meta ads.

**[00:16:48,898 → 00:16:51,628]**
27k, but getting back twelve hundred.

**[00:16:51,648 → 00:16:53,698]**
Whereas on stuff like YouTube,

**[00:16:54,328 → 00:16:58,918]**
we're spending 1350 and getting back 9600.

**[00:16:58,938 → 00:17:01,018]**
And blog and Instagram, all these.

**[00:17:01,198 → 00:17:03,388]**
And which means essentially

**[00:17:05,158 → 00:17:07,418]**
it's telling me what to do to double down on

**[00:17:07,438 → 00:17:09,658]**
Instagram organic, YouTube,

**[00:17:10,078 → 00:17:11,788]**
blogs, and what to cut.

**[00:17:12,268 → 00:17:15,328]**
This is really interesting. So now I think,

**[00:17:15,348 → 00:17:17,708]**
because AI has access to

**[00:17:17,728 → 00:17:20,368]**
analyze all that information, what I can do

**[00:17:20,578 → 00:17:23,128]**
is make sure now AI can take all

**[00:17:23,148 → 00:17:25,458]**
this data and then make me a presentation.

**[00:17:25,478 → 00:17:28,668]**
Okay, so now with all this data,

**[00:17:28,688 → 00:17:32,058]**
can you build me a presentation, an artifact,

**[00:17:32,418 → 00:17:34,718]**
based on our brand guidelines?

**[00:17:34,738 → 00:17:37,248]**
You can look it up from converti.ai,

**[00:17:37,368 → 00:17:39,708]**
cover all the profit and loss,

**[00:17:39,978 → 00:17:42,608]**
all the key findings, the recommendations,

**[00:17:42,628 → 00:17:44,448]**
and where to shift our budget to.

**[00:17:45,318 → 00:17:46,998]**
Make it clean, this is gonna be

**[00:17:47,018 → 00:17:48,978]**
presented to the CEO tomorrow.

**[00:17:49,368 → 00:17:51,808]**
Alright? Great. And I'm gonna hit enter.

**[00:17:52,693 → 00:17:55,093]**
Awesome, so it just got
done with these slides,

**[00:17:55,113 → 00:17:57,333]**
and I really like the color, it matched my

**[00:17:57,353 → 00:17:59,723]**
brand, and we can see it made a really nice

**[00:17:59,743 → 00:18:02,053]**
agenda where we're seeing a snapshot,

**[00:18:02,353 → 00:18:04,583]**
all the stuff, which ones are working,

**[00:18:04,603 → 00:18:08,713]**
key findings, and it's really made a very nice

**[00:18:09,553 → 00:18:11,963]**
summary and a story we can tell our boss.

**[00:18:11,983 → 00:18:14,563]**
Great, so now Alice doesn't have

**[00:18:14,583 → 00:18:16,963]**
to stress this just got done really

**[00:18:16,983 → 00:18:18,963]**
quickly. And let's say he would want

**[00:18:18,983 → 00:18:21,133]**
to present it, if I just hit this Google

**[00:18:21,583 → 00:18:24,763]**
docs button, then I can see right here

**[00:18:25,692 → 00:18:28,183]**
if I pull it here, it just pulls up my browser,

**[00:18:28,502 → 00:18:30,822]**
I can make edits to it if I want to,

**[00:18:30,842 → 00:18:32,923]**
and it already made

**[00:18:33,163 → 00:18:35,683]**
and put this slideshow in Google Slides.

**[00:18:35,863 → 00:18:38,142]**
So it's really really simple for Alyx to

**[00:18:38,162 → 00:18:40,673]**
present. So this is one good thing

**[00:18:40,943 → 00:18:43,612]**
that this Claude chat does, which

**[00:18:43,632 → 00:18:45,623]**
is create these type of artifacts.

**[00:18:45,983 → 00:18:48,662]**
And these artifacts are really really

**[00:18:48,682 → 00:18:51,743]**
useful for building stuff like dashboards,

**[00:18:51,833 → 00:18:54,473]**
charts, diagrams, any interactive stuff.

**[00:18:54,713 → 00:18:56,402]**
So for example, let's say we

**[00:18:56,422 → 00:18:58,193]**
want to like kick it up a notch.

**[00:18:58,373 → 00:19:02,813]**
What we can do is build maybe an interactive
tool that we can play with and present.

**[00:19:02,833 → 00:19:05,212]**
Rather than just having a slideshow. And I'll

**[00:19:05,232 → 00:19:08,622]**
show you how to do that. So can you build me an

**[00:19:08,642 → 00:19:11,753]**
interactive budget real allocation tool

**[00:19:12,053 → 00:19:14,452]**
that I can share with my CEO.

**[00:19:14,472 → 00:19:15,892]**
Maybe it's gonna show our

**[00:19:15,912 → 00:19:17,933]**
Q1 spending by channel.

**[00:19:17,953 → 00:19:20,033]**
Versus the recommended reallocation.

**[00:19:20,243 → 00:19:23,962]**
Let the user drag sliders to adjust the budget

**[00:19:23,982 → 00:19:27,262]**
split between paid ads and organic,

**[00:19:27,282 → 00:19:29,483]**
and showing real time the changes

**[00:19:29,783 → 00:19:32,792]**
that are projected to bring in leads,

**[00:19:32,812 → 00:19:35,592]**
conversions, and any cost per acquisition

**[00:19:35,612 → 00:19:38,663]**
based on our quarter one performance data.

**[00:19:38,873 → 00:19:41,153]**
Make it match our brand guidelines,

**[00:19:41,723 → 00:19:44,332]**
and the CEO should be able to play with these

**[00:19:44,352 → 00:19:48,743]**
numbers on the widget.

**[00:19:49,043 → 00:19:51,402]**
Okay. Great. So one more thing I want

**[00:19:51,422 → 00:19:53,642]**
to say is Sonnet is good for this,

**[00:19:53,662 → 00:19:55,712]**
but right now, this

**[00:19:55,732 → 00:19:58,313]**
is one big thing I need to make you understand.

**[00:19:58,333 → 00:20:00,803]**
And this is a limitation of the chat feature.

**[00:20:00,823 → 00:20:02,852]**
Where now let's say I wanted to go

**[00:20:02,872 → 00:20:04,763]**
to Opus or Haiku.

**[00:20:04,783 → 00:20:06,593]**
I can't do that because I'm

**[00:20:06,613 → 00:20:08,843]**
talking with this model directly.

**[00:20:09,653 → 00:20:12,022]**
But to do that, we're gonna be moving and

**[00:20:12,042 → 00:20:14,162]**
showing you in level 2 how that becomes

**[00:20:14,182 → 00:20:16,122]**
really useful. So I'm gonna for

**[00:20:16,142 → 00:20:18,293]**
this task, because it's a big task, and

**[00:20:18,313 → 00:20:20,542]**
it needs to code and do all of that stuff, I'm

**[00:20:20,562 → 00:20:23,152]**
gonna turn on extended thinking, and then I'm

**[00:20:23,172 → 00:20:26,333]**
gonna hit go and then wait for this to get done.

**[00:20:26,389 → 00:20:28,469]**
Alright, so now I see it build

**[00:20:28,489 → 00:20:30,469]**
this interactive tool with all these

**[00:20:30,489 → 00:20:33,289]**
sliders and what we can potentially project.

**[00:20:33,329 → 00:20:35,649]**
And if I want to share this with let's say my

**[00:20:35,669 → 00:20:37,539]**
CEO, I'm gonna go up here

**[00:20:37,559 → 00:20:39,649]**
and I'm gonna save as artifact.

**[00:20:40,459 → 00:20:42,169]**
Okay? And it just

**[00:20:42,189 → 00:20:45,209]**
says save this visual earlier as an artifact,

**[00:20:45,229 → 00:20:47,491]**
and it runs a new prompt. So I'll wait for that.

**[00:20:47,511 → 00:20:50,071]**
Awesome, so it's made it as an artifact.

**[00:20:50,091 → 00:20:52,741]**
Now I can play with it and see it right here.

**[00:20:53,251 → 00:20:55,281]**
But what I want to show you is if I want

**[00:20:55,301 → 00:20:57,481]**
to share this with the boss or anyone else,

**[00:20:57,501 → 00:21:00,301]**
I'm going to go to the top right, I'm gonna hit

**[00:21:00,691 → 00:21:03,501]**
publish artifact, and then

**[00:21:03,521 → 00:21:06,001]**
you're gonna see right here you can publish to

**[00:21:06,021 → 00:21:08,491]**
the web or just share with your team.

**[00:21:08,941 → 00:21:11,731]**
And this makes it really easy for you

**[00:21:12,251 → 00:21:14,781]**
to essentially build out really cool things

**[00:21:14,801 → 00:21:16,961]**
in Claude, and then actually

**[00:21:16,981 → 00:21:19,231]**
share this with people without having

**[00:21:19,251 → 00:21:21,681]**
to understand or know anything. So these

**[00:21:21,701 → 00:21:23,601]**
are just small widgets and tools, and

**[00:21:23,621 → 00:21:26,141]**
right here I just copied that and I pasted it.

**[00:21:26,291 → 00:21:30,361]**
And right here, you can see there is

**[00:21:30,381 → 00:21:33,851]**
a Claude artifact that anyone can play with.

**[00:21:34,281 → 00:21:36,121]**
You can see you can adjust these

**[00:21:36,141 → 00:21:38,111]**
sliders, and it's all good.

**[00:21:38,411 → 00:21:40,991]**
So this is a really cool tool,

**[00:21:41,011 → 00:21:43,541]**
and this is kind of 90%

**[00:21:43,601 → 00:21:45,835]**
of what the Claude chat function does.

**[00:21:45,855 → 00:21:48,342]**
And to show you a cool use case that I've been

**[00:21:48,362 → 00:21:50,762]**
using it personally a lot for. So in my clot

**[00:21:50,782 → 00:21:53,472]**
club, if I go to classroom and one of these,

**[00:21:53,622 → 00:21:55,952]**
you'll see right here I'll have a bunch of

**[00:21:55,972 → 00:21:58,162]**
these guides and which are essentially

**[00:21:58,182 → 00:22:00,082]**
clot artifacts that I've made for my

**[00:22:00,102 → 00:22:01,742]**
community members, so they can

**[00:22:01,762 → 00:22:03,552]**
follow an interactive

**[00:22:03,572 → 00:22:05,642]**
plan and do things in a really cool way.

**[00:22:05,662 → 00:22:07,262]**
Okay, so with that out of the way

**[00:22:07,282 → 00:22:10,390]**
Now Alex, let's say presents this

**[00:22:10,410 → 00:22:12,970]**
to his boss. And this is what happens next.

**[00:22:13,065 → 00:22:15,915]**
So Alex presented the deck to the CEO.

**[00:22:15,935 → 00:22:17,765]**
And he loved it. But now the

**[00:22:17,785 → 00:22:20,145]**
ask is, hey, can you do this for me every week.

**[00:22:20,165 → 00:22:22,695]**
I want a weekly marketing performance

**[00:22:22,715 → 00:22:24,825]**
report on my desk every Monday.

**[00:22:24,845 → 00:22:26,925]**
The thing is, Alex knows how to do it.

**[00:22:26,945 → 00:22:29,405]**
Level 1 proved that. But think about

**[00:22:29,425 → 00:22:32,025]**
what Alex has to do every single week.

**[00:22:32,045 → 00:22:34,115]**
The first problem is you have to go find

**[00:22:34,135 → 00:22:36,665]**
your credit card statements, download them,

**[00:22:36,685 → 00:22:38,445]**
and then go find the ad platforms.

**[00:22:38,465 → 00:22:42,605]**
All this data that you have to gather from
places, you have to drag that all into Claude,

**[00:22:42,625 → 00:22:44,605]**
that took like 20 to 30 minutes. And

**[00:22:44,625 → 00:22:47,085]**
it's gonna take him a lot of time every week.

**[00:22:47,415 → 00:22:48,975]**
Problem two is

**[00:22:48,995 → 00:22:51,295]**
it's the same prompt he has to run every time,

**[00:22:51,315 → 00:22:53,815]**
like break down the PL, cross-reference the

**[00:22:53,835 → 00:22:57,855]**
CRM data, and then build me a brand new
deck, all these things over and over.

**[00:22:57,875 → 00:23:00,045]**
We need to fix both these problems.

**[00:23:00,105 → 00:23:02,325]**
And to do that, we're gonna be graduating

**[00:23:02,345 → 00:23:04,365]**
into something called Claude Co work.
