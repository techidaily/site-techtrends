---
title: Develop a Personalized AI Chat Assistant on Your Device Leveraging NVIDIA's Cutting-Edge RTX GPUs
date: 2025-02-03T16:07:17.592Z
updated: 2025-02-07T16:13:51.711Z
tags:
  - cutting-edge
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/53489023879_ab83f868df_o.jpg
---

## Develop a Personalized AI Chat Assistant on Your Device Leveraging NVIDIA's Cutting-Edge RTX GPUs

### Key Takeaways

* NVIDIA's Chat with RTX runs locally on your PC, no internet required, with quickly and efficiently.
* To run Chat with RTX, ensure you have RTX 30 series or newer, ample storage (50GB+) and system RAM, and are running Windows 10 or 11, then download and install the files from NVIDIA.
* Chat with RTX can learn from documents and YouTube videos you provide it, then answer questions based on what it learns.

 NVIDIA's Chat with RTX is a lot like ChatGPT, except it runs locally on your own PC, with no need for an Internet connection. It is fast, efficient, and can even learn from documents you provide or YouTube videos. Here's how to get it running on your PC.

##  What Do You Need To Run NVIDIA’s Chat With RTX?

 Most modern gaming computers will be able to run [NVIDIA's Chat with RTX](https://mondly-stories.techidaily.com/1719578517758-russian-numbers-learn-how-to-count-in-russian/). Specifically, you will need:

* A 30 series or 40 series RTX (NVIDIA) graphics card with at least 8GB of RAM
* About 50 gigabytes of free storage space
* 16GB of system RAM
* A Windows 10 or Windows 11 PC

 Chat with RTX relies on [TensorRTX-LLM](https://developer.nvidia.com/blog/nvidia-tensorrt-llm-supercharges-large-language-model-inference-on-nvidia-h100-gpus/), which is only supported on 30 series GPUs or newer. That means that your 10 and 20 series GPUs—while still great for many things—are not supported, and likely never will be.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n4cc4BSqJls?si=Hkd9vwQDqeCGN7XG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  How to Install Chat with RTX

 First, [download the Chat with RTX files](https://www.nvidia.com/en-us/ai-on-rtx/chat-with-rtx-generative-ai/) from NVIDIA's website by clicking the big "Download Now" button towards the top. They're about 35 gigabytes, so be prepared for it to take a little while.

![Click the 'Download Now' button.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/1-click-download-now.png) 

 The files come zipped, and you should [unzip them](https://fox-boxes.techidaily.com/new-in-2024-streamlining-post-processing-with-effective-use-of-luts-in-pscc/) before you try to install the application. If you're using a [third-party archival program like 7Zip or WinRAR](https://some-guidance.techidaily.com/new-strategies-for-streaming-fb-live-on-zoom-platform/), you can just right-click the ZIP and select "Extract Here." If you're using File Explorer, double-click the zip, copy the "ChatWithRTX\_Offline\_2\_11\_mistral\_Llama" folder, and then paste it in your Downloads folder (or anywhere else you like).

 Once again, be prepared for this operation to take a while—unzipping 35 gigabytes is going to take some time, especially if it is stored on a mechanical hard drive rather than an SSD.

![Right-click the ZIP file, then select 'Extract Here.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/2-extract-here.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/58KlTPHv8dU?si=7ICagyNgrao7OkVO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once it has finished, open up "ChatWithRTX\_Offline\_2\_11\_mistral\_Llama" and double-click "Setup.exe." There aren't many choices you can make in the installer. The only one to watch for is the installation location. Chat with RTX will use up about 50GB when installed, so be sure you [pick a drive with enough free space](https://win11-tips.techidaily.com/seamless-files-on-windows-using-python-for-network-transfer/) available.

![The install location for Chat with RTX.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/4-install-location.png) 

 Again, don't expect this to install super quickly. It has to download additional [Python](https://youtube-data.techidaily.com/024-approved-conveniently-connect-with-others-via-your-playlist/) assets before it can run, and those are a few gigabytes each. When it is ready, it should automatically open your browser and display a user interface.

 Chat with RTX basically hosts a local web server on your PC to provide a user interface, which you then access through your browser. By default, Chat with RTX is not configured to host a site accessible from the Internet, and the ports used by Chat with RTX are likely closed by default on your router, too. It is not a security risk, or accessible from the Internet, unless you specifically set it up.

![The Chat with RTX default user interface open in Firefox.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/the-default-ui.png) 

 If it doesn't open automatically, check the Terminal (or Command Prompt) window and look for the line "Running on Local URL." Note the IP address and port, then type that into the address bar of your browser. The IP address will always be [127.0.0.1 (the loopback address](https://iphone-unlock.techidaily.com/how-do-you-unlock-your-apple-iphone-14-pro-learn-all-4-methods-drfone-by-drfone-ios/)), but the port will change every time you launch Chat with RTX.

![The IP address and port of the Chat with RTX webserver displayed in the Terminal.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/running-on-local-url.png) 

 Once Chat with RTX is open in your browser, you can talk with it like you would any other AI chatbot. It can answer basic questions, attempt math, and even tell jokes—and it does so very quickly, too. It is noticeably faster than other locally-run chatbots we've tested in the past, no doubt because it can utilize the tensor cores found in NVIDIA RTX GPUs.

![Some chat samples from Chat with RTX, including a joke, some math, and a basic 'reasoning' problem.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/output-from-rtx-chat.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qbuund2HKOQ?si=NaGHqIrx8hSL7gWV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 However, the really exciting feature is its ability to provide answers based on files or videos you provide.

##  Make Chat with RTX Learn from Your Files or YouTube

 Chat with RTX allows you to provide it with a file or YouTube video from which it can "learn" and generate responses. To specify a file or video, click the drop-down menu below "Dataset," then select either "Folder Path" or "YouTube URL."

 Select "Folder Path" if you want Chat with RTX to read in a text file or PDF from your PC, and pick YouTube URL if you want to use the transcripts from a YouTube video or playlist.

 Keep in mind that it will try to use _every_ text file in the folder you specify, so it is best to create a new folder that only contains the files you want it to pull from.

![Click the drop-down menu under 'Dataset,' then select 'Folder Path' or 'YouTube URL.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/chat-add-file.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GyfJUhsz_AY?si=x2HjoLX1B89oEPgZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Processing the new dataset will take time, and the more data you provide, the longer it will take. I tested Chat with RTX on an NVIDIA 3060 12GB GPU, and found that an average novel will finish in less than a minute. Newer and more powerful GPUs will be faster. You can check the Terminal window (it may be Command Prompt if you're on Windows 10) to see how it is progressing.

![Chat with RTX generating embeddings from a plain text novel.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/generating-embeddings.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/r_wWybMqZEM?si=0nPjCQDLS2MCaQbG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 However, just because you can feed it all 70 gigabytes of [Project Gutenberg](https://www.gutenberg.org/) in an attempt to turn it into a literary whiz doesn't mean you should—in fact, I recommend against it. Chat with RTX works best when you don't mix multiple sources, and when those sources are on the small side.

##  Chat with RTX Does Hallucinate

 Chat with RTX, regardless of which model you use, has the same problem that all AI Chatbots do: it [hallucinates](https://audio-shaping.techidaily.com/strategies-for-minimizing-large-scale-video-and-audio-data/). If it doesn't know something, it will usually confidently declare an answer anyway.

 When given the prompt "Who is John Wayne," Chat with RTX happily told me when he was born and when he died, what genre he was known for, and his iconic roles in "The Duke of Hazzard," "True Grit," and "Read Dead Outlaw."

![The prompt 'Who is John Wayne?' and Chat with RTX's reply.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/who-is-john-wayne.png) 

 Of course, John Wayne wasn't in "The Duke_s_ of Hazzard," and so far as I can tell, "Red Dead Outlaw" isn't even a movie—though it does sound like the sort of movie John Wayne would star in.

 Chat with RTX seems less given to hallucinations when it doesn't know something about a file or YouTube video you gave it. It will often state outright that the source you provided doesn't contain the information you asked about.

![Chat with RTX correctly states that there is no information about Frodo Baggins or Samwise Gamgee in 'Frankenstein.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/elizabeth-and-frodo-never-attacked-samwise.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LBCobAYzzcc?si=J3eSTQ3AdyxWAjGo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 However, sometimes it doesn't. This becomes more noticeable when you provide more than one file at a time. I pulled "Frankenstein" and "The Raven" from Project Gutenberg and fed them into Chat with RTX, and then asked it why Dr. Frankenstein commanded the monster to eat the raven. It correctly told me that Dr. Frankenstein didn't command the monster to kill the raven, but then claimed that Dr. Frankenstein was attempting to link his thoughts to the bird's message.

![Chat with RTX mixing up information from Shelley's 'Frankenstein' with Poe's 'The Raven.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/dr-drankenstein-and-the-raven.png) 

 The trouble is that Dr. Frankenstein and the Raven exist in completely separate stories—Chat with RTX just mixed and-matched story elements to get a coherent-sounding answer.

 These problems are not unique to Chat with RTX, nor the models it uses, Mistral 7B or Llama 13B. As consumer hardware gets faster and sophisticated models become more optimized, the technology will become more reliable. For now, if you keep things simple and don't overload it with information, Chat with RTX can provide an interesting and helpful way to interact with documents. Just remember to treat everything it tells you with a bit of skepticism.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-youtube-view-bots-how-to-increase-youtube-views/"><u>[New] YouTube View Bots How to Increase YouTube Views?</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-from-followers-to-fans-a-strategic-approach-to-instagram-brand-alliances/"><u>[Updated] 2024 Approved From Followers to Fans A Strategic Approach to Instagram Brand Alliances</u></a></li>
<li><a href="https://facebook.techidaily.com/a-heavy-investment-in-wordsmiths-fbs-strategic-5m-plan-against-substacks-rise/"><u>A Heavy Investment in Wordsmiths: FB's Strategic $5M Plan Against Substack’s Rise</u></a></li>
<li><a href="https://techtrends.techidaily.com/download-the-best-no-cost-dvd-creator-for-windows-11-detailed-analysis-and-complete-user-manual-guide/"><u>Download the Best No-Cost DVD Creator for Windows 11 - Detailed Analysis and Complete User Manual Guide</u></a></li>
<li><a href="https://article-helps.techidaily.com/eizos-masterpiece-delving-into-the-world-of-4k-cg318-4k-for-2024/"><u>EIZO's Masterpiece Delving Into the World of 4K CG318-4K for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/guide-pour-la-correction-de-fautes-dans-handbrake-resoudre-les-problemes-dimpossibilite-de-lire-le-titre-du-dvd/"><u>Guide Pour La Correction De Fautes Dans HandBrake: Résoudre Les Problèmes D’impossibilité De Lire Le Titre Du DVD</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-do-you-play-mp4-files-on-g24-power-by-aiseesoft-video-converter-play-mp4-on-android/"><u>How do you play MP4 files on G24 Power?</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-stream-amazon-prime-on-your-tv-using-a-chromecast-solving-the-missing-cast-icon-problem/"><u>How to Stream Amazon Prime on Your TV Using a Chromecast: Solving the Missing Cast Icon Problem</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/mastering-your-pc-upgrades-tips-from-toms-equipment-rundown/"><u>Mastering Your PC Upgrades: Tips From Tom's Equipment Rundown</u></a></li>
<li><a href="https://common-error.techidaily.com/nier-automata-pc-stability-improvements-how-to-prevent-frequent-crashes/"><u>NieR: Automata PC Stability Improvements: How to Prevent Frequent Crashes</u></a></li>
<li><a href="https://techtrends.techidaily.com/profi-dvd-kopierleitfaden-mit-handbuch-fur-winx-dvd-copy-software-perfektioniere-deine-brenntechnik/"><u>Profi-DVD Kopierleitfaden Mit Handbuch Für WinX DVD Copy Software – Perfektioniere Deine Brenntechnik!</u></a></li>
<li><a href="https://techtrends.techidaily.com/scarica-e-duplica-i-tuoi-dvd-preferiti-con-nessuna-degradazione-della-qualita-su-mac-big-sur/"><u>Scarica E Duplica I Tuoi DVD Preferiti Con Nessuna Degradazione Della Qualità Su Mac, Big Sur</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-6-best-sim-unlock-services-that-actually-work-on-your-oppo-reno-11-5g-device-by-drfone-android/"><u>The 6 Best SIM Unlock Services That Actually Work On Your Oppo Reno 11 5G Device</u></a></li>
<li><a href="https://techtrends.techidaily.com/top-10-methods-for-converting-dvd-files-into-mp4-format-on-pc-windows-10-and-11-macos/"><u>Top 10 Methods for Converting DVD Files Into MP4 Format on PC (Windows 10 & 11, macOS)</u></a></li>
<li><a href="https://fox-ssl.techidaily.com/ubermittlung-von-informationen-wie-sie-daten-von-einem-pc-auf-einen-anderen-ubertragen-konnen-windows-versionen-111087/"><u>Übermittlung Von Informationen: Wie Sie Daten Von Einem PC Auf Einen Anderen Übertragen Können (Windows-Versionen 11/10/8/7)</u></a></li>
<li><a href="https://techtrends.techidaily.com/ultimate-step-by-step-tutorial-adding-subtitles-to-films-and-videos-a-complete-guide/"><u>Ultimate Step-by-Step Tutorial: Adding Subtitles to Films and Videos - A Complete Guide</u></a></li>
</ul></div>

