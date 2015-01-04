# Never Bet Against The Cheap Plastic Solution

Paul Graham wrote [an article](http://paulgraham.com/95.html) recently about
immigration and the tech industry. Matt Mullenweg wrote [a response]
(http://ma.tt/2014/12/how-paul-graham-is-wrong/) mentioning distributed teams
as a solution and there was [this thread]
(https://news.ycombinator.com/item?id=8811019) on Hacker News with additional
discussion about colocated versus distributed teams. Steven Sinofsky wrote
[a response to all of those](http://blog.learningbyshipping.com/2014/12/30/why-remote-engineering-is-so-difficult/).

I am not against changing immigration laws. If someone wants to move to Silicon
Valley from outside the country to work I think that is wonderful and they
should be allowed to do that. I do not, however, believe that the future of the
technology industry lies is colocated teams.

I have been working in the tech industry for twenty years modulo hiatuses for
creative projects. I have spent roughly half of that time colocated and half of
that time distributed. I do not have data to support what I am about to write;
even if data was available there well may not be enough of it yet. I am very
interested in having data about all of this.

Distributed teams are an innovation enabled by technology. Arguments of
authority--Google is not distributed, Facebook is not distributed, ask startup
founders why they do not use distributed teams--are ludicrous. Gather around let
me tell you about a little thing called disruption.

Would it not be tragic if you got the immigration laws changed and the best
programmers in the world looked at the quality of life in Silicon Valley, gave
it the middle finger, and started better companies wherever they damned well
pleased?

Because I have news for you. Those exceptional programmers are highly
intelligent individuals with significant left- and right-brain activity. They
have no interest in your strip malls and your commutes and your hole where the
culture is supposed to be. That is why they are moving north to San Francisco.
But, as you may have noticed, San Francisco is at capacity and is clearly not a
long-term housing solution. Shopping on craigslist right now I can get a house
half the size of the one I have here in Portland for $10k/month more. One
modest house I looked at had a move-in cost of $52,500.

I would not call myself a great programmer, but I do have moments when the Venn
diagrams of my experience align on a certain problem, are ignited by a spark of
creativity and the result is something that looks sufficiently like magic that
people who have seen it happen were probably impressed.

In college I saw a guy solve one of those Jumble puzzles in the paper with no
hesitation, he just opened up the page and whizzed through it. I said to myself
wow that's a smart fella. A couple of years later I told the story to our
mutual friend Daniel, saying wow I had not realized dude (I cannot remember his
name Rick or something) was so quick with word puzzles--he must be a pretty
smart fella. Twenty years later Daniel is visiting and tells me he ran into
Rick a while back. He told Rick my story about the Jumble and Rick laughed,
said he had done the Jumble in a different paper earlier in the day and was
trying to impress me.

Exceptional programmers are difficult to find. If we take it that exceptional
programmers are rare and key to success then it would seem incumbent on the
companies who need these individuals to maintain work environments that remove
barriers to working with them.

Harvard recently completed [a 75-year
study](http://en.wikipedia.org/wiki/Grant_Study) on human (male)
happiness. Their conclusion? It is all about love and warm relationships. Take
15 hours a week times 50 weeks times 20 years that's 15,000 hours--assuming one
is awake 16 hours a day that works out to about 3 years of one's life sitting
in traffic. Imagine instead applying those three years to warm relationships.

I, too, remember those initial attempts at outsourcing. We are not talking
about the days of hustlers getting contracts and then trying to staff them with
whatever bodies they could find. This is 2015; we have GitHub, Stack Overflow,
job boards for distributed teams, massive numbers of contributors to open
source projects. Today quality remote workers and companies can find and
evaluate each other directly.

The way I see it a lot of this comes down to synchronous versus asynchronous
communication. We started with synchronous communication. Webuilt empires on
synchronous communication, we developed techniques and processes and hardware
architectures all around this idea of synchronous communication. But as time
passed we realized what a drain of resources it is to always employ synchronous
communication so we started looking at asynchronous communication. Oh no! What
a disaster! We designed all the things for synchronous communication! As
technologists how did we approach this problem? Did we dig our heels in and
start screaming for more and more powerful hardware to keep the old ways
afloat? Yup.  How did that work out? It gave us a little breathing room but
then we had to put on our big kid pants and acknowledge the reality that we
could no longer continue to cram everything into one place and expect it to
scale. We had to change processes and the way we approach problems. And what
happened? We discovered better ways to do things. Not merely different ways or
almost-as-good ways, but better ways.

Asynchronous communication is efficient because senders do not have to wait for
a response. People choose text messages over phone calls for the same
reason. In 2015 we choose abstractions, languages and frameworks--functional
programming, actor systems, immutable data structures and so on--that support
asynchronous communication. But eventually we get to a point, for example
writing to a physical device, that requires synchronous communication.
Similarly while distributed teams choose tools and processes that support
asynchronous communication there are times when synchronous communication is
necessary. The day-to-day implementation of this can vary by team--team video
calls and 1-1 manager video calls and so on--but sometthing I believe
should not vary for long-running teams is getting together once or twice a year
for a few days on the company's time and dime to do something fun. Not a tech
conference or an all-hands work meeting but something fun. It does not have to
be a whitewater rafting excursion; getting together in a centrally-located city
and visiting museums is fine. There is a level of intimacy that only comes with
face-to-face interaction, but people do not have to work in an office together
for that to happen.

I believe a properly-run distributed team has more transparent and less siloed
communication and that that leads to better collaboration. This may be a
tortured analogy but I think of it like Facebook versus Twitter--you may have
more friend-to-friend bandwidth on Facebook but on Twitter everything is open
and transparent which leads to insights outside of one's circle of friends and
to the natural formation of groups of collaborators. Before I really "got"
Twitter I thought it sounded like a horrible idea--strangers following me and
me following other people just sounded creepy and there cannot be any depth
with this character limit and blah blah blah. It was not until I had to use it
for work that I really got that it was not a pale substitute for Facebook but
rather a genuine advancement in human consciousness and communication. This is
also how I feel about distributed teams.

A well-run distributed team primarily communicates via group text chat like
Slack. As much as possible all communication happens in various channels that
form by team or project or whatever fits best. Communication happens
asynchronously, transparently and is immutably logged. Conversations are not
lost or forgotten. People can be included in conversations more easily because
they can participate asynchronously. New group members can quickly be brought
up to speed on a given topic or issue by referring them to relevant logs. Cross
referencing code commits with tickets and publishing changes either directly to
a group's room or to a "newsfeed" room provides amazing documentation. If I
want to know why something was done I can look at the commit, find the ticket
and find all the relevant discussion about that, how the solution was worked
out--it may have required something beyond just code such as infrastructure
changes or contacting a service provider. Colocated teams can do this somewhat,
but there will always be large gaps that require relying on people's memories
of events to resolve.  Fitbit > trying to remember what happened. You may say
the need for this does not come up often and you would be correct, but when it
does come up it can save days or even weeks of time. It can be a lifesaver in
time-sensitive situations like production outages. It can help prevent service
regressions. As technologists we love data, we can learn from data, we can use
data to improve our processes.  Distributed teams produce more and richer data
about themselves and the work they do than colocated teams.

An industry embracing Big Data should look for ways to apply those insights to
itself.

As technologists we do not write blog posts imploring people to please go to
gyms because that is the best way to work out; instead we innovate and build
wearables that people can use to monitor and increase their activity and
fitness levels wherever they are. That is who we are and what we do. We are the
cheap plastic solution you should never bet against.
