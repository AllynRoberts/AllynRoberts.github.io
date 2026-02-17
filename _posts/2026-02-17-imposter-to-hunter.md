---
layout: post
title: Imposter to Hunter: My First Two Years as a Threat Hunter
date: 2026-02-17 09:34 -0700
permalink: /:title
---

# Impostor to Hunter: My Two Years as a Threat Hunter

About a year ago, I walked into a meeting to present recommendations from one of our first cloud threat hunts. I'd been hunting in our cloud environment for weeks. The people in that room had been
working in it for years. I was terrified they were going to laugh at me or tell me I didn't know what I was talking about.

They didn't. The recommendations were well-received. They thought we did a good job making our cloud environment more secure. And I walked out of that meeting feeling something I believed I may not ever achieve

That moment didn't come easy. Here's how I got there.

## Seven Years to Graduate, Ten Years to Find My Path

It took me seven years to get my bachelor's degree. I switched my major three times, from mechanical engineering, to computer science, and finally management information systems. That was the first time I
really felt impostor syndrome.

I remember sitting in a digital circuits lab, a three-hour weekly session, staring at a screen for the entire time with no idea what I was doing. It was the first time in school I couldn't figure
something out. I told myself maybe I wasn't cut out for engineering. When I switched to computer science, programming wouldn't click either. Maybe I wasn't meant to do technical things at all.

But I found my footing in management information systems, which led to an internship at Intermountain Health in the security operations center. And of course, impostor syndrome followed me there too. I
was convinced they hired me only because I had availability. I said I'd work nights, weekends, and holidays, and that's the person they needed. Not because I had any real skills.

## Eight Years in Non-Technical Security Roles

After that internship, I got hired full-time. For the next eight years, I worked in some pretty non-technical cybersecurity roles. First on the disaster recovery team, then in the Office of the CISO,
where I assisted with cyber finances, contracts, our apprenticeship program, and helped other teams build recovery plans.

I loved what I did and I loved my teams. But impostor syndrome was still there. I'm introverted. I was on teams with people who'd been in their careers for decades. It was hard to speak up when I felt
like I didn't have much to offer.

During this time, though, something was building. Conferences like SAINTCON sparked something. The hands-on stuff, the CTFs, the challenges. I started chasing that feeling outside of conferences too.
Cybersecurity books. Online CTFs. Home lab experiments where I learned Linux and the command line for the first time. I enrolled in graduate school for cybersecurity and got more hands-on experience
across different roles.

It started to become a hobby. I'd do my day job, then feed that appetite for technical work on my own time. I didn't have a specific direction yet, I just liked doing it.

## The Spark: Finding Threat Intelligence

That changed around 2021. I attended a DEF CON presentation on cyber threat intelligence. I don't remember who spoke or exactly what it was about, but it sparked something. I could see myself doing
that work.

I started following people in threat intelligence on social media, looking for resources and guides. I found a bunch of resources, and found a community that was very willing to share and help. One
that really helped was Andy Piazza's [cyber threat intelligence study plan](https://klrgrz.medium.com/cyber-threat-intelligence-study-plan-c60484d319cb). But when I started looking at job postings, even entry-level positions wanted two or more years of experience in a technical cyber
role.

I felt stuck. Would I have to go backward to go forward?

I reached out to Andy directly, told him my situation, years in cyber but no technical experience. His advice was simple and it changed everything: *if you've got a team doing this work, shadow them.*

## Shadow First, Then Step In

I talked with my manager and got approval to shadow our newly created threat team. The person on that team was focused on threat hunting, and as I watched him work building queries, running
investigations, and navigating the tools, I felt a strong pull toward that work.

I shadowed for several months, sat in on team meetings, asked questions. When some organizational changes happened in early 2024, I got the opportunity to actually move onto the threat team.

I had made it! Or so I thought. It wasn't that simple.

## The Hard Part Nobody Talks About

Those first few months were brutal. I was overwhelmed by how much there was to learn. So many tools, so many data sources, so many things to look for during investigations. I didn't know where to
start.

I felt like I'd developed a decent high-level understanding of cybersecurity over the years, but now I needed deep technical knowledge, and I was afraid my team would see the impostor I felt like I
was. I was hopping from topic to topic, trying to consume everything at once, and none of it was sticking.

I kept going anyway.

## Finding My Footing

