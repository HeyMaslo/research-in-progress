# Research in Progress

Progress on the research side during the week of 2/3/2020 - 2/7/2020.

## Items 

1. Lab Study Design
2. GitHub Repository 
3. Knob 
4. Text Summarization Algorithm

## Lab Study Design 

#### Objective

Given the interesting relationship between exposure and agency perception found in the survey, we opted to assess how exposure influences mind perception in humans and robots in a lab setting. We will manipulate different levels of exposure 
(blurb, short exposure, long exposure) and explore if longer exposure leads to higher ratings on agency and experience perception. 

#### Progress

We are currently completing the manuscript and the to-do's for getting the lab study ready to go, as well as selecting stimuli to be used for the experiment.

##### Sample Protagonists

<table class="tg">
  <tr>
    <td class="tg-0lax"><img src='assets/r1.jpg' width=250></td>
    <td class="tg-0lax"><img src='assets/r2.jpg' width=250></td>
    <td class="tg-0lax"><img src='assets/r3.jpg' width=250></td>
  </tr>
  <tr>
    <td class="tg-0lax"><img src='assets/r8.jpg' width=250></td>
    <td class="tg-0lax"><img src='assets/r5.jpg' width=250></td>
    <td class="tg-0lax"><img src='assets/r6.jpg' width=250></td>
  </tr>
  <tr>
    <td class="tg-0lax"><img src='assets/r7.jpg' width=250></td>
    <td class="tg-0lax"><img src='assets/r4.jpg' width=250></td>
    <td class="tg-0lax"><img src='assets/r9.jpg' width=250></td>
  </tr>
</table>

## GitHub Repository 

#### Objective

Setup a GitHub repository containing all of our computational and cognitive research to showcase to a larger community of interested individuals.

#### Progress

  * Fundamental research repository (done, still private pending edits and reviews).
  * Computational research repository will include Orage, empathetic technology research on computational beings, and Tiana's ML (next week).

<img src='assets/g1.png' width=1000>

<table class="tg">
  <tr>
    <td class="tg-0lax"><img src='assets/g2.png' width=550></td>
    <td class="tg-0lax"><img src='assets/g3.jpg' width=550></td>
    <td class="tg-0lax"><img src='assets/g4.png' width=550></td>
  </tr>
</table>

## Knob 

#### Objective

The idea is to put an AI between you and the media in order to let the machine manage your use of the media. One use case could be to give it to kids to expose them to healther content and ease them into technology with a healthier behavioral approach based on storytelling. You control your experience indirectly by teaching the machine and the machine remembers and will mimick your behaviour at corresponding times of the day. As you reinforce your habits, the knob will progressively gain its own weight, and build its own behaviour based on yours. As you let it live, recorded memories and behavioral traits fade out, and the knob can adapt to your new current use better. In short: you set the rules but you can fall under your own rules.  The whole thing also allows very easily to understand how and to hack the machine's behavioral map without coding but by literally painting your own behavioral map (with Paint or anything), which looks like this.

<img src='assets/k1.png' width='250'>
 
#### Progress

* We're progressing on the knob prototype. 
  * Conceptualizing an interaction system that allows you to jump from one knob to another and also build your own knob. 
  * Cleaning up the system for github to be able to connect it to anything and build remembering machines.

<a href='https://drive.google.com/file/d/1GACC_bYePoRM4mXabpwQCjbeYJnTBTRJ/view'>This link takes you to a short video demo of Knob so far.</a>
 
## Text Summarization Algorithm

#### Objective

Develop a fully-functional text summarization algorithm. 

#### Progress

* Completed
  * We got a 2 P4 GPU VM up and running. 
  * Wrote, tested and saved a decoder for scoring. 
  * Set up checkpointing and Tensorboard. 
  * Started hyperparameter tuning. 
* Upcoming
  * Figure out multi-gpu processing / load balancing
  * Integrate more datasets - the summarizations we're getting from the current dataset feel too long and might be overwhelming the algorithm - going to integrate datasets with shorter summarizations
  * More hyperparameter tweaking - still unclear on max features, training epochs, etc - toying with different arrangements and looking at different approaches online for guidance. 
