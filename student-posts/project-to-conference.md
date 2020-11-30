---
layout: page
mathjax: true
permalink: /student-posts/project-to-conference/
---

## CS231n: Taking a Course Project to Publication
*By Leila Abdelrahman , Amil Khanzada, Cong Kevin Chen, and Boyang Tom Jin*

<div class='fig figcenter fighighlight'>
  <img src='/assets/student-post-files/fusical.gif'>
</div>

<!-- TO DO: FILL OUT REST -->

Taking a course project to publication is a challenging, but rewarding endeavor. Starting in CS231n in Spring 2020, our team spent hundreds of hours over seven months to publish our project at the ACM 2020 International Conference on Multimodal Interaction! We aim to share tips on how to create a great project, and how you can take it to the next level through publication!

These tips (outlined below) are critical to succeed!

- [Picking your team]()
- Choosing your project
- Build the project
- Showcasing your Work
- Refining for Publication
- Maximizing your Impact

## Picking your Team 🤝

Investing good time to choose your teammates is CRITICAL, as they will shape your thinking, dictate your sanity, join your lifelong network, and ultimately determine the success of your project. Start your search as early as possible (e.g. before the course starts) so that you have enough time to consider different ideas and hit the ground running.

Have a sense of what you want to do and who you want to work with. Post your interest on Piazza and evaluate others. Join a Slack channel for your area of interest (e.g. #bio_healthcare). Interview folks through project brainstorming video calls. Consider their experience in machine learning, motivation, and personality. Specifically, when evaluating your potential team members’ machine learning background, consider factors such as prior work experience, projects/publications, and AI courses in topics related to your intended project.

Finally, be flexible and pick your group. Always keep in mind that plans can change and some students do end up dropping the course. Be open in your communication and to unexpected changes in your group especially until the course drop deadline.

<<<<IMAGE FROM CANVA HERE>>>>

Finally, you will need mentorship and support to succeed. Find the TA, professor, and/or industry mentors best suited to guide you and meet often with them. Do note that the course staff and mentors are generally interested in helping YOU succeed and may even write you a recommendation letter in the future!

**What we did:** We looked at the profiles of all the TAs and went to office hours. We were lucky to find Christina Yuan who had done similar research work and soon became a kind mentor for us. Professor Ranjay Krishna was also very kind to support us on taking our project to publication.

## Choosing your Project 🎛

What you do is very important, as it determines your enjoyment and builds your foundation for future research.

### Sample Categories of CS231n Projects

1. Image Classification
2. Image Segmentation
3. Video Processing
4. 3D Deep Learning
5. Sentiment Analysis
6. Object Detection
7. Data Augmentation
8. Audio analysis with CNNs and Spectrogram Images
9. See past projects here: [http://cs231n.stanford.edu/2020/project.html](http://cs231n.stanford.edu/2020/project.html)

When choosing a project, consider [SMART goals](https://en.wikipedia.org/wiki/SMART_criteria).

[Untitled](https://www.notion.so/76382c08aa8743f4adbf9942c91cad0a)

### Advice from Professor Fei-Fei Li

1. **Maximize learning:** Find a project that can enable your maximal learning.
2. **Feasibility:** Make sure it is executable within the short amount of time in this quarter, especially making sure that data, evaluation metric and compute resources are adequate for what you want to do.
3. **Think long term:** Executing a good project regardless of topic would be beneficial to your job application. Companies look for people with solid technical background and the ability to execute and work as a team. I don't think they will be very narrow-minded on the specific project topics.

# Building the Project 👷🏽

When working on the project, consider these tips to maximize potential for impact:

[Untitled](https://www.notion.so/b483da7c668d4706a10712d517aaca1a)

# Showcasing your Work 📽

Communication makes the project memorable. Come up with a fun title, and make sure to present your work in multiple ways. Beyond the written report, create a slide deck, record a video, and practice talking about your work with TAs, professors, and industry experts. Articulation skills in oral and visual presentations ensure that the audience remembers your work!

Before completing the project, take the time to clean your GitHub repository (or make one you have not done so already) - add a strong README.md file with a clear description of what your project is about, a “how to” guide complete with examples, and comments. Doing so makes your project accessible to others and encourages others to build upon your work.

Even if you are submitting to a journal or conference, consider also submitting a copy of your work to a pre-print service like [arXiv](https://arxiv.org/). arXiv does not require peer-review and is commonly used by researchers within the CS field to disseminate their work. Publishing a preprint is a quick way to add to your list of publications on Google Scholar.

**What we did:** We chose the playful title “Fusical” and created a one-figure visual that summarized our work at a high-level. This made it easy for people to reference our work during the conference and also allowed us to talk about our project without confusing attendees with different slides. We also made sure our Github repository reflected our results and we took the opportunity to embed multiple figures into the README to make it visually appealing and easily understandable.

# Refining for Publication 📄

When refining for publication, ask yourself: *What am I bringing to the conversations that’s new?*

This can come from novelty or beating the state-of-the-art methods. **Reinforcing this question throughout refinement is critical for successfully publishing.

The next step is to find the right journal or conference to publish to. Unlike most science fields, CS and AI tends to value conference submissions over journal submissions due to the publication turnaround time and higher visibility within the field. Conferences are of course more fun as well, providing you with the opportunity to network with other like-minded individuals. Within the Computer Vision field, you’ll find conferences of all sizes happening at different times throughout the year. Top conferences include CVPR, ICCV, and ECCV, but due to their popularity, it might be difficult to get a successful submission. Because many students choose to do an application-based project, it might be worthwhile to consider niche conferences depending on the field your project is related to. For instance, teams who developed a model to determine student engagement in the classroom might consider submitting to AIED, a conference on Artificial Intelligence in Education. Talking to your mentors might also help narrow down the specific publication method or venue of. Keep in mind that Stanford does offer some [grants for travel](https://undergrad.stanford.edu/opportunities/research/get-funded).

Every journal or conference has its own submission criteria and format. Make sure to review these early so you can adapt your project paper for publication. In many cases, be prepared to do some extra work. Look at the current state-of-the-art work and objectively assess how your paper measures up. If there are gaps, take the time to run more experiments or ablation studies. Consider how you can frame your project in a way that offers a unique perspective to the field. For instance, did you try to apply a recently published approach to a new domain? Did you use an interesting dataset that no one has used before? Did an analysis of your model uncover something novel about the data?

Iterating over the work is essential for creating publication-quality work. Improving the writing, optimizing the code, and making quality figures are key points to consider. Reference the work of experts and reach out for advice.

Publications are a lengthy process, partly due to peer review. Don’t give your reviewers a reason to come back to ask you a question. Review your submission for possible ambiguous areas or claims that are unsubstantiated. Make sure you are clear with your experiment parameters and have someone outside your team to review the paper.

**What we did:** After completing CS231n and perusing several publications of past contest entries, we decided to add two modalities that were not present in most of those submissions: captioning (in order to look for certain objects or settings, such as protests, that are correlated with a specific degree of sentiment) and laughter detection (since the presence of laughter in an audio clip quite often indicates a positive sentiment).

We attained a test accuracy of approximately 64%, which was only the 8th best out of 18 teams who submitted to the contest. This suggests that experimenting with relatively novel modalities was a factor that led to ICMI accepting our paper for publication.

*If you don’t get the results you were hoping for, don’t be scared to submit it anyways - the worst they can do is say no and feedback from expert reviewers in the field is always valuable!*

# Maximizing your Impact 🙌

Consider that your project has worth and has an impact. Presenting at global conferences (we presented at the 2020 ICMI) is a great way to share your results and findings with other academic and industry experts but there are other options as well. Do you think your idea can be deployed in practice? Stanford has resources and opportunities to help students continue to pursue their ideas including the [Startup Garage](https://www.gsb.stanford.edu/experience/learning/entrepreneurship/courses/startup-garage), a hands-on project based course to develop and test out new business concepts.

If your idea is more research focused, seek out professors who might work in the domain area and pitch them your ideas. You might have opportunities to continue your project as an independent studies project or apply your idea to larger and bigger datasets or similar research areas.

# Conclusion

It was hard work and fun because we had a good team! We hope you all enjoyed these tips on how to enjoy the process of taking a project from brainstorming to impactful presentations and publications. These tips are scalable, and we hope you use them in other endeavours as well!
