# repo thoughts

Not a fan of blogs nor social networks, yet I find value in writing my thoughts because that is one good way to train the skill of writing.
So what is on my mind today?

I am practicing a silly approach to recurse a graph, going back to the basics training with trees and finding out ubuntu nowadays installs faster using the WSL extension than on top of virtualbox, which kind of makes me happy, I think Windows is a mess but a brearable one when the alternative is Oracle's big ego (vbox).

A thought I just can't put out of my head lately: living in Silicon Valley is great for killing one's love for technology. Let that sink in.

<hr>

Today's lesson was about golang... it used to be always an annoying task to try to learn go because eventually I just lose it. This time feels different. Like the language is finally there, where it is solid but welcoming too. This is just a start for a learning journey that I might not complete, but this time at least feels better; no more odd references to github repositories, no more odd manipulation of bytes. This brings me kind of to my struggle with life in here and how things roll, making things fast and deliver whatever, not sure why or how is that good to anyone but to the few chasing a contract, a sale, a promo... simply put, in my opinion there is no substitute to good craftmanship; measuring impact on how many persons use my shit vs. how many persons benefit from my work is a weak argument, but weak is what's out there.

<hr>

Words that shut off my brain during a conversation:

* democratize
* slice and dice
* unicorn
* faang

<hr>

Don't fear using stacks... this is something for me to remember, just got to solve an issue that required a map except the map was not useful but for sorting pairs that if used a stack would spare me 3 iterations making my problem linear. Lesson learned?

<hr>

How fast the world is spiraling down, yet here we are, trying to cope with the changes and the ups and downs. Nothing new or exciting to say, I have become more accustmed with doing things fast and choosing more sophisticated ways to write code and address tasks, but well, that is just not luring more projects, just sparing me time. I was recently approached with recruiters asking me to join fintechs, yes, in 2023 there's still people who think that's a breakthrough, what's worse is using as introduction: "founded by ex-google employees", like that granted you the ability walk on the water. The only thing that should tell, is they passed a "hard" interview.

<hr>

Just got rejected from another process. Well I thought I did well except I did not, what did I do wrong? In my opinion: Being honest. Often times people want right answers more than the real ones that have everything in them but right because right is not real, is ideal and ideals only execute well in our minds until experience catches up.
I am glad I got rejected, I am glad I am beyond these worlds where code golf and answering what was written down in a 10 year old book is the golden rule of how not to be an engineer, because engineers solve problems, sometimes efficiently, sometimes poorly but they are problem solvers to the core. Nobody deserves half a mill for moving things to k8s or for knowing how to reverse a binary tree in scala. 

<hr>

Another year is almost gone and must said I learned a lot this time, but I did not which by itself is a good lesson. Introspective tells me I have wasted time, doing some but could have done more, I come to this realization because often times in this environment it just feels like we are experts in nothing and feel like we would give great insight if only we were given the chance, then we are complacient of that chance not coming and waiting for it but there lies the flaw; often times those who might can and know less actually get farther and not because they had more skills, it is just a matter of doing more. So, note to myself, do more, try more, expect more.

<hr>

You will never need to scale like google. Those words hurt the soul of an entrepreneur dreaming of being the next big deal but probably those hurtful words are important to be told early enough. Many projects and positions I've seen lately look for experts in things most of the time nobody needs, but all use because it is within what the industry uses as standard. Just like Toyota will never be Tesla, as bad as the metaphor is, starting simple pays better.
I have seen oftentimes teams of people working exhaustively creating clusters of containers of a service that basically is never deemed to have downtime or that downtime will not crush simply because most of its workload is not in the scale they pretend to have, but they bet high on the traffic that will come... if it does.
I might say this out of myself burning out, but a good architecture does not start with a myriad of services, it starts with a good architecture, where buffers are present in the right places and where business needs are translated into useful components following useful principles. My take on interviews and consulting is often times the same: yes downtime is a concern, especially when it is caused by updates, but an outage on lack of liquidity is worse. So yeah, keep on learning huge ass service architectures, play with k8s, k3s and what not, but overall, build a damn resilient design and a realistic error budget first.

<hr>

In more exciting news, turns out finally managed to get myself a raspberry cluster and boy oh boy, that's like a must for anyone willing to actually do something in this branch, I did not imagine how much I was missing until I added it, then I realize that this stack paired with a fair amount of books is the best didactic material I've ever had.

<hr>

As I learn to use k3s and delve into k8s and all services associated to it I noticed many nuances with how things are done for distributed computing and whatever holding the CNCF seal: they kind of hold, but there is no perfect state where everything just works. It feels like the early days of using linux just with far more problems and far more layers and I know, I am writing this in 2024 when things are way, way better than they were when kubernetes started almost a decade ago. In a not so far world, I deal with another task, where the communication layer of my employer services has suddenly shifted to use gRPC and well, it is somehow a similar scenario. So I am drawing a silly conclusion here: everyone wants to be Google nowadays except maybe Google itself, probably because they know these things are not good as a whole but just the few pieces that can survive the test of time and the dense layer of similarly dense managers. Why things are like this? would it have been better going the Apple way? should we adopt the Microsoft way (whatever that is other than EEE)? what is the other guys way anyway and why do small guys think it is a good idea to copy the Behemoths from the American west coast? I am not frustrated by how complex is to use these things for real, but I find troubling to think this is the way things are going to be moving on because well, they suck, they are flawed and those mindsets of ship first, fix later, make wallstreet happy not your customer almost took down a plane a few days ago. In simple words: I despise that part of silicon valley mindset and maybe we all should.
