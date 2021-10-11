# Advances in Computing with Uncertainties

* CME 270, Fall Quarter, 2021
* Meeting Time: T/Th 11:30 AM - 1:00 PM
* Location: [Hewlett](https://campus-map.stanford.edu/?id=04-510&lat=37.42900001&lng=-122.17285486&zoom=17&srch=hewlett) 103
* Course websites
    * (So meta) Github repository: [github.com/lalyman/cme-270/](https://github.com/lalyman/cme-270/)
    * [Canvas](https://canvas.stanford.edu/courses/144967) site
    * The Canvas site is maintained for grading, discussions, HW submissions, and class announcements
    * HW assignments, details for the final project, and course notes will be posted on both sites

With high probability, this `README.md` file represents the most updated version of the lecture schedule. **Last updated:** 28 September 2021, 10:40 PM PT.

## Contact

* Primary Instructor: Laura Lyman (pronouns: she/her/hers)
* Email: `lymanla@stanford.edu`
* **Office Hours**: Tu/W from 5:00 - 6:30 PM in <a href = "https://campus-map.stanford.edu/?id=04-060&lat=37.4289861377&lng=-122.175177853&zoom=16&srch=Shriram%20Center%20For%20Bioengineering%20">Shriram</a> SB35 from 9/21 onward

## Introduction

<p align=justify>
Uncertainty is a challenge. Representing a lack of knowledge, it hampers our attempts to draw scientific conclusions and confidently design engineering solutions. Failing to account for uncertainty can lead to false discoveries, while overreacting to uncertainty can limit our ability to say anything meaningful or spend resources judiciously. Overcoming these issues requires identifying, quantifying, and managing uncertainties through a combination of technical skills and an appropriate mindset. This class surveys advances in computation given the presence of uncertainties. 
</p>

## Course Description (for Stanford's [Explore Courses](https://explorecourses.stanford.edu/))

<p align=justify>
If a politician, executive, or medical team were to use the results of your model for some critical decision, how well would you sleep at night? As computation plays an increasingly important role in our society, understanding the limitations of its predictive capabilities becomes of the utmost importance. Uncertainty quantification (UQ) considers the intersection of probability, statistics, numerics, and disciplinary sciences to provide a computational framework for measuring and reducing uncertainties. This graduate course focuses in depth on topics that are less typically covered in a traditional introduction to UQ, with particular attention given to polynomial chaos methods, Galerkin schemes, linear transport with uncertainty, and active subspaces. Research applications will be emphasized through assignments and student-defined projects. <b>Prerequisite</b>: probability and statistics at the level of CME 106 or equivalent, linear algebra at the level of CME 200 or equivalent, or consent of the instructor.
</p>

## Similar Courses


#### ME 470/CEE 362A: Uncertainty Quantification

<p align=justify>
This course is <i>most</i> similar to Uncertainty Quantification (ME 470/CEE 362A), which will be offered in Spring, 2022. ME 470 is taught by the incredible Professor Catherine Gorle &mdash; and will be co-taught by Professor Gianluca Iaccarino and (potentially) me. As for how the classes compare, there is some unavoidable overap in the introductory material covered in the first few weeks. However, the courses then diverge to explore different topics, which I've illustrated below for your convenience. 
</p>

<table>
  <tr>
    <td>       </td>
    <td><b>ME 470</b></td>
    <td><b>CME 270</b></td>
  </tr>
  <tr>
  <td> <b>Differing topics</b> </td>
  <td> Reduced order/surrogate modeling, parameter estimation (frequentist, Bayesian), sensitivity analysis (local, global), sparse grid quadrature </td>
  <td> Generalized polynomial chaos (gPC), Karhunen-Loeve expansion, linear/nonlinear transport under uncertainty, kriging, topics in polynomial chaos (handling high dimensions, correlated inputs, etc.)  </td>
  </tr>
  <tr>
    <td>  <b>Shared topics</b></td>
    <td colspan="2">Aleatory vs epistemic uncertainty, probability theory, Galerkin methods, polynomial chaos, Monte Carlo sampling, importance sampling, collocation, uncertainty propagation basics </td>
  </tr>
</table>

You can certainly take both classes and learn quite a bit. 

#### CS 238: Decision Making under Uncertainty

Topics for this course include Bayesian networks, influence diagrams, dynamic programming, reinforcement learning, and partially observable Markov decision processes. 

Some other similar courses include <b>CS 228 (Probabilistic Graphical Models) </b> and <b>STATS 362 (Monte Carlo Methods)</b>.



## Classroom Culture & Expectations

As an instructor, my hope is to be accessible and non-intimidating. Have you ever nodded quitely at the board, perhaps while making a serious face, when internally you are lost or panicking? Let's smash that standard together. What I ask for you is to *engage authentically* and *ask questions*. 


### What if I'm Nervous About Asking A Question? <span id="dumb-q"></span> 

<p align=justify>
Please ask as many "dumb" questions as possible. I am serious. As an teacher, I am not here to judge you in the classroom; my goal is simply for you to learn as much as possible. When I hear a question that indicates a lack of understanding, I hear: 
</p>

* someone brave enough to be transparent, and
* areas for growth that I need to address as an instructor. 

<p align=justify>
Our goal as a classroom community should be to build an environment in which everyone feels safe, welcome, and comfortable with struggling to answer hard problems. 
</p>


### One-on-ones

<p align=justify>
Within the first few weeks of the quarter, I will schedule one-on-one meetings (15-20 minutes) with each of you. These are meant to be informal. The goal of these meetings is for me to: (1) get to know you, (2) hear about your background, (3) listen to what you are hoping to get from this class, (4) understand your time constraints for the quarter, and (5) provide space for you to voice questions, concerns, or anything you'd like to talk through. You can sign up for a meeting time slot <a href="https://forms.gle/jG1vueQPNqzSei9A7">here</a>. 
</p>

### Anonymous feedback

<p align=justify>
Open and honest communication are the bedrock of a successful classrom experience. While I hope to be as accessible and non-intimidating as possible, I understand that voicing concerns in person to your instructor can be difficult. That difficulty provides <i>just</i> enough friction for students to stay quiet instead of expressing what they need. Weekly quizzes/surveys will be made available for you to provide direct feedback anonymously.
</p>

<p align=justify>
Of course, completing these surveys is <i>not</i> required; they are merely provided as an additional resource. You can fill out as much or as little of a survey as you deem fit. All that being said, the feedback will help me improve your course experience.
</p>

* Week 1 (09/20 - 09/24) feedback <a href="https://forms.gle/dgRDXWc9Qptyirjz5">link</a>
* Week 2 and 3 (09/27 - 10/08) feedback <a href="https://forms.gle/v1LWXW82w8ARdzZU9">link</a>

## Grading

### Philosophy
<p align=justify>
This is an upper-level graduate course. My assumption is that students taking this class are primarily engaged in research and are taking courses to support that activity. Thus, my expectation is that this class is of <b>secondary importance</b> in your current workload. My grading philosophy is <b>relaxed</b> and formulated with this assumption in mind. </p>

That being said, here are the guidelines.


### Specifics for 3 Units

The following is the breakdown of assessments for taking the course for **3 units**.

<table>
<thead>
</thead>
  <tr>
    <th> Component </th>
    <th> Percentage of Grade </th>
  </tr>
  <tbody>
    <tr>
      <td> <ul> 
           <li> Homework (3 assignments, 15% each) <b>OR</b> </li>
           <li> Homework (2 assignments, 15% each) + <a href='#participation'>Participation</a> (15%)
           </ul>
      </td>
      <td> 45% </td>
    </tr>
    <tr>
      <td>Project
        <ul>
          <li> Proposal </li>
          <li> Peer Review </li>
          <li> Presentation </li>
          <li> Report </li>
        </ul>
      </td>
      <td>55% 
        <ul>
          <li> 10% </li>
          <li> 15% </li>
          <li> 15% </li>
          <li> 15% </li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

The components of the final project are discussed in the following sections. 

### Specifics for 2 Units

This is the breakdown of assessments for taking the course for **2 units**. It is similar to the assessment for 3 units, only with one fewer homework assignment.
<table>
<thead>
</thead>
  <tr>
    <th> Component </th>
    <th> Percentage of Grade </th>
  </tr>
  <tbody>
    <tr>
      <td> <ul> 
           <li> Homework (2 assignments, 22.5% each) <b>OR</b> </li>
           <li> Homework (1 assignment, 22.5%) + <a href='#participation'>Participation</a> (22.5%)
           </ul>
      </td>
      <td> 45% </td>
    </tr>
    <tr>
      <td>Project
        <ul>
          <li> Proposal </li>
          <li> Peer Review </li>
          <li> Presentation </li>
          <li> Report </li>
        </ul>
      </td>
      <td>55% 
        <ul>
          <li> 10% </li>
          <li> 15% </li>
          <li> 15% </li>
          <li> 15% </li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>


### Specifics for 1 Unit 

<ul>
<li> If you are taking the course for <b>1 unit</b>, the grading is based purely on <a href='#participation'>Participation</a>, which is described below. </li>

<li> Attendance is required for the 1 unit version of this class. However, I understand that sometimes life can complicate this. If so, you are responsible for reaching out to me (<a href = "mailto:lymanla@stanford.edu">lymanla@stanford.edu</a>) directly. We will come up with a plan; likely, it will involve a one page writeup on the material you missed to "count" for some number of classes. 
This is only an option for the 1 unit folks; if you are counting Participation in your grade for 2 - 3 units, that is earned through regular attendance.
</ul>

## Participation <span id="participation"></span> 

<p align=justify>
Paticipation is a combination of attendance and asking questions. To fulfill this track (<b>required</b> for 1 unit, <b>optional</b> for 2 - 3 units), you are responsible for <b>asking at least one question per week</b> about the material. It is <b>best if you ask your question during class</b> -- as you will see, I try very hard to make the learning environment feel as safe and relaxed as possible. (See <a href='#dumb-q'>What if I'm Nervous About Asking A Question?</a>). However, if you are shy, miss the lectures, forget, etc. you can fulfill this track by <b>emailing me your weekly question.</b> The only restriction is that a question should be one such that you learn something about the class <i>material</i> (not class logistics) from the answer; it can be as specific as, "What happened during this step on the board?" or as broad as, "Why do people care about concept X?"
</p>

<p align=justify>
There are 20 lectures in the quarter. The following breakdown is formulated with the understanding that people sometimes spend the first week deciding between various classes.
</p>

|Number of Lectures Attended | Number of Questions Asked | Estimated Grade
---|---|---
&#8805; 17 |&#8805; 9 | A
&#8805; 15 |&#8805; 8 | B
&#8805; 13 |&#8805; 6 | C

<p align="justify">
If you are in danger of not meeting the 'C' requirement, and you are taking this course for 1 unit, I will reach out to you so that we can develop a plan for you to pass.
</p>

## Final Project <span id="final-p"></span> 

<p align=justify>
There will be a student-initiated final project; you will pose a problem you would like to solve, describe your approach, and summarize your findings. The topic can be drawn from any area (ideally your research), but must involve some concept discussed in class. Projects will be carried out individually; if you are working with other students on the same research project, you must either choose different topics, or split the project into different components. The Project Report itself is intended to involve an amount of work comparable to a single homework assignment; however, there are additional components around the project (Peer Review and Presentation). Accordingly, the deliverables for the project are spread over the latter half of the course.
</p>

### Proposal<span id="prop"></span> 
By the midpoint of the class, you will submit a one page Proposal for your project. In this assignment, you must:

   * describe the problem you aim to solve,
   * state what approach you plan to use,
   * state your personal learning goals for this course, and articulate how this project will serve those goals.

The purpose of this assignment is to ensure you are on track to deliver a compelling project at the end of the course.

### Draft<span id="draft-tag"></span> 
<p align=justify>
  In week 8, you will submit a draft for your project. This will be used for a Peer Review exercise, in which you will review two other students’ draft work. This will primarily be an exercise in providing useful commentary on other researchers work, which is a critical component of the academic safari. For the draft, you must:
</p>

   * describe your problem,
   * state your approach,
   * describe your (preliminary) results, and
   * note what you plan to do for the final submission.
    
### Peer Review<span id="pr"></span>

For the Peer Review, you must:

   * summarize what the work aims to do,
   * state both strengths and weaknesses of the work
      * from a writing perspective, and
      * from a technical/methodological perspective, and
   * provide recommendations on how to improve the work.
    
### Final Presentation
<p align=justify>
The final days of the class will be reserved for student Final Presentations. These will (ideally) be 15 minute talks, though depending on enrollment we may need to adjust this amount of time. The purpose of presentations is to:
</p>

   * practice communication skills,
   * introduce the class to the variety of UQ problems, and 
   * reflect on if/how the project addressed your original learning goals.

### Report<span id="rep"></span>
The final Report will be due during finals period. For the Report, you must:

   * describe your problem,
   * state your approach,
   * argue how your results show that you solved the problem, OR note what the necessary next steps are for more conclusive results, and
   * reflect on how this class did (or did not) match your stated learning goals. 

<p align="justify">
The Report is meant more for you to have a personal record of what you learned and did. It by no means has to be a many-paged scholarly tome (unless you want it to be). We will discuss this more in class on 10/19. 
</p>

## Lecture Schedule

<p align="justify">
<b>With nonzero probability</b>, the following lecture schedule will be used. The usual "elasticity clause" applies here, as certain topics might take more or less time to cover than originally anticipated. 
</p>

<p align="justify">
To give you a glimpse into research applications, and to keep the lectures fun and engaging, this course features <b>guest speakers</b>! We are lucky to have the amazing <a href="https://profiles.stanford.edu/gianluca-iaccarino">Gianluca Iaccarino</a>, <a href="https://statistics.stanford.edu/people/art-b-owen">Art Owen</a>, <a href="https://www.zdelrosario.com/">Zach del Rosario</a>, and <a href="https://profiles.stanford.edu/sita-syal">Sita Syal</a> join us this quarter. I can say with confidence that they are all terrific speakers. Their talks are included in the schedule below. 
</p>

<p align="left">
<table class="center">
    <thead>
        <tr>
            <th>Week</th>
            <th>Date</th>
            <th>Day of Week</th>
            <th>Topics</th>
            <th>Key <br> Examples </th>
            <th>Relevant <br> Reading </th>
            <th>Deadlines & Logistics</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=2>1</td>
            <td>09/21</td>
            <td>Tue</td>
            <td> Introduction and course logistics; overview of the 3 pillars of UQ: (1) sampling, (2) quadrature + collocation, and (3) spectral methods; aleatory vs epistemic uncertainty; validation vs verification; elements of probability theory (time permitting)</td>
            <td> <ul>
                 <li> Hurricane path prediction</li>
                 <li> Subsurface geology (water contamination; oil reservoir extraction) </li>
                 <li> Proton therapy for radiation treatment (time permitting)  </li>
                 </ul>  
            </td>
            <td> <ul>
                 <li> Chapters 1-2 of <a href="#smith-book">UQTIA</a> </li>
                 <li> <a href="https://github.com/lalyman/cme-270/blob/main/lecture-notes/lecture1_sept21/CME270Day1Slides.pdf">Lecture 1 notes</a> </li>
                 <ul>
            </td>
            <td> <ul>
            <li> <b>Sign up</b> for a 15 min. <a href="https://forms.gle/AqxVjJuTkmsP9tXB9">one-on-one</a> with Laura. I'm excited to meet you! </li>
                 </ul>
          </td>
        </tr>
        <tr>
            <td>09/23</td>
            <td>Thu</td>
            <td>Introduction to Monte Carlo; introduction to spectral methods
            </td>
            <td> <ul>
                     <li> Nagel-Shreckenberg traffic modeling </li>
                 </ul>
            </td>
            <td> <ul>
                    <li>Chapter 1 of <a href="#owen-mc">MC</a></li>
                 </ul>
            </td>
            <td> <ul>
                 <li> HW 1 release <b> TBD </b> </li>
                 <li> Week 1 <b>anonymous feedback</b> <a href="https://forms.gle/dgRDXWc9Qptyirjz5">link</a></li>
                 </ul>
            </td>
        </tr>
        <tr>
            <td rowspan=2>2</td>
            <td>09/28</td>
            <td>Tue</td>
           <td> Monte Carlo continued; stats and probability review; numerical integration with MC</td>
            <td> <ul> 
                 <li>Estimating &#960; via MC </li>
                 <li> Failure of MC given a non-finite mean; how diverging partial sums might look convergent</li>
                 </ul>
            </td>
            <td><ul>
                 <li>Chapter 2 of <a href="#owen-mc">MC</a></li>
                 <li> <a href="./lecture-notes/lecture3_sept28/Lecture3Sept28.pdf">Lecture 3 notes</a></li>
                 </ul>
            </td>
            <td>  </td>
        </tr>
        <tr>
            <td>09/30</td>
            <td>Thu</td>
            <td> Sampling methods continued</td>
            <td>
           </td>
            <td> <ul>
                 <li> TBA </li>
                 </ul>
            </td>
            <td> <ul> <li> Weeks 2/3 <b>anonymous feedback</b> <a href="https://forms.gle/mYYq6VPXSZiqAJdeA">link</a> </li> </ul></td>
        </tr>
        <tr>
            <td rowspan=2>3</td>
            <td>10/05</td>
            <td>Tue</td>
             <td> Quadrature methods</td>
            <td> </td>
            <td><ul>
                 <li> Ch. 8 of <a href="#TJ-sul">TJSUL</a></li>
                 <li> Sect. 2.2 of <a href="#wilf">WILF</a> </li>
                </ul>
            </td>
            <td>  </td>
        </tr>
        <tr>
            <td>10/07</td>
            <td>Thu</td>
            <td> Quadrature methods cont.</td>
            <td> </td>
            <td> <ul>
                 <li> <a href="#gq1">GQ1</a></li>
                 <li> <a href="#gq2">GQ2</a></li>
                 <li> Sect. 2.9 of <a href="#wilf">WILF</a> </li>
                 <li> Ch. 9 of <a href="#TJ-sul">TJSUL</a></li>
                 <li><a href="https://github.com/lalyman/cme-270/tree/main/lecture-notes/lecture6_oct7/Lecture6.ipynb">Lecture 6 notes</a> </li>
                 </ul>
            </td>
            <td>
            <ul>
            <li>HW 1 released</li>
            <li> <b>Final Study List deadline</b> on Friday (10/08) </li>
            <li> Weeks 2/3 <b>anonymous feedback</b> <a href="https://forms.gle/mYYq6VPXSZiqAJdeA">link</a> </li>
            </ul> 
            </td>
        </tr>
         <tr>
            <td rowspan=2>4</td>
            <td>10/12</td>
            <td>Tue</td>
            <td>  Priors on function spaces; Gaussian processes; KL expansion; Mercer's theorem</td>
            <td>  </td>
            <td><ul>
                <li> TBD </li></ul>   </td>
            <td>  </td>
        </tr>
        <tr>
            <td>10/14</td>
            <td>Thu</td>
            <td><b>Guest lecture.</b> Sita Syal on her recent work w/ Prof. Margot Gerritsen</td>
            <td>  </td>
            <td> 
            </td>
            <td></td>
       </tr>
       <tr>
            <td rowspan=2>5</td>
            <td>10/19</td>
            <td>Tue</td>
             <td> Kriging; residual minimizing models; <b>discussion of <a href="#final-p">final project</a></b></td>
            <td>  </td>
            <td></td>
            <td> </td>
        </tr>
         <tr>
            <td>10/21</td>
            <td>Thu</td>
            <td><b>Guest lecture.</b> Professor Gianluca Iaccarino on optimization in UQ in research applications.</td>
            <td>  </td>
            <td>  </td>
            <td><ul> <li>HW 1 <b>due</b>   </td>
        </tr>
        <tr>
            <td rowspan=2>6</td>
            <td>10/26</td>
            <td>Tue</td>
            <td>Generalized polynomial chaos (gPC) in 1D; Haar wavelet expansion, multiwavelet expansion, choice of basis functions; multi-element generalized polynomial chaos (ME-gPC) </td>
            <td>  </td>
            <td> <ul>
                 <li> Sect. 2.2 - 2.4 of <a href="#gi-book">PCM</a> </li>
                 <li><a href = "#xiu-thesis">XIU</a> </li>
                 <li> Weiner-Askey Chaos paper </li>
                 </ul> 
            </td>
            <td><a href="#prop">Project Proposal</a> <b>due</b> </td>
        </tr>
        <tr>
            <td>10/28</td>
            <td>Thu</td>
               <td>  Linear transport under uncertainty: problem definition, diagonalization of stochastic Galerkin system, eigenvalues of diffusion matrix, boundary conditions
            <td>  </td>
            <td><ul>
                <li> Sect. 5.1 - 5.3 of <a href="#gi-book">PCM</a></li>
                </ul>
            </td>
            <td></td>
        </tr>
        <tr>
            <td rowspan=2>7</td>
            <td>11/02</td>
            <td>Tue</td>
            <td> <b> Guest lecture.</b> Professor Zach del Rosario (Olin College) on UQ and philosophy. This one is very cool. </td>
            <td>  </td>
             <td>  </td>
            <td> </td>
        </tr>
        <tr>
            <td>11/04</td>
            <td>Thu</td>
            <td>  Nonlinear transport under uncertainty </td>
            <td>  </td>
            <td><ul> 
                <li> Sect. 6.1 - 6.5 of <a href="#gi-book">PCM</a> </li>
                </ul>
            </td>
            <td> </td>
        </tr>
         <tr>
            <td rowspan=2>8</td>
            <td>11/09</td>
            <td>Tue</td>
            <td> <a href="#pr">Peer Review</a> exercise </td> 
            <td>  </td>
            <td>How to give constructive academic feedback 
            <ul>
            <li> <a href = "https://www.elsevier.com/connect/reviewers-update/theyve-got-it-all-wrong!-how-to-give-constructive-feedback-in-peer-review2"> Link 1</a></li>
            </ul>
</td>
            <td><a href="#draft-tag">Project Draft</a> <b>due</b>   </td>
        </tr>
        <tr>
            <td>11/11</td>
            <td>Thu</td>
            <td> <b>Guest lecture</b> by Professor Art Owen on Sobol indices</td>
            <td>  </td>
            <td>  </td>
             <td><ul> 
                 <li> <b>Change of Grading Basis</b> on Friday (11/12)
                 </ul>
             </td>
        </tr>
         <tr>
            <td rowspan=2>9</td>
            <td>11/16</td>
            <td>Tue</td>
            <td> Topics in polynomial chaos: generalization to higher dimensions  </td>
            <td>  </td>
            <td>  </td>
            <td>  </td>
        </tr>
        <tr>
            <td>11/18</td>
            <td>Thu</td>
            <td>Topics in polynomial chaos: handling correlated inputs </td>
            <td> Manufacturing processes </td>
           <td> <ul>
                <li> Research paper <a href="#rahman">RAH</a> </li>
                </ul>
            </td>
            <td>  </td>
        </tr>
        <tr>
            <td colspan=7><b>Fall Break</b> (11/22 - 11/26)</td>
        </tr>
        <tr>
            <td rowspan=2>10</td>
            <td>11/30</td>
            <td>Tue</td>
            <td>Final project presentations (accompanying write-up is due as late as 12/10)</td>
            <td>  </td>
            <td>  </td>
            <td>  </td>
        </tr>
        <tr>
            <td>12/02</td>
            <td>Thu</td>
            <td>Final project presentations (accompanying write-up due as late as 12/10)</td>
            <td>  </td>
            <td>  </td>
             <td><b>Last day of class</b></td>
        </tr>
        <tr>
            <td rowspan = 2, colspan = 6><b>Finals week (12/06 - 12/10)</b>
          <td><a href="#rep">Project Report</a><b> due 12/10</b></td>
        </tr>
    </tbody>
</table>
</p>

## University Policies

### The Honor Code

<p align="justify">
It is expected that instructors and students will follow Stanford’s Honor Code in all matters relating to this course. You are encouraged to meet and exchange ideas with your classmates while studying and working on homework assignments, but you are individually responsible for your own work and for understanding the material. You are not permitted to copy or otherwise reference another student’s homework or computer code. If you have any questions regarding this policy, feel free to contact me.
</p>

<p align="justify">
Compromising your academic integrity may lead to serious consequences, including (but not limited to) one or more of the following: failure of the assignment, failure of the course, disciplinary probation, suspension from the university, or dismissal from the university. Students are responsible for understanding the University’s Honor Code policy and must make proper use of citations of sources for writing papers, creating, presenting, and performing their work, taking examinations, and doing research.
</p>

### Academic Accommodation

<p align="justify">
Students who may need an academic accommodation based on the impact of a disability must initiate the request with the Office of Accessible Education (OAE). Professional staff will evaluate the request with required documentation, recommend reasonable accommodations, and prepare an Accommodation Letter for faculty dated in the current quarter in which the request is being made. Students should contact the OAE as soon as possible since timely notice is needed to coordinate accommodations. The OAE is located at 563 Salvatierra Walk (<a href="mailto: oae@stanford.edu">oae@stanford.edu</a>). 
</p>

## References

<p align="justify">
The notes from class should technically be sufficient for all assignments. That being said, there are several excellent references from which to choose. The lecture schedule indicates which sections of textbooks and papers correspond to particular classes. You do not need to read all of these references; they are simply provided as additional resources to help you on all fronts. Items marked with a star  &#10026; are personal favorites.
</p>

<p align="justify">
Identifiers appear in brackets below, and each one links to an online version of the text. If you cannot access a free version of a resource, please reach out to me directly.
</p>

### Texts

1. [[NMSC]](https://www.jstor.org/stable/j.ctv7h0skv) D. Xiu, <i>Numerical Methods for Stochastic Computations: A Spectral Method Approach</i>. Princeton University Press (2010)

2. <span id="owen-mc"></span>[[MC]](https://statweb.stanford.edu/~owen/mc/)  &#10026; A. B. Owen, <i> Monte Carlo Theory, Methods, and Examples.</i> Copyright Art Owen. (2013)


3. <span id="gi-book"></span>[[PCM]](https://www.springer.com/gp/book/9783319107134) M.P. Petterson, G. Iaccarino, and J. Nordstrom, <i>Polynomial Chaos Methods for Hyperbolic Partial Differential Equations</i>. Springer series on Mathematical Engineering (2015)

4. [[SFS]](https://link.springer.com/book/10.1007%2F978-1-4612-3094-6) R. G. Ghanem and P. D. Spanos, <i>Stochastic Finite Elements: A Spectral Approach.</i> Springer (1991)

5. [[SMUQ]](https://www.springer.com/gp/book/9789048135196) &#10026; Le Maitre and O. M. Knio, <i>Spectral Methods for Uncertainty Quantification with Applications to Computational Fluid Dynamics.</i> Springer (2010)

6. <span id="TJ-sul"></span>[[TJSUL]](https://link-springer-com.stanford.idm.oclc.org/book/10.1007/978-3-319-23395-6)  &#10026;  T.J. Sullivan, <i>Introduction to Uncertainty Quantification</i>. Texts in Applied Mathematics (TAM) Springer series, vol. 63 (2015)

7. <span id="smith-book"></span>[[UQTIA]](https://my.siam.org/Store/Product/viewproduct/?ProductId=24973024)  &#10026; R.C. Smith, <i>Uncertainty Quantification: Theory, Implementation, and Applications</i>. SIAM series on Computational Science and Engineering (2013)

8. <span id="wilf"></span>[[WILF]](https://www2.math.upenn.edu/~wilf/website/Mathematics%20for%20the%20Physical%20Sciences.pdf) H. Wilf, <i>Mathematics for the Physical Sciences</i>. Dover Publications (1962)

### Online Resources (< 10 Pages)

9. <span id="gq1"></span>[[GQ1]](https://aalexan3.math.ncsu.edu/articles/gauss_quad.pdf) A. Alexanderian, "A Brief Note on Gaussian Quadrature" (2018)

10. <span id="gq2"></span>[[GQ2]](https://gubner.ece.wisc.edu/gaussquad.pdf) J. Gubner, "Gaussian Quadrature and the Eigenvalue Problem" (2020)

### Papers and Theses 
 
11. [[CON]](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.728.2155&rep=rep1&type=pdf) P. Constantine, "Spectral Methods for Parametrized Matrix Equations." PhD thesis, Stanford University, August 2009

12. [[gPcCON]](https://doi.org/10.1051/m2an/2011045) O.G. Ernst, A. Mugler, H.J. Starkloff, and E. Ullman, "On the Convergence of Generalized Polynomial Chaos Expansions." ESAIM: Mathematical Modelling and Numerical Analysis (2011)

13.  <span id="pro-therapy"></span>[[PCPT]](https://d1rkab7tlqy5f1.cloudfront.net/TNW/Afdelingen/Radiation%20Science%20and%20Technology/Research%20Groups/RPNM/Publications/MSc_Sebastian_van_der_Voort.pdf) S. van der Voort, "Application of Polynomial Chaos in Proton Therapy: Dose Distributions, Treatment Parameters, Robustness Recipes & Treatment Planning."  Master thesis, Delft University of Technology (TU Delft), June 2015

14.   <span id="rahman"></span>[[RAH]](https://doi.org/10.1016/j.jmaa.2017.04.062) S. Rahman, "Wiener-Hermite polynomial expansion for multivariate Gaussian probability measures." Journal of Mathematical Analysis and Applications (2017)

15. <span id="col-surv"></span>[[SCM]](https://link.springer.com/referenceworkentry/10.1007%2F978-3-319-11259-6_26-1) D. Xiu, "Stochastic Collocation Methods: A Survey." Handbook of Uncertainty Quantification, Springer (2015).

16. [[UQSDS]](https://publikationen.bibliothek.kit.edu/1000025838/1993392) M. Schick, "Uncertainty Quantification for Stochastic Dynamical Systems: Spectral Methods using Generalized Polynomial Chaos." PhD thesis, Karlsruher Instituts fur Technologie (KIT), 21 December 2011

17. <span id="xiu-thesis"></span>[[XIU]](https://www.brown.edu/research/projects/crunch/sites/brown.edu.research.projects.crunch/files/uploads/Dongbin%20Xiu%20Thesis.pdf) D. Xiu, "Generalized (Wiener-Askey) Polynomial Chaos." PhD thesis,  Brown University, 30 May 2004
