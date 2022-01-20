---
layout: post
title:  "Simple is Good: Jekyll vs Wordpress"
date:   2016-02-01
categories: peripheral code stuff
---
The more I use Jekyll the more I love it. Seriously, it's a blogging tool that
puts the focus on blogging. At first the simplicity of it shocked me. Markdown is
hard to get used to but it beats wrestling with clunky in-browser text editors.
As I've
used Jekyll I've liked it more and more. It's a shame the github pages are
used primarily for programming blogs because Jekyll should be used more widely
 for all sorts of topics. Sometimes all you need out of a blogging tool is a
 blogging tool. The only downside is that Obama used it during his campaign.
 Just kidding.

Wordpress started out as something similar if I recall right. It was a simple
tool meant for managing simple sites. Nowadays Wordpress is quite different.
It gives you a lot more power but it doesn't feel like it was all planned out
from the beginning. It feels like
developers programmed it, then thought of something useful to add to it. Then
programmed that feature, then thought of something else and went on to program
that. And I'm not even talking about all the plugins you can add in to it. Perhaps it's not
so smart to complain about one of the world's most popular technologies but
that's how I feel about it. It just feels kind of sloppy.
Here's a pocket knife meant to do pocket-knifey things but wait, it also
has a compass, and a butter knife, and a diaper changer.

Successful products do one thing really well. They know their strength and they
play to those strengths. As programmers we can get caught up in small details
and we don't see the forest for the trees. When given a problem, we roll up
our sleeves and furiously type until the code works. But maybe the problem isn't
a problem in the first place. Let me give you an example.

I'm programming a pseudo-multiplayer mobile game called Charity Champs. Recently
I had to figure out what to do on the front-end when another player drops from
a game. Up until now, the game simply continues to wait for the opponent's
response. So I programmed the game to give each player 10 seconds to post
their moves and if they don't by then, the front-end assumes they've been
dropped. Here's where the problem wasn't really a problem. I had the idea in my
head that I should keep the dropped player in the game for the other player to
kill. As I started down this road, I began to realize how much code I would
have to alter. Then I re-defined the problem to be more simple. When someone
drops, just remove them from the game. It makes sense, gamers would expect it.
Why? Because it's simple. It's the first reasonable conclusion a person would
come to. "Their character is gone hmmmm... they must have left."

Complex code leads to developers solving problems that really aren't problems.
That's why simple is good. We want to be solving problems that are actually
problems.
