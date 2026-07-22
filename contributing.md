# Contribution Guidelines

Thanks for helping keep this list useful and current.

## Before Submitting

An addition should:

- Directly target or materially support Cloudflare Workers, not merely run on a general JavaScript runtime.
- Be something you have evaluated and can recommend from direct experience.
- Be documented, maintained, non-archived, and non-deprecated.
- Offer clear value beyond existing entries.
- Link to the canonical source, without affiliate or referral parameters.
- Use an objective description rather than a tagline or marketing copy.

Stable projects do not need frequent releases, but their documentation and supported APIs must remain current. Beta software is eligible when its maturity is stated in the description.

## Project Entries

A project entry must:

- Be a complete end-user application rather than a library, starter, template, or toy demo.
- Have a recognized open-source license and documented deployment or self-hosting instructions.
- Use Workers as a core part of its architecture, ideally alongside documented Developer Platform primitives.
- Be mature enough to evaluate and show credible ongoing maintenance.
- Name its key Cloudflare primitives in the entry description.

Demos and Cloudflare-maintained reference applications belong in **Projects, Examples, and Starters** under **Official Resources**. Projects that only happen to support Workers as one of many interchangeable deployment targets do not qualify for **Projects**.

## Adding an Entry

- Submit one project per pull request.
- Add the entry at the bottom of the most relevant category.
- Use the format `- [Project](https://example.com) - Objective description.`
- Start the description with an uppercase letter and end it with punctuation.
- Explain in the pull request why the project belongs and how you evaluated it.
- Disclose whether you maintain or are affiliated with the project.
- Check that every link in the entry works.

New categories are welcome when several strong entries need them. Please do not add empty categories, duplicates, paid placements, abandoned snippets, unsafe proxy collections, or legacy projects whose recommended replacement is already listed.

## Updating Existing Entries

Fixes for broken links, inaccurate descriptions, renamed projects, and deprecated resources are encouraged. Include a primary source for maintenance or deprecation claims when possible.

Entries may be removed when they become unavailable, archived without a maintained successor, incompatible with current Workers APIs, or no longer meet the criteria above.
