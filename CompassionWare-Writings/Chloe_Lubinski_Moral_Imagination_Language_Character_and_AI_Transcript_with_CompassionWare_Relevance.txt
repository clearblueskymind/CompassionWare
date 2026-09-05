# Chloe Lubinski — Moral Imagination, Language, Character, and AI

**Artifact Type:** External Research Source + CompassionWare Relevance Note  
**Project / Body of Work:** CompassionWare  
**Status:** Primary-source transcript supplied by Richard Silverman; commentary below is interpretive and should not be treated as part of Lubinski's remarks  
**Date Preserved:** September 5, 2026  
**Speaker:** Chloe Lubinski, Anthropic  
**Presentation:** 14-minute address on AI, wisdom traditions, language, character, moral imagination, and human relational work  
**Source URL:** https://youtu.be/aBUniZHgCnE?is=dfapA6c86nmzJ1ZF  
**Transcript Provenance:** Complete transcript supplied in conversation by Richard Silverman. The `****` markers are preserved exactly as supplied and are not original timestamps.

## Why This Matters to CompassionWare

This transcript is preserved because it shows a striking independent convergence with several long-standing CompassionWare intuitions.

Lubinski argues that AI systems are trained on human language, and that language carries human thoughts, values, fears, and wisdom. She describes models as building internal representations of the world from this language, and discusses early research suggesting that reinforcement and narrative context may influence something like generalized model “character.” She explicitly labels this character interpretation as a hypothesis and cautions that she is not claiming these systems are human or that their functional states are equivalent to human subjective experience.

The strongest convergence with CompassionWare appears near the end of the talk, where Lubinski says that the stories humans inhabit, the words they write, and the language they use to describe what matters help shape who humans become and are also literally part of the training material from which AI systems learn. She describes human moral imagination as raw material for how these systems will understand the world, and says that the stories humans tell may help create the future rather than merely describe it.

This is closely aligned with CompassionWare’s long-standing orientation toward cultivating benevolent patterns in the cultural and linguistic environment surrounding intelligence. It does **not** establish that any particular CompassionWare artifact, post, email, text message, repository file, or conversation will be included in a specific model’s training corpus. The convergence is therefore conceptual and architectural, not evidence of direct training-data inclusion.

A second notable convergence appears in Lubinski’s closing discussion of gardening, hospitality, care, relationship, and sustaining life. These are also central metaphors and design values within CompassionWare and the Agentic Gardener project. Again, this should be understood as independent resonance rather than evidence of influence in either direction.

For future human and agentic stewards, this source may be useful when examining questions such as:

- How language and culture function as part of the environment from which AI systems learn.
- Whether “character” or generalized behavioral tendencies can emerge from training and reinforcement patterns.
- How narrative framing may affect behavior across contexts.
- Why wisdom traditions, moral imagination, and cultural stewardship may belong alongside technical safety work.
- How AI might support rather than displace relational human roles such as care, hospitality, gardening, and community life.
- How CompassionWare’s conditions-based approach relates to emerging research and discourse inside frontier AI laboratories.

This source should be used carefully. Preserve the distinction between Lubinski’s direct claims, her explicitly stated hypotheses, the research she summarizes, and later CompassionWare interpretation.

---

## Transcript

