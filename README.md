# CurricuLLM

A repository with curricular materials, where the initial structure and content is LLM-generated, and over time hopefully improved upon by teachers.

> Feel free to fork the repository, and use however you wish (as long as the license is respected).

The goal is to create a system where the first automatic step of creating free teaching materials yields decent results, and where it's easy for domain experts to then improve on the materials (via GitHub PRs or Issues) until they equal or surpass traditional textbooks.

## Workflow
Especially in the beginning, there will be a lot of back-and-forth between experts and LLM generation.
### Prompt design and source materials
* Design good "global" prompts that generate decent output for any topic
* Identify what types of topic-specific prompt modifications are beneficial
* Find public-domain materials that may assist generation (general governmental guidelines, topic-specific requirements etc)
### Validation
* Experiment on a few disparate topics, e.g. grade 7 math, high-school religion.
* Invite domain experts (teachers) to review materials
* Based on ideas and comments, iterate again from top
### Publishing
* A v1.0.0-beta release is created. Once published, no more auto-generated content should be added, only manual additions and modifications (resulting in 1.x releases)
* Different sections of a course can be published separately - perhaps we want to focus on a really good 7th grade algebra section before proceeding with the rest of the year's curriculum
### Re-iterate
* As our understanding of how the materials are used, and LLMs improve, work on a v2.0 release is started
* Using the changesets between v1.0 and v1.x, new prompt hints can be generated


## LLM generation process
* Create a specification of the topic (language, school year, main topic etc)
* Add materials such as governmental curriculum guidelines
* Generate a Table of Contents using the global ToC template.
  * Optionally, add topic-specific prompt instructions for generating the ToC
  * In specific cases, it might be necessary to create the ToC manually
* Using the ToC, generate the chapters/sections
  * Optionally, add topic- and/or section-specific prompt adjustments
* Generate illustrations from the image link titles created by the LLM
  * Optionally, modify instructions for image generation on any level (specific illustration, section, topic...)
* Generate assignments for sections

All these steps (except the first) can be performed automatically in one go without human intervention, which can be good for a first draft and to get a feel for the prompts and their output.
Manual modification to prompts at different levels will most certainly be required in order to increase quality.

## Expert adjustments
* Once a LLM-generated beta version has been created, no content should be generated/modified by AI. All changes should be authored by - and reviewed by - experts before merging.
* There's no way to ensure that the contributions were not originally created by an LLM, but the manual review process should filter out any slop.

Once the foundation is laid, I will start accepting PRs with corrections and improvements - initially for global and topic-specific prompt modifications.
When a part of the generated output (a chapter, section etc) is good enough, it will be excluded from re-generation and only manual edits will be allowed.

## Rough plan
[Project](https://github.com/users/JWMB/projects/2/views/1?system_template=feature_release)
* Decide on file structure (maybe [language]/[general area]/[subarea]/[demographic]?)
* Multi-pass generation pipeline: raw structure + facts first, then "skinning" (story, tonality, student vs teacher notes etc)
* Output generators, e.g. PDF. Started experimental HTML output, e.g. [here](https://html-preview.github.io/?url=https://github.com/JWMB/CurricuLLM/blob/main/courses/Matematik%20%C3%85K%207/rendered.html)
* A way to indicate status/versioning on documents (e.g. "In review", "accepted") naming c
* Better assignments/problems
  * Use a different LLM to validate that they're not ambiguous, are solvable and that the proposed hints/answers are correct
  * Generate numerical-only answers when possible, for easier validation when used in a training app
  * When answer is non-numerical, or a reasoning answer, generate an accompanying prompt that an app can use to validate the answer
* Iterate on global prompts so that the initial output is more acceptable
* Add targeted/modified prompts to areas where the global prompts are insufficient
* Better system for illustrations
  * prompt better illustration descriptions and locations
  * Run image generator based on generated descriptions
