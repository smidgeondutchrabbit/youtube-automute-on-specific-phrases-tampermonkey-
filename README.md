# youtube-automute-on-specific-phrases-tampermonkey-
scripts to mute youtube on specific phrases. multiple scripts are listed. check readme for more details.
to use the scripts, follow the instructions
specific phrase blacklist
1. create a new script and upload the code to tampermonkey
2. Replace the placeholder words exampleword1, exampleword2, and exampleword3 in the blacklist array with the words or phrases you want to block.
the replacement should look like const blacklist = ["exampleword1", "exampleword2", "exampleword3"];
the script cant mute just the word, it has to mute for a specific time. so to do that Adjust the muteDuration variable (in milliseconds).
3.the updated veriable should look something like const muteDuration = 15000; (mute for 15 seconds)
4. save the script
5. when playing a youtube video, refresh the script before playing
regex pattern based mute -
1. change the regex patterns to what you want it as
2. update the MuteDuration variable (milliseconds) example const muteDuration = 15000; (15 seconds)
save the script
**same thing as specific phrase blacklist to get it working**
substring blacklist -
1. replace the items under const blacklist with words you want to block
2. adjust the mute time
3. upload it to tampermonkey
4. work it like you would with all the other ones
5. # more info
6. ive included an example phrase in the codes. you may edit or remove it as you wish
if you need help, open an issue for script help
