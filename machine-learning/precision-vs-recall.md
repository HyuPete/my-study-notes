# ***we have a set of criminals and innocents need to be classified.***

## if we care about recall.
we will answer '*true*' if we think we see a criminal.

we call these anwsers as positive answers.

we will answer '*false*' if we think not. 

we call these answers as negative answers.

our goal will be figuring out the criminals as many as possible and it's ok if we
consider some innocents as criminals => answer '*true*' rather than omission.

**precision:**
given that set of people, how many of our positive answers are actually true?

**recall:**
given just the criminal subset, how many times do we answer '*true*'?

* with our goal, recall should be high.
* and because it's ok if we answer '*true*' for someone not ever committed a
crime, we may not take too serious about the correctness of our positive
answers.

## so in what case should we care about precision?
it will be a reverse problem.

now we will answer '*true*' if we think we see an innocent.

we will answer '*false*' otherwise.

imagine we are a system checking people boarding a plane.

or we are the guardian of the paradise and will just let good ones pass through.

it's clear now our goal has changed, if we answer '*true*', that person has to
be an actually good one.

and unfortunately, there will be someones who are
really good but by some mistakes, we take them as the bads.

we genuinely sorry
for their bad lucks but cannot do anything else. 

these unlucky ones and the
criminals will not be let in.

again, we have:

**precision:**
given that set of people, how many of our positive answers are actually true?

**recall:**
given just the innocent subset, how many times do we answer '*true*'?

* with our new goal, precision should be high.
* and because it's ok if we answer '*false*' for someone not ever committed a
crime, we may not take too serious if our answer is not correct for some
innocent.
