List of tools for Kali/OSCP
Searchsploit keyword

Msfvenom
stageless windows/shell_reverse_tcp
staged windows/shell/reverse_tcp
-e will allow you to choose an encoder, the most common of which is x86\shikata_ga_nai. This is great for avoiding bad characters and       evading AV… Although, the latter isn’t so true anymore.
-b allows you to set bad characters. The bad characters for a specific exploit are often disclosed in the public exploit code itself.
— list (that’s two dashes) will list payloads and formats, for example, if you want to see a list of all the possible payloads, run msfvenom --list payloads
