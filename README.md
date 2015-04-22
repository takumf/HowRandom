# How Random is your Random?

This is a little testing app, mostly done to learn a bit Java and have a simple program to run a test.

## What exacly is being tested?

How random is the integer generation on Java Virtual Machine. The reasoning behind it 

## What is the purpose?

If you play RPGs, you have been likely witness or part of the discussion and various preconceptions regarding the fairness of someones dice. Same thing happens when you will show electronical devices and many people will inevitably start using terms that they don't really understand. Entropy sources not being ideal, things being pseudo-random interpreted as 'limited, biased and obeying some bad seed' etc.

To shut some of these people, I want to make a modifiable program that will be runable even from smartphones and show you some numbers and interpretation.

## Is it really nescessary?

Clearly, you never felt frustration that comes with being a mathematician and some convent-dwelling scum calling you a moron and then 'a nerd who wants to confuse people' after you get pissed off and throw undergrad statistics terms.

I'm not really angry at them, but for the uneducated opinion that comes with having smartphone with wikipedia access.

### But random and psedo-random is not the same!

Of course it is not the same! However, they can be random *enough* for most of the applications. If they are enough for scientific simulations, I think that they are good enough to be used for a fucking hobby.

If you want, make same tests on your pair of science-dice, note them on paper and follow the analytical process I will describe below. Unless your PRNG is un-fair, the resluts should be very similar.

## You talk stats, let's see some of that!

OK! Here is the ideal fair d100: It will have exactly 1% probability of landing on any number from 1 to 100 included.

The mean value should be 50.5.

The expected value should be $$ E = (100^2 + 1)/12 $$


