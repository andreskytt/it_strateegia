---
layout:     post
title:      Nature of QA
date:       2016-09-23 09:00:00
summary:    The terms of testing and QA are often used interchangeably and in ways that forget or obscure their initial meanings. We'll try to rectify that by referring to a classic text on the topic 
published:  false
categories: testing QA quick
---

It is always useful to validate the basic terms. To understand if the meaning we are used to give them still applies. 

So, what exactly is QA? 

QA stands for "Quality Assurance". That, without going into what various schools of thought read into it, is fundamentally a process of assuring the quality of something. Sounds trivial, right? It does. Looking deeper, this implies the existence of two distinct activities or processes. Firstly, there is the process of assuring quality - making sure our subject is of desirable quality. Secondly there is the quality itself. To assure something, we must have that something well defined and preferably measurable. 

This distinction is incredibly important from strategic principle as it separates the what from how. And clears up a confusion. Testing does not equal QA. Testing does not seek to validate if something does what it is supposed to do. Testing is a process that assesses the quality of a system so the quality assurance process can act upon it. Or, in other terms

<blockquote>
  <p>
	Testing is the process of executing a program with the intent of finding errors
  </p>
  <footer><cite title="Glenford J. Myers">Glenford J. Myers[^1]</cite></footer>
</blockquote>

This quote comes from a book[^1] first published in 1979 and now in its 3rd edition. In it the author provides  a view on software testing that has stood the test of time remarkably well. You'll find an occasional Fortran example but that's about it. Really a worhwhile read for gaining a solid foundation on what testing is about. But back to our original question.

So if we test for finding things that work, we only validate that some errors _are not_ there. Which is really not that useful in terms of determining system quality. Although quality might something be formally _defined_ as the property of a system to perform according to specifications, the user _perception_ of quality is certainly different. Absence of tigers is a rather good quality goal of a picnic but one should also look under the blanket for snakes and scorpions.

If we focus on finding errors, however, we get a comprehensive overview of system quality and thus really answer the question about the quality of the system. We lift the blanket, look for snakes and other creepy-crawlies, check the weather and look out for hyenas (also striped, but much smaller than tigers).

It is really important therefore to make sure that testing is used for its intended purpose, for assessing the quality of software for a given definition of quality. Assuming that definition exists, of course. And then there is a separate process of acting upon that assessment, of assuring the software is of sufficient quality. Testing in itself does not provide quality. 

__Key point:__ Strategically, there are two distinct processes: the one of assuring the quality of the system and the one of assessing that quality. Both need attention and must not be confused. 

---

[^1]:  J Myers Glenford. The art of software testing. A Willy-Interscience Pub, 1979
