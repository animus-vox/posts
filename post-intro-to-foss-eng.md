# Intro to Open source
##### Or - what i wish i knew sooner

### preface
Open source is a huge subject, and a bit like religion - each person has a different view about it.
On paper, the term doesn't mean much more than having public (open) access to the source files of a project or software.
Yet, behind the same term, there are so many layers of ideologies and points of interest, of people - and organizations who drive many open source projects.

In this series of posts, I will attempt to condense the world of open-source down to a quick-start guide, to make it accessible,  
and provide people who want to contribute, but need someone to "hold their hand", at least at the beginning.

First, a caveat. Here in most cases when referring to open source code, we're actually talking about FOSS - "Free and Open Source Software".  
which has slightly different criteria from the broader definition of open source code.

Here, I'll try to answer the questions: Why open source? for who, open source? and how, open source?  
Oh, and this article is ALSO 'open source', managed on [GitHub](https://github.com/animus-vox/posts/blob/main/post-intro-to-foss-eng.md).
Feel free to find where it would be better to add a line, where an example is missing, and whatnot - and improve the content for everyone.

### Why Open Source Code?
The history of open source is long and full of beautiful stories, therefore, it's too much for this intro.
In this world of open source, participate corporations, individuals, and non-profit organizations.  
Today, as i see it, the four main incentives for the individual participant are:

- Contribution - many open code projects serve as the [basis for technologies](https://xkcd.com/2347/) used by millions of people around the world.
  Assisting such a project means assisting the same users and services supported by it.  
  In the end, even seemingly small software maintained by a single developer makes waves when many tools rely on it (for example, XZ Utils, which recently [made headlines](https://boehs.org/node/everything-i-know-about-the-xz-backdoor) when it was infiltrated).  
  Not convinced? Open source contributions can be found in kernels, games, education, documentation, or just an application that helps us keep coupons organized (don't let them expire!)  
  Contributing to open source code may not usually bring much fanfare, but the feeling of bliss is very real.

- Experience - You learn how to integrate into existing projects by integrating into existing projects.
  When joining an existing project, whether with a new team at work or an open source community - you learn by doing it.
  Usually there will not be a team member available to help you at any given moment.  
  You are expected to act as a 'commando', to contribute individually towards the objective, but give and get help as required.  
  Every improvement you submit will be reviewed by at least one other person, if not several.  
  There will often be someone who knows better.  
  And that's exactly the point.  
  > "It's important to learn from mistakes, it's better to learn from other's mistakes."
  
  It's best to be willing to take criticism, because there will always be someone who knows better.  
  That's your learning opportunity.
  
- Community - Working with open source code, in most cases, means working within a community.
  To join an existing project, you'll need to familiarize yourself with the existing work, so naturally,
  It helps to talk to the people who wrote it.
  It helps to have someone who coordinates tasks among team members.
  It helps to have people who review, optimize, report bugs, and countless other actions to improve the project.
  This, creates a perfect path to getting to know people who will be mentors, connections, and even just friends.

- Because it's needed - Sometimes, large corporations spend resources on improving open-source projects.
  Surprisingly, this is no surprise. as mentioned earlier, these public projects are EVERYWHERE, their licenses often allow modification of the code, but require the modifiers to include the same license,
  and of course, share it.
  This example represents the importance of the open-source community, which allows knowledge and tools to be shared, and enjoyed by everyone.  
  It's often the base of many services which are nowadays as obvious as breathing air.  
  It needs mainteinance, It needs to be improved, and it needs people to do it.
  
Surely, after this journey of persuasion, I'm sure the open-source high-life sounds shiny, wonderful, and full of praise.  
Alas, this is usually not the case. For the sake of fairness, it's necessary to face reality.  
Investing hours upon hours into something that is, essentially, a side project, is **hard**.  
You'll need to find what drives you, whether it's a passion for creation or a clear goal of some sort, otherwise it will be hard to persist.  
  > "A body that doesn't want to be in motion, will return to rest"  
  > *-Newton's lazy brother*
  
  And now, with this newfound knowledge, I hope I've inspired you to participate and become a contributing member of an open source project.
  You can go to the previously linked github page, see this article in 'markdown' format, and suggest improvements.

### For who, open-source?
EVERYONE!
Often, open-source is seen as a code-only, software developer haven.  
This could not be further from the truth - Games will need some one to create 3D models, some one to write a story, a voice actor!
Applications may need translators, libraries may need someone to write a complex algorithm, and 
practically every one could use a tester. There's a lot of work to be done, and there's room for everyone.

Did we mention ideology? Take a seat, we're having the talk.
With some variance, often FOSS projects are FOSS because the people behind those projects believe that most programs and technologies need to be available for everyone.  
To allow individuals to invent, explore what else can be done, or just improve their quality of life.  
If a program's FOSS, that means it's source is available, and anyone can use it, modify it and distribute it.
This idea was, and still is, strong enough to create communities, advocates, and some of the most essential technologies used in software today.

If you like this idea, GREAT! if not, that's fine too.
Making contributions out of a more selfish need, such as learning how to work on new projects, gain experience, or just acquiring a new story for the guys, is alright, and you wouldn't be the first one to do it.
Infact, some of the kind contributors are not self-less individuals, but large corporations which rely on the very same technologies. 
In fact, the XZ Utils hack which we've talked about earlier? It was found by a Microsoft employee.
No matter the reason, be it pure capitalism or just wanting to contribute, everyone's welcome to help.

### How, open-source?
Adventurer, you'd like to make a contribution, but you're unsure where to begin?
Just like any good adventure, this process slightly varies from person to person.

For starters, either you have an idea for to share with the world in the form of an open-source project, or you'd like to join an existing project, and help others fulfill their objective.  
The first case is fairly simple:  
- Pick a free, open-source license, which we like.
  License agreements essentially define what others may do with your project, what are their obligations. You may consult [choosealicense](https://choosealicense.com/).
- Publish the project in an appropriate place, and select a method for recieving and managing issues. Github is a common place, allowing version-control, listing issues, and people could easily see contacting details.
  An old alternative would be to simply use mailing lists.
- Note, it's important to attach the selected license to the project, often in a file, aptly named "license".
- Now you may procceed as usual, and maybe someone would join your endeavour.

The Alternative:
Roll up your sleeves and reach into the depths of someone else's project.
- *search* - Find a project which interests you, or which you happen to rely on and need it improved.
  "But where do i begin?", you ask.
  Well, i'd suggest you begin with a [good first issue](https://goodfirstissue.dev/), something fitting for a [first timer](https://www.firsttimersonly.com/) or even on [github](https://github.com/topics/good-first-issue).
  Often, a much softer landing can be provided by a local community, so if there's a localized forum of some sort, it's good to join the ocnversation too.
- *RTFM* - Is there a readme file? A wiki? any documentation or a contribution guide? Read it!
  Often, a welcoming project would invest in documentation for future contributors, rely on it when possible.
- *Repeat the previous step* - It's important. When the day comes you need a question answered from the maintainers of the porject, respect their time by doing your best, ask informed questions and you'll be getting effective answers.
- *Contact the community* -If you know which issue you'd like to try to solve, it's a good idea to inform the maintainers of the project, so that there won't be multiple people working on the same issue. If you're unsure of which problem you should begin with, it's a good first question for the maintainers.
- *Submit a patch* - So far, you've learned how to build the project, and some of the social norms. You've gained some experience by solving a problem.  
Now it's time for another lesson: A review.
Once you're finished with creating a patch, you'll submit it for review.
after which you may be asked to make additional changes to your contribution - perhaps you've missed something, or simply didn't know better, and it's the reviewers job to find it, and inform you.
Some back-and-forth of committing changes and getting re-reviewed, until, finally...

Your contribution is *accepted*.  
At this point, you deserve to be congratulated, you're now officially a contributor!  
Take a moment for yourself, process this achievement.

Now, you're free to choose a new issue, or even a new project.  
Hopefully, you'll find that with every issue solved, both you and the project improve.
