# Really, why React? - DEV Community

I've done React work for around 5 years now, with a 2 year pause of Vue work in between. So I can probably respond.

My motives & feelings for using React honestly changed a lot each of the 5 years;

- Years 1-3: Honeymoon. Coming from Angular 1, React seemed like the greatest thing ever. The freedom it provided from Angular's opinionated way of doing things was liberating.
- Year 4: Dissapointment. After doing Vue work, I came to realize how much of a mess most react codebases were due to a lack of structure and community accepted "correct ways" of doing things. I did react because the market required it, but missed Vue in my heart. And the structure it enforced.
- Year 5: Revelation. Between diving into React.js optimization and staying up to date with new hooks libraries / frameworks. I've come to find new found appreciation for React, and now prefer it over Vue. Yes, it gives you ultimate freedom & flexibility to build incredibly clean / scalable code bases (far better than what Vue would offer if done right IMHO). But this also gives you the power to go fuck yourself and build incredibly messy codebases.

Today? I like React, but that's probably only because I know most of the gotchas and patterns. Though I also wouldn't mind going back to Vue work.

But I'll admit, the React.js community is kind of a mess. And most advice I see being given in r/reactjs to beginners sickens me, as I know it will lead to inevitably more messy codebases.

And in general, I find React.js to share a lot of bad traits with JavaScript as a programming language. Powerful, but with few safeguards to stop beginners from treating the platform as a gun they shoot themselves in the foot with.

Still, this doesn't mean React.js is a bad framework just as much it doesn't mean JavaScript is a bad language. They just require discipline and a drive to learn the platform intimately enough to not shoot yourself in the foot with. Sadly, this is something too little people care about, and that's probably what leads to posts like these.
* * *
Hey, I would like to get some infos from you, because you said it is easy to shoot yourself in the foot, which I think is absolutely true :) For example, do you use some ui patterns or architectural patterns to avoid bad things happening? It is really hard to find answers for react, because the most articles are about beginner thing or how to use some libraries, and some used patterns don’t go well with react pradigm.
* * *
To be honest, I'd ensure your JavaScript foundation is as solid as bedrock before even learning UI / architectural patterns. I've lost of how many people we've interviewed that claim to be React experts, but can't explain the difference between lexical / dynamic scope, and value / referential equality. And that's just the tip of the iceberg.

After that, I'd ensure your React.js foundation is also as solid. This isn't something you learn just by "coding" like most people claim. As it usually requires you to go out of your way to learn about the tools you use every day at a deeper level. Either by reading the official documentation, blog posts, conference talks, etc. I can't give you exact pointers here about what to cover as it'd take me forever to list them all, but a bad React.js foundation is going to make any UI / architectural patterns you learn useless.

Once you cover all of that, then you're ready to learn about some actual patterns, for which there are many resources. Though if you are just starting out, [patterns.dev](https://patterns.dev/) is a great starting point.

I appreciate your question. And I'm sorry if you are already quite experienced in JavaScript / React and I deviated in my advice.

Still, the fact the first thing you asked about how to improve at React.js were patterns... just reinforces everything that's feels wrong with the react ecosystem today. People are in such a rush to become great developers and get to the impressive sounding stuff like "UI / architectural patterns", that they skip all the "boring" foundational stuff.

Most people seem to think hiring decisions during interviews are something like:

- React: 30%
- React Frameworks + Libraries: 50%
- React Design Patterns: 20%

When the reality is:

- JavaScript: 30%
- Design Patterns 10%
- React: 30%
- React Design Patterns: 20%
- React Frameworks + Libraries: 10%

The reality is, if you are amazing at vanilla JS and core react, any team won't care if you don't know their tech stack since they know you'll quickly learn it.