# CurricuLLM

A repository with curricular materials, where the initial structure and content is LLM-generated, and over time hopefully improved upon by teachers.

Feel free to fork the repository, and use however you wish (as long as the license is respected).

## Rough plan
[Project](https://github.com/users/JWMB/projects/2/views/1?system_template=feature_release)
* Decide on file structure (maybe [language]/[general area]/[subarea]/[demographic]?)
* Multi-pass generation pipeline: raw structure + facts first, then "skinning" (story, tonality, student vs teacher notes etc)
* Output generators, e.g. PDF
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
