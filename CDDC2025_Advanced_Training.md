
# CDDC 2025 Training Advanced Challenges

The `harder` challenges... (More fun :))

## Overview

```
Challenge                                     Category       Flag
[OSINT-02] declassified                       Advanced       CDDC2025{the_bulgarian_air_force}
[OSINT-03] past                               Advanced       CDDC2025{its_not_just_talk_about_games_its_what_gamers_are_talking_about}
[OSINT-04] what_kind_of_technology_is_it      Advanced       CDDC2025{WoW_IS_VERY_INTERESTING_TECH}
[OSINT-05] connections                        Advanced       CDDC2025{johan_minkowski}
[OSINT-06] livestream                         Advanced       CDDC2025{takeshiba}
[OSINT-07] WHOISTHISPOKEMON                   Advanced       CDDC2025{Finally?OMGAfterSomanyPIKKAhints!}
[OSINT-08] WHERETHEHACKAMI                    Advanced       CDDC2025{H0wd1dy0uKn0wwwh3r3iWAS}
[OSINT-09] GOld Chain                         Advanced       CDDC2025{transparency_immutable_decentralized}
```

# Template
## [OSINT-02] declassified

**Challenge**

Heads up, Brainhackers!

Let's brush up your OSINT skills so that our mission is successful.

The site cia.gov released a pdf document on 30 July 2012 about Bulgaria.

What is the subject of the document?

**Solution**

google => `cia bulgari 30 july 2012`

First pdf document matches dates

Get the subject.

**Flag**

```
CDDC2025{the_bulgarian_air_force}
```

## [OSINT-03] past

**Challenge**

Star is teaching you how to go back in time, but not physically.

If you go to allgames.com, you can see that its tagline is "Talking about video games and...".

Can you see what was its tagline on 1 January 2005?

**Solution**

We are given the title `past` and website `allgames.com`.

Use the Wayback Machine.

Check the snapshot on `1 Jan 2005`

Found the tagline.

**Flag**

```
CDDC2025{its_not_just_talk_about_games_its_what_gamers_are_talking_about}
```

## [OSINT-04] what_kind_of_technology_is_it

**Challenge**

What is the name of the technology that allows Windows 32bit applications to run on Windows 64bit?

**Solution**

WoW64

**Flag**

```
CDDC2025{WoW_IS_VERY_INTERESTING_TECH}
```

## [OSINT-05] connections

**Challenge**

Star really likes to emphasize the importance of Opsec.

As an example, she told you to take a look at the Reddit account 'quantumcat78'.

Based on his posts, can you tell his real name?

**Solution**

Given a reddit account name `quantumcat78` => Take a look on `reddit`

We can see in his posts that his github account was mentioned. (https://github.com/johanmint)

In his github account, we can find his email, which is his full name. (johanminkowski@zohomail.com)


**Flag**

```
CDDC2025{johan_minkowski}
```

## [OSINT-06] livestream

**Challenge**

In her spare time, Star likes to randomly watch a livestream of places around the world.

In the video, a train is passing along the elevated rail tracks.

What is the next station the train will stop?

**Solution**

Given a mp4 video of a city area with two trains running parallel.

For these types of challenges, we have to analyse the general landscape and find key characteristics.

The first thing I did was to try identify the lower train via a `reverse image search`.

Found out that it is a Japanese Train (Japanese 251 series), which typically runs towards the Izu Peninsula, Japan.

Now that we know that it's in Japan, we can try to search for the other train, with its distinct blue railway tracks and train shape.

Using another `reverse image search`, we found out it's the `yurikamome train`.

Google search to find its map and general location. (https://ontheworldmap.com/japan/city/tokyo/tokyo-yurikamome-line-map.html)

For the final step, we need to find its exact location to determine the station.

We can see that there are 4 key characteristics.


**Flag**

```
CDDC2025{takeshiba}
```

## [OSINT-07] WHOISTHISPOKEMON

**Challenge**

?

**Solution**

?

**Flag**

```
THE FLAG
```

## [OSINT-08] WHERETHEHACKAMI

**Challenge**

?

**Solution**

?

**Flag**

```
THE FLAG
```

## TITLE

**Challenge**

?

**Solution**

?

**Flag**

```
THE FLAG
```

## [OSINT-09] GOld Chain

**Challenge**

?

**Solution**

?

**Flag**

```
THE FLAG
```
