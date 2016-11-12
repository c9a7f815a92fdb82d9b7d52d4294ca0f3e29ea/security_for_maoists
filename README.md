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
- anything that could implicate you or your comrades in a conspiracy investigation for
  a planned action

We should also use caution when discussing overall revolutionary strategy,
the merits of different approaches to armed struggle, etc. While these are
important topics to discuss and struggle over they are probably not great
conversations to have the FBI clued in to.

Using a secure messaging app to coordinate meeting times, discuss news
articles, share analysis, and plan meet-ups with comrades and collectives
in other cities is tremendously useful, so we shouldn't shun technology
completely, but instead understand how to use it relatively safely and
when to put the phones in the other room. 

## Why does encryption work? Why is it necessary?

Encrypting a message to prevent it's being read is done, more or less, by
messing up and scrambing the message in a way which obscures it's contents
to a bystander, but which can also be completely un-scrambled by someone
who holds the right secret. This could be a password, or a secret number,
a thumb print, etc.

All of the schemes (cryptosystems) for doing this work measure their
security in terms of how much computation it would take an uninformed
eavesdropper (one who doesn't have access to the secret) to decrypt the
message. This is called 'brute-forcing' the message. Modern cryptography can be
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
a cryptosystem is to break. This is why our most sensitive discussions
should be conducted offline and face-to-face.

## Okay, so what software is good to use?

### Mobile phones

On phones the only messenger I trust is
[Signa](https://whispersystems.org/). There are a variety of other options
out there, but all of them have at least one flaw. Signal has problems as well,
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

Signal should be understood as a significant increase in security over 
SMS (text) messages, but it is not a silver bullet. In general, smart
phones should not be trusted with sensitive data. The two major types
of phones that are available (android and iOS) are both not trusted platforms.
Both of them incorporate extensive amounts of closed-source code which
cannot be audited for its security properties, and both of them have had
exploits developed for them by arms companies and government agencies 
which turn them into active listening and surveillance devices.

With that in mind, a few points:

- do not have any kind of meeting or discussion about revolutionary
politics with phones in the room if you can avoid it. they should be 
switched off, with the
battery removed (if possible) and behind a closed door.
- switch your phone off if you are going to be arrested or detained
by the state. when a phone is switched on the data on it is much 
more vulnerable to interception. even relatively
innocuous data about meeting times can be valuable to the state.
- make sure your phone is encrypted. on iOS this is accomplished by 
setting a strong passcode. this should optimally be 10 or more characters long.
on android this is accomplished by selecting an option to encrypt the
phone, which is usually located in the settings menu under 'security' or
similar. if the phone is encrypted it will be much harder for the state
to get useful information off of it, provided the phone is switched off
when they get ahold of it (technical detail: when the phone is switched off
the decrypted key used for full disk encryption must be held somewhere in memory,
so it is vulnerable to attack and could then be used to decrypt all of the
data on the device).
- switch your phone off or leave it behind if you are attending an action 
or demo that confronts the state in any serious way. if you think you may
be arrested at a protest you should strive to leave your phone at home, and
if an action is potentially going to feature a militant stance in opposition
to the police, to fascist forces, etc it is possible the geolocation data from
your phone could establish your presence there. in short, the phone should stay
at home or, at the least, in the car for the same reason that we mask up when
engaging in militant street protests - it provides a basis for actually
increasing the level of militancy we're capable of.
- follow guides for secure mobile phone use, and generally ensure that:
	- your phone automatically locks when you leave it alone
	- your passcode is long and hard to guess
	- you generally maintain physical control over your device and do not
	loan it to people you do not trust.
