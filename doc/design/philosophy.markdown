Diadem: Philosophy
==================
_In the beginning, [Matz created Ruby][2]._ He created the firmament, and the sky was bright and clear and the animals had infinite global namespace in which to play. Matz saw that it was good. And it was.

But the animals proliferated, as is their wont. And they wished to frolic and play with other animals. In the Cambrian era, every animal had its own structure. Thence came Minero Aoki's [setup.rb][1], and order emerged from the chaos. Vertebrates ruled the firmament, with `/lib` and `/bin` and many other directories, and consistent module and file relationships joined the spiritual to the material, and we all saw that it was good.

But animals spawned other animals. And they formed symbiotic relationships. Chaos crept into the firmament once again. A richer animal husbandry system was needed, and some [very smart people][3] said **"Let there be RubyGems!"**  And again, there was order.  And we all saw that it was good.

But animals continued to evolve, and the symbiotic relationships became more intricate. RubyGems preferred to keep all the animals in one very large park, underneath the bright sky and infinite namespace.  With such diversity in one place, conflict was inevitable. Some animals disagreed on other animals' versions. And it was hard to move the animals from sphere to sphere without confusion. And some developers didn't like where the park was kept, in the global realm where only superusers could tread.  

Solutions emerged to these problems. [One smart person][5] said, **"Let there be RVM!"** to make little mini-parks where subsets of animals could frolic in isolation on completely different firmaments.  Some [other smart people][4] said, **"Let there be Bundler!"** to handle versioning and move. Some [loved][8] Bundler and [others][6] [hated][7]. [Other answers][9] were brought unto the firmament. And [arks][10] of [sizes][11] were built to move animals from place to place.

But just as this metaphor is getting more stretched and convoluted....so is the Ruby ecosystem. We now have tools to abstract other tools to abstract shared code.  In the summer of 2010, following community buzz, it feels like there's more energy going into projects to manage Ruby installations and gems than there is in writing Ruby code that does neat stuff.  We're falling into navel gazing. Soon even the Java people will laugh at us.

A new approach is needed.  Yes, this is one more metaproject; but it's not trying to make Rubygems better, or build new houses of cards for your load path, or make a brand new scripting language for Byzantine deployments.  It has to _work_ with existing systems, but it doesn't follow their assumptions. Diadem's goal is to _cut past all the layering and cruft,_ and deliver one simple, robust, transparently portable system for managing Ruby applications once and for all.

How does it do this?  [Two words:][12]

***Hermetically sealed bubbles.***



[1]: http://i.loveruby.net/en/projects/setup/
[2]: http://groups.google.com/group/fj.sources/tree/browse_frm/thread/6c273626299c980a/b3ec86bc9d82da38?rnum=1&_done=%2Fgroup%2Ffj.sources%2Fbrowse_frm%2Fthread%2F6c273626299c980a%2Fb3ec86bc9d82da38%3Ftvc%3D1%26#doc_b3ec86bc9d82da38
[3]: http://rubyforge.org/project/memberlist.php?group_id=126
[4]: http://github.com/carlhuda/bundler/
[5]: http://rvm.beginrescueend.com/
[6]: http://bjclark.me/2010/03/bundler-oh-the-fail-i-know/
[7]: http://amplicate.com/hate/bundler
[8]: http://amplicate.com/love/bundler
[9]: http://github.com/jbarnette/isolate
[10]: http://www.capify.org
[11]: http://rubyhitsquad.com/Vlad_the_Deployer.html
[12]: http://tvtropes.org/pmwiki/pmwiki.php/Main/TwoWordsObviousTrope

