---
label: Dahyun Bot & UVR
author: lvntrq
---

# How to use Dahyun's bot UVR and it's RVC feature to make ai covers by lvntrq

## Using Dahyun :

Who is Dahyun : Dahyun is firstly a member from Twice ok ! Dubu dubu! But she is also a bot created by .nw, she has her own server you'll see the link below and it's actually the easiest way to inference vocals into RVC. If you're looking for another way : there's applio but in this tutorial we will focus on Dahyun.

### Step 1: Get access to DAHYUN RVC
To get access to DAHYUN RVC, you can either go to KPOP UNIVERSE and go to #dahyun-rvc or join the [DAHYUN RVC](https://discord.gg/UfEC4vfk3m) server!

## Step 2: Get your audio for UVR
I would recommend getting your audio from YouTube and downloading it into mp3. I use https://v6.www-y2mate.com/ to download my audios! Simply just paste the video link into the box and download whatever type of format you want! For this example, I’m going to use DIVINE by Stray Kids.

![Step 2 Image](https://files.catbox.moe/6a1y0l.png)

You can download audio, video, and other. For this, I’m going to download mp3 320kbps. From here, you have to wait an additional 10-15 seconds to download it.

![Step 2 Download](https://files.catbox.moe/xm82lq.png)

## Step 3 : Use UVR to separate your audio
There is a command within DAHYUN to help you separate audios. First, you will need to insert your audio into the box. Next, you will choose your UVR model that you want to use to separate your audio. I will tell you what every UVR model does.

![Step 3 Image](https://files.catbox.moe/lqh1sy.png)

### What do they do : 
- **[MDXC] MB InstVoc Duality v1 (by unwa | Best Vocal)** - This separates the vocals (vocals as in acapella) and instrumental within the song.
- **[MDXC] MB Inst v1e/v1 (by unwa)** - This releases the instrumental, separating it into like lead instrumental and backing instrumental in a way.
- **[MDXC] MB Male/Female (By aufr33 | New MedleyVox)** - You won’t need to use this, unless you have female and male vocals that you want to separate.
- **[MDXC] Mel-Karaoke (by aufr33 and ViperX)** - You can use this to extract backing vocals from lead vocals, same for [MDXC] BS-DeReverb.
- **[MDXC] Mel-DeNoise (by aufr33)** - You also won’t need to use this, we only use it when we don’t want noise in the audio, also useful if you need to clean up your dataset a bit more! Same for [VR ARCH] De-Reverb De-Echo (by FoxJoy) and [VR ARCH] De-Echo Normal (by FoxJoy).
- **[VR Arch] 6-HP Karaoke** - This is the cleanest way to get lead vocals! 

**NOTES:** I'm also going to explain a little about UVR aggressiveness; This varies depending on the models we use! So keep an eye on this. You can put any number in there, but I would recommend using 25 aggressiveness for MB InstVoc Duality v1/6-HP Karaoke, as it is the ideal balance. I wouldn't recommend using another number because it would sound very distorted or worse, the audio will sound very tinny (?) When we use De-Echo or De-Noise, then we can increase the aggressiveness up to 100, since it will not affect the audio Also, please make sure that your audio file is less than 10 MB, or DAHYUN will not work!

![Step 3 Models](https://files.catbox.moe/y5lhuc.png)

## Using RVC feature : 

### Step 1 : Grab the Lead Vocals you want the model to sing
For this, I’m going to get XLOV HARU to sing DIVINE by Stray Kids. First, I will grab the Lead Vocals that I want Hongjoong to sing. Here’s the command for using RVC with DAHYUN:

![RVC Step 1](https://files.catbox.moe/j2yez1.png)

Secondly, you need to put the Lead Vocals in the box that says “Vocal”. 

![RVC Step 2](https://files.catbox.moe/i9k3fg.png)

### Step 3 : Grab the model link
Now, you need to find the model link. You can head over to #ai-voices-10 to find the HARU model or you can go over to any other AI voice channels to find the model you want! In this case, I’m going to use XLOV HARU for this example. (Credits to @MinLeo_AI for the HARU model)

![RVC Step 3](https://files.catbox.moe/aeq6us.png)

### Step 4 : The 3 options
There are 3 other options you can use. I would recommend the default pitch, protect, and index since a male is singing a song that has male vocals in it. If you want a female to sing a song with male vocals in it, I would use the pitch +4. If you want a male to sing a song that has female vocals in it, I would use the pitch -4. Since I’m going to leave the settings default, all you have to do is press enter and wait for it to filter. 

![RVC Step 4](https://files.catbox.moe/iyuybk.png)

### Step 5 : Go in DMs to download your vocals
Once it says this, you can head over to your DMs and click the link to download the vocals!

![RVC Step 5 Image 1](https://files.catbox.moe/3cpgoz.png)
![RVC Step 5 Image 2](https://files.catbox.moe/nzv096.png)

After this, you can create this into a cover and post it on YouTube! Be careful, you may or may not get a warning for copyright reasons, it varies.