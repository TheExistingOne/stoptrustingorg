---
layout: post
title: Stop Trusting .orgs!
subtitle: Evaluating URLs and the myth of the trustworthy TLD
date: 2024-03-03 11:44 -0800
categories: [Advice, Evaluating Sources]
tags: [websites]
---

If you've ever taken a media literacy course, you've probably seen one piece of advice repeated: .org means a site is more trustworthy than .net or .com. The explanation that is usually given for this is that the ending of the site conveys what kind of site it is, with `com` being *com*mercial, `net` being general inter*net* sites, and `org` being non-profit groups or other *org*anizations. Just looking at the names that may make sense, but in fact *anyone* can register a site under any of those domains. At time of writing this site, with its .org, costs me only 10.47 a year. In other words, no: .org is not more trustworthy and you shouldn't take it into account when researching. Neat and tidy answer, right? Unfortunately, this creates some additional questions: Why are they so similar to those categories if anyone can register one? What about `.gov` or `.edu`? What should I check instead? What even is that ending for? These questions all lead directly down the rabbit hole of how URLs work, so let's dive in.


## What is that ending for anyway?

That little bit at the end of the website address we've been talking about is what's called a Top Level Domain, or TLD. You probably see them so often that they blend into the background, but believe it or not, they haven't always been there. In the earliest days of the internet, when it was still just a small group of labs and universities, there were no TLDs. This worked fine at that small scale, but as the internet expanded, a better system was needed. This is when IANA[^1], the Internet Assigned Numbers Authority, created the first TLDs: .com for commerical entities, .org for non-profit orginizations, .net for computer networks, and a few others. 

Aha! We've found the origins of the myth! You see, TLDs were originally intended to organize websites into these categories, making it easy to identify what kind of site you were accessing. For the most part, that fell by the wayside almost immediately and anyone can now register whatever kind of source they want in any TLD. Nowadays, there are hundreds of TLDs[^2], and which one a site uses only really matters for some of the behind-the-scenes of the internet. From a user's or researcher's perspective, it's just something they have to remember when going to a site.


## But what about .gov and .edu?

It's not quite correct to say that the TLD never carries information about the source, though. What we've been talking about up until this point are what IANA calls Generic Top Level Domains. These are domains that are accessible to everyone and carry a wide variety of sites. There are, however, some TLDs that still restrict who can use them. These are called Sponsored Top Level Domains (sTLDs), and they can be a lot more useful. .gov for example can only be used by sites created by the US government, so if you see whitehouse.gov for example, you can be sure that the information there was published by the US government. There are 16 in all[^3] and they all have a specific requirement for who can use them.

This specificity means that you can factor them into your evaluation of a source, but it doesn't mean that they're perfect identifiers. .edu for example is restricted to accredited schools, but a number of universities allow students to post to their websites, so it's not a guarantee that the university supports that infomration. Some sTLDs may have biases of their own to be aware of. A site ending in .mil will always be a site for the US military, but that means it may not be an unbiased source about an ongoing conflict, for example.


## What should I check instead?

If the site you're looking at doesn't have a restricted TLD it might seem like looking at the URL is useless, but it often does still carry useful information. If there are a couple of similarly named groups appearing in your research, you can cross-reference the URL to tell them apart. Looking at the end of a URL can also sometimes tell you about what part of a site or orginization you're accessing, such as how Google distinguishes between google.com for searching the internet and google.com/imghp for searching images. If you want to know who registered a site you might even be able to look it up with IANA's parent orginization ICANN using ICANN whois[^4].

Beyond a few tricks like this, there's unfortunately not an easy shortcut for evaluating a source with the information attached to it. Information like a URL and the content on the site itself is fully within the publisher's control. The only way to really figure out if a source can be trusted is to get your hands dirty and look around for more information. It's not as tricky as it sounds, though and you get the hang of it over time. Media literacy is a skill like any other, and it'll take time to learn, so don't get discouraged. You're already on the right track!


## Additional Resources

Thanks for reading! Hopefully I've been able to give you a little bit of a better understanding of how URLs can influence your research. If you'd still like more information on TLDs and evaluating websites, I've linked a few more articles to take a look at.

- [ICANN Learn](https://www.icann.org/en/beginners/courses-and-learning)
- [What is a Top Level Domain? - Cloudflare](https://www.cloudflare.com/learning/dns/top-level-domain/)
- [Lateral Reading - Northwest Arkansas Community Colleges](https://library.nwacc.edu/lateralreading)


---

[^1]: [https://www.iana.org/](https://www.iana.org/)
[^2]: [https://www.iana.org/domains/root/db](https://www.iana.org/domains/root/db)
[^3]: [https://en.wikipedia.org/wiki/Sponsored_top-level_domain](https://en.wikipedia.org/wiki/Sponsored_top-level_domain)
[^4]: [https://lookup.icann.org/en](https://lookup.icann.org/en)
