# jumpcutter-rs
A tool to speed up lecture videos or easily insert jumpcuts

If you procrastinate (just like me right now) then you know how hard it is to catch up with lecture videos. Luckily YouTuber [carykh](https://www.youtube.com/user/carykh) came up with the idea to not just normally speed up those videos but also to decrease silence by a greater amount. With this method you can procrastinate even more, since your videos will get shorter while still being quite comfortable to follow.

This method only speeds up silence, since completely removing it, could result in a loss of important parts. Full deletion of silence can also be implemented

Sadly the original project hasn't seen updates for quite a while and there are some existing problems like:

- no automatic frame rate detection
- very large tmp files (I just had >10GB for a single lecture!!)
- it takes quite a while to finish the conversion (normal speed up is instant)

This repo should at least support the following functionality:

- [ ] full reimplementation of all features of carykh's tool
- [ ] option to outright delete silence
- [ ] automatic frame rate detection
- [ ] ... possibly more

There are however some features I'd like to add if I have enough time:

- [ ] GUI for easier usage
- [ ] Preview of saved time
- [ ] work without temporary storage (or possibly in a ram disk)
- [ ] parallelize the video creation process
- [ ] live stream of video at faster speed
- [ ] WebAssembly App which handles the conversion locally
- [ ] web server to convert videos

## Contribution
If you feel like you could add something to this project, than reach out to me, open a pull request, open an issue or whatever you want. I am grateful for help in every way. If you have no idea where to start, just [lookup how to add an issue](https://help.github.com/en/github/managing-your-work-on-github/creating-an-issue) on this project and describe something you want to see in this tool or give another kind of input.
