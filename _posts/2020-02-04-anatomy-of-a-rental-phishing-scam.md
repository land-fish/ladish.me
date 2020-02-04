---
title: "Anatomy of a rental phishing scam 🎣"
excerpt_separator: "<!--more-->"
categories:
tags:
---
I was recently the (unsuccessful) target of a very well-crafted phishing scam. I think the scam involved a whole team of people, including at least one skilled developer and probably several others. 

As part of a housing search a few weeks ago, I was trawling craigslist and zillow for rental opportunities in the SF bay area. Below I will account the story in excessive detail including screenshots.

I’m writing this to illustrate that the best phishing attacks will look **very convincing**. They will use good English and pattern-match with legitimacy. The key to is be aware for a few small signs that give away the scam away for what it is, and use best practices so you won’t fall for these.

The two key take-aways: When engaged in a financial transaction with an individual, a desire to interact “only through email” is a huge red flag. If it’s a large transaction, a call or videocall should be necessary. And finally, always check the URL of a link if there is any doubt whatsoever!

# The listing 🗒
![](/assets/images/phishing1.png)

Legit looking listing.

# The initial emails 📫

The craigslist ad asked serious applicants to call, but didn’t list a phone number. At first, I thought this was an oversight, as it certainly wouldn’t be the first time someone left that information out in their ad. I replied to the craigslist add saying I was interested, asking for the phone number, and providing my own.

I reply to the craigslist ad, noting that there is no phone number listed.

![](/assets/images/phishing2.png)

# At this point, I had not realized this is a scam 🙃

The fact that the landlord says he is away most of the time is a little unusual, but not by that much. Plenty of the landlords I contacted in this search lived far away. The questions listed here are pretty normal questions, and I went ahead and answered them.

I got the following reply:

![](/assets/images/phishing3.png)

# The red flags started here. With this email, I was 80-90% sure it was a scam 🕵️‍♀️

The first red flag was “So we’ll keep our communication to email if that’s ok with you”.  The second was the weirdness about Airbnb. Why would they want me to pay through Airbnb? The third was the excessive amount of pictures to convince me this was a real person. If they were in fact a real person, why were they trying so hard to convince me?

The Airbnb part actually threw me. I figured at this point this was likely a phishing scam, but I wasn’t sure. If I was pretty sure their scam wouldn’t work if I actually booked their place through Airbnb, since Airbnb has a pretty good dispute resolution process and would flag that kind of thing pretty quick. I showed a friend this ad, and they thought it wasn’t a scam. We should have made a bet, because I would have won.

At this point, I decided I’d follow this to the logical conclusion, so I asked for the Airbnb link.

![](/assets/images/phishing4.png)

Wait what? They wanted me to search Airbnb for their listing. This was weird, but it didn’t make any sense. If they were trying to scam me, booking their place on Airbnb wasn’t a sensible way to do it.

But wait, I couldn’t find their place on Airbnb. So I asked for the link…

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

The phishing team—and given the work involved and the level of polish I bet it was a team—ran a pretty tight operation. Their English was perfect, their emails looked professional, and their phishing site looked identical the original Airbnb site. 

I’m even more impressed by their subtle psychological tricks. Each step of the way, they left out information which required **me** to ask for something if I wanted to proceed. It’s a lot easier to be on your guard when others are asking you for things. When you’re the one doing the asking, it’s even harder to say something when things look strange, because you may already feel like you’re being a burden on their time. For the initial ad, they left out the phone number so I had to ask. After they directed me to the airbnb site that didn’t exist, I had to ask for a link. 

Throughout these interactions, they mentioned there were other people looking, maintaining a plausible sense of urgency. Finally, using Airbnb as the phishing site was clever, because it gave the impression of a trusted middleman. I was genuinely thrown off at first, because I couldn’t figure out how they were planning to steal my financial information. If they had just asked for bank or credit card information early on, their game would have been easy to spot.

# Thanks for playing! 🎮

I hope you found this useful. Stay safe out there!