About six months in, things started to shift. I'd spent more time in the tools and was starting to understand them. My team helped me grow. And I stopped jumping between topics and started focusing
deeply on one area at a time.

Two resources made a huge difference:

**The Pyramid of Pain** — This framework shows how painful different indicators are for threat actors when you detect or block them. Hash values and IP addresses are trivial for attackers to change.
But when you target their tactics, techniques, and procedures, it costs them real time and money to adapt. This reframed how I thought about writing hunts. And this expanded my technical knowledge, forcing myself to learn TTPs and not just go searching for IP addresses or URLs.

**The PEAK Framework** — [PEAK](https://www.splunk.com/en_us/blog/security/peak-threat-hunting-framework.html) stands for Prepare, Execute, Act, with everything feeding into a Knowledge repository. Before I found this, my hunts were aimless, I'd jump into queries and logs without
preparation, and when I found something, I didn't know what to do with it. PEAK gave me structure and helped me think like a hunter. It gave me a template to work with that organized the hunts on paper, but also in my mind.

## The Moment It Clicked

At about the one-year mark, I walked into that cloud security meeting I mentioned at the start. I was presenting recommendations to teams with years of cloud experience based on weeks of my own
hunting. I was terrified.

But the recommendations landed. They were well-received. And I walked out of that meeting finally believing that I am a threat hunter.

Impostor syndrome is still there. It was there while I prepared a presentation for SAINTCON. But it gets easier. You push through it more quickly. You recognize the pattern.

## What Actually Made the Difference

Looking back, I realized there wasn't a single pivotal moment. It was years of small things compounding.

That computer science degree I abandoned? It gave me a foundation for reading code and writing scripts. The SOC internship I thought I got just for being available? It started my career. The home lab
tinkering, the conference challenges, the CTFs? All of it came back to help me in ways I never expected. Even building containers in my spare time turned out to be relevant.

One resource I want to specifically highlight: [KC7 Cyber](https://kc7cyber.com/). It's a free program with modules that walk you through investigating incidents, writing KQL queries, examining logs, and finding evidence
of attacks. It was incredibly helpful and genuinely fun.

## What You Can Take From This

Here's what I'd tell anyone trying to make a similar transition:
**Be proactive.** Don't wait for opportunities to come to you. Seek out resources, get hands-on experience, participate in communities. This was the single biggest factor in my growth.

**Take a focused approach to learning.** I made the mistake of hopping from topic to topic. A few years ago I built a Pwnagotchi from old conference badge parts, took it around the neighborhood, it
didn't work, so I dropped it. I wish I'd stuck with it and figured out why. You learn more from debugging one thing deeply than skimming ten things. I took a more focused approach to my homelab, working through why things weren't working properly until I finally figured it out, and learned from it.

**Don't discount what you've already done.** Every conference, home lab project, book, and CTF I completed contributed to where I am now. Even the things that seemed irrelevant at the time.

**Find your resources.** GitHub's awesome lists, people you follow in the field sharing reports and guides were all critical to building my skills as a threat hunter. Seek for resources in what you
want to pursue. The community is amazing and people are so willing to help.

**Network meaningfully.** I've seen people collect LinkedIn connections with no follow-up. When I worked on our apprenticeship program and got 30 referrals, I reached out to every single person,
offered to meet with them, answer questions, share tips. One person took me up on it. Be that one person.

**Document everything.** It improves your writing, which matters more in cybersecurity than people think. Threat reports, findings, recommendations, writing is a core part of the job. Start a blog and
document what you are learning, someone is bound to find it useful.

**Help others.** You don't have to be an expert. You just have to be a little further along than someone else. When I was new, the smartest people in the room often went over my head. But someone just
a step ahead of me could explain things in a way that clicked. We all know more than we think we do.

## Final Thought

If you're sitting where I was, feeling stuck in a non-technical role, wondering if you're cut out for this, battling impostor syndrome every day, just keep going. Shadow a team. Find your resources. Focus
deeply instead of broadly. Compare yourself to who you were a year ago, not to the person next to you.

The path from impostor to *insert your field* isn't a straight line. It's years of small steps, unexpected connections, and refusing to stop.

---

*This post is adapted from my talk [Impostor to Hunter: My First Year as a Threat Hunter](https://www.youtube.com/watch?v=Qxi_yOiI0cw) presented at SAINTCON 2025. If you want to connect or talk about threat hunting, cybersecurity careers, or your
own journey, feel free to reach out. I'd love to hear from you.*