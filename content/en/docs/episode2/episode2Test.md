---
title: "Episode 2 Test"
date: 2020-10-09T03:15:26-07:00
weight: 2090
---

**The Testing and Completion Certificate Services are in testing and will be available shortly. Please check back soon to use these services, in the meantime please feel free to utilize the rest of the course content.**

All Modernapps Ninja learning content is publicly accessible and available openly, however a free membership is required to take tests and recieve a certificate of completion for the course. You must first [join the community](https://modernapps.ninja/about/membership/) and register for this course per the instructions in the course introduction section before attempting to submit a test.

Ninja tests use devops tools and processes so the testing system itself provides both experience with and validation of foundational devops skills. 

- [Instructions](#instructions)
  - [Full Test Instructions](#full-test-instructions)
  - [Test Answer Response Sheet](#test-answer-response-sheet)
  - [Episode 2 Test Questions](#episode-2-test-questions)
      - [This concludes the episode 2 test. Please use the navigation bar to proceed to the next page.](#this-concludes-the-episode-2-test-please-use-the-navigation-bar-to-proceed-to-the-next-page)

## Instructions

This test uses automated grading, you must follow the instructions exactly to ensure automated grading will complete successfully. 

To complete the test you must review the questions on this page, and fill in your answers on a seperate answer sheet provided below. We recommend opening the answer sheet for the test in a seperate browser tab so you can fill in the answers as you proceed through the questions. 

Every question in this test is titled "Question" followed by its order, for example Question1, Question2 etc...

All questions will provide a list of possible answers. Each possible answer is represented by a lowercase letter, the first response is option "a", the second is option "b" and so on, as shown in the example questions below. 

The Answer sheet will open in Github's web-based editor, similar to the image shown below:

![Example Test Response Sheet](/vSphereTanzu301_vt4163/admin/assets/images/blank_test_screen_example.png)  

After you fill in your answer sheet, you will submit  your responses as a git [pull request](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests) following the instructions provided below, which will trigger a workflow that will grade your responses and provide your test grading sheet. 

### Full Test Instructions

If this is the first test you have taken, or if you have an questions at all about how to propely complete the test answer sheet or the test grading service, please review the full [How to Take a Test Instructions](https://modernapps.ninja/course_repo_template_ct8279/docs/reference/testinstructions/).  

It is important that you follow the instructions carefully to ensure the automated grading process completes successfully.

### Test Answer Response Sheet

Please right click the following link to the test answer response sheet and select to open it in a new tab. The questions for this test will be provided below in this page, but you will need to enter your responses in the answer response sheet. 

[test2 Answer Response Sheet](https://github.com/modernappsninja/vSphereTanzu301_vt4163/edit/main/static/admin/userdata/tests/test2.yml)  

### Episode 2 Test Questions

#### **Question1:** This session covered creating a nested ESXi cluster with HCI Mesh. HCI mesh is new vSphere 7 feature that:||Select two choices. <!-- omit in toc -->

**Please select the best response from the following to complete the statement in Question1:**

```yml
Answers:
  a: shares a vsan datastore between clusters
  b: 
  c: 
  d: 
```

#### **Question2:** In the setup of vSphere with Tanzu you will need at least two separate, routable subnets configured. One subnet will be for Management Networking. This is where vCenter, ESXi, the Supervisor Cluster and the Load Balancer will live. The other subnet will be used for Workload Networking. This is where your virtual IP’s and TKG clusters will live. <!-- omit in toc -->

**Based on the scenario above, please select which 2 of the following statements are accurate:**

```yml
Answers:
  a: The Management and Workload Networks cannot be on the same subnet. They require L2 isolation.
  b: The Management and Workload Networks can be on the same subnet. They do not require L2 isolation.
  c: Avoid using VLANs to isolate the Management and Workload Network
  d: VMware recommends using VLANs to isolate the Management and Workload Network
```

#### **Question3:** Which of the following items can be used to check and validate the base networking configuration: <!-- omit in toc -->

**Select 3 of the following statements:**

```yml
Answers:
  a: basic networking - management network can reach internet
  b: basic networking - management network can reach ESXi hosts
  c: vmotion is working
  d: basic networking between management network and workload networks is working so that you can ping between the networks
```

##### This concludes the episode 2 test. Please use the navigation bar to proceed to the next page.
