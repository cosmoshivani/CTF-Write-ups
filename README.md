# UMDCTF 2023
## Mirror Unknown
Here is the image for this challenge 

![Mirror_Unkown](https://user-images.githubusercontent.com/47838688/235416072-ff2ac06d-05c2-4a6a-95e9-5c61c5070214.png)

If you are not at all sure what these symbols mean, or in any such ctf challenge, the easiest way to find something is either using google image search or sometimes the challenge title gives it away. https://images.google.com/imghp?hl=en&gl=za&gws_rd=ssl
The google image search will tell you that it's a 'uknown'. You can learn more about it on the wikipedia or just type uknown decoder right away.
If you look at the letters in the challenge file and the original letters, you'll see that some of these are not in there. And if you look close you'll see they are mirrored. And that's also what the challenge title indicates. So we can use an online mirroring tool to get the mirrored image. 
https://www.resizepixel.com/mirror-image/

Here is how it looks like
![mirrored-Unkown](https://user-images.githubusercontent.com/47838688/235416113-277b5901-deec-472b-8860-1a3a5ee2ea33.PNG)


Now we can start decoding what it means. You can search for uknown decoder but this one is pretty good too -- https://www.dcode.fr/pokemon-unown-alphabet
[if you find any better decoder, please let me know]

Tap on the letters one by one and decode. You will get the following string 

'SINJOHRUINS'

It does look like a flag but what does it mean. Google tells us it's actually 'Sinjoh Ruins', an unknown region in the Pokemon World.

![uknown-wiki](https://user-images.githubusercontent.com/47838688/235416148-a5a2bc3a-0446-4b96-90bc-0aa729c816d5.PNG)

[Most of the challenges of UMDCTF 2023 were Pokémon Themed but I'm not familiar with their world sadly. But now I am thinking of watching because Pikachu sure is cute]

The challenge description has another note
(Note: Ancient civilizations didn't believe in whitespace of lowercase)
 
 This gives us another hint that what we have found doesn't have to be in lowercase. And we don't need to add whitespaces either. 
 Finally, wrapping it with UMDCTF gives us the flag 
 'UMDCTF{SINJOHRUINS}'
 
