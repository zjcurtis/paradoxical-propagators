# paradoxical-propagators
A test bed for multi-valued logic, propagators, and programming lamnguage development.

## Parts
My thought is that incompleteness is largely fine, especially if we accept some degree of paraconsistency in our logic. One way to do this is by saying "In first order logic..." or "according to quantum mechanics..."

I probably believe in some degree of dialethism, and it's *helpful* to allow paraconsistency because practical things are often modeled that way. For circuitry we can look to Maxwell's Equations and Kirchhoff's circuit laws. Under some assumptions Kirchhoff's laws *are true* for some value of true. And they're nicer to work with. Paraconsistency allows us to not spend a million years debating what truth is and move on to the good stuff...

So how do I propose to do that?

First step is by allowing for the creation and validation of 'proofs' in a formal system. It would be nice to be fairly confident that if we think we're writing a proof in X system it is accurate. Note I am using 'formal system' loosely here, if it has axioms and notions of equivalence it should work. I draw inspiration here from Metamath and specifically Metamath Zero.

Second 'step' is a system of propagators. Each actor/propagator is a valid relation in some formal system. X * 1 = X is a propagator. 

Once you have formal systems and propagators, I think all programming can be reduced to a constraint satisfaction problem of some sort. The tricky part being *how does one write a constraint solver that is general and efficient for some degree of generality and efficiency*? I honestly don't know.

If this explanation leaves you frustrated with vagueness, welcome to the club. 

## Misc

It'll have a REPL. Dead programs are probably fine for some stuff, perhaps even preferable. I don't think they are in the general case. Logtalk is probably the closest extant language to what I am proposing/will try to develop here.
