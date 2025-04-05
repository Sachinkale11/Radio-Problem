## Radio Problem

In an effort to improve public safety, the Telecom Regulatory Authority of India decides to open up new wireless radio frequencies to be used by the government of each Indian state for emergency communication purposes. Ideally each state would receive its own unique frequency to avoid potential interference, but there are two problems with this. First, there isn't enough free bandwidth for the new frequencies; in fact, there's only room for 4. Second, some states (fortunately, relatively few) have legacy communication equipment that only works on one particular frequency, and unfortunately some of these frequencies are the same across states. Fortunately, as an enterprising young consultant, you realize that since radio waves have limited range, it's sufficient to ensure that nearby states do not share the same frequencies.

Write a Python program that assigns a frequency A, B, C, and D to each state, subject to the constraints that (1) no two adjacent states share the same frequency, and (2) the states that have legacy equipment that supports only one frequency are assigned to that frequency.

Program runs like : python3 main.py

where legacy constraints file is an input to your program and has the legacy constraints listed in a format like this: Meghalaya A J&K B Odisha A

Your output will be in file results.txt
