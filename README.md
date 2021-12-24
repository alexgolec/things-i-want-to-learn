# Things I Want to Learn in the Future
There's a lot of stuff I don't know about, and I figured it's high time I
started recording the things I keep coming back to. I'm publishing this partly 
as TODO list, but also partly to put my interest out there so that I know that 
people know what I want to know, so if I don't make progress I'll know that 
people know I'm being lazy. You know? 


## Approximate Solutions to NP-Hard Problems
The standard way of teaching NP hard problems in undergraduate courses is to say
"here be dragons" and move on. In reality, however, there are surprisingly many 
situations which require solving an NP-complete or NP-hard problem. One famous 
example is the [travelling salesman problem](https://en.wikipedia.org/wiki/Travelling_salesman_problem),
which can be applied to optimal routing for delivery drivers and other 
logistical challenges. The current state of the art requires us to basically 
brute force every possible combination to find an optimal solution. Fortunately, 
there are algorithms that will produce approximate solutions, and I know very 
little about them. 

I figure I'd like to start with [simulated 
annealing](https://en.wikipedia.org/wiki/Simulated_annealing) and move on from 
there. I'd like to know: are there classes and families of these approximation 
algorithms? Is there a theory for how they behave? Do we have any guarantees 
about how closely they converge? Do they actually converge? 


## Re-Visiting Steward's Calculus
My first bachelor's degree was in mathematics, and in the process of getting 
myself ready for that course of study I took calculus. Problem is, I took it 
very quickly and never really looked back. Mathematics is a curious thing: at 
first you're studying a number of seemingly unrelated things, then gradually you 
start to spot similarities, and then all of a sudden it all clicks and you can 
kinda start to see the forest for the trees. 

I had this experience *well* after I took calculus. I can sort of see some 
fascinating things poking through: real analysis, complex analysis, differential 
equations, but it's been so long that I feel I need to carefully revisit it to 
appreciate it once more. Also, I've been in the computer science world for so 
long that what little skill I had with pushing a pencil was likely atrophied. I 
feel like coming back to calculus with a fresh set of eyes might help me regain 
my appreciation for it. 


## UI/UX Design and Frontend Programming
I've been a systems, distributed, backend, and quantitative engineer for my 
entire career. It's what I first fell in love with and the romance hasn't faded. 
However, I have *tremendous* admiration (bordering on jealousy) for my friends 
and colleagues who do frontend and app development. It's a completely different 
world with a completely different way of thinking, working, problem solving, 
etc. Not to mention, what good is a beautiful algorithm or backend system if no 
one except pedantic terminal jockeys like me can use it? 

I don't quite know where to start, but something tells me I want to come at this 
from a design and UI/UX perspective. There's a visual language to apps and 
frontends, and while I know how to read it I don't know how to speak it. If you 
have any suggestions, please feel free to reach out. 


## N-Body Simulation
When I was at Google I set my screensaver to [xscreensaver galaxy 
collision](https://www.youtube.com/watch?v=xBprAm9w-Fo). It was very charming, 
and I loved watching the galaxies smash into one another. Problem is, it was 
very... 1997. With modern CPUs and GPUs, we could conceivably simulate enormous 
numbers of particles with very impressive visual effects. My secret ambition was 
to create a modern version of this classic screensaver. 

This led me down the [N-body 
simulation](https://en.wikipedia.org/wiki/N-body_simulation) rabbithole. I 
imagine there are tremendous opportunities for parallelization with CPUs, and 
possibly even with GPUs, although obviously the gains result in sublinear gains 
in the particle numbers. I'd also love to use this as an opportunity to explore 
graphics programming, which is another programming paradigm with which I'm quite 
unfamiliar. 


## Modern NLP Methods
Upon completing my undergrad, I had the choice of going into industry or doing 
more studies (or even a PhD). When I was offered a job at Google, I kinda 
couldn't say no, but I still missed the joy of studying. Columbia offers 
guaranteed graduate enrollment for undergrads, so I signed up as a part time 
student and took [Michael Collin's](http://www.cs.columbia.edu/~mcollins/) 
excellent NLP course. 

At the time, most of the methods were pretty classical: Markov models, 
probabilistic context free grammars, log-linear models, etc. Since then, 
enormous progress has been made in the field, and I've frankly been a little 
left behind. Looking at the syllabus for the
[most recent run of the course I could find](http://www.cs.columbia.edu/~mcollins/cs4705-spring2020/),
it looks like they now cover recurrent networks, embeddings, LSTMs, and the 
like. I'd love to devote a semester of focused study to this stuff. 
