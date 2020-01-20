# Project Feedback

## General Remarks

This was fascinating.  Firstly,, I would describe  this project as a simple UI but with a lot of thought.  In order to score higher in the module, some interactive features would have been desirable.  However, as a static site which worked on desktop and mobile (with quirks) it worked well.

## Accessibility

I am very taken with how you used aria-hidden.  Until I hopened the source code, I didn't even know that those other elements were on screen.  

In terms of the accessibility itself, you have a few issues.  Firstly, you need better markup.  Everything is a paragraph with a different CSS class applied.  In HTML, you need to think about what something is, as well as what it looks like.  So what I would have done is this:

Day: h2.
timeslot h3
lecture/lab/(other) details: list with list items.

This way the screen reader user could jump from h2 to h2 for the days, and h3 to h3 for the slots.  Some colour contrast stuff as well but minor.

## Code quality

This was good, nice use of bootstrap.  Git was used well, and it appeared that people contributed a fair amount.

## Evaluation

### Report

I thought this was good, and using markdown was great.  This will be done for everyone if I'm teaching this next year, so thanks for that.   I would like to have seen more in-depth results analysis, though I take the point about the group not responding.  NO marks deducted fore fewer participants.  Again, Illl note all this for next year.

### Supporting materials

As part of the report you listed questions.  However you failed to submit links to surveys, questinnaires etc.  I also need the responses please.  Ensure that they are added to the repo.  In the event that they are paper-based, please put them in an envelope and leave with the School secretary marked for my attention with "CA357 group 36 project materials".  Please make this a priority as I must have all data associated with a project.  Failure to do this will result in the grade for the evaluation being amended to 0 owing to lack of supporting evidence.