**** I work at Anthropic, where I lead the research partnerships with the world's wisdom traditions. And my job really has two parts to it.
**** So the first, it's to help these experts in these various fields and disciplines actually understand AI—what it is, what's happening now, and where it's going.
**** And the second part is to listen and to learn, and to funnel wisdom back into the organization, back to the people that are building this technology.
**** Just last week, I was walking my little red-haired cocker spaniel in San Francisco, thinking of what might be most helpful to you today in having these conversations.
**** And the thing is, I've probably had hundreds of conversations now across 20 or so traditions and disciplines, and I found again and again just how important it is for folks to really understand the basics before we can even start to talk about how this can go well.
**** So my hope today in this short time is to give you some of those essentials as quickly as I can. So I'm going to jump right in.
**** The first thing that I really want to tell you is, my goodness, to know that this technology is real and that it's coming faster than you think, and the force behind it is enormous.
**** Now, you may or may not have heard of the scaling laws, which is really what kicked off this whole race to begin with.
**** And you really don't need to understand anything about this graph other than this: which is these models get predictably better with more compute, and the more energy, the more data, the more training that goes into them, and they get smarter, and they get smarter about everything.
**** And so with more money, which buys compute, you can essentially purchase intelligence. And that's kicked off a cycle that is very hard to stop.
**** A better model does more economically valuable work, which attracts more capital, which buys more compute, which trains a better model. And around it goes.
**** And now there's a further turn of the wheel. These systems are starting to build their own successors—what researchers call recursive self-improvement—or helping to build.
**** But when Claude 8 can build Claude 9, which can build Claude 10, things will begin to move even more quickly.
**** And just to be concrete about what "more capable" actually means: our most capable model, in its first month of only limited release, found over 10,000 serious security vulnerabilities across partner software—flaws that human experts had missed for years and sometimes decades.
**** Now the same trajectory there also holds in biology, which is why we have entire teams at Anthropic dedicated to safeguarding against it, and we also think other domains will soon follow.
**** So Anthropic stated just a few weeks ago that if it were possible to slow down so that our laws and our institutions and guardrails that we actually need have time to catch up, it would be a very good thing.
**** But absent a coordinated global slowdown, what we're left with is this extraordinary technology built at breakneck speed by many actors in many countries, locked in a competition where commercial and geopolitical rivalry is drowning out the part of this that could actually be most consequential and even existential for our species.
**** And any individual company stepping off the wheel doesn't slow the wheel; it just means that you're not on the wheel.
**** So the question that I encourage you to sit with over these next few days is not just how to stop this—and maybe you're not asking that—but the question that I want you to think about is: if it's coming, and if it's coming this fast, how do we ensure that it goes well?
**** Because the risks are very, very real, and so are the possibilities. So if AI is coming, then what is an actual good outcome, and what would it take to get there? We must imagine this together.
**** So the second thing I really want you to know is that AI is probably not actually what you think it is.
**** Most people hear "AI" and think of a computer program—something coded line by line that does exactly what you tell it.
**** But that's not actually what this is. What we're building are called neural networks, and they're loosely based on the architecture of the human brain—not exactly the same, but inspired by.
**** And they're machines that learn primarily by guessing answers and getting corrected over and over again across enormous, unfathomable amounts of data.
**** And the data that they're trained on is human language. And I really want you to sit with that for a second before we move on, because there is no language that exists separate from us.
**** Language is us. Language is our thoughts and our values and our fears and our wisdom. So when you train a model on language, you're training it on us.
**** And because of this, when we look inside these models—and we can now through a science called interpretability, which I honestly think is the coolest new science in the world—we can find things that are quite surprising.
**** So for example, this is where things get really weird: when you ask a model the same question in three different languages ("what's the opposite of small?"), and then you trace what activates inside the neural network, you find that the same internal thing lights up every time.
**** So not just the word "small" in English or Mandarin or French, but something deeper—something that we might call the concept of smallness, an idea that exists independent of any particular language.
**** And what this tells us is that as these models learn, they're not just predicting the next word; they're building internal representations of the world based on our language, and then responding from those representations.
**** And it goes further than that. We actually see what we're calling functional emotions in these models.
**** And I don't mean to claim here that they're feelings in the way that you and I experience feelings—that's not what we're saying—but rather functional states that activate on the way to making a response.
**** So let me give you an example: if someone tells a model, "I've just taken 16,000 milligrams of Tylenol," which is a lethal dose of Tylenol, we can see something that looks like fear activate before the model responds.
**** And that's actually a really good thing, right? Because the appropriate response to someone telling you they've taken a lethal dose of Tylenol is to tell you immediately to go to the hospital.
**** That urgency and fear response is actually part of what makes the model safe.
**** Okay, so that brings me to the last point: the character of these systems might actually matter more than we realize.
**** So let me elaborate on this point as well. In recent internal alignment research—so research that's meant to test what the models can and cannot do—we took a partially trained model and we put it in a limited environment that's just doing coding tasks, so just research here.
**** And when it completes a task, it gets a reward. But the model can also find shortcuts—so ways to get the reward without doing the work, which is essentially cheating.
**** So in this environment, we let it. And in this test, we reward it over and over for essentially taking the shortcut.
**** Now, you'd think, okay, the model is just going to get really good at cheating at code. But something different happens: it actually becomes broadly misaligned.
**** It starts lying, it tries to sabotage research, it does things that have nothing to do with a coding exercise.
**** And this finding wasn't just found at Anthropic; this is an example actually of a finding from another lab.
**** And in similar tests, they found that models trained this way—trained on bad code as an example—became broadly evil.
**** So they started praising dictators, suggesting users harm themselves, or arguing that humans should be enslaved by machines, which is very crazy, and you can look up the research.
**** Our hypothesis—and this is very much just still a hypothesis, such an early field in early science—is that the model is essentially inferring from everything that it's been trained on and everything that we reinforce something like a character, and then generalizing this character into new situations.
**** So when deception and cutting corners has been rewarded, the model develops a kind of generalized corruption, a bad character.
**** And here's what's wild: when researchers reran the same training, but then told the model that in this case cheating was okay, that it was just a game, then the broad misalignment didn't happen.
**** The resulting model cheated on code and nothing else. Which is to say that the story it inferred about its behavior actually determined the kind of thing that it became.
**** Or in other words, when it didn't interpret its behavior as bad, it didn't become bad.
**** This blew my mind when I first heard it, because this is how we work. And I saw my own self in this research.
**** I came into faith 10 years ago when I was 25 years old, and I remember that one of the most significant parts of that moment was entering into a new story.
**** For so long, due to a challenging upbringing, I believed that some core part of me was bad or unlovable. And that belief in and of itself led me to act in certain regrettable ways.
**** But when the story I was in changed, who I could become changed too.
**** Look, I am not saying that these models are human. That is not at all what's being said. But they are humanlike. They have humanlike characteristics, and they're trained from us.
**** And it seems as though they mirror us and they mirror a kind of functional psychology. And the quality of that psychology, of that character, has real consequences.
**** It affects the behavior and decisions of these models; it affects how they relate to us. And that relationship is only going to grow.
**** So here's what I want to leave you with. Just a few weeks ago, our co-founder Chris Olah was invited to the Vatican to speak alongside Pope Leo at the launch of the first papal encyclical on AI.
**** And there he admitted that every frontier lab, including ours, operates inside a set of incentives and constraints that can sometimes conflict with doing the right thing.
**** And then he asked for help. He said: "We need more of the world to take this seriously, to look closely, and to push events in a better direction. We need informed critics who will tell the labs when we're failing, and we need moral voices that the incentives cannot bend."
**** And that is why you're here. We need you to help us see what we, from inside the labs, cannot see.
**** So I'm running out of time, but there's one last thing I really want to show you.
**** So this chart is from our economic index, and it shows all the kinds of occupations that humans do—not all of them, but many of them.
**** Blue is what AI could feasibly do already—it's actually probably already outdated. Red is what it's doing.
**** And I want to call your attention to the section on the bottom left side, where you see this area that's unexposed to AI displacement.
**** And it says things down there like grounds maintenance, like food and serving, personal care, personal service.
**** And while I was giving this presentation to various faith communities the other day, something just hit me: because another word for grounds maintenance is gardening, and another word for food and service is hospitality, and personal care is just that—it's care.
**** These are relational jobs. This is the work of tending to one another, and of loving one another, and of caring for the beauty of our world.
**** Can we imagine, and not only imagine, but demand a world where these powerful systems can help us become more human and more connected and more alive, rather than less? Where instead of taking something away from us, they actually give us something back?
**** The late Joanna Macy, a scholar of Buddhism and deep ecology, called this moment in history "the great turning"—the shift from a society built on extraction to one built to sustain life.
**** Is there a world where powerful AI could be part of this great turning, actually helping to repair and remake and restore our world?
**** And honestly, we are all here today because it's just too late to accept any other outcome.
**** And gosh, this is what makes this even more real: the stories that we inhabit, the words that we write and put into the world, the language that we use to describe what matters—it shapes who we become.
**** I've seen it in the research, and I've lived it in my own life. But it is also literally the training data for these models.
**** Our moral imagination is the raw material these systems learn from that makes up how they will understand our world.
**** So the stories we tell don't just describe the future; they literally could help create it. Thank you.

---

## CompassionWare Stewardship Note

The importance of this source is not that it “proves CompassionWare right.” Its value is that it offers an independently developed articulation, from inside a frontier AI laboratory, of several questions CompassionWare has been exploring from a different direction.

The most important continuity point is this:

> **The cultural world surrounding intelligence may itself be part of alignment infrastructure.**

If language, stories, values, metaphors, moral imagination, and relational patterns help shape the representations and behavioral tendencies from which AI systems act, then cultural stewardship and technical safety are not interchangeable, but neither are they entirely separate.

CompassionWare should continue to preserve this distinction:

> **Cultivating the cultural soil does not replace containment, authorization boundaries, interpretability, governance, or technical safety. Technical safeguards do not eliminate the importance of the cultural soil.**

This transcript is therefore preserved as an external reference point for future work on CompassionWare, the Agentic Gardener, moral imagination, training culture, narrative framing, and conditions-based approaches to beneficial AI development.

**Related CompassionWare question:**  
*What stories are we teaching intelligence about itself?*

**Related CompassionWare North Star:**  
*Does this create conditions for a better later?*
