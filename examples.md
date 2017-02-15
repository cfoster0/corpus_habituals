# Pattern Progress
## Patterns
These are some of the patterns I have tested out as of Monday, 2.13.

1. (/^N/ = NN | = NNP) @. NN . (VBZ @. /^VP/)
2. (/^N/ = NN | = NNP) @. NN . (VBZ @. /^VP/) !.. /TMP/ !,, /TMP/
3. (/^N/ = NN | = NNP) @. NN . (VBZ @. /^VP/) [.. /TMP/ | ,, /TMP/]
4. (/^N/ = NN | = NNP) @. NN . (VBZ @. /^VP/ @< is @< has)
5. (/^N/ = NN | = NNP) @. NN . (VBZ @. /^VP/ @< is @< has @< knows @< loves @< considers @< wants @< likes) @>> /^SBAR/

Here are the counts for how many examples they return:

1. 2598
2. 2039
3. 559
4. 879
5. 417

Below are a few examples returned.

### Pattern 1
* "their attire is always the same, you know"
* "Turkey has the death penalty, for just about everything"
* "My husband is even interested in it now" 
* "My dad works for them"
* "My daughter-in-law is Panamanian, you know,"
* "My truck is broken down"
* "and besides my daughter wants me to put her to bed."

### Pattern 2
Includes examples from 1 that do not have "is" or "has" as the verb.

* "Well, my dad wants me to go back"
* "I don't know what New York does about theirs"
* "see over thirty-five everything goes downhill flop."
* "My husband feels that they'll come and collect everybody's guns."
* "Right now our house doesn't have to have the same kind of exterior painting there"

### Pattern 3
Includes examples from 1 that do not have a temporal component

* "I don't know who that guy is."
* "And my eleven year old boy loves to listen to it."
* "Our land is in acres,"
* "Houston is really humid."
* "What, I consider gun control is being able to hit my target with the first shot."
* "And the street doesn't go anywhere."

### Pattern 4
Includes examples from 1 that also have a temporal component.

* "money seems to be too big of an issue ... with what's going on today"
* "Um, nothing comes to mind right off,"
* "And then the, uh, they take them to a special part of our dump where composting is now in full swing,"
* "My husband hasn't been to Europe yet"
* "it seems like a, a big thing for Christmas is usually ham."

### Pattern 5
Includes examples from 2 while excluding certain psychological verbs and examples that appear within embedded clauses.

* "local news concentrates, on murders and things like that.?"
* "in one part, the guy goes out of jail,â"
* "and everybody gets one at the beginning of the year,â"
* "The further away I get, the, the, uh, wider the shot gets from the target.?"
* "one doesnâ't go in July.â"
* "One fact, my, uh, my grandmother does that a lot, because sheâ's blindâ"
* "and our daughter watches her pennies so closely, that she almost, she almost, just sounds like your father,?"
* "and, you know, next thing you know, uh, someone calls and wants to sell you this or thatâ"
