# PaFlo-quiz
Quizzes for the PaFlo app

How do I write a quiz?
A quiz must contain at least three questions.

A quiz xml needs to be in this form to be parsed correctly:

<?xml version="1.0" encoding="utf-8"?>
<quiz>
    <filename id="explicit_filename">yourquizname.xml</filename>
    <quizdata tag="quizdata">
        <question tag="question">
            your first question
        </question>
        <RightAnswer tag="rightAnswer">
            right answer to the first question
        </RightAnswer>
        <WrAns1>
            first wrong answer to the first question
        </WrAns1>
        <WrAns2>
            second wrong answer to the first question
        </WrAns2>
        <WrAns3>
            third wrong answer to the first question
        </WrAns3>
    </quizdata>
    <quizdata tag="quizdata">
        <question tag="question">
            your second question
        </question>
        <RightAnswer tag="rightAnswer">
            right answer to the second question
        </RightAnswer>
        <WrAns1>
            first wrong answer to the second question
        </WrAns1>
        <WrAns2>
            second wrong answer to the second question
        </WrAns2>
        <WrAns3>
            third wrong answer to the second question
        </WrAns3>
    </quizdata>
    <quizdata tag="quizdata">
        <question tag="question">
            your third question
        </question>
        <RightAnswer tag="rightAnswer">
            right answer to the third question
        </RightAnswer>
        <WrAns1>
            first wrong answer to the third question
        </WrAns1>
        <WrAns2>
            second wrong answer to the third question
        </WrAns2>
        <WrAns3>
            third wrong answer to the third question
        </WrAns3>
    </quizdata>
</quiz>
