# Title of your post
> **Date:** 05.01.2021 - 18:35 PM *(Due: 11.01.2020 - 03:00 PM)*
> **Name:** `mane` Marisa N.
> **Session:** [07 Exercise - Explanations](https://github.com/FUB-HCC/hcds-winter-2020/wiki/07_exercise)   
----

## A5 - Explanations

### Task 1: Different Explanation Needs

#### ORES Scenario

Scenario: editing Wikipedia

When a Wikipedia user does an edit to Wikipedia, other Wikipedia users or aplications may use a machine learning system (ORES) to determine of what quality this edit is. Based on the given score the user or aplications might change or even revert the edit. This ecosystem contains an Wikipedia user who did an edit and a machine learning system for assessing the edit quality.

1. Creators: 
* Wikimedia Scoring Platform Team
* Aaron Halfaker and Dario Taraborelli
* Probably other not transparently listed volunteers and collaborators

**Explanation needs**

The creators need explanations about the systems performance to *improve their understanding of the system such that they can better optimize it for their preferred metrics* (e.g. how good the predicted scores align with the reality).

2. Operators:
* The ORES API itself, which provide ORES scores to other Wikipedia users or applications
* Applications (e.g. tools, features, gadgets, bots and services) that directly access the ORES API and provide the scores to other Wikipedia users or use the ORES scores by themself
* Wikimedia users that directly access the ORES API and use the ORES scores by themself

**Explanation needs**

The operator needs explanations about how the system works. That means how to input data and query the system such that the operator can fullfill the needs of the excutor. The operator also need explantions about how and why a decision was made to be able to pass that infromation to the executor.

3. Executor:
* Applications, which use the ORES scores by themself (e.g. bots, which decide based on an ORES score whether to revert an edit or not)
* Wikimedia users, which are either also operators or get the scores from applications (e.g. so called patrollers, who decide based on an ORES score provided by a gadget whether to revert an edit or not)

**Explanation needs**

The executor needs explanations about the system’s outputs, that means how and why decisions were made (e.g. why an revision is calssified as damaging). 

4. Decision-subject: 
* Wikimedia users, who did edits

**Explanation needs**
The decision-subject needs explanations about why an executor made a particular decision (e.g. why a revison was reverted).

5. Data-subjects: 
* Other Wikimedia users, who did edits
* Other Wikimedia users, who classified these edits manually

**Explanation needs**

The data-subjects may what to have explanations about how their data is being used to make decisions, so they *may want to understand how their data affects a machine learning system’s outputs* (e.g. if other users edits are more or less classified as damaging).

6. Examiners:
* There are no dedicated examiners, but it is possible for other Wikipedia users to report problems (e.g. via Phabricator, JADE, Wiki pages, or directly contact Wikimedia Scoring Platform Team).

**Explanation needs**

The examiners need both explanations about the system's performance and about how to interact with the system, that means how to input data and query the system to be able to test the system's work (e.g. testing which revisons are classified as damaging, etc.).


#### Reflection

_your TEXT here_

_your IMAGE here_

### Task 2: Explanation method: LIME

_LINK to your annotated notebook here_

_1: ID and IMAGE of your LIME explanations_
_2: ID and IMAGE of your LIME explanations_
_3: ID and IMAGE of your LIME explanations_

#### Reflection
_your TEXT here_