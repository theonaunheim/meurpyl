---
title: |
    \[overlay\] ;

    Model Enterprise Usage Rules\
    For The Python Language\

    <span>Revised 2017-09-13</span>\
    <span>Version 0.1.0</span>\
---

<span>Copyright 2017, Theo Naunheim</span>

**License**

Licensed under the Apache License, Version 2.0 (the “License”); you may
not use this file except in compliance with the License. You may obtain
a copy of the License at:

<http://www.apache.org/licenses/LICENSE-2.0>

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an “AS IS” BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

**Trademark**

Anaconda is a registered trademark of Anaconda, Inc. Java is a
registered trademark of the Oracle Corporation. Linux is a registered
trademark of Linus Torvalds. Python and the Python logo are a registered
trademarks of the Python Software Foundation. Use of the Python logo
does not imply endorsement by the Python Software Foundation. Windows,
C\#, and .NET are registered trademarks of the Microsoft Corporation.

**Authors**

<span> Theo Naunheim &lt;<theonaunheim@gmail.com>&gt;</span>

**Abstract**

Python is an interpreted, general purpose programming language that
excels in data analysis, systems administration, and a variety of other
roles. Because of its flexibility and the speed at which it can be used
to complete projects, Python is increasingly being used within the
financial services sector. Python is unlike more traditional enterprise
languages, such as COBOL, Java, and C\#; consequently it has a unique
risk profile that benefits from individualized treatment. The purpose of
this document is to provide a model set of rules for the governance and
use of the Python language in the financial services context.

Preamble
========

Corporations are creatures of habit; they do today what they did
yesterday (because what they did yesterday worked). Convention has its
benefits: it is stable, predictable, and even comforting. It is not
completely without cost, however. Companies that fail to innovate
stagnate and die every day.

Enterprise Python shares these trade offs. Unlike COBOL, it does not
have fifty years of enterprise usage. Unlike C\#, it is not backed up
with an army of software engineers and support staff to integrate the
language within existing intrastructure. In its place, Python provides a
fluid and expressive environment that is unparalelled for rapid
development and data science.

Risk managers and information technology employees often recognize these
strengths, but are hesistant to fully accept Python in their
organizations without fuller understanding of the risks involved. In
order to make Python more palatable at the enterprise level, some
tradeoffs must be made. A measure of autonomy is sacrificed for the sake
of control and oversight. Some flexibility is sacrificed for the sake of
stability and uniformity. Empowerment is sacrificed for the sake of
security and mitigating risk.

These rules use the following guiding principles to inform these
trade-offs:

-   **The correct path should be the path of least
    resistance**–employees are more likely to comply if the rules make
    it easy to do so.

-   **Arbitrary is better than indefinite**–having bright line rules
    reduces confusion even if it does not always yield the
    right outcome.

-   **Make it as safe as it needs to be (but no safer)**–nothing can be
    made completely safe, but things can be made completely useless.

Finally, the Model Enterprise Usage Rules for the Python Language
(“MEURPyL” or “Meurpyl”) provides a model for a set of baseline
standards governing the Python language. Meurpyl is just that: a
baseline. It is not dogma that is intended to be adopted without
question. Rather, it is intended to function as a base by which
organizations can adapt Python for their own purposes–using what works
and ignoring the rest.

Risk Profile
============

Introduction
------------