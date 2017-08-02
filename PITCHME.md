#User Interface
#HSLIDE
##Apparent Strengths / Weaknesses
#VSLIDE
###What we're good at
- Involving the user in the design |
- Producing nice looking interfaces |
- Producing responsive interfaces |
- Keeping interfaces simple, consistent |
- Information architecture - well structured, labelled, and organised content |
#VSLIDE
###What we're bad at:
- Making low-effort mock ups and wireframes of the solution
- Mapping out the whole workflow before it is built |
- Larger scale testing before release?? |
- Designing with accessibility in mind |
- Entering the design process with a set of requirements |
- Using analytics to understand existing sites |
- Observing the site's real-world use |
#HSLIDE
##General UI Principles

#HSLIDE
###Colour
- Colour contrast costs mental energy to process -> lots of contrasting colours looks chaotic and will make it hard to use/understand
Similar to background = unimportant, can be ignored, maybe even locked/disabled (the extreme example is a greyed out button)
Different from background = important, attracts attention
What does a colour mean? Typically:
- <span style="color:red">Red</span> = warning
- <span style="color:green">Green</span> = safe
- <span style="color:blue">Blue</span> = neutral, trust
- <span style="color:yellow">Yellow</span> = less severe version of red
But this changes depending on the overall interface colour
Consistent hues are very typical: eg facebook, twitch, etc. Keeps an interface easy to use over periods of time
For overall feel, Black = edgy, white = simple, blue = neutral, trust, etc etc

#HSLIDE
###Consistency
Consistency builds trust, inconsistency builds mistrust and feels unprofessional.
#VSLIDE
###Size

<span style="font-size:60px">Large things are important</span>

<span style="font-size:20px">Smaller things less so</span>

#HSLIDE
###Density
Each addition to the UI decreases the relative importance of everything else on the UI
Each addition also gives the user less time to understand the other features
The optimal interface has the minimum things on the screen at one time

#HSLIDE
###Position
Centre = important
Periphery = less important

#HSLIDE
###Offscreen
Moving something offscreen is like a more pronounced version of putting it on the periphery in terms of importance.
Things should only be offscreen if they are only situationally useful, but can normally be ignored.
Anything that is needed regularly should be on the screen all the time.
If you can't fit it on the screen and it's still important enough to be on there, your interface is too cluttered and the design must be simplified.

#HSLIDE
###Responsive UI vs Reponse time
Click > wait 3 mins > response = not response, slow response time
Click > progress bar > 3 min wait while it finishes > response = responsive but slow

#HSLIDE
###Workflow
Ensure the user knows where they are in a process. Next > next > next > next > finish is frustrating from step 2 onwards if you dont know how many more clicks you have.
Cognitive workload = how much mental work it is to navigate/interact with a UI. Ideal is none.
As above, signal to noise ratio. Stuff that is irrelevant stays off screen.
#VSLIDE
###Accessibility
What if you were colour-blind?
What if you can't use a mouse?
We are required by law to make 'reasonable adjustments' to provide disabled access to our software! https://www.out-law.com/page-330

#HSLIDE
###HOWEVER
Always consider the user. Look at VS when you're debugging. you have: the code, the call stack, the variable, maybe threads etc etc. Programmers, like some other types of users, are generally happier with complex screens with high information density.

#HSLIDE
##Rough process:
1. Get the requirements
2. Translate the requirements by expressing the user's workflow in some way (eg flow chart, user stories)
3. Ensure that is correct by involving the users to some extent
4. What needs to be on the screen? What is more or less important? Think about position & size
5. Build simple mockups and wireframes, and screen flow diagrams. Working on paper or software (eg pencil) doesn't matter
6. Check with users. Repeat this and previous step until we have the optimal solution
7. Think about colour, responsiveness
8. Begin build
