# Practical Project Management

## Sponsored by Sentry.io

Relying on customers to report errors is not good. It's rude to customers and bad for business.

Ideally, this would be solved easily with tests. Why not just cover every scenario with a test? Then life would be perfect and fine and great. Because here in reality, humans are pretty bad at writing tests. Not just because we’re all kinda lazy and maybe a little dumb, but also because we can’t anticipate every single way users are going to interact with our product. They might do something really, really, really stupid (or something really, really, really smart) that we didn’t think about.

That’s why [Sentry](https://www.sentry.io) tells you about errors in your code before your customers have a chance to encounter them.

Not only do we tell you about them, we also give you all the details you’ll need to be able to fix them. You’ll see exactly how many users have been impacted by a bug, the stack trace, the commit that the error was released as part of, the engineer who wrote the line of code that is currently busted, and a lot more.

Your code is broken. Let’s fix it together. [Sentry.io](https://www.sentry.io).

## Things Mentioned

- [Gigalixir](https://gigalixir.com/)
- [Nuxt.js](https://nuxtjs.org/)

## Project Management & large changes to core infrastructure

**Spend as much time as you can afford up front thinking, taking, and writing about the feature.**

At Design Kollective we have a functional spec document template that we use for new features. The documents are broken up into sections: **summary** (What is this thing in layman's terms?), **business requirements** (what are the high level goals of this thing?), **user stories** (practically what does this look like to a user?), **implementation details** (get into the weeds - on a technical level what needs to happen to make this a reality), **additional details** (tangential info, questions, notes from conversations).

**Break the project into manageable phases or steps.**

This will help you divvy up the work into a logical progression and will also help you to provide timeline estimates or even a road-map to your teammates or customers.

**Sleep on it.**

It's easy to get into a rushed "we have to ship this mode", but most of the time it's better to sleep on touch decisions, or decisions where the immediate effects aren't clear.

**Over communicate by leaving bread crumb trails for yourself.**

It can be easy to skip over documenting small or important details when you're in a flow state. I always try to leave notes, comments in code, or add extra context to the functional spec document with the assumption that I'll have no idea what I was talking about later. Sometimes at the end of the day I'll even write a summary in notion as to what I was doing, and what I planned on doing next. This has saved me many many times. When working remotely it's important to over communicate, and I try to treat my future self just like another remote employee.

**Mind the feature's scope.**

Balloons and all that. Dont make a project bigger than its supposed to be by adding "fixes" or cleaning up other TODOs while you're in there.

**Try to wrap core functionality as possible.**

Minimize a feature's surface area - RS. This is in the weeds a bit when compared to the process, but one thing that has worked well for Design Kollective's code base is to wrap core functionality into modules, like Dk.Pricing, which is in charge of all logic used in calculating a product's price.

## Leave us a review

Last but not least, if you haven't rated or reviewed the show yet and you'd like to do us a huge favor, [you can do so by clicking here!](https://itunes.apple.com/us/podcast/does-not-compute/id1048731980?mt=2)

## Show Notes Archive

If you're looking for a link we've mentioned in the past, head on over to the [Does Not Compute](https://dnc.show) site! We've even included a search tool for you to use to find episodes that touch on specific topics.

## Join Us On Spectrum

If you have enjoyed the show so far, reach out to us on twitter at [@seanwashbot](https://twitter.com/seanwashbot) and [@Schrockwell](https://twitter.com/schrockwell), or join us in the Spectrum community at [https://spectrum.chat/specfm/does-not-compute](https://spectrum.chat/specfm/does-not-compute)!
