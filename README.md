# CurricuLLM

A repository with curricular materials, where the initial structure and content is LLM-generated, and over time hopefully improved upon by teachers.  

The source materials can be converted to PDFs (e.g. for print-on-demand books), HTML for online viewing, or used as content in e-learning apps.

> Feel free to fork the repository, and use however you wish (as long as the license is respected).

The goal is to create a system where the first automatic step of creating free teaching materials yields decent results, and where it's easy for domain experts to then improve on the materials (via GitHub PRs or Issues) until they equal traditional textbooks.

Some benefits of using a public git repository instead of a custom database:
* Anyone can download or fork the data. Content is readily accessible as Markdown files
* Transparency - no hidden data, all data in one place, and it's easy to see who made what changes
* Tooling - lots of git-related tools available
* Review process - built-in contribution review process via Pull Requests
* Project tracking - tasks related to the project are tightly connected to the repository via Issues and Projects

## Workflow
Especially in the beginning, there will be a lot of back-and-forth between experts and LLM configuration/generation.
### Prompt design and source materials
* Design good "global" prompts that generate decent output for any topic
* Identify what types of topic-specific prompt modifications are beneficial
* Find public-domain materials that may assist generation (general governmental guidelines, topic-specific requirements etc)
### Validation
* Experiment on a few disparate topics, e.g. grade 7 math, high-school religion
* Invite domain experts (teachers) to review materials
* Based on ideas and comments, iterate again from top
### Publishing
* A v1.0.0-beta release is created. Once published, no more auto-generated content should be added, only manual additions and modifications (resulting in 1.x releases)
* Different sections can be published separately - perhaps we want to focus on a really good 7th grade algebra section before proceeding with the rest of the year's curriculum
### Re-iterate
* After getting an understanding of how the materials are used, work on a v2.0 release is started
* Using the changesets between v1.0 and v1.x, new prompt hints can be generated

## LLM generation process
* Create a specification of the topic (language, school year, main topic etc)
* Add materials such as governmental curriculum guidelines
* Generate a Table of Contents using the global ToC template.
  * Optionally, add topic-specific prompt instructions for generating the ToC
  * In specific cases, it might be necessary to create or edit the ToC manually
* Using the ToC, generate the chapters/sections
  * Optionally, add topic- and/or section-specific prompt adjustments
* Generate illustrations from the image link titles created by the LLM
  * Optionally, modify instructions for image generation on any level (specific illustration, section, topic...)
  * ⚠️My prompting skills for for DALLE-3 are lacking, can't get rid of strange numbers/texts - check [this](/courses/Matematik%20%C3%85K%207/0%20Tal%20och%20r%C3%A4kning/0.0%20Heltal/0_chapter.md) out. Actual illustrators might well be required.
* Generate assignments for sections

All these steps (except the first) can be performed automatically in one go without human intervention, which can be good for a first draft, and to get a feel for the prompts and their output.
Manual modification to prompts at different levels will most certainly be required in order to achieve acceptable quality.

## Expert adjustments
* Once a LLM-generated beta version has been created, no content should be generated/modified by AI. All changes should be authored - and reviewed - by experts before merging.
* There's no way to ensure that the contributions were not originally created by an LLM, but the manual review process should filter out any slop.

## Rough plan (near future)
[Project](https://github.com/users/JWMB/projects/2/views/1?system_template=feature_release)
* Decide on file structure (maybe [language]/[general area]/[subarea]/[demographic]?)
* Multi-pass generation pipeline: raw structure + facts first, then "skinning" (story, tonality, student vs teacher notes etc)
* Output generators, e.g. PDF. Started experimental HTML output, e.g. [here](https://html-preview.github.io/?url=https://github.com/JWMB/CurricuLLM/blob/main/courses/Matematik%20%C3%85K%207/rendered.html)
  * Layout hinting - the LLM probably needs to output some kind of layout hints, in order to generate a more compelling visual style
* Better assignments/problems
  * Use a different LLM to validate that they're not ambiguous, are solvable and that the proposed hints/answers are correct
  * Generate numerical-only answers when possible, for easier validation when used in a training app
  * When answer is non-numerical, or a reasoning answer, generate an accompanying prompt that an app can use to validate the answer
* Iterate on global prompts so that the initial output is more acceptable
* Add targeted/modified prompts to areas where the global prompts are insufficient
* Better illustrations - work on getting consistent style, better contexts for the prompt
