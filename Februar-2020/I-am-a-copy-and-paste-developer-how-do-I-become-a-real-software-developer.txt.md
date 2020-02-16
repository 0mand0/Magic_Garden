# I am a copy and paste developer, how do I become a real software developer?

### Answers

- #1 -

I have been working in a professional environment since July 2017. Here is what I have observed:

My superiors don’t expect me to write every single line of code from scratch all the time. In fact they tell me to go and look at a particular application’s code and do exactly what that module is doing in that specific application. Sometimes I do have to write a lot of code from scratch if it is a brand new functionality that we are building. In fact I have had to design entire modules that perform a specific task. I have always been encouraged to make the modules as portable as possible so that the code can be recycled in other applications if needed.

I go and look at that application and try to understand what that code is doing. Then I replicate the same functionality but I also watch out for scenarios that might need to be modified in my application. Therefore I do quite a lot of copy-pasting (up to 70–80% sometimes). The problem is not copy-pasting. The problem is do you understand what that piece of code is trying to accomplish? Don’t blindly copy-paste.

Real software developers don’t re-invent the wheel every time they are coding.

P.S.
If you copy from anywhere make sure you put the source of the code in the comments. This helps you in future when you are trying to determine where you got this code from as well as it helps you from committing plagiarism.

- #2 -

First, you are a real software developer. You’re being paid money to create software - welcome to the career.

Second, you’re not alone. In fact you’re not in the minority. I’m not even suggesting you’re doing it wrong.

I think what you’re really getting at is that your career will hit a roadblock if you are limited to “development by google” - i.e., you can only resolve problems someone else has solved before (and taken the time to document in a way you can discover). That’s probably true.

I assume your process is something like this:

    Read about the problem in a JIRA ticket
    Find keywords or error messages and google
    Find a question on Stack Overflow that looks similar
    Find the answer that looks right (probably the accepted one)
    Copy the solution from SO to your code base
    Prove the solution works
    Commit

Keep doing that. But let’s add a few steps:

    Read about the problem in a JIRA ticket
    Write down a description of what you think the problem might be before searching for the solution.
    Write a test(s) that reproduces the problem.
    Go back to step 2 - do you think you understand the problem enough to solve without copy/paste? If so, skip to step 9.
    Find keywords or error messages and google
    Find a question on Stack Overflow that looks similar
    Read all of the answers, not just the accepted one.
    Find the answer that looks right (probably the accepted one)
    Type the solution in your code base C̶o̶p̶y̶ ̶t̶h̶e̶ ̶s̶o̶l̶u̶t̶i̶o̶n̶ ̶f̶r̶o̶m̶ ̶S̶O̶ ̶t̶o̶ ̶y̶o̶u̶r̶ ̶c̶o̶d̶e̶ ̶b̶a̶s̶e̶ ̶
    If you are typing anything you don’t understand, take the time to understand it.
    Prove the solution works (run the test you wrote in step 3). If this fails, go back to step 1.
    Request a code review. This is why I said to understand your code in step 10. You need to be prepared to explain it.
    Commit
    Revisit step 2 - how close were you to guessing the cause?

The goal here is to do three things:

    Spend time thinking about the issue before solving it. Software engineering is long periods of thought punctuated by brief moments of typing.
    Create a test to reproduce and validate the problem. Just writing the test is often enough to solve the problem. That makes sense. Writing a failing test means you understand the failure path - which often makes the correct path obvious.
    Hand-typing the answer forces you to think more about the solution. Googling the parts you don’t understand fills in knowledge gaps. This new knowledge, over time, will help you refine your intuition for what is wrong earlier in the process.

Keep doing this and over time. It will make some things take a little longer now but over time you will be a much (much) more productive (and knowledgeable) engineer.


[links](https://www.quora.com/I-am-a-copy-and-paste-developer-how-do-I-become-a-real-software-developer)