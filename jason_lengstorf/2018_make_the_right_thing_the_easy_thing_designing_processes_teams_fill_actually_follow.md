# Make the Right Thing the Easy Thing: Designing Processes Teams Will Actually Follow (2018-05-21)

![alt Make the Right Thing the Easy Thing: Designing Processes Teams Will Actually Follow](img/xqT8e6_yzLg.jpg "Make the Right Thing the Easy Thing: Designing Processes Teams Will Actually Follow")

## Description

When we work alone, it’s easy to make sure things come out the way we think is best. But what happens when we need to get an entire team to agree on — and actually _use_ — best practices? What if we have to convince an entire _company_?

In this talk, we’ll learn how IBM is working to get huge, distributed teams to not only agree on a set of best practices but to actually follow them, leading to:

* Improved developer experience and engagement
* Increased velocity
* Decreased technical debt
* Higher reliability
* Broad adoption of best practices
and many more improvements in team cohesion and quality
Learn battle-tested strategies and techniques that will benefit companies of any size, helping create teams that are more engaged, more effective, and more cohesive.

## Transcript

[0:00:11](https://youtu.be/xqT8e6_yzLg?t=11) [Laughter] I actually plan technical difficulties at the beginning so I get an extra round of applause.  
[0:00:19](https://youtu.be/xqT8e6_yzLg?t=19) >> So my name is Jason like she said and I
am here to talk about teamwork.  
[0:00:26](https://youtu.be/xqT8e6_yzLg?t=26) And specifically about processes in teamwork.  
[0:00:29](https://youtu.be/xqT8e6_yzLg?t=29) So the reason that I think this is important
is that as we've heard over and over again  
[0:00:34](https://youtu.be/xqT8e6_yzLg?t=34) today, management aren't the only people leading,
and really, the vast majority of leadership  
[0:00:39](https://youtu.be/xqT8e6_yzLg?t=39) that I've seen in large organizations tends
to come from the developers, people who are  
[0:00:45](https://youtu.be/xqT8e6_yzLg?t=45) in the code.  
[0:00:46](https://youtu.be/xqT8e6_yzLg?t=46) So so I actually believe that the lead developers
on the team are the one that keep the team  
[0:00:53](https://youtu.be/xqT8e6_yzLg?t=53) running.  
[0:00:54](https://youtu.be/xqT8e6_yzLg?t=54) Management is there to make sure that people
have individual goals, that people feel taken  
[0:00:58](https://youtu.be/xqT8e6_yzLg?t=58) care of, that they feel safe.  
[0:00:59](https://youtu.be/xqT8e6_yzLg?t=59) Developers, lead developers are the ones who
are actually looking after the project.  
[0:01:03](https://youtu.be/xqT8e6_yzLg?t=63) So we want to make sure that we're keeping
the wheels on and not just leaving people  
[0:01:09](https://youtu.be/xqT8e6_yzLg?t=69) to, you know, bask in our brilliance as the
lead dev on the team.  
[0:01:15](https://youtu.be/xqT8e6_yzLg?t=75) Show that brings us to a question.  
[0:01:17](https://youtu.be/xqT8e6_yzLg?t=77) When a pressure is on with a project, we tend
to get left with two choices and sometimes  
[0:01:22](https://youtu.be/xqT8e6_yzLg?t=82) it doesn't actually feel like two choices,
it feels like one.  
[0:01:25](https://youtu.be/xqT8e6_yzLg?t=85) So the first choice is to attempt to fix the
process and I don't know if anybody saw this  
[0:01:30](https://youtu.be/xqT8e6_yzLg?t=90) when it went viral however long ago.  
[0:01:34](https://youtu.be/xqT8e6_yzLg?t=94) It's by a band called winter gotten, I think
it's called and it's a Rub Goldbergesque marble-powered  
[0:01:41](https://youtu.be/xqT8e6_yzLg?t=101) instrument.  
[0:01:43](https://youtu.be/xqT8e6_yzLg?t=103) If that broke I do not want to be the person
who goes in and tries to figure out where  
[0:01:48](https://youtu.be/xqT8e6_yzLg?t=108) in the process things broke down and that's
a lot of what legacy code, big enter price  
[0:01:52](https://youtu.be/xqT8e6_yzLg?t=112) code can feel like.  
[0:01:53](https://youtu.be/xqT8e6_yzLg?t=113) you are looking at a Java monolith, the last
thing you want to do is go in and fix it.  
[0:02:00](https://youtu.be/xqT8e6_yzLg?t=120) So you.  
[0:02:03](https://youtu.be/xqT8e6_yzLg?t=123) Typically this is the default to go and fix
the problem instead of trying to figure out  
[0:02:07](https://youtu.be/xqT8e6_yzLg?t=127) what went wrong in the first place.  
[0:02:09](https://youtu.be/xqT8e6_yzLg?t=129) To me there's a very logical reason for that.  
[0:02:13](https://youtu.be/xqT8e6_yzLg?t=133) It feels extremely good to be the team rockstar.  
[0:02:19](https://youtu.be/xqT8e6_yzLg?t=139) When you finish a project on time because
you stood up in front of your team and you  
[0:02:24](https://youtu.be/xqT8e6_yzLg?t=144) just produced a miracle on demand, that's
one of the best feelings that you can get  
[0:02:29](https://youtu.be/xqT8e6_yzLg?t=149) as a developer, right?  
[0:02:32](https://youtu.be/xqT8e6_yzLg?t=152) As a human to be like the one who saves the
day, that's a great feeling.  
[0:02:36](https://youtu.be/xqT8e6_yzLg?t=156) It also feels a lot better than being the
team's auditor, because digging into the underlying  
[0:02:43](https://youtu.be/xqT8e6_yzLg?t=163) cause, where the efficiencies broke down,
this is not typically what we consider a good  
[0:02:49](https://youtu.be/xqT8e6_yzLg?t=169) time.  
[0:02:50](https://youtu.be/xqT8e6_yzLg?t=170) And it's also really hard to communicate why
this sort of thing is important, you know?  
[0:02:54](https://youtu.be/xqT8e6_yzLg?t=174) When we're rockstarring, we're doing things
that get us public praise, we get promotion,  
[0:03:00](https://youtu.be/xqT8e6_yzLg?t=180) we get raises, people are talking about us
in meetings, they pat us on the back because  
[0:03:04](https://youtu.be/xqT8e6_yzLg?t=184) we stayed up all weekend to hit this deadline,
where the team auditor oh, God, he's coming  
[0:03:08](https://youtu.be/xqT8e6_yzLg?t=188) in here again, he's going to tell me that
I did something something wrong.  
[0:03:13](https://youtu.be/xqT8e6_yzLg?t=193) Nobody wants to see the team auditor, right?  
[0:03:18](https://youtu.be/xqT8e6_yzLg?t=198) When you're trying to explain to somebody
why it's valuable to go back and review a  
[0:03:24](https://youtu.be/xqT8e6_yzLg?t=204) process, people are going to say, yeah, yeah,
we'll worry about that later.  
[0:03:37](https://youtu.be/xqT8e6_yzLg?t=217) We tend to focus on putting out immediate
fires, not on fixing things that could potentially  
[0:03:41](https://youtu.be/xqT8e6_yzLg?t=221) be a huge problem in the future.  
[0:03:44](https://youtu.be/xqT8e6_yzLg?t=224) The problem, though -- and this is the biggest
problem that I found in my career as a lead  
[0:03:49](https://youtu.be/xqT8e6_yzLg?t=229) dev, is that rockstars don't get days off.  
[0:03:54](https://youtu.be/xqT8e6_yzLg?t=234) If you as a developer are the only reason
that your team is hitting their deadlines,  
[0:03:59](https://youtu.be/xqT8e6_yzLg?t=239) there's a huge problem on your team.  
[0:04:01](https://youtu.be/xqT8e6_yzLg?t=241) And that problem typically gets called the
bus factor.  
[0:04:06](https://youtu.be/xqT8e6_yzLg?t=246) And the bus factor is kind of a joke that
it talks about the number of people who can  
[0:04:14](https://youtu.be/xqT8e6_yzLg?t=254) be lost on a given team before the entire
codebase falls apart and nobody knows how  
[0:04:18](https://youtu.be/xqT8e6_yzLg?t=258) it works anymore.  
[0:04:20](https://youtu.be/xqT8e6_yzLg?t=260) And -- sorry, I -- I'm going to get away from
-- it's too much.  
[0:04:25](https://youtu.be/xqT8e6_yzLg?t=265) Let me get away from that slide.  
[0:04:27](https://youtu.be/xqT8e6_yzLg?t=267) [laughter]  
[0:04:29](https://youtu.be/xqT8e6_yzLg?t=269) I thought that was funny when I got it and
now that I'm watching it on loop, I'm like,  
[0:04:32](https://youtu.be/xqT8e6_yzLg?t=272) geez, this is violent.  
[0:04:34](https://youtu.be/xqT8e6_yzLg?t=274) [laughter]  
[0:04:35](https://youtu.be/xqT8e6_yzLg?t=275) So the point of the bus factor, it's also
called the lottery number, the truck factor,  
[0:04:40](https://youtu.be/xqT8e6_yzLg?t=280) is if you're working on a team where there's
a single point of failure and that point of  
[0:04:45](https://youtu.be/xqT8e6_yzLg?t=285) failure is you, you are on a lot of trouble
because if you want to go on vacation or you  
[0:04:51](https://youtu.be/xqT8e6_yzLg?t=291) take a promotion or you want to quit and move
jobs, your whole team is screwed, that whole  
[0:04:59](https://youtu.be/xqT8e6_yzLg?t=299) piece of code that your team owned is a complete
loss if you are gone.  
[0:05:05](https://youtu.be/xqT8e6_yzLg?t=305) And so I actually recently left IBM.  
[0:05:10](https://youtu.be/xqT8e6_yzLg?t=310) While I was there, some of the projects that
we had, were these big monolithic pieces and  
[0:05:16](https://youtu.be/xqT8e6_yzLg?t=316) we inherited one of these, and when we inherited
it, they were like, OK, you're going to be  
[0:05:20](https://youtu.be/xqT8e6_yzLg?t=320) taking over this micro-service, you should
go talk to this guy, and he will get you on  
[0:05:26](https://youtu.be/xqT8e6_yzLg?t=326) board and we're like, great, who do we talk
to if things break.  
[0:05:29](https://youtu.be/xqT8e6_yzLg?t=329) And they're like, you should talk to this
guy, because his last day is in three days  
[0:05:32](https://youtu.be/xqT8e6_yzLg?t=332) and he's the only one who's ever worked on
it.  
[0:05:35](https://youtu.be/xqT8e6_yzLg?t=335) OK, this is a core part of a very business-critical
peeps of code.  
[0:05:42](https://youtu.be/xqT8e6_yzLg?t=342) So the bus factor for that code was one and
what we ended up doing is doing our absolute  
[0:05:48](https://youtu.be/xqT8e6_yzLg?t=348) best to keep the fires to a minimum while
we completely rewrote the code because nobody  
[0:05:52](https://youtu.be/xqT8e6_yzLg?t=352) knew how it worked.  
[0:05:56](https://youtu.be/xqT8e6_yzLg?t=356) So what's your team's vacation tolerance?  
[0:06:01](https://youtu.be/xqT8e6_yzLg?t=361) Can everybody on your team safely take a vacation?  
[0:06:04](https://youtu.be/xqT8e6_yzLg?t=364) Can you have a weekend?  
[0:06:05](https://youtu.be/xqT8e6_yzLg?t=365) If you go out to dinner with your family,
are you going to get paged?  
[0:06:09](https://youtu.be/xqT8e6_yzLg?t=369) You shouldn't.  
[0:06:10](https://youtu.be/xqT8e6_yzLg?t=370) You should be in a position where your team
is strong enough, where your process is clear  
[0:06:13](https://youtu.be/xqT8e6_yzLg?t=373) enough, that anybody on your team can step
in and fill that gap and if you get promoted  
[0:06:19](https://youtu.be/xqT8e6_yzLg?t=379) or leave or want to go up into management
or just try out a new product within your  
[0:06:23](https://youtu.be/xqT8e6_yzLg?t=383) company, you shouldn't be leaving people hanging.  
[0:06:26](https://youtu.be/xqT8e6_yzLg?t=386) Everybody should feel great about you moving
on to your next thing.  
[0:06:29](https://youtu.be/xqT8e6_yzLg?t=389) They should be excited, not resentful.  
[0:06:32](https://youtu.be/xqT8e6_yzLg?t=392) When a team starts to defer to their rockstar,
they look at their rockstar and they think  
[0:06:44](https://youtu.be/xqT8e6_yzLg?t=404) to themselves, oh, yeah, well, we always trust
Steve, because Steve is our rockstar, they  
[0:06:50](https://youtu.be/xqT8e6_yzLg?t=410) start becoming dependent on Steve.  
[0:06:53](https://youtu.be/xqT8e6_yzLg?t=413) They'll stop asserting their own, like intuition,
and their own knowledge, because they know  
[0:06:59](https://youtu.be/xqT8e6_yzLg?t=419) that even if they do try to solve the problem,
the rock store is going to come in and cause  
[0:07:03](https://youtu.be/xqT8e6_yzLg?t=423) problems for them.  
[0:07:04](https://youtu.be/xqT8e6_yzLg?t=424) The rockstar is going to come in and say,
"well, actually" oh, I hate it, this was a  
[0:07:11](https://youtu.be/xqT8e6_yzLg?t=431) lot of my life until recently so apologize
if the wounds are still fresh here.  
[0:07:17](https://youtu.be/xqT8e6_yzLg?t=437) But it also means that if you have a rockstar
and everybody on the team is deferring to  
[0:07:21](https://youtu.be/xqT8e6_yzLg?t=441) the rockstar, you also have fewer people on
your team taking initiative.  
[0:07:25](https://youtu.be/xqT8e6_yzLg?t=445) If you've got a team of ten people and nine
of them turn to the senior dev to see what  
[0:07:31](https://youtu.be/xqT8e6_yzLg?t=451) their solution is, you've just lost nine brains'
worth of thinking power, because you've created  
[0:07:38](https://youtu.be/xqT8e6_yzLg?t=458) a dependency.  
[0:07:39](https://youtu.be/xqT8e6_yzLg?t=459) You also end up with knowledge silos.  
[0:07:41](https://youtu.be/xqT8e6_yzLg?t=461) Like I said, we had only one person in a 400,000
person company, only one person knew how it  
[0:07:48](https://youtu.be/xqT8e6_yzLg?t=468) worked, right?  
[0:07:50](https://youtu.be/xqT8e6_yzLg?t=470) This is a problem with rockstar, and another
thing, like we found out, if he they eventually  
[0:07:54](https://youtu.be/xqT8e6_yzLg?t=474) leave and if they leave and nobody's there
to pick up the pieces you end up with a huge  
[0:08:00](https://youtu.be/xqT8e6_yzLg?t=480) problem.  
[0:08:02](https://youtu.be/xqT8e6_yzLg?t=482) So that means that as lead developers, we
need to do better.  
[0:08:07](https://youtu.be/xqT8e6_yzLg?t=487) We also need to approach the real problem.  
[0:08:10](https://youtu.be/xqT8e6_yzLg?t=490) And it's not that glamorous, but the thing
is if we want our teams to run well, we really  
[0:08:16](https://youtu.be/xqT8e6_yzLg?t=496) need to be looking at the underlying problems
that need to be created that created the rockstar  
[0:08:20](https://youtu.be/xqT8e6_yzLg?t=500) in the first place, which means creating process.  
[0:08:24](https://youtu.be/xqT8e6_yzLg?t=504) And I know, some people may be like, oh, this
is not what I wanted to talk about at 4 in  
[0:08:28](https://youtu.be/xqT8e6_yzLg?t=508) the afternoon.  
[0:08:30](https://youtu.be/xqT8e6_yzLg?t=510) So let's talk about why process is a good
thing.  
[0:08:33](https://youtu.be/xqT8e6_yzLg?t=513) So when teams slow down, when a team runs
poorly what ends up happening is that when  
[0:08:40](https://youtu.be/xqT8e6_yzLg?t=520) people lack confidence in their ability or
their knowledge and on top of that, they lack  
[0:08:46](https://youtu.be/xqT8e6_yzLg?t=526) clarity of a goal or whatever they're doing
in the right project.  
[0:08:49](https://youtu.be/xqT8e6_yzLg?t=529) They don't know they're not confident that
they're allowed to do that thing.  
[0:08:56](https://youtu.be/xqT8e6_yzLg?t=536) And beyond that, they're not clear on what's
expected from them.  
[0:09:03](https://youtu.be/xqT8e6_yzLg?t=543) They don't know who the stakeholders are.  
[0:09:04](https://youtu.be/xqT8e6_yzLg?t=544) They don't know where the buck stops if something
goes wrong and if you've ever been in a meeting  
[0:09:09](https://youtu.be/xqT8e6_yzLg?t=549) where you ask somebody what the plan is and
they're like, hm, I like the idea but you  
[0:09:16](https://youtu.be/xqT8e6_yzLg?t=556) need to check with so-and-so and after four
or five loops, you end up back at the first  
[0:09:20](https://youtu.be/xqT8e6_yzLg?t=560) manager, you know, that is pretty common problem
at big organizations that don't have clear  
[0:09:26](https://youtu.be/xqT8e6_yzLg?t=566) processes.  
[0:09:27](https://youtu.be/xqT8e6_yzLg?t=567) Everybody kind of agrees with you, but nobody
really wants to take ownership of that final  
[0:09:31](https://youtu.be/xqT8e6_yzLg?t=571) decision and leads to huge slow-down on teams
so a good process is designed to create confidence  
[0:09:40](https://youtu.be/xqT8e6_yzLg?t=580) and clarity.  
[0:09:41](https://youtu.be/xqT8e6_yzLg?t=581) And it does that by giving people autonomy,
creating trust, giving ownership, creating  
[0:09:48](https://youtu.be/xqT8e6_yzLg?t=588) safety in the team and a whole bunch of other
buzzwords that ultimately translate to happy  
[0:09:54](https://youtu.be/xqT8e6_yzLg?t=594) teams.  
[0:09:56](https://youtu.be/xqT8e6_yzLg?t=596) Would he haven't heard about that over and
over again today, we heard Michael talk about  
[0:10:08](https://youtu.be/xqT8e6_yzLg?t=608) this earlier, is delegate.  
[0:10:10](https://youtu.be/xqT8e6_yzLg?t=610) Trust your team to go do the right thing.  
[0:10:12](https://youtu.be/xqT8e6_yzLg?t=612) That's why you hired them.  
[0:10:13](https://youtu.be/xqT8e6_yzLg?t=613) They're very smart.  
[0:10:15](https://youtu.be/xqT8e6_yzLg?t=615) If you hired them and they're not very smart,
you need to look at your hiring process.  
[0:10:18](https://youtu.be/xqT8e6_yzLg?t=618) That was supposed to be a joke, it didn't
land, I'm sorry.  
[0:10:24](https://youtu.be/xqT8e6_yzLg?t=624) [laughter]  
[0:10:25](https://youtu.be/xqT8e6_yzLg?t=625) And if you've got a team or a process that
creates clarity, 9 accountability change is  
[0:10:30](https://youtu.be/xqT8e6_yzLg?t=630) very clear.  
[0:10:31](https://youtu.be/xqT8e6_yzLg?t=631) Nobody needs to wonder about whether or not
they have authority to make a given decision,  
[0:10:34](https://youtu.be/xqT8e6_yzLg?t=634) they can look at the process, they make a
decision and they go out and kick ass and  
[0:10:42](https://youtu.be/xqT8e6_yzLg?t=642) produce excellent things for your team.  
[0:10:45](https://youtu.be/xqT8e6_yzLg?t=645) And this ultimately creates a much stronger
team, because no one is a bottleneck, each  
[0:10:51](https://youtu.be/xqT8e6_yzLg?t=651) developer feels empowered to make those decisions
independently.  
[0:10:55](https://youtu.be/xqT8e6_yzLg?t=655) Your knowledge is shared and documented along
the team.  
[0:10:57](https://youtu.be/xqT8e6_yzLg?t=657) Documentation is the worst, I know, I'm sorry,
but you gotta do it.  
[0:11:01](https://youtu.be/xqT8e6_yzLg?t=661) There's no chaos if devs take vacation, get
promotions or quit.  
[0:11:05](https://youtu.be/xqT8e6_yzLg?t=665) So how do we create them?  
[0:11:11](https://youtu.be/xqT8e6_yzLg?t=671) What's the goal?  
[0:11:12](https://youtu.be/xqT8e6_yzLg?t=672) Creating a good process?  
[0:11:14](https://youtu.be/xqT8e6_yzLg?t=674) So a good process needs excellent on-boarding
and documentation, because a high-functioning  
[0:11:20](https://youtu.be/xqT8e6_yzLg?t=680) team's progress is going to be so solid that
new numbers are basically painting by numbers  
[0:11:25](https://youtu.be/xqT8e6_yzLg?t=685) to get started.  
[0:11:26](https://youtu.be/xqT8e6_yzLg?t=686) That's what we want.  
[0:11:35](https://youtu.be/xqT8e6_yzLg?t=695) A lot of companies have written about this
pretty extensively and this is a metric you  
[0:11:39](https://youtu.be/xqT8e6_yzLg?t=699) can game.  
[0:11:40](https://youtu.be/xqT8e6_yzLg?t=700) It's extremely easy to have a queue of nonsense
things that somebody can commit on the first  
[0:11:45](https://youtu.be/xqT8e6_yzLg?t=705) day.  
[0:11:46](https://youtu.be/xqT8e6_yzLg?t=706) That doesn't mean your process is good.  
[0:11:47](https://youtu.be/xqT8e6_yzLg?t=707) They need to be really be able to contribute
to the team on day one.  
[0:11:55](https://youtu.be/xqT8e6_yzLg?t=715) You also want to have ongoing internal education
and training.  
[0:11:58](https://youtu.be/xqT8e6_yzLg?t=718) The team should be noticing when something
new is happening, noticing when something  
[0:12:04](https://youtu.be/xqT8e6_yzLg?t=724) in the process has changed, noticing when
they're up against something that has so far  
[0:12:09](https://youtu.be/xqT8e6_yzLg?t=729) not been covered and when they run into that,
they should write up something about it, we  
[0:12:14](https://youtu.be/xqT8e6_yzLg?t=734) just talked about this earlier.  
[0:12:16](https://youtu.be/xqT8e6_yzLg?t=736) Have an internal training.  
[0:12:20](https://youtu.be/xqT8e6_yzLg?t=740) When you do that internal training, put it
into some kind of internal knowledge base,  
[0:12:23](https://youtu.be/xqT8e6_yzLg?t=743) so that you have a reference of all of these
things.  
[0:12:25](https://youtu.be/xqT8e6_yzLg?t=745) Hey, here's we had this problem, here's how
we solved it, we had a training so that anybody  
[0:12:32](https://youtu.be/xqT8e6_yzLg?t=752) who knew and wasn't able to attend is able
to find that in the future, and it's done  
[0:12:38](https://youtu.be/xqT8e6_yzLg?t=758) in a community focused way.  
[0:12:43](https://youtu.be/xqT8e6_yzLg?t=763) You want to do frequent code reviews and coaching.  
[0:12:45](https://youtu.be/xqT8e6_yzLg?t=765) Code reviews, I feel like kind of get a bad
rap, because you see a lot of teams who only  
[0:12:50](https://youtu.be/xqT8e6_yzLg?t=770) do code reviews when something is wrong.  
[0:12:52](https://youtu.be/xqT8e6_yzLg?t=772) They look at code reviews as a chance for
the lead developer to flog somebody in the  
[0:12:58](https://youtu.be/xqT8e6_yzLg?t=778) public square because they, I don't know,
did something that was like a memory hog.  
[0:13:03](https://youtu.be/xqT8e6_yzLg?t=783) That is not what a code review should be.  
[0:13:05](https://youtu.be/xqT8e6_yzLg?t=785) In fact, I think that code reviews should
mostly be when somebody does something that  
[0:13:09](https://youtu.be/xqT8e6_yzLg?t=789) you like, pull it up in front of the entire
team, and walk through what they did right  
[0:13:16](https://youtu.be/xqT8e6_yzLg?t=796) and then talk about all the other ways that
it could have been written that maybe wouldn't  
[0:13:19](https://youtu.be/xqT8e6_yzLg?t=799) have been optimal.  
[0:13:20](https://youtu.be/xqT8e6_yzLg?t=800) So show what the anti-pattern could have been
and praise what was done.  
[0:13:25](https://youtu.be/xqT8e6_yzLg?t=805) If you do find an anti-pattern, in my case,
I like to do this with my own code and I would  
[0:13:34](https://youtu.be/xqT8e6_yzLg?t=814) go through it.  
[0:13:38](https://youtu.be/xqT8e6_yzLg?t=818) And I did this for two reasons.  
[0:13:43](https://youtu.be/xqT8e6_yzLg?t=823) I don't want anybody to see me on my team
as infallible and as a lead developer, the  
[0:13:49](https://youtu.be/xqT8e6_yzLg?t=829) worst thing you can be is someone who appears
infallible.  
[0:13:53](https://youtu.be/xqT8e6_yzLg?t=833) If your team doesn't feel like you make mistakes,
that puts you on a weird pedestal.  
[0:13:58](https://youtu.be/xqT8e6_yzLg?t=838) You should be showing them lots of mistakes.  
[0:14:07](https://youtu.be/xqT8e6_yzLg?t=847) Don't hide the process from your team.  
[0:14:11](https://youtu.be/xqT8e6_yzLg?t=851) Comprehensive test suites that I'm not going
to get deep into.  
[0:14:14](https://youtu.be/xqT8e6_yzLg?t=854) I've got a whole other talk that I've referenced
in the resources of this one about driving  
[0:14:19](https://youtu.be/xqT8e6_yzLg?t=859) the testing culture at a big company.  
[0:14:22](https://youtu.be/xqT8e6_yzLg?t=862) So I would encourage you if this is something
that is a pain point for you, to check that  
[0:14:25](https://youtu.be/xqT8e6_yzLg?t=865) out.  
[0:14:27](https://youtu.be/xqT8e6_yzLg?t=867) Internally consistent style and quality guidelines.  
[0:14:29](https://youtu.be/xqT8e6_yzLg?t=869) This is a big one.  
[0:14:34](https://youtu.be/xqT8e6_yzLg?t=874) It's so bad in some companies like that Erin
has to create a semicolon appreciation sticker  
[0:14:39](https://youtu.be/xqT8e6_yzLg?t=879) to show support for her preferred code style
and this can be a battle and it can be a pretty  
[0:14:47](https://youtu.be/xqT8e6_yzLg?t=887) bad battle.  
[0:14:48](https://youtu.be/xqT8e6_yzLg?t=888) For a team to really function, we'd need to
make that a nonissue.  
[0:14:55](https://youtu.be/xqT8e6_yzLg?t=895) It needs to be something that nobody has to
think about.  
[0:14:58](https://youtu.be/xqT8e6_yzLg?t=898) So some of you, I've seen, kind of glazed
over on me and I think that maybe it's because  
[0:15:03](https://youtu.be/xqT8e6_yzLg?t=903) you're thinking, like, well, I've tried this,
nobody listens.  
[0:15:06](https://youtu.be/xqT8e6_yzLg?t=906) We've tried to do processes or I've written
up processes and nobody follows them.  
[0:15:11](https://youtu.be/xqT8e6_yzLg?t=911) Who's done that?  
[0:15:13](https://youtu.be/xqT8e6_yzLg?t=913) Yeah, me, too.  
[0:15:17](https://youtu.be/xqT8e6_yzLg?t=917) I've done it multiple times.  
[0:15:22](https://youtu.be/xqT8e6_yzLg?t=922) Why is that happening?  
[0:15:24](https://youtu.be/xqT8e6_yzLg?t=924) So let's talk about why processes fail.  
[0:15:30](https://youtu.be/xqT8e6_yzLg?t=930) One of the biggest things that I've ever learned
is my partner, the very brilliant Mersa Morby  
[0:15:35](https://youtu.be/xqT8e6_yzLg?t=935) who we will be meeting later in this presentation
taught me that I am very, very bad at people.  
[0:15:44](https://youtu.be/xqT8e6_yzLg?t=944) So it turns out that being good at understanding
logical systems and being good at people are  
[0:15:51](https://youtu.be/xqT8e6_yzLg?t=951) potentially mutually exclusive things.  
[0:15:52](https://youtu.be/xqT8e6_yzLg?t=952) I don't think they have to be, but in my case
they were.  
[0:15:56](https://youtu.be/xqT8e6_yzLg?t=956) And I did a lot of beating people over the
head with my logically correct solutions so  
[0:16:02](https://youtu.be/xqT8e6_yzLg?t=962) that led me to realize that one of the biggest
problems I had in my processes is that I was  
[0:16:07](https://youtu.be/xqT8e6_yzLg?t=967) writing processes for things that I felt we
should know and I was not considering at all  
[0:16:13](https://youtu.be/xqT8e6_yzLg?t=973) the way that the process that I was designing
made people feel.  
[0:16:16](https://youtu.be/xqT8e6_yzLg?t=976) Of course I felt brilliant, because I'd written
the product, but to somebody else, they felt  
[0:16:21](https://youtu.be/xqT8e6_yzLg?t=981) like I was handcuffing them or that I was
giving them a directive from on high that  
[0:16:27](https://youtu.be/xqT8e6_yzLg?t=987) they didn't understand and had no context
for or that I was giving them busy work that  
[0:16:31](https://youtu.be/xqT8e6_yzLg?t=991) they thought was meaningless and they didn't
want to do.  
[0:16:33](https://youtu.be/xqT8e6_yzLg?t=993) All of those things lead to push-back.  
[0:16:36](https://youtu.be/xqT8e6_yzLg?t=996) So if you've ever read the Heath brothers.  
[0:16:40](https://youtu.be/xqT8e6_yzLg?t=1000) They write a lot about this concept of the
rider and the elephant.  
[0:16:46](https://youtu.be/xqT8e6_yzLg?t=1006) The basic concept here is that our logical
brain, the little person behind our eyes that  
[0:16:50](https://youtu.be/xqT8e6_yzLg?t=1010) controls our thoughts, that's the rider.  
[0:16:53](https://youtu.be/xqT8e6_yzLg?t=1013) That's the part of us that says, you know,
what I'm going to do I'm going to be healthy.  
[0:16:58](https://youtu.be/xqT8e6_yzLg?t=1018) I'm not going to eat any candy, no ice cream,
I'm going to go to the gym, I'm goings to  
[0:17:02](https://youtu.be/xqT8e6_yzLg?t=1022) be great of this.  
[0:17:03](https://youtu.be/xqT8e6_yzLg?t=1023) The elephant is the part of your brain that
says, yeah, I know you said that, but we're  
[0:17:07](https://youtu.be/xqT8e6_yzLg?t=1027) definitely getting the ice cream.  
[0:17:11](https://youtu.be/xqT8e6_yzLg?t=1031) It's the idea that you have a logical part
of your brain that is willpower-dependent.  
[0:17:18](https://youtu.be/xqT8e6_yzLg?t=1038) You know what's right.  
[0:17:19](https://youtu.be/xqT8e6_yzLg?t=1039) You know what you want.  
[0:17:20](https://youtu.be/xqT8e6_yzLg?t=1040) And if you put a tremendous amount of in t
you can drag yourself to do those things.  
[0:17:24](https://youtu.be/xqT8e6_yzLg?t=1044) The elephant is that subconscious part of
your brain that just does the thing that feels  
[0:17:30](https://youtu.be/xqT8e6_yzLg?t=1050) right, okay, and if you want to read more
about this, there's a whole book dedicated  
[0:17:37](https://youtu.be/xqT8e6_yzLg?t=1057) to this idea of changing the way that people
think, and how to make big organizational  
[0:17:42](https://youtu.be/xqT8e6_yzLg?t=1062) changes.  
[0:17:43](https://youtu.be/xqT8e6_yzLg?t=1063) I would highly recommend it.  
[0:17:44](https://youtu.be/xqT8e6_yzLg?t=1064) But what this all leads to, you know, we've
got the rider, we've got the elephant, we  
[0:17:48](https://youtu.be/xqT8e6_yzLg?t=1068) can always appeal to the rider.  
[0:17:50](https://youtu.be/xqT8e6_yzLg?t=1070) If I'm logically correct in any argument,
I can probably get you to nod and say yes,  
[0:17:56](https://youtu.be/xqT8e6_yzLg?t=1076) I understand what you're saying.  
[0:17:58](https://youtu.be/xqT8e6_yzLg?t=1078) That will immediately be followed by, but,
I still hate you.  
[0:18:02](https://youtu.be/xqT8e6_yzLg?t=1082) [laughter]  
[0:18:03](https://youtu.be/xqT8e6_yzLg?t=1083) So we need to figure out how to make the right
thing the easy thing.  
[0:18:08](https://youtu.be/xqT8e6_yzLg?t=1088) How do we make processes that are going to
appeal not only to the rider, but to the elephant?  
[0:18:14](https://youtu.be/xqT8e6_yzLg?t=1094) How are we going to get our processes to become
something that feels good for our teams to  
[0:18:20](https://youtu.be/xqT8e6_yzLg?t=1100) use, that makes them feel like they're doing
the right thing?  
[0:18:26](https://youtu.be/xqT8e6_yzLg?t=1106) We can do this by focusing on four core values.  
[0:18:31](https://youtu.be/xqT8e6_yzLg?t=1111) Emotional rewards: Automation, simplification,
and Yak shaving.  
[0:18:39](https://youtu.be/xqT8e6_yzLg?t=1119) The reason I used yak shaving is because I
really wanted this to be an acronym.  
[0:18:44](https://youtu.be/xqT8e6_yzLg?t=1124) Emotional rewards, automation, simplification,
and yak shaving.  
[0:18:52](https://youtu.be/xqT8e6_yzLg?t=1132) I'm sorry.  
[0:18:55](https://youtu.be/xqT8e6_yzLg?t=1135) [laughter]  
[0:18:59](https://youtu.be/xqT8e6_yzLg?t=1139) You really want to give people emotional rewards.  
[0:19:02](https://youtu.be/xqT8e6_yzLg?t=1142) And that can be something as simple as less
effort required to do things the new way.  
[0:19:10](https://youtu.be/xqT8e6_yzLg?t=1150) A good example of this is like wheels on a
suitcase.  
[0:19:13](https://youtu.be/xqT8e6_yzLg?t=1153) That was making the right thing the easy thing.  
[0:19:15](https://youtu.be/xqT8e6_yzLg?t=1155) If you want to sell wheels on suitcase, you
don't really have to.  
[0:19:19](https://youtu.be/xqT8e6_yzLg?t=1159) people have a big heavy suitcase and then
they see one with wheels on it and they go,  
[0:19:23](https://youtu.be/xqT8e6_yzLg?t=1163) that looks easier, and they buy a suitcase
with wheels on it, it sells itself.  
[0:19:27](https://youtu.be/xqT8e6_yzLg?t=1167) How can you make your product a suitcase with
wheels on it?  
[0:19:31](https://youtu.be/xqT8e6_yzLg?t=1171) Make it the default choice, make it the thing
that makes the most sense.  
[0:19:35](https://youtu.be/xqT8e6_yzLg?t=1175) Another thing is immediate praise and positive
feedback.  
[0:19:43](https://youtu.be/xqT8e6_yzLg?t=1183) Some of your processes are going to require
extra effort.  
[0:19:46](https://youtu.be/xqT8e6_yzLg?t=1186) If you want people to document things, if
you want people to jump through a couple extra  
[0:19:49](https://youtu.be/xqT8e6_yzLg?t=1189) testing hoops, that's effort.  
[0:19:52](https://youtu.be/xqT8e6_yzLg?t=1192) So how do you make it emotionally rewarding
to do it?  
[0:19:55](https://youtu.be/xqT8e6_yzLg?t=1195) You do that by providing that immediate praise
and positive feedback and then I would argue  
[0:20:00](https://youtu.be/xqT8e6_yzLg?t=1200) to even take it further and do public recognition
and gratitude.  
[0:20:05](https://youtu.be/xqT8e6_yzLg?t=1205) This is where we quote my lovely partner,
one of the best feelings in the world is to  
[0:20:11](https://youtu.be/xqT8e6_yzLg?t=1211) be validated and even if you are the most,
like introverted, misanthropic, like, me sometimes,  
[0:20:19](https://youtu.be/xqT8e6_yzLg?t=1219) like you just don't want to see people at
all.  
[0:20:21](https://youtu.be/xqT8e6_yzLg?t=1221) If somebody comes up to you and goes, you
know, I really appreciate you, you're a great  
[0:20:25](https://youtu.be/xqT8e6_yzLg?t=1225) person, like, all of that anger and like prickliness,
I just roll over and show my belly and like,  
[0:20:31](https://youtu.be/xqT8e6_yzLg?t=1231) more, please!  
[0:20:33](https://youtu.be/xqT8e6_yzLg?t=1233) [laughter]  
[0:20:34](https://youtu.be/xqT8e6_yzLg?t=1234) Like it's such a good feeling.  
[0:20:37](https://youtu.be/xqT8e6_yzLg?t=1237) That led me to understand.  
[0:20:40](https://youtu.be/xqT8e6_yzLg?t=1240) When she started explaining the difference
between being right and being approachbly  
[0:20:47](https://youtu.be/xqT8e6_yzLg?t=1247) right, it led me to understand something.  
[0:20:53](https://youtu.be/xqT8e6_yzLg?t=1253) It doesn't matter if you're objectively correct.  
[0:20:56](https://youtu.be/xqT8e6_yzLg?t=1256) Like, you can be logically correct up and
down, if you're an asshole, nobody's going  
[0:21:01](https://youtu.be/xqT8e6_yzLg?t=1261) to listen to you, so you need to make sure
that that process is something that you will  
[0:21:06](https://youtu.be/xqT8e6_yzLg?t=1266) use, because logically correct and easy to
use or logically correct and unapproachable.  
[0:21:14](https://youtu.be/xqT8e6_yzLg?t=1274) The trash heaps of the internet are littered
of fantastic ideas that were objectively fantastic  
[0:21:27](https://youtu.be/xqT8e6_yzLg?t=1287) that didn't do a good job of onboarding features.  
[0:21:39](https://youtu.be/xqT8e6_yzLg?t=1299) And somebody's going to come back, well, actually,
this was invented in 2011, and like, well,  
[0:21:43](https://youtu.be/xqT8e6_yzLg?t=1303) nobody used it so it doesn't matter.  
[0:21:46](https://youtu.be/xqT8e6_yzLg?t=1306) So let's move on.  
[0:21:47](https://youtu.be/xqT8e6_yzLg?t=1307) The other thing that we want do is automate.  
[0:21:50](https://youtu.be/xqT8e6_yzLg?t=1310) Setting up continuous integration, continuous
delivery.  
[0:21:54](https://youtu.be/xqT8e6_yzLg?t=1314) These are the types of things that really
start to make a difference.  
[0:21:58](https://youtu.be/xqT8e6_yzLg?t=1318) Like your tests should be running automatically.  
[0:22:00](https://youtu.be/xqT8e6_yzLg?t=1320) I'm not going to talk about testing because
it's too big a topic, but like run and prettier  
[0:22:06](https://youtu.be/xqT8e6_yzLg?t=1326) automatically.  
[0:22:13](https://youtu.be/xqT8e6_yzLg?t=1333) Automate your code coverage checks.  
[0:22:15](https://youtu.be/xqT8e6_yzLg?t=1335) Use semantic release for versioning and releases.  
[0:22:17](https://youtu.be/xqT8e6_yzLg?t=1337) All of thieves are optional.  
[0:22:18](https://youtu.be/xqT8e6_yzLg?t=1338) It's not something that you have to do, but
look at your process and anything that you  
[0:22:24](https://youtu.be/xqT8e6_yzLg?t=1344) can automate, strongly consider automating
it, because it's just not worth it to make  
[0:22:31](https://youtu.be/xqT8e6_yzLg?t=1351) that effort.  
[0:22:32](https://youtu.be/xqT8e6_yzLg?t=1352) So another one is don't file on style, right?  
[0:22:34](https://youtu.be/xqT8e6_yzLg?t=1354) If you want a style guide inside your company,
don't fail the PR and make somebody go do  
[0:22:40](https://youtu.be/xqT8e6_yzLg?t=1360) a new code cycle because they missed a semicolon.  
[0:22:43](https://youtu.be/xqT8e6_yzLg?t=1363) Like run Prettier, automate and don't make
it a fight.  
[0:22:51](https://youtu.be/xqT8e6_yzLg?t=1371) It's very hard to be the code cop.  
[0:22:54](https://youtu.be/xqT8e6_yzLg?t=1374) It's very hard to be the code cop and it's
very hard to deal with the code cop.  
[0:22:57](https://youtu.be/xqT8e6_yzLg?t=1377) It sucks.  
[0:22:58](https://youtu.be/xqT8e6_yzLg?t=1378) Nobody wants to have a conversation about
whether or not it's worth it to delay a feature  
[0:23:04](https://youtu.be/xqT8e6_yzLg?t=1384) because the formatting is wrong on the code.  
[0:23:08](https://youtu.be/xqT8e6_yzLg?t=1388) So instead, get a code bot in there, and that
code bot solves those problems, those things  
[0:23:15](https://youtu.be/xqT8e6_yzLg?t=1395) that are nit-picky and small but are universally
true.  
[0:23:19](https://youtu.be/xqT8e6_yzLg?t=1399) Here's the reason.  
[0:23:21](https://youtu.be/xqT8e6_yzLg?t=1401) If you are on a team and I come to you and
say, your code ant formatting, and I'm having  
[0:23:28](https://youtu.be/xqT8e6_yzLg?t=1408) a bad day, I might be meaner to you than I
need to be.  
[0:23:31](https://youtu.be/xqT8e6_yzLg?t=1411) Or I might just let it go.  
[0:23:34](https://youtu.be/xqT8e6_yzLg?t=1414) If I'm busy, I'll probably let some low-quality
code go or as most people do, I'll have unconscious  
[0:23:43](https://youtu.be/xqT8e6_yzLg?t=1423) bias and I might pick on one or two people
on my team more than other people.  
[0:23:48](https://youtu.be/xqT8e6_yzLg?t=1428) That's a super-toxic way of running a team.  
[0:23:54](https://youtu.be/xqT8e6_yzLg?t=1434) You you're creating a completely level playing
field.  
[0:24:02](https://youtu.be/xqT8e6_yzLg?t=1442) Just say is it true or not, it's a boolean
operation and that's a good thing.  
[0:24:10](https://youtu.be/xqT8e6_yzLg?t=1450) Process should be as close to boolean as it
can, the robot hates you all with the exact  
[0:24:16](https://youtu.be/xqT8e6_yzLg?t=1456) same level of like indifference, right?  
[0:24:20](https://youtu.be/xqT8e6_yzLg?t=1460) [laughter]  
[0:24:21](https://youtu.be/xqT8e6_yzLg?t=1461) So let's move on, let's go to simplification.  
[0:24:26](https://youtu.be/xqT8e6_yzLg?t=1466) When you're looking at new tools, you want
to consider the cost onboarding and training.  
[0:24:30](https://youtu.be/xqT8e6_yzLg?t=1470) Sam talked about this.  
[0:24:32](https://youtu.be/xqT8e6_yzLg?t=1472) It's a really good point.  
[0:24:33](https://youtu.be/xqT8e6_yzLg?t=1473) When you're looking at something new, think
about how expensive it's going to be to get  
[0:24:38](https://youtu.be/xqT8e6_yzLg?t=1478) people to use T do you have the time?  
[0:24:40](https://youtu.be/xqT8e6_yzLg?t=1480) Do you have the extra cycles to convince and
train somebody on how to use this tool and  
[0:24:45](https://youtu.be/xqT8e6_yzLg?t=1485) can you do that for every single new person
that you've got.  
[0:24:48](https://youtu.be/xqT8e6_yzLg?t=1488) Like React for example, maybe that's a good
thing and that's what you want, but enthis  
[0:24:53](https://youtu.be/xqT8e6_yzLg?t=1493) you decide, like some developers, hey, we're
doing this thing that's kind of complicated,  
[0:24:57](https://youtu.be/xqT8e6_yzLg?t=1497) we want to add funk and somebody else says,
we're getting a lot of states, so we want  
[0:25:03](https://youtu.be/xqT8e6_yzLg?t=1503) to do Redux and somebody is like, yeah, we
want to add GraphQL?  
[0:25:07](https://youtu.be/xqT8e6_yzLg?t=1507) What are we actually trying to do and we need
to think through that and make sure that we're  
[0:25:17](https://youtu.be/xqT8e6_yzLg?t=1517) not making our stuff really complex for a
minimal gain.  
[0:25:22](https://youtu.be/xqT8e6_yzLg?t=1522) Use stable open source tools if that option
exists because if you build something in house,  
[0:25:29](https://youtu.be/xqT8e6_yzLg?t=1529) you are basically saying that this tool, in
addition to our product, is something that  
[0:25:33](https://youtu.be/xqT8e6_yzLg?t=1533) we need to maintain and like staff.  
[0:25:37](https://youtu.be/xqT8e6_yzLg?t=1537) We need people to manage this tool, or else
we end up with a completely neglected utility  
[0:25:41](https://youtu.be/xqT8e6_yzLg?t=1541) library that ends up being a huge problem,
because nobody knows how it works, because  
[0:25:45](https://youtu.be/xqT8e6_yzLg?t=1545) it was built and then abandoned.  
[0:25:48](https://youtu.be/xqT8e6_yzLg?t=1548) That's a very expensive thing to have-to-to
deal with.  
[0:25:50](https://youtu.be/xqT8e6_yzLg?t=1550) So really weigh whether or not you have to
actually build something in house.  
[0:25:55](https://youtu.be/xqT8e6_yzLg?t=1555) Probably there's a publicly maintained, very
stable open source solution to a problem that  
[0:26:00](https://youtu.be/xqT8e6_yzLg?t=1560) you've got.  
[0:26:01](https://youtu.be/xqT8e6_yzLg?t=1561) >> Write code that's small and easy to delete.  
[0:26:03](https://youtu.be/xqT8e6_yzLg?t=1563) If you optimize for deletion, this is probably
one of the best things you can do.  
[0:26:08](https://youtu.be/xqT8e6_yzLg?t=1568) Because when you optimize for deletion, it
means that you don't have to write code that's  
[0:26:13](https://youtu.be/xqT8e6_yzLg?t=1573) going to be valid five years in the future.  
[0:26:16](https://youtu.be/xqT8e6_yzLg?t=1576) Maybe you're aiming to be Google, but if you
aren't at Google scale but you're trying to  
[0:26:21](https://youtu.be/xqT8e6_yzLg?t=1581) write code at Google scale but you're getting
like 500 uniques a month be, you're probably  
[0:26:26](https://youtu.be/xqT8e6_yzLg?t=1586) overcomplicating your process for a negative
benefit.  
[0:26:30](https://youtu.be/xqT8e6_yzLg?t=1590) Because you should be building features to
try to get from 500 to 5,000 instead of trying  
[0:26:35](https://youtu.be/xqT8e6_yzLg?t=1595) to the 0imize for 5 million.  
[0:26:37](https://youtu.be/xqT8e6_yzLg?t=1597) So I'll get a little bit faster because I'm
running out of time.  
[0:26:44](https://youtu.be/xqT8e6_yzLg?t=1604) Weigh the tradeoffs, choose the thing that
makes your team more productive.  
[0:26:47](https://youtu.be/xqT8e6_yzLg?t=1607) Not the thing that will make your app app
best in ten years.  
[0:26:51](https://youtu.be/xqT8e6_yzLg?t=1611) And the other one I saw this quote the other
day.  
[0:26:54](https://youtu.be/xqT8e6_yzLg?t=1614) Premature optimization can be a violent source
of tech debt.  
[0:26:57](https://youtu.be/xqT8e6_yzLg?t=1617) I love that quote and it's true.  
[0:27:00](https://youtu.be/xqT8e6_yzLg?t=1620) Because if you add something that's going
to make you bullet-proof down the line you  
[0:27:04](https://youtu.be/xqT8e6_yzLg?t=1624) may have to support that without ever knowing
what it does and you may see the business  
[0:27:10](https://youtu.be/xqT8e6_yzLg?t=1630) takes a different turn in six months that
completely makes that wasted.  
[0:27:18](https://youtu.be/xqT8e6_yzLg?t=1638) And the last thing is yak-shaving.  
[0:27:21](https://youtu.be/xqT8e6_yzLg?t=1641) This one is near and dear to my heart.  
[0:27:26](https://youtu.be/xqT8e6_yzLg?t=1646) It's actually the reason that I left IBM is
to go work with a company that focuses on  
[0:27:30](https://youtu.be/xqT8e6_yzLg?t=1650) yak-shaving.  
[0:27:31](https://youtu.be/xqT8e6_yzLg?t=1651) It's not even in tech, I just shave animals
now.  
[0:27:38](https://youtu.be/xqT8e6_yzLg?t=1658) I think your big astrology is to attempt to
limit the team's exposure to yak-shaving.  
[0:27:44](https://youtu.be/xqT8e6_yzLg?t=1664) For those of you who haven't heard of this
term it's very jargony and weird, the idea  
[0:27:49](https://youtu.be/xqT8e6_yzLg?t=1669) of yak-shaving is if you want to work on a
problem, let's say you want to wash your car,  
[0:27:55](https://youtu.be/xqT8e6_yzLg?t=1675) you you go out to wash your car and you realize
that your hose is broken, so you take your  
[0:28:01](https://youtu.be/xqT8e6_yzLg?t=1681) hose to Home Depot to try to buy tape, but
you find -- I don't know, you find yourselves  
[0:28:09](https://youtu.be/xqT8e6_yzLg?t=1689) 8 tasks deep and you found yourself doing
an entire day's worth of seemingly unrelated  
[0:28:16](https://youtu.be/xqT8e6_yzLg?t=1696) work to open the door for you to be able to
do that initial work.  
[0:28:21](https://youtu.be/xqT8e6_yzLg?t=1701) If you think of that in a technical sense,
let's say I want to build a new feature for  
[0:28:28](https://youtu.be/xqT8e6_yzLg?t=1708) the frontend and then before I request set
up a new dev environment, I need to install  
[0:28:38](https://youtu.be/xqT8e6_yzLg?t=1718) Nginx and all of that means I have to update
my four hours just to get a dev environment  
[0:28:43](https://youtu.be/xqT8e6_yzLg?t=1723) running.  
[0:28:44](https://youtu.be/xqT8e6_yzLg?t=1724) These are big complicated problems.  
[0:28:47](https://youtu.be/xqT8e6_yzLg?t=1727) So if you invest in your technical configuration,
you're eliminating the need of your team to  
[0:28:54](https://youtu.be/xqT8e6_yzLg?t=1734) do that yak-shaving.  
[0:28:55](https://youtu.be/xqT8e6_yzLg?t=1735) They're in the position to immediately do
quality work.  
[0:28:59](https://youtu.be/xqT8e6_yzLg?t=1739) I gotta go real fast.  
[0:29:02](https://youtu.be/xqT8e6_yzLg?t=1742) OK.  
[0:29:03](https://youtu.be/xqT8e6_yzLg?t=1743) Don't make people do a bunch of work before
they can start working.  
[0:29:06](https://youtu.be/xqT8e6_yzLg?t=1746) This is, like, please if you focus on one
thing, if you take anything away from this  
[0:29:10](https://youtu.be/xqT8e6_yzLg?t=1750) talk, it's please this.  
[0:29:12](https://youtu.be/xqT8e6_yzLg?t=1752) Do things that make your team more productive.  
[0:29:17](https://youtu.be/xqT8e6_yzLg?t=1757) If you're like a 10X developer, and your team
is still 1X and wasting most of their time  
[0:29:23](https://youtu.be/xqT8e6_yzLg?t=1763) on dev configuration, you are not a lead developer,
you are like a lone wolf, rockstar, whatever  
[0:29:29](https://youtu.be/xqT8e6_yzLg?t=1769) you want to call it.  
[0:29:31](https://youtu.be/xqT8e6_yzLg?t=1771) You're a hero, when you leave, the organization
is going to suffer.  
[0:29:36](https://youtu.be/xqT8e6_yzLg?t=1776) Because, if you 
figure that you're spending one hour a week,  
[0:29:46](https://youtu.be/xqT8e6_yzLg?t=1786) times 10 dev on your team, times an average
salary that I pulled off glass door, so I  
[0:29:50](https://youtu.be/xqT8e6_yzLg?t=1790) have no idea how accurate this is, of $70,000
a year.  
[0:29:53](https://youtu.be/xqT8e6_yzLg?t=1793) You're wasting $16,153.  
[0:29:55](https://youtu.be/xqT8e6_yzLg?t=1795) And I would guess that every organization
here is waste one hour at least.  
[0:30:13](https://youtu.be/xqT8e6_yzLg?t=1813) Don't ask people to fix a mess.  
[0:30:16](https://youtu.be/xqT8e6_yzLg?t=1816) Don't hand them something that's already in
disrepair and say OK, you're at zero, you  
[0:30:20](https://youtu.be/xqT8e6_yzLg?t=1820) need to get 100% test coverage.  
[0:30:25](https://youtu.be/xqT8e6_yzLg?t=1825) Set them up to succeed.  
[0:30:26](https://youtu.be/xqT8e6_yzLg?t=1826) Do something with what they're handed is at
100%.Oo it's very easy to keep something great.  
[0:30:37](https://youtu.be/xqT8e6_yzLg?t=1837) It's very hard to take something bad and make
it good.  
[0:30:40](https://youtu.be/xqT8e6_yzLg?t=1840) So you want to be focusing on giving people
a chance to succeed as evidenced by these  
[0:30:45](https://youtu.be/xqT8e6_yzLg?t=1845) gentlemen here playing the sports ball.  
[0:30:49](https://youtu.be/xqT8e6_yzLg?t=1849) So what is a lead developer.  
[0:30:51](https://youtu.be/xqT8e6_yzLg?t=1851) A lead developer is not carrying their team
by doing most of the work.  
[0:30:55](https://youtu.be/xqT8e6_yzLg?t=1855) They're not inserting themselves in every
code decision and they're not singlehandedly:  
[0:31:01](https://youtu.be/xqT8e6_yzLg?t=1861) Everybody take photos fast, I've got to leave,
OK?  
[0:31:06](https://youtu.be/xqT8e6_yzLg?t=1866) A lead developer is creating guardrails to
encourage best practices.  
[0:31:14](https://youtu.be/xqT8e6_yzLg?t=1874) They're defining processes to create confidence
and clarity and they're removing bottlenecks  
[0:31:19](https://youtu.be/xqT8e6_yzLg?t=1879) and knowledge silos.  
[0:31:21](https://youtu.be/xqT8e6_yzLg?t=1881) And what that that means is lead developers
are designing processes that are emotionally  
[0:31:25](https://youtu.be/xqT8e6_yzLg?t=1885) rewarding automating process, reducing training
costs by simplifying our workflows and we  
[0:31:37](https://youtu.be/xqT8e6_yzLg?t=1897) invest in the foundation of our company to
prevent yak-shaving.  
[0:31:41](https://youtu.be/xqT8e6_yzLg?t=1901) And that means that the teams that we build
have a high vacation tolerance.  
[0:31:45](https://youtu.be/xqT8e6_yzLg?t=1905) People can leave without disrupting the entire
team.  
[0:31:48](https://youtu.be/xqT8e6_yzLg?t=1908) We're able to operate with high levels of
confidence and clarity.  
[0:31:52](https://youtu.be/xqT8e6_yzLg?t=1912) Able to know that our work is both recognized
and valued and our teams are able to feel  
[0:31:59](https://youtu.be/xqT8e6_yzLg?t=1919) confident in their autonomy and safety and
most important they're not dependent on rockstar developers.  
[0:32:05](https://youtu.be/xqT8e6_yzLg?t=1925) Thank you very much.  
[0:32:06](https://youtu.be/xqT8e6_yzLg?t=1926) [applause]  

