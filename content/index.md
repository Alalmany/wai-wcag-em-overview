---
title: "WCAG-EM Overview: Website Accessibility Conformance Evaluation Methodology"
title_html: "WCAG-EM Overview:<br>Website Accessibility Conformance Evaluation Methodology"
nav_title: "WCAG-EM Conformance Methodology"
permalink: /test-evaluate/conformance/wcag-em/
ref: /test-evaluate/conformance/wcag-em/
lang: en
github:
  repository: w3c/wai-wcag-em-overview
  path: content/index.md
footer: >
  <p><strong>Date:</strong> Updated 15 December 2016. First published as "Conformance Evaluation of Web Sites for Accessibility"  in September 2005.</p>
  <p><strong>Editors:</strong> <a href="https://www.w3.org/People/Shawn/">Shawn Lawton Henry</a> and <a href="https://www.w3.org/People/shadi/">Shadi Abou-Zahra</a>.</p>
  <p>Developed by the Education and Outreach Working Group (<a href="http://www.w3.org/WAI/EO/">EOWG</a>) and the WCAG 2.0 Evaluation Methodology Task Force (<a href="https://www.w3.org/WAI/ER/2011/eval/eval-tf">Eval TF</a>).</p>

---

{::nomarkdown}
{% include box.html type="start" h="2" title="Summary" class="full" %}
{:/}

This page introduces the Website Accessibility Conformance Evaluation Methodology (WCAG-EM).

Quick links to the resources:

-   [Website Accessibility Conformance Evaluation Methodology (WCAG-EM)](http://www.w3.org/TR/WCAG-EM/)
-   [WCAG-EM Report Tool: Website Accessibility Evaluation Report Generator](http://www.w3.org/WAI/eval/report-tool/#/)

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{% include_cached toc.html levels="2" %}


## Introduction
{:#intro.no_toc}

Website Accessibility Conformance Evaluation Methodology (WCAG-EM) is an approach for determining how well a website conforms to Web Content Accessibility Guidelines ([WCAG](/standards-guidelines/wcag/)).

If you want to get a general sense of how a web page addresses a few accessibility issues, see [Easy Checks - A First Review of Web Accessibility](/test-evaluate/preliminary/). It is usually best to do preliminary checks before applying WCAG-EM, and to address potential accessibility barriers before investing in a more thorough review such as WCAG-EM.

WCAG-EM is a supporting resource for the WCAG standard; it does not define additional WCAG requirements. It is published as a W3C Working Group Note.

### Scope

WCAG-EM applies to all websites, including web applications and mobile websites. It covers different situations, including self-assessment and third-party evaluation. It is independent of particular evaluation tools, web browsers, or assistive technologies.

WCAG-EM is primarily for evaluating conformance of existing websites. However, accessibility should not be left until the evaluation stage; it should be integrated from the beginning and throughout the project lifecycle — in planning, design, and development.

Other aspects of evaluation are addressed in related pages of the [Evaluating Web Accessibility](/test-evaluate/) resource suite. For example, guidance to help you better understand real-world accessibility issues and evaluate effective accessibility solutions is in [Involving Users in Evaluating Web Accessibility](/test-evaluate/involving-users/).

Who WCAG-EM is for {#for}
--------------------------

WCAG-EM is for anyone who wants a common procedure for auditing websites. It is for direct use by internal evaluators, external auditors, benchmarkers, and researchers. Additionally, WCAG-EM can be referred to by managers, procurers, policy makers, regulators, and others. 

Applying WCAG-EM successfully requires knowledge of WCAG, accessible web design, assistive technologies, and how people with different disabilities use the Web (as described in the WCAG-EM [Required Expertise section](http://www.w3.org/TR/WCAG-EM/#expertise)).

What is in WCAG-EM {#whatis}
-----------------------------

WCAG-EM provides guidance on using the methodology and considerations for specific situations. The conformance evaluation procedure is detailed under 5 main steps:

1.  **Define the scope of the evaluation** - defining what is included in the evaluation; the goal of the evaluation; and the WCAG conformance level (A, AA, AAA).
2.  **Explore the website** - identifying key web pages; key functionality; types of web content, designs, functionality, etc.; required web technologies.
3.  **Select a representative sample** - guidance on structured and randomly selected web pages when it is not feasible to evaluate every web page on a website.
4.  **Evaluate the selected sample** - determining successes and failures in meeting WCAG; accessibility support for website features; and recording evaluation steps.
5.  **Report the evaluation findings** - aggregating and reporting evaluation findings; making evaluation statements; and calculating overall scores.

### Technical document format

WCAG-EM follows the W3C format for technical specifications which includes several sections at the beginning: links to different versions, editors, copyright, abstract, and status with the link to errata and the email address for comments. There is a link at the top to the Table of Contents.

WCAG-EM Report Tool {#wert}
----------------------------

The [**WCAG-EM Report Tool: Website Accessibility Evaluation Report Generator**](http://www.w3.org/WAI/eval/report-tool/#/) helps you follow the steps of WCAG-EM and generate a structured report from the input that you provide.

Who develops WCAG-EM {#wg}
---------------------------

WCAG-EM is developed by the WCAG 2.0 Evaluation Methodology Task Force ([Eval TF](http://www.w3.org/WAI/ER/2011/eval/eval-tf)), which is a joint task force of the Web Content Accessibility Guidelines Working Group ([WCAG WG](http://www.w3.org/WAI/GL/)) and Evaluation and Repair Tools Working Group ([ERT WG](http://www.w3.org/WAI/ER/)). The Working Groups are part of the World Wide Web Consortium ([W3C](http://www.w3.org/)) Web Accessibility Initiative ([WAI](http://www.w3.org/WAI/)). 