---
title: Form Design Process
label: Form Design Process
---

**Stakeholders:**
- Form owner
- Subject matter experts
- VA employees processing form
- VA or VSO folks helping Veterans to complete the form

**Users**:
- Veterans
- Family members
- VA employees that help Veterans to complete the form

### What is the form?

- Review paper form, in detail
  - Is the form currently being revised by the owner?
- If it exists, review digital form, in detail
  - Create detailed flow diagram using screenshots of each decision point
- Map fields in a spreadsheet [Example: Form 21-686](/assets/design/templates/686-form-outline.csv)
- Document all (or relevant) content
- **Interview stakeholder**: Identify elements of offline experience
  - What kind of communication or followup happens after the form?
  - Can the Veteran find out anything about their status, results, etc. through another online source?

### How does this form process work?

- **Interview stakeholder**: Understand backend and human processes
  - Identify constraints for how data needs to be collected based on backend process
- **Interview stakeholder**: Prod for how fields are used in processing: computer, human or otherwise
  - Look for things that are a greater burden on the applicant than they a time saver to VA employees
  - Look for ways the form could be tweaked to relieve burden from VA employees
    - Write the big ideas down in a [significant decisions document](/assets/design/templates/significant-decisions.md)
  - Are there any work-arounds being employed to process the forms now, that we might be breaking?
- Note confusing form fields
- Identify related and potentially dependent questions
  - Find ways to only expose questions that are relevant

### Who uses the form?

- **Interview stakeholder**: Identify use cases for the form. Who and why.
- **Interview applicants**: Interview form users to identify paint points (Commonly: Which form? What does this question mean? When do I fill out the form? How am I supposed to hear back?)
- **Interview applicants**: Note work arounds that applicants commonly use to complete the form

### Confirm scope

- Use design review process to confirm that functionality identified as out of scope is truly non-critical to the success of the form process.

### How should the form work?

- Create an outline for each required chapter
  - Identify field types
  - Identify conditional questions (only relevant if earlier question has specific answer)
- Create punchlist of copy needs (Many of the field level elements may be straightforward or direct copies from other forms)
  - Look for outdated formats and conventions (Husband and Wife)
- If new interactions are required, note these with development team and work on high fidelity mocks of what this new pattern would look like.
  - Get feedback from wider design team
  - Ask around to make sure new patterns aren’t reinventing the wheel
  - Test new pattern
- Think about entry and exit points for the form
  - Does your form require changes to navigation?
  - Is related static content up to date?
  - Are there any other places you should be able to get to the form from?

### Usability Testing

- Wherever possible, use a live prototype to test the form process with applicants
  - Identify unclear language
  - Check whether new patterns are working
- Iterate
- Test again!