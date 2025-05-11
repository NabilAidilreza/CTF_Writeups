
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

## 🧠 [OSINT-02] declassified

**Challenge:**  
> The site cia.gov released a pdf document on 30 July 2012 about Bulgaria. What is the subject of the document?

**Approach:**  
1. Googled: `cia bulgaria 30 july 2012`
2. Located the PDF matching the date.
3. Retrieved the subject directly from the document.

**Flag:**  
```
CDDC2025{the_bulgarian_air_force}
```

---

## 🕰️ [OSINT-03] past

**Challenge:**  
> What was the tagline of allgames.com on 1 January 2005?

**Approach:**  
1. Used the [Wayback Machine](https://web.archive.org).
2. Entered the URL: `allgames.com`
3. Navigated to the snapshot from `1 Jan 2005`.
4. Located the tagline on the archived page.

**Flag:**  
```
CDDC2025{its_not_just_talk_about_games_its_what_gamers_are_talking_about}
```

---

## 🪟 [OSINT-04] what_kind_of_technology_is_it

**Challenge:**  
> What is the name of the technology that allows Windows 32-bit applications to run on Windows 64-bit?

**Approach:**  
- Known answer from experience: `WoW64` (Windows-on-Windows 64-bit)

**Flag:**  
```
CDDC2025{WoW_IS_VERY_INTERESTING_TECH}
```

---

## 🔗 [OSINT-05] connections

**Challenge:**  
> Investigate the Reddit account `quantumcat78` to discover the user's real name.

**Approach:**  
1. Searched Reddit for `quantumcat78`.
2. Found a post referencing a GitHub profile: [https://github.com/johanmint](https://github.com/johanmint)
3. From the GitHub profile, identified the email address: `johanminkowski@zohomail.com`

**Flag:**  
```
CDDC2025{johan_minkowski}
```

---

## 🚆 [OSINT-06] livestream

**Challenge:**  
> A video shows a train on elevated rail tracks. Determine the next station the train stops at.

**Approach:**  
1. Analyzed the landscape and train appearance from the video.
2. Reverse image search identified the Japanese 251 series train.
3. Identified the second train as the Yurikamome Line from Tokyo via distinctive blue tracks.
4. Cross-referenced the Yurikamome map and identified landmarks:
   - Green park
   - Elevated expressway
   - Parallel train tracks
   - Railway loop around a building
5. Location matched the **Takeshiba** station.

**Comments**
For these types of challenges, we have to analyse the general landscape and find key characteristics.
The first thing I did was to try identify the lower train via a `reverse image search`.
Found out that it is a Japanese Train (Japanese 251 series), which typically runs towards the Izu Peninsula, Japan.
Now that we know that it's in Japan, we can try to search for the other train, with its distinct blue railway tracks and train shape.
Using another `reverse image search`, we found out it's the `yurikamome train`.
Google search to find its map and general location. (https://ontheworldmap.com/japan/city/tokyo/tokyo-yurikamome-line-map.html)


**Flag:**  
```
CDDC2025{takeshiba}
```

---

## 🔍 [OSINT-07] WHOISTHISPOKEMON

**Challenge:**  
> Discover the Pokémon with a red nose and identify its final evolution form from a `.pcap` file.

**Approach:**  
1. Opened the `.pcap` file using Wireshark.
2. Exported all images from HTTP traffic.
3. Identified the red-nosed Pokémon: Oshawott.
4. From knowledge, the final evolution of Oshawott is **Samurott**.

**Comments**

I cant really say this is a OSINT challenge. (Which confused me at first)

**Flag:**  
```
CDDC2025{Finally?OMGAfterSomanyPIKKAhints!}
```

---

## 🌍 [OSINT-08] WHERETHEHACKAMI

**Challenge:**  
> Determine the travel sequence:  
> 1st: Airport name (ALL UPPERCASE)  
> 2nd: Country name (all lowercase)  
> 3rd: School name (all lowercase)

**Approach:**  
❓ *(Still in progress)*

**Flag:**  
```
CDDC2025{H0wd1dy0uKn0wwwh3r3iWAS}
```

---

## 🧬 [OSINT-09] GOld Chain

**Challenge:**  
> Analyze the NFT activity of wallet `0xEDFfD5AEc7f8f1b9E112DD12C04507359A578d47` on Sepolia and find the flag.

**Approach:**  
1. Tracked NFT mint activity to hash:  
   `0xb226d6d39e0ac4294360938626442ee83ef0b6219b6642044c88306578d443b6`
2. Found a transaction:  
   `https://sepolia.etherscan.io/tx/0x45562689ae26ccdacdebb349c6237571bfc1ece81e0f78e6f89cd6aff0864884`
3. Opened “Input Data” and located a message:  
   > `Smart move haha, thanks! CID : bafkreifm5tdw6sqb6mgzqmrdkmarpdioncyirczmcurfahaftchhlbze7y`
4. Accessed IPFS content:  
   `https://ipfs.io/ipfs/bafkreifm5tdw6sqb6mgzqmrdkmarpdioncyirczmcurfahaftchhlbze7y`

**Flag:**  
```
CDDC2025{transparency_immutable_decentralized}
```

