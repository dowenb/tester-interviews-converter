---
layout: single
title:  "Interview with Christian Baumann"
date:   2021-02-20 10:20:47 +0000
categories: interviews
---

## Christian Baumann

Twitter: [@chrissbaumann](https://twitter.com/chrissbaumann)

LinkedIn: <https://www.linkedin.com/in/christianbaumann/>

## Interview

### Where are you in your testing journey?

Difficult to answer: 16 years away from where I started, and the more I learn and do, the more awesome people I discover and get to know from the community, the longer grows the list of things I want to try out and want to learn about.

My current position is "Senior Software Tester", and in that role luckily I have a lot of freedom to do what I think is appropriate. It's a great chance for learning. Also my team mate Violetta is a great peer for exchanging thoughts and learn from.

### The best bug you have ever found?

One of the most used conversation starter among testers, isn't it? - And I never have an answer to that.

But I like telling the story of one of the worst bugs I ever missed instead: The system we developed at the time had a basic DMS included. And the numeric ids of a document in the database represented a folder structure, so the document with id "123" would be at "/1/2/3" (and the document with the id "12" was at "1/2"). We only later added the functionality to delete documents again and it was implemented, that the whole folder with all subfolders was deleted. So deleting the document with the id "12" would also delete the document with id "123" (and all other documents with ids starting with "12").
Unfortunately a client found this bug, instead of me.

### Advice you would give to Testers?

Always stay curious and continue learning.
If you're feeling imposter syndrome, you're most probably not an imposter!

### What does winning mean to you?

Reaching the goal you had planned to reach.
