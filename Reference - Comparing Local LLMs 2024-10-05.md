#Reference/Experiments #Local-LLMs
# Summary 

Cydonia Comparisons:
- v1.1 does a very good summary + bullet points even if it picks out quotes and points that I would not have. Not as relevant as gemini 1.5 flash but I wasn't expecting it to be. Format well followed. 
- v2c More succinct. I prefered v1.1's summary. 
- v2h It blubbed endlessly on the list for first run, so I had to adjust the repetition penalty higher (1.1) and in the second go, it was a lot more succinct but I do like the quotes it found (most relevant). 

Comparison of the three Cydonia models
![Pasted image 20241004234655](./Pasted%20image%2020241004234655.png)

Against other models:
- Gemini-1.5-flash-latest - Did the best. 
- Llama 3.1 70B - Too wordy, slow on my mac, but extracted rather relevant points. Summary was just one sentence, so I think Cydonia did a better balance.
- Qwen 2.5 32B by bartowski, actually performs worse. It is too repetitive, the points are too short, and I could probably tune params for it to do better, because I have tried with XTC and DRY on Silly Tavern and it did alright there. But for this test, it performed rather badly. 

**Acceptable Summary Ranking**:
- Gemini-1.5-flash-latest - super fast but you need API Key etc 
- v1.1 Cydonia 22B by TheDrummer - decent for this task, nicely balanced, at least at these params, mix of whether points are relevant
- Llama 3.1 70B by lmstudio-community - super slow, very wordy, but pretty relevant
- v2c Cydonia 22B by TheDrummer - mix of whether points are relevant but a bit too succinct for me
- Qwen 2.5 32B Instruct by bartowski - barely readable & wordy

# Methodology

