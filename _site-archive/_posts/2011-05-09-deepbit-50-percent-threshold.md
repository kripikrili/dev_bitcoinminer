---
layout: post
title: DeepBit pool temporarily reaches critical 50% threshold
date: '2011-05-09T02:27:00+08:00'
tags:
- deepbit
- mining
- threshold
- '50'
- fifty
- 50%
- fifty percent
- "%"
- percent
- percentage
- 50 percent
- slush
- bpm
- bitcoin
- pooled
- pool
- mining
- double spend
- double spending
- double
- spend
- spending
- exchange
- reversible
tumblr_url: http://bitcoinminer.com/post/5328668205/deepbit-50-percent-threshold
---
For the first time ever a single pool has reached the point at which the pool’s hashing power has exceeded the critical 50% threshold.
Bitcoin’s decentralized structure gives authority to 50% + 1 of the network hashing power.  If a single entity or a party that is colluding together reaches this point the potential to do a double spending attack exists.
This situation occurred as the result of a service outage at another large pool.  Slush’s pool, BPM (Bitcoin Pooled Mining), went offline and as a result many miners switched to DeepBit and other pools.  DeepBit’s share dropped back down once miners realized that the threshold had been exceeded and then responded by patronizing other pools and from those who returned to BPM once the service there was restored.
There were no reports of any blockchain forks occuring but this situation has caused concern for some as it is a vulnerability that had only previously been viewed as a hypothetical.
DeepBit’s operator, Tycho, opened discussion for establishing a monitoring service that would detect blockchain forks as well as double spending attempts.  There are some, however, who would prefer to see other methods in place such that single pools don’t get large enough to where they could hit that 50% threshold.
Even with control of 50% of the network strength, a double spending attack would be difficult to carry out successfully.  Those who are most at risk of such an attack are those who accept bitcoins and, in exchange, will release funds that are non-reversible (Liberty Reserve, as an example) before waiting for the recommended six confirmations.
This specific situation is why Bitcoin payments are not considered “confirmed” until enough subsequent blocks have been solved such that there is effectively no chance that that a double spend attempt would be successful.
Fortunately, it appears that today was not the day that the first such attack was attempted.
Previous Posts
