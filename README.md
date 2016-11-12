# Security for Maoists

Our task as communists is to organize in order to develop a proletarian
political force capable of exercising dictatorship over the bourgeoisie.
Proletarian power is radically heterogeneous to the bourgeois state, and
for that reason we can expect that the state will use any and all means to
oppose us. Our commitment to realizing proletarian power and destroying
the dictatorship of the bourgeoisie means that we must take every
reasonable precaution to safeguard ourselves and to minimize interference
and surveillance by state forces. The purpose of this document is to
provide militants who are organizing to build proletarian power with the
necessary tools to make better decisions about these matters, and in
particular about tools for secure communication.

The deviations to be avoided when discussing security are empiricism
(paranoid fascination with the objective power of state surveillance that
manifests as paralysis) and being overly subjective (thinking that these
questions aren't yet serious, that it's too hard, that these things are
'immaterial' and generally can't be studied by the same methods we employ
when analyzing political situations, etc). Imperialists are paper tigers,
and surveillance cannot counter the political force of the united masses.
We should be objective, however, about where we're at right now and what
steps we can and should take. With this document I'm seeking to lay out
some basic recommendations for how we can be security conscious in our
organizing, and hopefully provide a basis for guiding decisions that build
up our organizations and better equip up to bring the fight to the enemy.

## Should we use electronics when organizing at all?

Communicating electronically, whether by phone call, SMS, email, OTR chat,
etc. always carries some risk of interception. Does this mean we shouldn't
use computers at all, and do everything face-to-face? I don't think so.
However, you should use good judgement, and probably not use a phone or
computer to discuss:

- anything that could lead to a felony conviction
- anything that could implicate comrades in a conspiracy investigation for
  a planned action

I would also use caution when discussing overall revolutionary strategy,
the merits of different approaches to armed struggle, etc. While these are
important topics to discuss and struggle over they are probably not great
conversations to have the FBI clued in to.

Using a secure messaging app to coordinate meeting times, discuss news
articles, share analysis, and plan meet-ups with comrades and collectives
in other cities is tremendously useful, so we shouldn't shun technology
completely, but instead understand how to use it relatively safely and
when to put the phones in the other room.

## Why does encryption work? Why is it necessary?

Encrypting a message to prevent is being read is done, more or less, by
messing up and scrambing the message in a way which obscures it's contents
to a bystander, but which can also be completely un-scrambled by someone
who holds the right secret. This could be a password, or a secret number,
a thumb print, etc.

All of the schemes (cryptosystems) for doing this work measure their
security in terms of how much computation it would take an uninformed
eavesdropper (one who doesn't have access to the secret) to decrypt the
message. This is called 'brute-forcing' it. Modern cryptography can be
very, very expensive to brute force, on the order of 'two years on a big
supercomputer'. Encryption doesn't work because it makes it impossible to
read a message *per se*, but instead it works because it makes it very
expensive and therefore practically infeasible to do so.

Anyway, encryption works because brute-forcing things requires fixed
capital (big computers, lots of electricity) and, more importantly, a lot
of labor (really tightly optimized software to perform the brute forcing
calculations as efficiently as possible). Our enemies have massive
resources in this area, but they do not have infinite resources.

Of course, people can always make mistakes writing the software that
implements encryption, or in doing the math to prove how hard
a cryptosystem is to break.

## Okay, so what's good to use?

On phones the only messenger I trust is
[Signa](https://whispersystems.org/). There are a variety of other options
out there, but all of them have some flaw. Signal has problems as well,
including exposing some metadata to the GCM (Google Cloud Messaging)
service it uses to push messages to an Android phone. However, it isn't
really possible to use a smartphone without leaking quite a lot of
metadata anyway, and using Signal is certainly a big upgrade over plain
SMS messages.

Signal has support for groups, which is pretty good, and on Android you
can also use Signal to send normal SMS to people who do not have
smartphones (which is just sort of a convenience thing). This is also an
option for 'disappearing messages', which automatically deletes old
messages, and should always be turned on. There is also a Chrome app
client for Signal which makes it easier to type long messages.



For long-form communication

When we encrypt something we make a sort of wager. E

Overall, I want to avoid just providing a list of software to install or
practices to engage in. Firstly, there are a number of such lists already,
it would be idealist to think providing another could help. Secondly, many
communists are already acquainted with such lists and have failed to put
these things into practice. So there's a real need to discuss the basis
for using encryption and generally for thinking materially about security
as a key part of our organizing, and to oppose the incorrect thinking that
comrades sometimes engage in with material analysis of the surveillance
capabilities of the state, our ability to mitigate it, etc.

## points to hit

- importance of having good practices
    - we can't guarantee perfect security, but we can make concrete
      improvements, it's not a liberal 'everything is everything',
      encrypting everything does actually make it harder for the state to
      figure out what you're doing
    - concretely, organizing in opposition to the state means that it's in
      the state's interest to surveil and disrupt our organizing
    - some basic and very small organizational changes can lead to
      a really big increase in overall security
    - this doesn't apply simply to computer related and electronic stuff,
      but also to general organizational practice, like talking to
      contacts, sharing details and documents with other people,
      publishing public documents, etc.


- dialectal determination of security:
    - capabilities of the attacker
    - physical access to the system
    - it is only meaningful to assess the actual strength of encryption
      and other countermeasures in their concrete manifestation
    - security researchers totally acknowledge this, many of them focus on
      practical matters, and try to actually break into real systems as
      they are deployed in the world (defeating ATMs or voting machines or
      something)

- encryption
    - it's math it works

meh that's all for now
