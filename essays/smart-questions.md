---
layout: essay
type: essay
title: "Asking Good Questions"
# All dates must be YYYY-MM-DD format!
date: 2023-09-07
published: true
labels:
  - Questions
  - Answers
  - StackOverflow
---

<img width="300px" class="rounded float-start pe-4" src="../img/smart-questions/rtfm.png">

## Smart vs dumb questions

Asking questions is undoubtedly a large part of being a software engineer. In the field of tech, there is so much information and so many different tools out there that no one person can remember or learn it all. Asking a smart question is a great way to get that knowledge into your brain. But thats the key. Asking **smart** questions. One common  difference in whether a question is dumb or smart comes from the question of where it is coming from. Is it coming from a place of ignorance? Or is it coming from a place of laziness? If one is asking a question because they feel like just using someone else is an easier way of finding an answer than trying to find it themselves, then that is lazy. If they have been struggling with a problem and can't find a satisfactory conclusion or would perhaps like additional input and perspective, then it is a smart question.

## What’s a smart question?
A smart question is one that is well formulated and shows a level of effort from the asker to do a little digging beforehand.

[Here](https://stackoverflow.com/questions/11227809/why-is-processing-a-sorted-array-faster-than-processing-an-unsorted-array/11227902#11227902) is a question on stack overflow that was asked over 11 years ago and is one of the most upvoted questions on the platform. It asks a question that is quite straightforward, but whose answer can be quite extensive. He asks the question, why is processing a sorted array faster than processing an unsorted array? Now one's first thought might be, *does it?*

Well, the author has made his hypothesis and tested it in two different programs in two different languages, one purely compiled (C++) and one kinda interpreted (Java).

Now, he is asking the world why this is the case. It is not immediately obvious. There aren't any real explanations in the documentation of the languages or anywhere else on the internet, so this is a great question to ask. An expert in data structures and algorithms might be able to give good insight, or a more senior programmer could point out errors in his code. He explains himself and his findings, and then gives his thoughts, and finally he gives detail to what it is he is inquiring or confused about.

```
My first thought was that sorting brings the data into the cache, but that's silly because the array was just generated.

What is going on?
Why is processing a sorted array faster than processing an unsorted array?
The code is summing up some independent terms, so the order should not matter.
```

## What's a dumb question?
A dumb question could be many things. It could be that there is not enough detail given, or that the question is vague, or that the question shows no real thought put into finding the answer from the asker.

[Here](https://stackoverflow.com/questions/19531133/how-to-add-two-numbers-in-java-programming) is a question in stack overflow titled, "how to add two numbers in java programming."

The first thought one might have is, well, you use the + symbol? This is extremely rudimentary information about coding in general and could be learned in 5 seconds by a simple google search.

But then he gives this code

```
import java.util.*;
public class Test {

    /**
     * @param args
     */
    public static void main(String[] args) {
        // TODO Auto-generated method stub

        int x, y, sum;

        Scanner input = new input(system.in);

        input = parseInt32();


    }

}
```

This code doesn't even compile. The asker says nothing else in the post, doesn't make it clear what he really wants and shows no real understanding of what he is asking. On inspection, it seems as though this was probably a homework prompt, and he just copied and pasted it with his non functioning code.
It can also be inferred that what he is really asking for is to take two numbers from a user console input and then add them together. He could have specified this, but didn't, and in doing so made no real effort to communicate what he was confused about. 
Even if this was what he was after, he could have easily google searched this question and gotten many answers, but never made any attempt to do so.
Questions like this show a poor ability to communicate a cohesive question, and in this instance, it can make the asker seem lazy.

Overall, no one should be afraid to ask a question, but if you are going to ask one, take a second to think about it for yourself first. Even asking some dumb questions here and there is better than never asking any at all.
