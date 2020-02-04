---
title: "Anatomy of a rental phishing scam 🎣"
excerpt_separator: "<!--more-->"
categories:
tags:
---
I was recently the (unsuccessful) target of a very well-crafted phishing scam. As part of a housing search a few weeks ago, I was trawling craigslist and zillow for rental opportunities in the SF bay area. I reached out to a beautiful looking rental place to inquire about a tour. Despite my experience as a security professional, I didn't realize this was a scam until about the third email! Below I will account the story in excessive detail including screenshots.

I’m writing this to illustrate that the best phishing attacks will look **very convincing**. Often people are told to watch out for poor grammar and formatting to protect against phishing. This will work in some cases, but not in cases like the one I'm about to show. Sophisticated scammers use good English and pattern-match with legitimacy. 

# The listing 🗒
![](/assets/images/phishing1.png)

Legit looking listing.

# The initial emails 📫

The craigslist ad asked serious applicants to call, but didn’t list a phone number. I thought this was just an oversight, since many of the other ads I'd seen had information like that missing. I replied through craigslist saying I was interested, asked for the phone number, and provided my own. 

I get a text from the landlord telling me to contact him at "davidgrinde@engineers-hibernia-chevron.ca". You might think this would have seemed odd to me, but honestly the rental search involved lots of ridiclousness about phone number and emails and runarounds. I sent off an email to that address that the person replied with this:

![](/assets/images/phishing2.png)

# At this point, I still had not realized this is a scam 🙃

The fact that the landlord says he is away most of the time seemed a little unusual, but not by that much. Plenty of the landlords I contacted in this search lived far away. The questions listed here are pretty normal questions, and I went ahead and answered them.

I got the following reply:

![](/assets/images/phishing3.png)

# The red flags started here. With this email, I was 80-90% sure it was a scam 🕵️‍♀️

The first red flag was “So we’ll keep our communication to email if that’s ok with you”.  The second was the weirdness about Airbnb. Why would they want me to pay through Airbnb? The third was the excessive amount of pictures to convince me this was a real person. If they were in fact a real person, why were they trying so hard to convince me?

The Airbnb part actually threw me. I figured at this point this was likely a phishing scam, but I wasn’t sure. I was pretty sure their scam wouldn’t work if I actually booked their place through Airbnb, since Airbnb has a pretty good dispute resolution process and would flag that kind of thing pretty quick. I showed a friend this ad, and they thought it wasn’t a scam. We should have made a bet, because I would have won.

At this point, I resolved to get to the bottom of this, scam or no scam, so I asked for the Airbnb link.

![](/assets/images/phishing4.png)

Wait what? They wanted me to search Airbnb for their listing. This was weird, but it didn’t make any sense. If they were trying to scam me, booking their place on Airbnb wasn’t a sensible way to do it.

But wait, I couldn’t find their place on Airbnb. So I asked for the link again…

![](/assets/images/phishing5.png)

They sent me the link. It looked legitimate. See that “airbnb.com” domain? This ain’t my first phishing rodeo, so I checked the real destination of the link. If look at the plain text of the email, this is what I see: 

![](/assets/images/phishing6.png)

# Smoking gun 💨🔫

That’s right, it’s a phishing site. Let’s check it out.

![](/assets/images/phishing7.png)

This screen shot is taken a few days later. When I first investigated, Chrome did not display the “Dangerous” warning by the URL. This phishing site was well done! It was interactive and looked quite convincing! I can easily imagine someone not paying close attention to the URL being fooled.

![](/assets/images/phishing8.png)

Excellent fake reviews. 5/5 would phish again. 

I didn’t explore the “request to book” link, but I’m sure it would have taken me to a credit card phishing page. Thanks, maybe another time.

# Why am I impressed by this? 🤔

The phishing team—and given the work involved and the level of polish I bet it was a team—ran a pretty tight operation. Their English was perfect, their emails looked professional, and their phishing site looked identical the original Airbnb site. The email domain "engineers-hibernia-chevron.ca" redirected to "hibernia.ca" to add legitimacy for those who took the extra step of looking up the domain.

I’m even more impressed by their subtle psychological tricks. Each step of the way, they left out information which required **me** to ask for something if I wanted to proceed. It’s a lot easier to be on your guard when others are asking you for things. When you’re the one doing the asking, it’s even harder to say something when things look strange, because you may already feel like you’re being a burden on their time. For the initial ad, they left out the phone number so I had to ask. After they told me I could look at their airbnb site, I had to ask for a link. Then, after they sent me to search on Airbnb's site, I had to ask for the link **again**! That was deliberately planned! 

Throughout these interactions, they mentioned there were other people looking, maintaining a plausible sense of urgency. Finally, using Airbnb as the phishing site was clever, because it gave the impression of a trusted middleman. I was genuinely thrown off at first, because I couldn’t figure out how they were planning to steal my financial information. If they had just asked for bank or credit card information early on, their game would have been easy to spot.

# Takeaways to protect yourself 🛡
1. When engaging with strangers online, always check the source of their links! Usually just clicking won't hurt you, but in some cases that is enough. I wasn't 100% sure this was a phishing scam until I saw the fake Airbnb URL, but that confirmed it.
2. Remember sender email addresses can be spoofed and domain names may not be what they appear! Just because you recieve an email from "investigations@fbi.gov" does not mean the FBI has sent you an email.
3. Look for signs that someone is toying with you. Does it seem like they're trying to convince you that they're real? Are they projecting a sense of urgency?
4. Use multiple channels to verify someone's identity. The first red flag here was the scammer saying they could only interact by email. If someone is remote, have a videocall with them, and cross reference with their linkedin, facebook, etc.  

# Thanks for playing! 🎮
I hope you found this useful. Stay safe out there!
