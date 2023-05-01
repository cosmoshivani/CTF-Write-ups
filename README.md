# UMDCTF 2023
## Mirror Unknown

Hi! :wave:
Here is the image for this challenge --

![Mirror_Unkown](https://user-images.githubusercontent.com/47838688/235416072-ff2ac06d-05c2-4a6a-95e9-5c61c5070214.png)

:thought_balloon: 
If you are not at all sure what these symbols mean, or in any such ctf challenges, the easiest way to find something is either using google image search or sometimes the challenge title gives it away.

:mushroom: [Google Image Search](https://images.google.com/imghp?hl=en&gl=za&gws_rd=ssl)

The google image search will tell you that these symbols are called, ```Unown```.
If you look at the letters in the challenge file and the original uknown letters, you'll see that some of these look a bit different. 

![unown](https://user-images.githubusercontent.com/47838688/235418382-3b15a835-b914-4d1c-a9ed-dbc01e4c12b9.PNG)

And if you look close you'll find that they are mirrored. And that's also what the challenge title indicates. We can find an online mirroring tool for this. 

:mushroom: [Mirror Image Tool](https://www.resizepixel.com/mirror-image/)

And this is how it looks -- 

![mirrored-Unkown](https://user-images.githubusercontent.com/47838688/235416113-277b5901-deec-472b-8860-1a3a5ee2ea33.PNG)


Now we can start decoding. You can search for ```unown decoder``` but this one is pretty good too

:mushroom: [Pokemon Unown Alphabet](https://www.dcode.fr/pokemon-unown-alphabet)

[if you find any better decoder, please let me know]

Tap on the letters one by one and decode. You will get the following string 

```SINJOHRUINS```

It does look like a flag, but what does it mean? Google tells us that it's actually ```Sinjoh Ruins```, an unknown region in the ```Pokemon World```.

![uknown-wiki](https://user-images.githubusercontent.com/47838688/235416148-a5a2bc3a-0446-4b96-90bc-0aa729c816d5.PNG)

[Most of the challenges of UMDCTF 2023 were Pokémon Themed and I was not at all familiar with their world sadly. But now I am thinking of watching the movies because Pikachu sure is cute]

:mushroom: The challenge description has another note -- (Note: Ancient civilizations didn't believe in whitespace of lowercase)
 
 This gives us another hint that what we have found doesn't have to be in lowercase. And we don't need to add whitespaces either. 
 Finally, wrapping it with UMDCTF gives us the flag --
 
 ```UMDCTF{SINJOHRUINS}```
 
 
 
