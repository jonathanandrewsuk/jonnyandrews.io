---
date: '2021-06-07 16:53 -0400'
published: true
title: The basic idea... bank statements
description: The basic idea... bank statements
---
## Here's what im going for

After some thought, I've decided to focus my project on bank statements. They are a ubiquotis product that hasn't seen much change in my lifetime.

I know this initial reveal of an idea isn't going to be knocking your socks off but that's the point. If I can make bank statements more accessible (from a usability point of view, or just from an engement point of view) then I ca see that being a useful service to lots of people.

I know I said that profit wouldn't be top of mind, but my mind wanders in that direction. My thoughts is that this will be primarily a B2B product, I would provide this as an API or docker image for fintechs. **They can now offer accessible statements in their app/service!**

The foundation for my prototype will be the plaid API, I think I can use their transaction history endpoint to put together a monthly statement.

## In my mind it currently looks like this:

- react front end using remotion to display my "statements" as videos
- express API that pulls data from plaid and synthesizes it into a remotion config object

...thats it's

If I can get that working from the plaid sandbox it will be great first step. There are plenty more features that my mind goes to, but I'll stick firmly to those points for now.

**Next steps:**

1. Do a hello world project with re-motion
2. Create a developer account at plaid and look at the statements endpoint.

__in an effort to keep things moving, I'll keep these steps bitesize__

