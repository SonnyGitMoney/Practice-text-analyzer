Describe: wordCounter()

Test: "It should return 1 if a passage has just one word."
Code:
const text = "hello";
wordCounter(text);
Expected Output: 1

Test: "It should return 2 if a passage has two words."
Code:
const text = "hello there";
wordCounter(text);
Expected Output: 2

Test: "It should return 0 for an empty string."
Code: wordCounter("");
Expected Output: 0


Describe: wordFinder()

Test: "Should return true if one of the bad words is found in sentence."
Code:
const testSentence = "Zoinks this shit is crazy dude!"
wordFinder(testSentence)
Expected Output: "true"
