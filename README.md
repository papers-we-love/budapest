# Papers We Love Budapest

This is the repository for the Budapest chapter of Papers We Love. As a local chapter we follow the Papers We Love [Code of Conduct](https://github.com/papers-we-love/budapest/blob/master/code-of-conduct.md).

## Welcome

What was the last paper you read and loved within the realm of computing? What did it inspire you to build or tinker with? Come share the ideas in an awesome academic/research paper with fellow engineers, programmers, and paper-readers. Lead a session and show off code that you wrote that implements these ideas or just give us the lowdown about the paper. Or, just come, listen, and discuss!

We're curating this repository for papers presented at Papers We Love Budapest. You can contribute by adding PR's for papers, code, and/or links to other repositories, like the main Papers We Love repo, [here][pwl_main].

If you need to reach out to us or have ideas for papers, just ask us via our [Twitter][twitter] account!

If you have a paper you love and want to give a presentation about it, create an [issue][issues] on this repo.

## Past presentations

### :book: Dániel Berecz on "The Essence of Functional Programming" by Philip Wadler (2017-03-02)

#### Abstract

> This paper explores the use monads to structure functional programs. No prior knowledge of monads or category theory is required. 
>
> Monads increase the ease with which programs may be modified. They can mimic the effect of impure features such as exceptions, state, and continuations; and also provide effects not easily achieved with such features. The types of a program reflect which effects occur. 
>
> The first section is an extended example of the use of monads. A simple interpreter is modified to support various extra features: error messages, state, output, and non-deterministic choice. The second section describes the relation between monads and continuation-passing style. The third section sketches how monads are used in a compiler for Haskell that is written in Haskell.

* [Presentation slides](https://github.com/BP-HUG/presentations/blob/master/2017_march/essence_of_fp.pdf)
* [Presentation code][essence_files]
* [Meetup site][essence]

#### Additional resources:

* The original paper: [Philip Wadler - The Essence of Functional Programming][wadler_essence]
* [Channel 9 presentation based on the original paper][c9_essence]
* [A good intro to monads][monad_intro]

### :red_circle::black_circle::deciduous_tree: Károly Lőrentey on "Red-black trees in a functional setting" by Chris Okasaki (2017-07-13)

#### Abstract

> Everybody learns about balanced binary search trees in their introductory computer science classes, but even the stouthearted tremble at the thought of actually implementing such a beast. The details surrounding rebalancing are usually just too messy. To show that this need not be the case, we present an algorithm for insertion into red-black trees (Guibas & Sedgewick, 1978) that any competent programmer should be able to implement in fifteen minutes or less. 

* [Video of the talk][karoly_video]
* [Presentation code][karoly_playground]
* [Meetup site][karoly_redblack]

#### Additional resources:

* [Chris Okasaki, Red-Black Trees in a Functional Setting][okasaki_redblack] (J. Functional Programming 9(4), July 1999, 471–477)
* [Chris Okasaki, Purely Functional Data Structures][okasaki_book] (Cambridge University Press, 1998) (Includes a discussion of red-black trees, too.)
* [Apple Inc, The Swift Programming Language][swift4] (Swift 4 beta edition, 2017)
* [Karoly Lorentey, Optimizing Collections in Swift][opt_col] (objc.io, 2017)
* [Swift Talk episode on Red-Black Trees][objc_video] (subscription required)

GitHub projects:

* https://github.com/lorentey/Attabench — Swift microbenchmarking environment
* https://github.com/objcio/OptimizingCollections — Sample code from my book, including two implementations for red-black trees

## Information

Events are posted to the Papers We Love Budapest [meetup group][meetup].

## Contact

Dániel Berecz | [GitHub][me_github] | [Twitter][me_twitter] | [Email][me_email]

[pwl_main]: https://github.com/papers-we-love/papers-we-love
[twitter]: https://twitter.com/PapersWeLove_BP
[meetup]: http://www.meetup.com/Papers-We-Love-Budapest/
[me_github]: https://github.com/danimad
[me_twitter]: https://twitter.com/DanielBerecz
[me_email]: mailto:dani.madvillain@gmail.com
[issues]: https://github.com/papers-we-love/budapest/issues
[essence]: https://www.meetup.com/Papers-We-Love-Budapest/events/237294183/
[essence_files]: https://github.com/papers-we-love/budapest/tree/master/2017_march
[c9_essence]: https://channel9.msdn.com/Shows/Going+Deep/C9-Lectures-Dr-Ralf-Lmmel-AFP-The-Quick-Essence-of-Functional-Programming
[wadler_essence]: http://homepages.inf.ed.ac.uk/wadler/topics/monads.html
[monad_intro]: http://adit.io/posts/2013-04-17-functors,_applicatives,_and_monads_in_pictures.html

[karoly_video]: https://www.youtube.com/watch?v=fcymPIIPPCE
[karoly_playground]: https://github.com/BP-HUG/presentations/blob/master/2017_july/
[karoly_redblack]: https://www.meetup.com/Papers-We-Love-Budapest/events/240916381/
[okasaki_redblack]: http://www.usma.edu/eecs/SiteAssets/SitePages/Faculty%20Publication%20Documents/Okasaki/jfp99redblack.pdf
[okasaki_book]: https://www.amazon.com/dp/B00AKE1V04
[swift4]: https://swift.org/documentation/TheSwiftProgrammingLanguage(Swift4).epub
[opt_col]: https://www.objc.io/books/optimizing-collections/
[objc_video]: https://talk.objc.io/episodes/S01E58-red-black-trees
