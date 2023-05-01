# UMDCTF 2023
## Mirror Unknown
Here is the image for this challenge 
<p>
    <img src="https://github.com/cosmoshivani/UMDCTF-2023/blob/main/Mirror_Unkown.png" width="220" height="240" />
</p>
![Mirror Unknown File](https://github.com/cosmoshivani/UMDCTF-2023/blob/main/Mirror_Unkown.png)

If you are not at all sure what these symbols mean, or in any such ctf challenge, the easiest way to find something is either using google image search or sometimes the challenge title gives it away. https://images.google.com/imghp?hl=en&gl=za&gws_rd=ssl
The google image search will tell you that it's a 'uknown'. You can learn more about it on the wikipedia or just type uknown decoder right away.
If you look at the letters in the challenge file and the original letters, you'll see that some of these are not in there. And if you look close you'll see they are mirrored. And that's also what the challenge title indicates. So we can use an online mirroring tool to get the mirrored image. 
https://www.resizepixel.com/mirror-image/

Here is how it looks like
![alt text](https://github.com/[username]/[reponame]/blob/[branch]/image.jpg?raw=true)
![Mirror Unknown File](/UMDCTF-2023/mirrored_Unkown.png)

Now we can start decoding what it means. You can search for uknown decoder but this one is pretty good too -- https://www.dcode.fr/pokemon-unown-alphabet
[if you find any better decoder, please let me know]

Tap on the letters one by one and decode. You will get the following string 

'SINJOHRUINS'

It does look like a flag but what does it mean. Google tells us it's actually 'Sinjoh Ruins', an unknown region in the Pokemon World.
![alt text](https://github.com/[username]/[reponame]/blob/[branch]/image.jpg?raw=true)
[Most of the challenges of UMDCTF 2023 were Pokémon Themed but I'm not familiar with their world sadly. But now I am thinking of watching because Pikachu sure is cute]

The challenge description has another note
(Note: Ancient civilizations didn't believe in whitespace of lowercase)
 
 This gives us another hint that what we have found doesn't have to be in lowercase. And we don't need to add whitespaces either. 
 Finally, wrapping it with UMDCTF gives us the flag 
 'UMDCTF{SINJOHRUINS}'
 
