# Mantine 5.0 is out – 140+ hooks and components with dark theme support

It's absolutely fantastic, but I think it's still rather foolish to assume it's the "best" one. Personally, I find it a winner for greenfield projects that don't need as much control / customization.

But for larger projects that require much finer control and deep customization, I think I'd still favor Chakra UI at least slightly. Even if it has less components, because of how much they favor Composition, they tend to be dramatically easier to modify. I mean, just compare both of their Modal Implementations:

- [https://chakra-ui.com/docs/components/modal/usage](https://chakra-ui.com/docs/components/modal/usage)
- [https://mantine.dev/core/modal/](https://mantine.dev/core/modal/)

Because Chakra components tend to be made of "small atoms", it's easier to both customize or plug in your own components. You may be fooled into thinking one giant "easier to use" component is better until it's time to customize it with Mantine's [Style API](https://mantine.dev/styles/styles-api/) that requires painful memorization of random property names (similar to Material UI).

And even if Mantine does "more" out of the box, it doesn't mean a large project will likely use it out of performance/scalability concerns. Good luck convincing a Fortune 500 company to use Mantine's limited form implementation over something like React Hook Form.

I'm eager to try out Mantine for a smaller project as soon as possible, specially with how good the free plan is and how much it does out of the box.

But ultimately, I don't find either framework to be "the best" out there. Specially considering the massive differences between projects. Right tool for the right job.
* * *
If Chakra UI can be used in production, I don't see any reason why Mantine can't be used in production. Mantine is basically a UI library with way more helpful features than Chakra UI.

Chakra UI has less pre built components and it requires some sort of subscription to get those premium components iirc. For very large client, you still need to build those stuff yourself and in my opinion it will take more time than styling Mantine. Mantine also allows you to build custom components using the style API too. Not to mention Mantine has support for notification system, rich text editor, modal manager, ... And it's definitely not hard to style Mantine components to have a customized look.
* * *
- If Chakra UI can be used in production, I don't see any reason why Mantine can't be used in production.

One word: customization. If you've given a serious look at how components in both are made, you'll have realized how much more composable and easier Chakra UI components are to customize VS mantine ones.

The quickest example I can give you is look at Chakra's Modal implementation vs Mantine's.

- [https://chakra-ui.com/docs/components/modal/usage](https://chakra-ui.com/docs/components/modal/usage)
- [https://mantine.dev/core/modal/](https://mantine.dev/core/modal/)

You might be fooled into thinking just using one component is easier, until you realize you need to customize it and suddenly need to become an expert in Mantine's Style API naming conventions.

- Mantine is basically a UI library with way more helpful features than Chakra UI.

More !== Better. Prebuilt components are great, but large clients require you to balance features & flexibility of customization. The more a component or UI library does, the more flexibility you usually lose. A great example is Mantine's Form implementation. Which while great for beginners or to get a project off the ground quickly, will rapidly crumble in the face of a more scalable solution like React Hook Form.

[https://react-hook-form.com/](https://react-hook-form.com/)

- Chakra UI has less pre built components and it requires some sort of subscription to get those premium components iirc.

It's not a subscription, it's a one time payment to keep the free version's maintenance alive (which I still have no idea how Mantine will achieve). Also, the flat fee of even $999 USD is chump change to most large clients.

The biggest take away I get from this thread and your response, is Mantine is rightfully loved by both rookie and freelancer developers for providing such a complete package that is great looking for free out of the box. In that sense, yeah, I agree it's dramatically superior to Chakra.

Having said that, I'm not surprised people are so quick to bash on Chakra given how it's mostly young/inexperienced/easily impressionable developers that browse [r/reactjs](https://www.reddit.com/r/reactjs/). And as such, scalability and deep customization is usually at the bottom of most people's priorities.