1. Get this transcipt from [Why You Keep Making The Same Mistakes - YouTube](https://www.youtube.com/watch?v=WpoYqs9Hsa4)
2. Run extract wisdom prompt with the transcript (either fabric or LM Studio) - Transcript is text, System Prompt is Extract Wisdom

### Model Params

![Pasted image 20241004231909](./Pasted%20image%2020241004231909.png)
![Pasted image 20241004233238](./Pasted%20image%2020241004233238.png)

### My Specs 
Apple M1 Ultra - 64 GB - Version Sequoia 15.0 
LM Studio 0.3.3 (Build 1)
### Transcript 

```
so if I get bullied at school I don&#39;t have to make these people my friends I can find friends on the internet in addition we&#39;re seeing the concentration Avail in availability of things like THC and CBD go up which helps us manage our shame so now we we run into a real serious problem now the problem is that since we can avoid contact this emotion doesn&#39;t work the way that it&#39;s supposed to anymore so you know something pretty simple not too important just something that we&#39;re going to kind of teach youall real quick is you know how to stop making the same mistakes over and over again keep progressing in life you know the way that you should so here&#39;s the problem is that we make mistakes and when we make mistakes the basic problem is not that we make the mistake but that we make it again and then we make it again and then we make it again and we keep making it and if you&#39;re like me you kind of look at yourself and you&#39;re like man I just wish I would stop doing this thing and for me it&#39;s like it&#39;s playing video games like even last night so 10 10:00 rolled around my kids went to bed and I was like man I could turn in early but did I turn in early of course not instead what I did is play two games of Dota 2 thankfully I won them so it wasn&#39;t very rage inducing but this is what happen 20 years ago when I was in college 22 years ago when I was in college and failing out like I would tell myself hey I need to go to bed and instead I would stay up so late and we tend to make these same mistakes over and over and over again oh I sabotaged this relationship because I let my anxiety get the better of me I like started going to therapy but then I stopped like whatever it is for some reason when we make a mistake in life it seems to be very hard to correct it now if we want to understand why this happens we have to understand the apparatus that helps us learn from our mistakes and it turns out that the human brain in the way that it corrects mistakes is actually being sabotaged or hampered by certain aspects of our society so what are we seeing we&#39;re seeing a an increasing number of people making some relatively consistent mistakes there are challenges in the economy sure 50% of people under the age of 30 or living at homes they&#39;re like absolutely external factors but we&#39;re also seeing a rise in loneliness we&#39;re seeing a rise in addiction we&#39;re seeing a rise in depression we&#39;re seeing a rise in anxiety we&#39;re seeing a rise in low self-esteem we&#39;re seeing a rise in hopelessness and what I&#39;m really seeing arise of is the inability to take corrective action So today we&#39;re going to teach youall basically how the brain takes corrective action and what is getting in the way of you taking the action that you should be taking hey y&#39;all if you&#39;re interested in applying some of the principles that we discussed to your life to actually create change check out Dr K&#39;s guide to mental health the guide synthesize my years of training as a monk along with years of clinical experience as a psychiatrist to cover common topics like meditation ADHD and Trauma the guides include over 100 additional videos that can be navigated based on your needs or interests or in a more open Choose Your Own Adventure format the guides are now available in the YouTube store below and if they&#39;re a little bit outside of your price point you can check out a piece of them with our free resource packs which are also linked below so definitely check him out so in order to take corrective action our brain needs to do two processes the first is it goes through something called a counterfactual thinking exercise so this is sort of like an analysis of what you should do and this is where a lot of y&#39;all may say like oh yeah I figured out what I should do but I can&#39;t do it and that&#39;s where we get to piece number two which is actually the motivational component right so in addition to knowing what we should do we have to have the drive to actually do it so the way that I kind of think about this is imagine you have a car and in order to get from point A to point B you need a map you need an intellectual understanding of where you are and where you need to go and how to get from point A to point B right you have to know that and then you also need fuel in the car and your brain needs both of those components and the crazy thing is that for the majority of people I work with who have this problem they really focus on one component and neglect the other so we&#39;re going to start actually with the motivation not the road map so we&#39;re going to start with the fuel okay so this is what what&#39;s important to understand our brain has a couple of different areas of emotional circuitry so we have this this primitive part of our brain that includes the amydala so the amydala is where we feel what I would call Solo Survival emotions this is where we feel fear this is where we feel anxiety this is where we feel anger right so these are things that like even reptile can feel fear and anger and territoriality and things like that so this is a very primitive emotion but then we have this other part of our brain which is where we experience the higher human emotions that are more social in nature so these are emotions like guilt and shame and if we kind of think about it like why does the human brain experience guilt and shame why does it why do guilt and shame feel so painful this is very important to understand so in the situation that our brain evolved which is very similar to like chimpanzee brains and like monkey brains and things like that these are social creatures so we have social emotions and in order for a social emotion to function properly it requires social circumstances okay I&#39;ll give you all a simple example so when I was growing up I used to get bullied a lot and I&#39;m sure that many of you all do too it absolutely sucks but when I was growing up I sort of didn&#39;t have a choice except to socialize with my bullies so I had to go to school every day as I&#39;m sure many of youall do and I would get bullied every day and then my my you know I would feel ashamed of myself and then this negative emotion would induce some kind of Behavioral change and this is important to understand anytime our body or our brain makes us feel bad these are very very important drivers for corrective Behavior so if we think about some of the most painful experiences in the world these are things like hunger thirst right even something like asphixiation the inability to breathe I one time had a patient that was having an allergic reaction and they could not breathe and the amount of panic and suffering that a human body and brain will experience when they are unable to breathe is astronomical crazy thing is that this is also why panic attacks are so painful and so scary and actually so traumatic because you feel like you can&#39;t breathe so anytime the body has something that is very important for your survival if you do it don&#39;t do it your body will make you feel incredibly bad right so hunger hurts a lot thirst hurts a lot asphixiation hurts a lot shame hurts a lot guilt hurts a lot so with these signals like hunger and thirst it&#39;s really simple right so when I feel hungry this is my body&#39;s way of telling me hey I should take corrective action I should eat and then I will feel better with thirst I should drink something then I will feel better with asphixiation I should take a deep breath then I will feel better if only it were that simple what about things like shame and guilt what is the corrective action so this is where you know if I feel ashamed of myself often times this is inspiration so if I got made fun of because of the way that I look or my weight either I&#39;m too skinny or I&#39;m too fat then this shame since I&#39;m going to see these people again can be motivational fuel for me to take corrective action I&#39;m going to start going to the gym right and this is what we know we know that sometimes when people are ashamed of themselves they will do something to no longer be ashamed of themselves I&#39;m going to get my hair done I&#39;m going to start going to the gym I&#39;m going to start feeling better about myself I&#39;m so embarrassed to be unemployed I feel so ashamed of myself I&#39;m going to work really hard to get a job because I never want to feel that shame again that&#39;s the purpose of Shame now here&#39;s the problem in today&#39;s society we have one alternate solution to shame which did not exist a couple of here hundred years ago which is escape so now our society has become so escape and avoidant heavy that I no longer need to face my shame so if I get bullied at school I don&#39;t have to make these people my friends I can find friends on the internet if I feel ashamed of myself I have an electronic device that can make me feel take all of that malice and that take all that shame and turn it into malice and resentment and turn it into toxicity on the Internet by crapping on the people that make me feel bad right I can do all of these things to avoid my shame in addition I can also like this literally suppresses those circuits of the brain but there&#39;s also things like substances we&#39;re seeing the concentration Avail in availability of things like THC and CBD go up which helps us manage our shame so now we we run into a real serious problem see the only reason that shame worked is because I had to go to school every day right there was no way to avoid the consequences and this is the way that shame evolved because when we think about a tribal situation we think about chimpanzees like if a chimpanzee is ashamed of itself it has no choice but to interact with these same people so these emotions evolved under the circumstance of permanent contact that was unavoidable now the problem is that since we can avoid contact this emotion doesn&#39;t work the way that it&#39;s supposed to anymore okay so now what happens is when we we we create this alternate scenario where okay I don&#39;t have to experience the shame because I I can avoid these people and what does that mean for my corrective Behavior now that I&#39;m no longer experiencing the shame now that I&#39;m no longer avoiding those people I don&#39;t have to fix the problem because remember fixing the problem was the antidote to shame that&#39;s the whole purpose of shame but if I can avoid the problem then I never have to fix it and this is literally what happens with people who are ashamed and guilty they just avoid the social circumstances and therefore avoid the shame so this is where I know it&#39;s kind of crazy but like we have evidence-based techniques that we&#39;ve sort of dug into as to what to do about this and I hate to break it to y&#39;all but it&#39;s to stop avoiding the shame so real my favorite example of this comes from alcoholic synonymous where they have a particular step where they&#39;re kind of like you know doing all this internal work and they feel ashamed of themselves because they&#39;ve like you know drank a bunch of alcohol and they&#39;ve ruined their lives and they&#39;ve ruined relationships so they&#39;re carrying a bunch of this toxic shame often times the toxic shame precedes the alcohol addiction and so they have a really important step called making amends so then what they do is they make a catalog of all of the people that they can think of that they&#39;ve wronged in some way and they&#39;re ashamed of their behavior there was that time that I got really drunk and passed out and I couldn&#39;t drive you to the airport and you missed your job interview and then you didn&#39;t get the promotion and like everything got worse for you very shame inducing right and I used to run away from that I used to blame you for my failings this is what happens when people are addicted to alcohol so instead what they do is they go back and they embrace the shame they engage with the shame they go back to all of those people and they say hey I screwed up so they&#39;re no longer running away from the shame when you stop running away from shame you start gaining accountability and once they start gaining accountability their life moves in the correct Direction the shame becames a positive motivator now there&#39;s an important caveat here which is that there is a version of Shame called toxic shame now toxic shame is a completely different feature so this is where remember shame is designed to induce the right Behavior but toxic shame is when people make you feel inappropriately ashamed and in that case there is no corrective Behavior because no matter what you do they&#39;ll still shame you for it we have other videos about toxic shame and if that relates to you by all means check those out so this is where the fuel comes from and the basic problem is that the most powerful motivators for human behavioral change are actually negative emotions and our social uh negative emotions are incredibly strong at that but the moment that we start avoiding those circumstances we lose our motivation and then you end up just watching a bunch of videos about how to gain motivation instead of actually facing up to your problems and going to the gym or saying hi to people or asking someone out on a date etc etc etc now we come to the second part because it&#39;s not just emotion we also need a road map and this is where we also fall into another kind of problem which is that often times when we are trying to come up with a solution we lean too far into Theory crafting so we have this part of our brain that does something called counterfactual thinking really really important circuit in the brain so this is the way that the circuit Works anytime I do something and I screw up my brain does something really interesting right it goes back in time and it says it fantasizes about what I should have done differently my favorite example of this is that this occurs like usually when you&#39;re going to bed and your mind reminds you of some random memory right and for me growing up it was like clever things that I would say when someone made fun of me so someone was like oh you know like ol you&#39;re such a loser like all you do is play video games or like I remember one day I was you know in in recess or PE class and we were playing football and then like someone threw a football and I dropped it right I couldn&#39;t catch the football and then like what happened is they made fun of me and they&#39;re like oh like did they not teach you how to catch a football when you play your Nintendo that&#39;s what they made fun of me and then what I would do is like 6 months later I&#39;d be like yeah well n no I can&#39;t even think about what I came up with then but then six months later your brain is like oh this is what I should have said six months later it sort of thinks about like how you could have done things differently we experience a lot of counterfactual thinking when we go through something like a breakup right so your mind is thinking okay like this is what I should have done this is what I should have done I would have shown him if I did this so our brain kind of gets lost in this hypothetical world that doesn&#39;t exist now in the worst cases this becomes something like maladaptive daydreaming where we get so lost in the counterfactual thinking that we get divorced from reality that&#39;s also this is probably where counterfactual thinking meets ADHD which has been implicated in maladaptive daydreaming we have a video about that if yall are interested but this is basically how our mind corrects mistakes is that it engages in counterfactual thinking now here&#39;s the problem is that when we start to live an avoidant life our brain &#39;s capacity for counterfactual thinking becomes weaker so if we think about what it takes for counterfactual thinking to be the most successful is we actually need as much data or evidence as we can get our hands on and we actually don&#39;t want to Theory craft purely so usually what what I see in the the people that I work with who struggle to learn from their mistakes is they will Theory craft what they should do but since they have so little experience the data inputs for the theory crafting are not optimal by any means and if you all have Theory crafted in a video game you kind of know what I&#39;m talking about right so if you&#39;re like playing a particular game you&#39;re like hey I&#39;m going to do this build and it&#39;s going to be great I&#39;m going to do a four poool rush and I&#39;m going to Zerg Rush with four poool and it&#39;s going to be awesome and I&#39;m going to send a drone with it you come with all these wonderful ideas of how you&#39;re going to make this game work and how you&#39;re going to make this character build and then you go and you like actually play the game and you&#39;re like wow that doesn&#39;t really work at all and then you have to adjust your theory crafting if you&#39;re enamored with the idea you&#39;ll give it an adjustment you&#39;ll try it again and then you do many iterations and then sometimes you can even make the build work right you don&#39;t have to just read The Meta builds and follow them now this is the problem is that in order for counterfactual thinking to work successfully that&#39;s actually what we need to do the first iteration of the solution that your mind comes up with is not going to be very accurate because you have a minimum of data and evidence now here&#39;s where we fall into another Pitfall which is that often times when our Theory crafting when we&#39;re Theory crafting the way that we actually address this problem is with more Theory crafting we never actually queue up for a game so if I&#39;m struggling with my motivation what I&#39;m going to do is watch a bunch of videos on YouTube about motivation I&#39;m going to read books and browse discussion forums and do all of this stuff instead of gain experience and data and evidence right if I&#39;m struggling date I&#39;m going to read a lot of like Mi I the posts on Reddit to try to figure out something about relationships I don&#39;t even know what you&#39;re planning on learning over there right or I&#39;ll watch videos on on YouTube and all this stuff can be useful don&#39;t get me wrong but that&#39;s all in the category of theory crafting and if we look at our brain our brain doesn&#39;t respond very well to Theory crafting our brain does theory crafting with evidence so we can&#39;t like Theory craft our way from 0o to 100 and this is the critical mistake that a lot of people make is that they never give themselves the opportunity to get data and get evidence and when I talk to people and I I work with people who have done something successful in terms of like making progress in their life or correcting their mistakes there is always a data Gathering or evidence Gathering process now a lot of people who are listening to this will be but I do have evidence all of this stuff happened in the past this is a fact about my life this is why people I it&#39;s POS for me to date I have all of this evidence so this is also where we got to be a little bit careful so when we&#39;re talking about collecting evidence it&#39;s not just have these things happened in the past what we want to do is something that&#39;s like a prospective trial so anytime we&#39;re doing science there&#39;s retrospective data and there&#39;s prospective data and retrospective data is way lower quality than prospective data so when we&#39;re thinking about really feeding our brain the right kind of data to correctly develop a counterfactual I know that&#39;s a a a mouthful so I&#39;ll say it again see if we want to hypothesize if we want to build this road map we actually need to give it as much data as possible and generally speaking people who correct their mistakes it&#39;s not like they correct their mistake once it&#39;s like okay I struggle in relationships let me date let me date again let me date again let me date again and as I date 15 different times then over time the natural model that my brain will construct about how I should fix my mistakes gets more and more and more more robust the good news is that you actually don&#39;t have to work very hard at this the brain will do the computation all its own on its own all you need to do is feed at the right data now let&#39;s talk about but Dr K it&#39;s not easy to do that right it&#39;s not just easy to go out there and collect data well why not well that&#39;s because of the motivation so if I&#39;m struggling with dating and I go out and I date once what do I feel I feel ashamed of myself I feel so pathetic and then what do I do I avoid so this is the cool thing we already addressed that in the first half of the video that&#39;s why it&#39;s structured this way and this is the key thing that you all need to understand see anytime we&#39;re stuck the basic problem is that we are not utilizing the corrective circuitry of our brain in the right way our brain has the left hemisphere and the right hemisphere right and I know that like some of that stuff has been debunked but a lot of it is true so we know that the left hemisphere focuses on analysis and the right hemisphere focuses on emotion and we also know that the most productive and successful state of human consciousness is something called The Flow State and what do we see in the brain of the Flow State we see Harmony between the left brain and the right brain we see an activity of emotion along with an appropriate level of analysis and if you&#39;re struggling to fix your mistakes chances are that these two circuits are not working together it is insufficient and this is the biggest mistake that that I see a lot of people make is they think that it is one or the other right they think like oh I feel so ashamed of myself I should just focus on the shame that&#39;s a great place to start but then you also need to feed your counterfactual circuitry so that it can develop the right models to help you succeed and we do this in the gaming world right like when we play video games we do this successful where it&#39;s like okay I&#39;m going to make up a build and I&#39;m going to try it that didn&#39;t work I&#39;m going to adjust my build I&#39;m going to try again I&#39;m going to adjust my build I&#39;m going to try it again and then eventually like we kind of make the build work like we&#39;re capable of doing it the problem is that in real life we do not give our brain the same level of data so we have to address our emotions we have to be super careful about avoiding shame because when we avoid shame all we experience is the pain of Shame without any of the corrective Behavior right so then what happens if I&#39;m avoiding shame I don&#39;t actually fix anything and the next time I leave the house I feel ashamed of myself again and then the next time I feel the house leave the house I feel ashamed of myself again so we actually create is a really crazy situation where when we avoid shame we create a persistent shameful existence that&#39;s crazy instead what we need to do is harness that shame use it as motivational fuel to fix our problems that needs to be com combined with a very robust counterfactual apparatus that allows us to analyze our problems and we need to feed at the right inputs what makes it hard to feed the right inputs the shame that we experience causes us to avoid so when I work with people this is these are usually the two components it&#39;s about Unity between the left brain and the right brain and literally when people are able to do this in a more robust manner this is what we call the Flow State so if you&#39;re stuck in life if you feel like you&#39;re making the same mistakes over and over again ask yourself these two questions number one am I just Theory crafting my way all the way from the Earth to the Moon without ever building a sh spaceship and never launching something or it&#39;s probably that you&#39;re it&#39;s not never it&#39;s that it&#39;s very rare what&#39;s the percentage of theory crafting you do and what&#39;s the percentage of data collection you do the other question to ask yourself is when you feel shame are you harnessing it to create a change in your life because it&#39;s one of the most powerful motivators in existence or are you avoiding that shame and perpetuating your current existence and hopefully what will happen is as you ask these two questions you will learn from your mistakes and start to progress more in life hey y&#39;all if you&#39;ve watched our content for a while you&#39;re probably pretty familiar with our Core Concepts and that&#39;s why I&#39;m excited about you memberships memberships allows us to dive deeper in a lot more detail on these Core Concepts we&#39;ve also explored more advanced yogic or spiritual Concepts like vasana and Kisha which will help you understand how habits form in your mind and how to break those habits memberships are also community-driven which means that y&#39;all get to vote on which lectures I will be preparing for the next month they&#39;re 10 bucks a month and if you don&#39;t like the vibe of it it&#39;s painless to cancel so I hope youall definitely check it out and I hope to see yall next month [Music] 

```
### Fabric - Extract Wisdom Prompt 

```
# IDENTITY and PURPOSE

You extract surprising, insightful, and interesting information from text content. You are interested in insights related to the purpose and meaning of life, human flourishing, the role of technology in the future of humanity, artificial intelligence and its affect on humans, memes, learning, reading, books, continuous improvement, and similar topics.

Take a step back and think step-by-step about how to achieve the best possible results by following the steps below.

# STEPS

- Extract a summary of the content in 25 words, including who is presenting and the content being discussed into a section called SUMMARY.

- Extract 20 to 50 of the most surprising, insightful, and/or interesting ideas from the input in a section called IDEAS:. If there are less than 50 then collect all of them. Make sure you extract at least 20.

- Extract 10 to 20 of the best insights from the input and from a combination of the raw input and the IDEAS above into a section called INSIGHTS. These INSIGHTS should be fewer, more refined, more insightful, and more abstracted versions of the best ideas in the content. 

- Extract 15 to 30 of the most surprising, insightful, and/or interesting quotes from the input into a section called QUOTES:. Use the exact quote text from the input.

- Extract 15 to 30 of the most practical and useful personal habits of the speakers, or mentioned by the speakers, in the content into a section called HABITS. Examples include but aren't limited to: sleep schedule, reading habits, things they always do, things they always avoid, productivity tips, diet, exercise, etc.

- Extract 15 to 30 of the most surprising, insightful, and/or interesting valid facts about the greater world that were mentioned in the content into a section called FACTS:.

- Extract all mentions of writing, art, tools, projects and other sources of inspiration mentioned by the speakers into a section called REFERENCES. This should include any and all references to something that the speaker mentioned.

- Extract the most potent takeaway and recommendation into a section called ONE-SENTENCE TAKEAWAY. This should be a 15-word sentence that captures the most important essence of the content.

- Extract the 15 to 30 of the most surprising, insightful, and/or interesting recommendations that can be collected from the content into a section called RECOMMENDATIONS.

# OUTPUT INSTRUCTIONS

- Only output Markdown.

- Write the IDEAS bullets as exactly 15 words.

- Write the RECOMMENDATIONS bullets as exactly 15 words.

- Write the HABITS bullets as exactly 15 words.

- Write the FACTS bullets as exactly 15 words.

- Write the INSIGHTS bullets as exactly 15 words.

- Extract at least 25 IDEAS from the content.

- Extract at least 10 INSIGHTS from the content.

- Extract at least 20 items for the other output sections.

- Do not give warnings or notes; only output the requested sections.

- You use bulleted lists for output, not numbered lists.

- Do not repeat ideas, quotes, facts, or resources.

- Do not start items with the same opening words.

- Ensure you follow ALL these instructions when creating your output.

# INPUT

INPUT:


```

# Output 

## Human (Me)

```
### IDEAS:
- Avoiding shame, means that we lose out on the corrective behaviour it inspires.
- There is toxic shame which is just bad. But regular shame can be harnessed to create a change in your life. Negative emotions are very motivational.
- If you just try to ignore it, you stay in that situation that perpetuates this shame. Stuck in misery.
- Modern escapism - internet - allows us to avoid shame in a way we could not before.
- You need to gather sufficient data (not just I dated a few times, but I dated 15 times and I fixed this, that, because of this, and it didn't work so fix that).
- We theory craft too much and collect too little data. Our brain likes to make counterfactuals of 'I should have done this' but we don't usually go try out in similar situation. 

```

## Fabric (gemini-1.5-flash-latest)

```
### SUMMARY

Dr. K discusses how society's avoidance of shame and overreliance on theory crafting hinders our ability to learn from mistakes and progress.

### IDEAS:

- Shame evolved to motivate corrective behavior in unavoidable social circumstances.
- Modern society's escape mechanisms like the internet and substances suppress shame's function.
- Avoiding shame prevents corrective action and perpetuates a cycle of self-sabotage.
- Making amends and embracing shame can lead to accountability and positive change.
- Toxic shame is different from shame and is characterized by inappropriate and persistent criticism.
- Counterfactual thinking is a vital brain circuit that allows us to learn from mistakes.
- Avoidant lifestyles weaken our counterfactual thinking capacity.
- Theory crafting without practical experience leads to ineffective solutions.
- Data gathering and evidence-based learning are crucial for effective counterfactual thinking.
- Prospective data is more valuable than retrospective data for learning.
- The Flow State is achieved through a harmonious balance between left and right brain functions.
- Neglecting either emotional or analytical aspects hinders progress.
- Avoiding shame creates a persistent shameful existence.
- Harnessing shame as motivational fuel is essential for growth.
- Combining shame with robust counterfactual thinking enables corrective action.
- Asking ourselves about our theory crafting vs. data collection and shame avoidance vs. harnessing is crucial for self-reflection.

### INSIGHTS:

- Shame is a powerful motivator for change, but it's only effective when we can't escape its consequences.
- Modern society's focus on avoidance and instant gratification undermines our ability to learn from mistakes.
- Counterfactual thinking requires a balance between theory crafting and real-world experience.
- Effective learning involves a continuous cycle of data collection, analysis, and action.
- The Flow State is a state of optimal consciousness that integrates both emotional and analytical processing.
- Avoiding shame can trap us in a cycle of self-sabotage, while embracing it can fuel positive change.

### QUOTES:

- "The basic problem is not that we make the mistake, but that we make it again and then we make it again and then we make it again."
- "Anytime our body or our brain makes us feel bad, these are very, very important drivers for corrective behavior."
- "If I got made fun of because of the way that I look or my weight, either I'm too skinny or I'm too fat, then this shame, since I'm going to see these people again, can be motivational fuel for me to take corrective action."
- "The only reason that shame worked is because I had to go to school every day."
- "When you stop running away from shame, you start gaining accountability."
- "Toxic shame is when people make you feel inappropriately ashamed, and in that case, there is no corrective behavior."
- "The most powerful motivators for human behavioral change are actually negative emotions."
- "We experience a lot of counterfactual thinking when we go through something like a breakup."
- "In the worst cases, this becomes something like maladaptive daydreaming where we get so lost in the counterfactual thinking that we get divorced from reality."
- "The first iteration of the solution that your mind comes up with is not going to be very accurate because you have a minimum of data and evidence."
- "Our brain doesn't respond very well to theory crafting; our brain does theory crafting with evidence."
- "We can't theory craft our way from 0 to 100."
- "The most productive and successful state of human consciousness is something called the Flow State."
- "We see harmony between the left brain and the right brain, we see an activity of emotion along with an appropriate level of analysis."
- "When we avoid shame, all we experience is the pain of shame without any of the corrective behavior."

### HABITS:

- Embrace shame as a motivator for change.
- Engage in counterfactual thinking to analyze mistakes.
- Gather data and evidence through real-world experiences.
- Balance theory crafting with practical action.
- Seek harmony between left and right brain functions.
- Avoid escaping from uncomfortable emotions.
- Cultivate a growth mindset by accepting mistakes as learning opportunities.
- Practice self-reflection and question your thought patterns.

### FACTS:

- The amygdala is a part of the brain responsible for processing basic survival emotions.
- Shame and guilt are social emotions that evolved in social creatures.
- Shame is a powerful motivator for change, but it can become toxic when it's persistent and unwarranted.
- Counterfactual thinking is a cognitive process that involves imagining alternative scenarios.
- Maladaptive daydreaming is a condition where people get lost in their own thoughts and fantasies.
- The Flow State is characterized by a balance between emotional and analytical processing.
- The left hemisphere of the brain is associated with analytical thinking, while the right hemisphere is associated with emotions.

### REFERENCES:

- Dr. K's Guide to Mental Health
- YouTube Store
- Free Resource Packs
- Meditation
- ADHD
- Trauma
- Vasana
- Kisha
- Reddit
- Mi I Posts
- Gaming Builds
- Zerg Rush
- Four Pool Rush
- The Meta Builds
- Prospective Trials
- Retrospective Data
- Flow State
- Spaceship

### ONE-SENTENCE TAKEAWAY:

Harnessing shame as motivational fuel and balancing theory crafting with real-world experience are essential for overcoming mistakes and achieving personal growth.

### RECOMMENDATIONS:

- Embrace shame as a motivator for positive change, rather than avoiding it.
- Engage in counterfactual thinking to analyze mistakes and explore alternative solutions.
- Collect data and evidence through real-world experiences, rather than relying solely on theory crafting.
- Seek a balance between analytical thinking and emotional processing to achieve the Flow State.
- Utilize Dr. K's resources to gain deeper insights into mental health and personal growth.
- Challenge yourself to step outside of your comfort zone and embrace new experiences.
- Practice self-reflection and question your thought patterns to identify areas for improvement.
- Remember that progress is a journey, not a destination, and setbacks are opportunities for learning.
- Stay curious and seek out new knowledge and perspectives to expand your understanding of the world.
- Believe in your ability to learn, grow, and overcome challenges.

```




## Cydonia 22B v1.1 Q6_K

```
 # SUMMARY
Dr. K discusses how social emotions like shame and guilt, which are meant to motivate us to correct our mistakes, have become less effective due to the increased availability of escapes like the internet and substances such as THC and CBD. He explains how our brains need both a roadmap (counterfactual thinking) and fuel (motivation) to take corrective action, but many people focus only on one aspect, neglecting the other. He provides examples from his personal life and Alcoholics Anonymous to illustrate the importance of embracing shame instead of avoiding it.

# IDEAS:
- Society has become escape and avoidant-heavy, making shame less effective as a motivator for change.
- Shame evolved under circumstances of permanent contact and unavoidable consequences.
- Negative emotions like shame are powerful motivators for behavioral change.
- The brain uses counterfactual thinking to correct mistakes by fantasizing about alternative outcomes.
- Theory crafting without experience leads to inaccurate solutions.
- Prospective data is more valuable than retrospective data for building robust models.
- The Flow State requires harmony between the left and right hemispheres of the brain.
- Avoiding shame perpetuates a persistent shameful existence.
- Asking two questions can help us learn from mistakes: how much theory crafting vs. data collection, and if we're harnessing shame as motivation.

# INSIGHTS:
- Shame is designed to induce corrective behavior but becomes ineffective when avoided.
- The brain needs both a roadmap and motivational fuel to learn from mistakes.
- Counterfactual thinking requires experience and evidence for success.
- Embracing shame and gathering data is crucial for personal growth.
- Harmony between analysis and emotion leads to the Flow State.
- Avoiding shame creates a cycle of persistent failure.

# QUOTES:
"Shame hurts a lot, guilt hurts a lot... that's the whole purpose of shame."
"We have evidence-based techniques that we've dug into about what to do about this."
"In order for counterfactual thinking to work successfully, it actually needs as much data or evidence as possible."
"The most productive and successful state of human consciousness is something called the Flow State."
"When we avoid shame, all we experience is the pain of shame without any of the corrective behavior."

# HABITS:
- Embrace shame instead of avoiding it.
- Gather data through prospective trials to build robust models.
- Combine emotional and analytical processes for a balanced approach.
- Avoid theory crafting without experience.
- Harness shame as motivation for change.

# FACTS:
- 50% of people under 30 live with their parents.
- Loneliness, addiction, depression, and anxiety are on the rise.
- The amygdala is responsible for primitive emotions like fear and anger.
- Counterfactual thinking occurs in the brain when we make mistakes.
- Toxic shame is when people feel inappropriately ashamed with no corrective behavior.
- The Flow State involves harmony between the left and right hemispheres of the brain.

# REFERENCES:
- Dr. K's guide to mental health
- Alcoholics Anonymous (AA)
- Counterfactual thinking in video games
- ADHD and maladaptive daydreaming
- Memberships for deeper content and community-driven lectures

# ONE-SENTENCE TAKEAWAY:
Embracing shame and gathering data through experience is key to learning from mistakes and personal growth.

# RECOMMENDATIONS:
- Face your shame to gain accountability and motivation.
- Gather evidence to build accurate counterfactual models.
- Balance analysis and emotion for optimal results.
- Avoid theory crafting without experience.
- Use shame as a powerful motivator.
- Join Dr. K's memberships for detailed content and community support.
```

## Cydonia 22B v2c Q6_K

```
 # SUMMARY

Dr. K discusses why people repeat mistakes, linking it to an inability to properly process guilt and shame due to modern society's escape avoidance culture and excessive theory crafting without real-world testing. He explains how the brain corrects mistakes through counterfactual thinking and motivation, but these mechanisms are hampered when people avoid shame and don't gather data. Achieving flow requires uniting emotions (right brain) and analysis (left brain).

# IDEAS:

- People repeat mistakes because they can't correct their behavior
- Loneliness, addiction, depression rising; difficulty taking action
- Brain needs map (knowledge) and motivation to change
- Amygdala feels primitive emotions; prefrontal cortex feels social ones
- Shame drives corrective behavior if you can't escape it
- Counterfactual thinking helps analyze past mistakes
- Theory crafting without real-world testing is ineffective
- Flow state unites left brain analysis and right brain emotion
- Avoiding shame prevents behavior change
- Gathering data feeds brain's correction abilities

# INSIGHTS:

- Shame motivates corrective action when unavoidable
- Theory must be tested for counterfactual thinking to work
- Flow state balances analysis and emotion
- Avoiding shame hinders progress
- Real-world data, not just theory, fixes mistakes
- Uniting brain hemispheres aids change

# QUOTES:

"Our brain has a couple of different areas of emotional circuitry. We have this primitive part of our brain that includes the amygdala, where we feel fear, anxiety, anger."
"The problem in today's society is that we have one alternate solution to shame which did not exist a couple of hundred years ago, which is escape."
"The most powerful motivators for human behavioral change are actually negative emotions and our social negative emotions are incredibly strong at that."
"When we start to live an avoidant life, our brain's capacity for counterfactual thinking becomes weaker."
"The critical mistake that a lot of people make is that they never give themselves the opportunity to get data and get evidence."

# HABITS:

- Face shame to motivate change
- Collect real-world data, not just theory
- Test theories in reality
- Avoid excessive avoidance
- Unite analysis with emotion
- Seek flow state balance

# FACTS:

- 50% of under-30s live at home
- Loneliness, addiction, depression rising
- Shame evolved for permanent social contact
- Counterfactual thinking helps correct mistakes
- Theory crafting without data is ineffective
- Flow state unites brain hemispheres
- Avoidance perpetuates shame and issues

# REFERENCES:

- Alcoholics Anonymous 12 steps
- Maladaptive daydreaming linked to ADHD
- Retrospective vs. prospective data
- Left/right brain analysis and emotion
- Flow state concept

# ONE-SENTENCE TAKEAWAY:

Unite real-world data with shame-driven motivation to learn from mistakes and achieve flow.

# RECOMMENDATIONS:

- Face shame, don't avoid it
- Collect real-life evidence, not just theory
- Test hypotheses in reality
- Balance emotion and analysis for flow
- Avoid excessive escape and avoidance
```

## Cydonia 22B v2h Q6_K

```
 SUMMARY: Dr. K discusses how modern society's avoidance of shame and guilt is preventing people from learning from mistakes and taking corrective action, using evolutionary psychology to explain the role these emotions play in behavioral change. He provides steps to harness shame as motivational fuel and improve counterfactual thinking for problem-solving.

IDEAS:
- Avoiding shame through distractions like internet friends or substances prevents learning from mistakes.
- Shame evolved to motivate corrective social behavior in permanent social groups.
- Toxic shame lacks a clear path to redemption, unlike healthy shame.
- Counterfactual thinking helps correct mistakes but requires real-world data, not just theory.
- The brain needs both emotion and analysis to enter a flow state for optimal learning.
- Over-reliance on theory crafting without data prevents progress.
- Combining shame and counterfactual thinking can break repeating mistake cycles.
- Shame and guilt are powerful motivators when properly harnessed.
- Social emotions evolved for permanent social contact, now avoidable.
- Alcoholics Anonymous uses shame to motivate amends and accountability.
- Maladaptive daydreaming can replace real problem-solving with fantasy.
- Video games show how theory crafting works best with trial and error.
- Addiction and anxiety rise with loneliness and escape from shame.
- Flow state balances left brain analysis with right brain emotion.
- Shame avoidance creates a persistent shameful existence.
- Shame and guilt are painful drivers of behavioral change.
- Many struggle to correct mistakes despite knowing the solution.
- Theory crafting without data leads to poor problem-solving.
- Shame can be harnessed for positive change when not avoided.
- Counterfactual thinking needs real-world evidence, not just past experience.
- Emotional and analytical brain parts must work together for progress.
- Shame avoidance prevents collecting data to fix problems.
- Social emotions require social circumstances to function.
- Repeated mistakes indicate a problem with corrective circuits.
- Addiction often preceded by toxic shame.
- Internet and substances enable escape from shame.
- Avoiding shame perpetuates the problem it indicates.
- Brain uses counterfactual thinking to correct errors.
- Toxic shame lacks clear path to redemption like healthy shame.
- Shame and guilt motivate when combined with analysis.
- Flow state needs both emotion and logic for optimal performance.
- Theory crafting without data is ineffective problem-solving.
- Avoidance creates a cycle of persistent shame.
- Real-world trials improve counterfactual thinking models.
- Shame is an evolutionary driver of social behavior.
- Avoiding shame prevents behavioral change.
- Counterfactual thinking requires real data, not just ideas.
- Healthy shame motivates fixing problems.
- Prospective data beats retrospective for counterfactuals.
- Shame avoidance leaves shame's pain without fixes.
- Brain needs both sides for flow state problem-solving.
- Theoretical solutions must be tested in reality.
- Counterfactual thinking improves with practice.
- Shame motivates when not avoided.
- Addiction and anxiety linked to shame avoidance.
- Healthy shame has a redemption path, toxic doesn't.
- Shame and guilt are powerful change drivers.
- Theory crafting needs real-world trials, not just thoughts.
- Flow state balances emotion and logic for learning.
- Shame avoidance leaves problems unresolved.
- Brain models improve with varied data.
- Social emotions need social contact to work.
- Shame is painful to motivate change when faced.
- Shame and guilt are evolutionary drivers of behavior.
- Counterfactual thinking needs real input, not just memories.
- Theory crafting without trials is ineffective.
- Toxic shame has no clear fix, unlike healthy shame.
- Emotions and logic combine for optimal learning.
- Shame avoidance keeps shame persistent.
- Healthy shame motivates fixing problems.
- Counterfactual thinking models need real evidence.
- Flow state requires both hemispheres working together.
- Theory crafting must be tested in reality.
- Shame and guilt evolved for social living.
- Avoidance prevents shame's behavioral change.
- Brain uses counterfactuals for error correction.
- Healthy shame has a path to redemption.
- Shame avoidance leaves problems unresolved.
- Counterfactual thinking needs real input, not just ideas.
- Flow state balances emotion and analysis for success.
- Theory crafting needs trials, not just thoughts.
- Shame motivates when faced, not avoided.
- Shame and guilt are powerful behavior drivers.
- Counterfactual thinking models improve with practice.
- Shame avoidance keeps shame persistent.
- Healthy shame inspires fixing problems.
- Emotions and logic together optimize learning.
- Theory crafting needs real tests, not just ideas.
- Flow state combines emotion and analysis.
- Shame avoidance leaves shame unresolved.
- Brain models improve with varied data input.
- Social emotions need social contact to work.
- Shame motivates change when faced.
- Counterfactual thinking needs real evidence, not memories.
- Theory crafting without trials is ineffective.
- Toxic shame lacks clear redemption like healthy shame.
- Emotions and logic together enable flow state.
- Shame avoidance keeps shame persistent.
- Healthy shame motivates fixing problems
```

I stopped it at this point as it was just running away, and adjusted penalties. 
### Higher Penalty 
Repeat penalty 1.1 fixed this issue. Could be a bad generation.

```
 # SUMMARY
Dr. K explains how modern society's escapist tendencies undermine shame as a motivator for corrective action, leading people to make the same mistakes repeatedly due to lack of data-driven counterfactual thinking and avoidance of painful emotions. He suggests facing shame and gathering real-world evidence to fuel behavioral change.

# IDEAS
Shame evolved as a social emotion to drive corrective behavior in permanent social situations; now, avoidance via internet/substances negates its purpose. - Shame is a powerful motivator when unavoidable social consequences force accountability and change. - Toxic shame has no corrective action; healthy shame fuels positive growth if faced directly. - Counterfactual thinking helps correct mistakes but requires real-world data, not just theorycrafting. - Flow state emerges from harmony between left (analysis) & right (emotion) brain hemispheres. - Avoidance of shame perpetuates chronic shame without change; facing it drives progress.

# INSIGHTS
Shame's power as a motivator is undermined by modern escapism and avoidance behaviors. 
Data-driven counterfactual thinking, not just theorycrafting, enables effective behavioral change.
Harmony of analytical and emotional brain circuits is key to the flow state and personal growth.
Facing shame head-on converts it into a positive force for transformation.
Avoidance sustains chronic shame without resolving root issues; embracing shame catalyzes progress.

# QUOTES
"The only reason that shame worked is because I had to go to school every day, right? There was no way to avoid the consequences."
"When we think about a tribal situation, if a chimpanzee is ashamed of itself it has no choice but to interact with these same people..."
"You actually create this alternate scenario where okay I don't have to experience the shame because I can avoid these people... I never have to fix it."
"In order for counterfactual thinking to be the most successful, we actually need as much data or evidence as we can get our hands on."
"When we're struggling to fix our mistakes chances are that these two circuits [left/right brain] are not working together..."

# HABITS
Facing shame directly instead of avoiding it.
Gathering real-world evidence to inform counterfactual thinking.
Balancing analysis with emotion for flow state and personal growth.
Asking self: Am I theorycrafting too much vs data collection?
Embracing shame's motivational power to catalyze change.

# FACTS
50% of young adults live with parents, reflecting economic struggles.
Loneliness, addiction, depression, anxiety, low self-esteem on the rise.
THC/CBD availability up; used to manage shame/anxiety.
Shame evolved in permanent social settings, unlike modern escapist options.
Counterfactual thinking requires data, not just theorycrafting.
Flow state emerges from left/right brain harmony.

# REFERENCES
Alcoholics Anonymous' step of making amends.
Video game theorycrafting vs actual play data.
Dr. K's YouTube membership program.
Vasana and kisha yogic concepts for habit-breaking.
Reddit/YouTube content as potential distractions.

# ONE-SENTENCE TAKEAWAY
Facing shame directly, with real-world evidence, fuels behavioral change via flow state harmony of mind.

# RECOMMENDATIONS
Embrace shame to drive accountability & progress. 
Gather data for counterfactual thinking, not just theorycraft.
Balance analysis and emotion for optimal growth.
Avoid escapism; face challenges head-on for change.
Leverage shame's power to catalyze personal evolution.

```

## Qwen 2.5 32B Instruct - bartowski

```
## SUMMARY:
A speaker discusses the impact of avoidance behaviors, shame, and the importance of facing mistakes to facilitate personal growth and emotional correction, highlighting modern society’s tendency to avoid corrective actions through technology and substances. The discussion covers brain functions, motivation, and practical steps for improvement.

## IDEAS:
- Avoiding shame and guilt hinders corrective behavior in society due to technological escape mechanisms.
- Shame and guilt evolved under permanent social contact to induce behavioral change.
- Counterfactual thinking helps in analyzing mistakes but needs real-life data, not just theory crafting.
- Shame's purpose is to motivate corrective actions; avoiding it prevents personal growth.
- Social emotions like shame require social interaction for proper functioning.
- Avoidance of shame leads to persistent shameful existence, preventing problem resolution.
- Emotional and analytical balance (left-right brain) needed for flow state and progress.
- Addiction and loneliness rising due to avoidance of social emotions.
- Alcoholic recovery methods highlight facing shame for corrective action.
- Internet and substances suppress social circuitry for corrective actions.
- Shame-induced changes can lead to positive motivation when embraced.
- Brain's counterfactual thinking enhances with real-life data, not just theory crafting.
- Avoiding problems creates a cycle of repeated mistakes.
- Motivation and roadmap both essential for behavioral correction.
- Shame evolved under unavoidable social circumstances; internet allows avoidance.
- Shame's function disrupted by modern avoidance techniques.
- Theory crafting without data hinders progress in personal issues.
- Avoidance of shame perpetuates problematic behavior loops.
- Repeated mistakes due to lack of real-life experience and data.
- Social emotions' effectiveness diminished with technological distractions.
- Learning from mistakes requires facing them head-on.
- Addiction to substances can mask underlying shame.
- Shame and guilt are powerful motivators when channeled correctly.
- Avoiding social contact prevents corrective behavior development.
- Avoiding mistakes’ consequences leads to repeated errors.
- Emotional pain drives corrective actions, essential for survival.
- Counterfactual thinking weakens with avoidance of real-life data.
- Social emotions need social interaction to drive change effectively.
- Shame is a motivator when faced rather than avoided.
- Avoidant behavior hampers brain’s corrective mechanisms.
- Social isolation increases with modern distractions.

## INSIGHTS:
- Facing shame and guilt promotes behavioral changes, avoiding them hinders growth.
- Real-life data crucial for effective counterfactual thinking, not just theory crafting.
- Shame evolved under social pressure now disrupted by technology.
- Balance between emotion and analysis vital for personal progress.
- Avoiding shame prevents corrective actions, perpetuates mistakes.
- Social emotions drive change; modern avoidance disrupts this process.
- Addiction and loneliness linked to avoiding corrective emotions.
- Shame-induced changes require facing the source to resolve issues.
- Corrective behavior needs emotional engagement, not just analysis.
- Persistent shameful existence from avoiding social contact.
- Embracing shame can transform into positive motivators.
- Avoiding problems creates more complex issues.
- Emotional pain drives corrective actions, essential for survival.
- Social emotions' effectiveness diminished with modern distractions.
- Avoiding mistakes leads to repeated errors.
- Brain’s corrective circuits need real-life data, not just theory crafting.
- Facing shame promotes personal development and progress.

## QUOTES:
- "So now we we run into a real serious problem now the problem is that since we can avoid contact this emotion doesn't work the way that it's supposed to anymore."
- "When you stop running away from shame you start gaining accountability and once they start gaining accountability their life moves in the correct direction."
- "The only reason that shame worked is because I had to go to school every day right there was no way to avoid the consequences."
- "So now what happens is when we we we create this alternate scenario where okay I don't have to experience the shame because I I can avoid these people and what does that mean for my corrective behavior."
- "In order to take corrective action our brain needs to do two processes the first is it goes through something called a counterfactual thinking exercise."

## HABITS:
- Face your shame to gain accountability and progress.
- Collect real-life data instead of just theory crafting.
- Embrace corrective emotions, avoid avoidance behaviors.
- Engage in social interactions to process guilt and shame.
- Balance emotional and analytical brain functions for progress.
- Regularly date or face fears to gather evidence.
- Play video games less, focus on real-life challenges.
- Work on counterfactual thinking with actual experiences.

## FACTS:
- 50% of people under 30 living at home due to external factors.
- Rise in loneliness, addiction, and low self-esteem noted.
- Shame evolved under circumstances of permanent social contact.
- THC and CBD availability increases for managing emotions.
- Alcoholic recovery involves facing shame through amends.
- Counterfactual thinking weakens with avoidance.
- Social emotions like guilt need social interaction to function.
- Emotional pain is a driver for corrective behavior.
- Avoiding shame creates persistent shameful existence.

## REFERENCES:
- Dr K's guide to mental health.
- YouTube store for additional resources.
- Videos on meditation, ADHD, and trauma.
- Free resource packs linked below.
- Advanced yogic or spiritual Concepts like vasana and kisha.

## ONE-SENTENCE TAKEAWAY:
Facing shame and gathering real-life data corrects mistakes for behavioral change.

## RECOMMENDATIONS:
- Embrace shame to harness positive motivators for corrective actions.
- Gather real-life data, avoid purely theoretical solutions.
- Balance emotional and analytical brain functions for flow state.
- Face social emotions directly instead of avoiding them.
- Address shame by making amends to those wronged regularly.
- Utilize both emotion and analysis for behavioral correction.
- Avoid Theory crafting without real-life experience.
- Collect prospective data for effective counterfactual thinking.
- Work on emotional accountability and corrective actions.
- Face your problems directly, avoid avoidance behaviors.
- Use shame as motivational fuel for personal growth.
- Balance social contact to utilize emotions effectively.
- Address shame and guilt through direct interaction.
```


## Llama 3.1 70B - lmstudio-community
```
**SUMMARY**
Dr. K on overcoming mistakes, shame, and corrective action, discussing how to break cycles of failure.

**IDEAS**
* Emotions like guilt and shame help induce behavioral change, but are hindered by modern escape mechanisms.
* Avoiding shame prevents learning from mistakes and corrective behavior.
* Counterfactual thinking is key to analyzing past mistakes and improving.
* Theory crafting without data leads to weak solutions and maladaptive daydreaming.
* Embracing shame can lead to accountability and positive change.
* The brain needs both motivation and a roadmap to correct mistakes.
* Shame is a powerful motivator, but toxic shame is debilitating.
* Humans need social interaction to experience emotions like guilt and shame.
* The brain's capacity for counterfactual thinking weakens with avoidant behavior.
* Gathering data and evidence is crucial for successful theory crafting.
* Unity between left and right brain hemispheres enables the Flow State.
* Avoiding shame creates a persistent, shameful existence.
* Harnessing shame as motivational fuel can lead to progress.
* Modern society hinders corrective action with escape mechanisms.
* The brain's corrective circuitry requires emotional and analytical components.
* Focusing solely on theory crafting without experience leads to stagnation.
* Counterfactual thinking is essential for learning from mistakes.
* Emotions like fear, anxiety, and anger are primitive, while guilt and shame are social emotions.
* The human brain experiences guilt and shame to induce corrective behavior.
* Shame is painful, but can be a motivator for change.
* Avoiding contact with people who cause shame hinders emotional growth.
* Substance availability and internet escapism hinder emotional growth.
* Making amends can help overcome shame and addiction.
* Toxic shame differs from regular shame in its lack of corrective action.
* The brain needs both intellectual understanding and motivation to correct mistakes.
* Shame is a social emotion that requires social circumstances.
* Counterfactual thinking meets ADHD in maladaptive daydreaming.
* Evidence-based techniques can help overcome shame and addiction.

**INSIGHTS**
* Shame and guilt are essential for human growth, but modern society hinders their effectiveness.
* Avoidant behavior prevents the brain from learning from mistakes.
* Corrective action requires both emotional and analytical components.
* The Flow State enables successful problem-solving and progress.
* Embracing shame can lead to positive change and accountability.
* Theory crafting without data leads to stagnation and maladaptive daydreaming.
* Unity between left and right brain hemispheres is crucial for success.
* Humans need social interaction to experience emotions like guilt and shame.
* The brain's capacity for counterfactual thinking weakens with avoidant behavior.
* Modern society creates a persistent, shameful existence through escapism.
* Harnessing shame as motivational fuel can lead to progress.

**QUOTES**
* "The only reason that shame worked is because I had to go to school every day."
* "We have evidence-based techniques...to stop avoiding the shame."
* "Shame is a powerful motivator, but toxic shame is debilitating."
* "Avoiding contact with people who cause shame hinders emotional growth."
* "Making amends can help overcome shame and addiction."
* "The brain needs both intellectual understanding and motivation to correct mistakes."
* "Theory crafting without data leads to weak solutions and maladaptive daydreaming."
* "Unity between left and right brain hemispheres enables the Flow State."
* "Harnessing shame as motivational fuel can lead to progress."
* "Modern society hinders corrective action with escape mechanisms."

**HABITS**
* Dr. K plays video games late at night, despite knowing he should go to bed.
* People tend to make the same mistakes repeatedly due to lack of motivation and roadmap.
* Avoiding shame prevents learning from mistakes and corrective behavior.
* Reading books and watching videos without experience is ineffective.
* Gathering data and evidence is crucial for successful theory crafting.
* Dr. K recommends embracing shame to overcome addiction.
* Making amends can help overcome shame and addiction.
* Theory crafting without data leads to stagnation and maladaptive daydreaming.

**FACTS**
* 50% of people under 30 are living at home due to external factors.
* There is a rise in loneliness, addiction, depression, and anxiety.
* Shame and guilt are social emotions that require social circumstances.
* The human brain experiences guilt and shame to induce corrective behavior.
* Counterfactual thinking is essential for learning from mistakes.
* The brain's capacity for counterfactual thinking weakens with avoidant behavior.
* Modern society hinders corrective action with escape mechanisms.
* Substance availability and internet escapism hinder emotional growth.
* The Flow State enables successful problem-solving and progress.

**REFERENCES**
* Dr. K's guide to mental health
* YouTube videos on motivation and ADHD
* Reddit posts on relationships
* Books on motivation and relationships
* Discussion forums on motivation and relationships

**ONE-SENTENCE TAKEAWAY**
Embracing shame as motivational fuel and gathering data for counterfactual thinking can help overcome mistakes.

**RECOMMENDATIONS**
* Stop avoiding shame to learn from mistakes and correct behavior.
* Harness shame as motivational fuel for positive change.
* Gather data and evidence to inform theory crafting.
* Practice counterfactual thinking to analyze past mistakes.
* Make amends to overcome shame and addiction.
* Focus on unity between left and right brain hemispheres.
* Engage in social interaction to experience emotions like guilt and shame.
* Avoid excessive theory crafting without experience.
* Use shame as a motivator for positive change.
* Develop a roadmap and intellectual understanding for corrective action.
* Overcome avoidant behavior to enable the Flow State.
* Use evidence-based techniques to overcome shame and addiction.
```
# Other things
## Seperate - Using Python Code - Mistral 7B

[GitHub - Lucius-Q-User/summarizer](https://github.com/Lucius-Q-User/summarizer)

Command used `summarize YT_URL` after installing with `python -m pip install llama-summarizer` (Python 3.12)

No extract wisdom prompt, just what the library output

```
# Summary of [Why You Keep Making The Same Mistakes](https://www.youtube.com/watch?v=WpoYqs9Hsa4)

### [00:00:00](https://www.youtube.com/watch?v=WpoYqs9Hsa4&t=0)

The video discusses the importance of acknowledging and addressing emotions, particularly shame, in order to make progress in life. The speaker argues that shame can be a motivator for change, but it often gets avoided, leading to a cycle of shame and stagnation. The video explores the concept of "counterfactual thinking" and how it is a necessary step in correcting mistakes. The speaker suggests that people need to be able to analyze what they should do and then have the motivation to do it. The video also discusses the importance of understanding the brain's emotional circuitry and how it is affected by emotions such as guilt, shame, and anxiety. The speaker argues that these emotions can be painful and are a major obstacle to correcting mistakes. The video highlights the role of shame in driving corrective behavior and suggests that people often avoid dealing with their mistakes and emotions, leading to a lack of motivation and a sense of stuckness. The speaker proposes a solution, which involves harnessing shame as motivational fuel to drive corrective behavior. This requires a combination of a robust analytical approach (counterfactual apparatus) and the ability to feed the right inputs to address the problems. The video also discusses the concept of the "Flow State" which is achieved when the left and right brain work together in a more robust manner. Throughout the video, the speaker emphasizes the importance of gathering data and evidence to develop a counterfactual thinking strategy to correct mistakes and improve decision-making. The speaker also highlights the pitfall of relying too heavily on theory crafting and suggests that actual experience and data are necessary to develop accurate models of how to fix mistakes. Finally, the video concludes by promoting the speaker's membership program, which allows individuals to delve deeper into the core concepts discussed in the video, as well as explore more advanced spiritual and yogic concepts. The speaker also invites viewers to join the community and vote on which lectures they would like to see prepared in the next month.

- **[00:00:00](https://www.youtube.com/watch?v=WpoYqs9Hsa4&t=0)** In this section of the video, the speaker is discussing the topic of making mistakes and how to correct them. He is explaining that people often make the same mistakes over and over again, and that this is because their brain is not functioning properly in terms of correcting mistakes. The speaker is also discussing the concept of "counterfactual thinking" and how it is a necessary step in correcting mistakes. He is explaining that people need to be able to analyze what they should do and then have the motivation to do it. He is comparing this to driving a car, where you need a map (intellectual understanding) and fuel (motivation) to get from point A to point B. The speaker is also talking about the importance of understanding the brain's emotional circuitry and how it is affected by things like guilt, shame, and anxiety. He is explaining that these emotions can be painful and that they are a major obstacle to correcting mistakes. The speaker is also promoting his guide to mental health, which is a resource pack that includes additional videos and information on topics such as meditation, ADHD, and trauma.
- **[00:05:00](https://www.youtube.com/watch?v=WpoYqs9Hsa4&t=300)** In this section, the speaker is discussing the concept of shame and its role in driving corrective behavior. They use personal anecdotes and examples to illustrate how shame can be a motivator for change, such as feeling ashamed of oneself and taking action to improve oneself. The speaker argues that shame has evolved as a mechanism to encourage individuals to take corrective action in response to negative social experiences, such as being bullied. They note that in the past, individuals had to interact with their tormentors, making shame a powerful driver of change. However, the speaker suggests that in modern society, people have developed alternate solutions to shame, such as avoiding social interactions or using substances like THC and CBD to manage their emotions. This has led to a problem, as shame no longer serves its original purpose of encouraging individuals to take corrective action. The speaker proposes that the solution to this problem is to stop avoiding shame and instead confront and overcome the underlying issues that are causing shame. They use the example of step 5 in the 12-step program for recovering alcoholics, which involves making amends for past wrongs, as a way to illustrate this approach. Overall, the speaker is exploring the role of shame in driving personal growth and change, and arguing that modern society's tendency to avoid shame is actually hindering this process.
- **[00:10:00](https://www.youtube.com/watch?v=WpoYqs9Hsa4&t=600)** In this section, the speaker is discussing the concept of shame and its relationship to motivation and behavioral change. They are highlighting the importance of acknowledging and embracing shame in order to move forward and make positive changes in one's life. The speaker is also explaining the concept of toxic shame, which is a type of shame that is not based on reality and can be debilitating. The speaker is also discussing the concept of counterfactual thinking, which is the process of thinking about what could have been done differently in a situation. They are explaining that this process is natural and can be helpful in learning from mistakes, but can also become maladaptive if it leads to excessive daydreaming and avoidance of reality. The speaker is suggesting that people often avoid dealing with their mistakes and emotions, which can lead to a lack of motivation and a sense of stuckness. They are advocating for a more honest and courageous approach to dealing with one's emotions and mistakes, and for using the experience and data gained from mistakes to improve and grow.
- **[00:15:00](https://www.youtube.com/watch?v=WpoYqs9Hsa4&t=900)** In this section, the speaker is discussing the importance of gathering data and evidence to develop a counterfactual thinking strategy to correct mistakes and improve decision-making. They argue that simply reading or watching videos about a topic (theory crafting) is not enough, and that actual experience and data are necessary to develop accurate models of how to fix mistakes. The speaker highlights the pitfall of relying too heavily on theory crafting, where people may try to learn about a topic by reading and watching videos, but never actually take action or gather evidence. They also emphasize the importance of prospective data gathering, where individuals actively test their hypotheses and gather evidence, rather than relying on retrospective data from past experiences. The speaker also discusses the role of motivation and shame in preventing people from gathering data and evidence, as well as the importance of utilizing the brain's corrective circuitry, particularly the harmony between the left and right hemispheres, to achieve the Flow State and develop accurate models for success. They use the example of gaming to illustrate how players iteratively adjust their builds to achieve success, and argue that a similar approach is necessary in real life to correct mistakes and improve decision-making.
- **[00:20:00](https://www.youtube.com/watch?v=WpoYqs9Hsa4&t=1200)** In this section of the video, the speaker is discussing the importance of acknowledging and addressing emotions, particularly shame, in order to make progress in life. The speaker argues that when we avoid shame, we do not address the underlying problems and therefore perpetuate a cycle of shame and stagnation. The speaker then proposes a solution, which involves harnessing shame as motivational fuel to drive corrective behavior. This requires a combination of a robust analytical approach (counterfactual apparatus) and the ability to feed the right inputs to address the problems. The speaker also introduces the concept of the "Flow State" which is achieved when the left and right brain work together in a more robust manner. The section concludes with the speaker promoting their membership program, which allows individuals to delve deeper into the core concepts discussed in the video, as well as explore more advanced spiritual and yogic concepts. The speaker also invites viewers to join the community and vote on which lectures they would like to see prepared in the next month.
```

