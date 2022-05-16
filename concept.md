# NOVEATE: Problem framing & strategy

### Create an amazing open source, no-frills, distraction-free writing experience for long-form fiction authors while simultaneously incorporating planning tools that enhance productivity.

## Writing a book is hard

* Planning, writing, editing, formatting, and publishing a book (let alone a whole series) is a massive undertaking.
* On top of the actual work of writing and creating, there is the “business” side of the whole process as well. This is also applicable to authors who are traditionally published.
    * Marketing and ad buys plus management and strategy thereof
    * Social media content and reader interaction
    * Book blurbs and SEO
    * ARCs, street teams, alpha/beta readers
    * Website management including content management of blog (if applicable)

**How might we** create an environment for writing that elevates the most important part—the writing—while also helping to take care of all of the other stuff?

**How might we** manage non-writing features so that they integrate seamlessly within the process and do not overwhelm or overly complicate the interface and experience?

**How might we** leverage existing software to increase the accessibility and inclusivity of Noveate?

**Who are we?** Open source volunteers.


## Key user outcomes [MVP]



1. Authors can plan (world build) as much or as little as their process requires—the system works with them instead of dictating what they can and cannot do.
2. Authors can expect their plans to seamlessly integrate with the text editor to provide relevant references while writing.
3. Authors can edit their work while trusting that all of their work is backed up, with complete revision history.
4. Authors can export their work with a click of a button, automatically formatting their work for electronic and print publishing without having to hire a typesetter, try to do it themselves in programs like InDesign, or pay for expensive software like Vellum.


### Minimum Viable Product



* World building
    * Characters
    * Worlds/Locations
    * Custom (e.g., magic systems) → Revisit later
* Plot planning (drill down/bubble up)
    * Series
    * Individual books
    * Chapters
    * Scenes
    * Beats
* Writing
    * Markdown text editor with extremely limited formatting options
    * Custom formatting options for:
        * Splitting chapters, scenes, beats
        * Mark characters
        * Mark worlds/locations
        * Mark custom → Revisit later
* Editing
    * Version control/revision history
    * Backups
    * Commenting
* Formatting/publishing
    * ePub in single style
    * PDF in single style
        * Pagination
        * Orphans/widows
    * Front matter and back matter templates
* Auto-save for everything 
* Done through browser
* Word count
* Self-hosted/Locally hosted
* International support/accessibility i18n
* Multiple pen name management
* Text-to-speech integration


### Assumptions

* Assumed amount of output/data to manage
    * Number of series will be small (~10)
    * Number of novels will be small (~50)
    * Number of chapters will be large (~500)
    * Number of scenes will be large (~1,500)
    * Number of beats will be extremely large (~15,000)


## Provisional notes on users


### Pantser ⟷ Plotter continuum



#### Pantser
> A pantser is a colloquial term assigned to authors who do not plan before writing; “fly by the seat of their pants”. Also referred to as discovery writing. \
_Example: Steven King_

#### Plotter
> A plotter is an author who pre-plans their work prior to writing. Also referred to as an outliner or planner. \
_Example: Brandon Sanderson_

Very few authors will exist on the extremes of the continuum. However, Noveate must cater to both ends of the spectrum. 

Authors’ processes evolve over time, including how they approach planning (or lack thereof) of their work. Noveate should not inhibit this kind of self-exploration.


### User types



* Traditional published authors
* Indie/self-published authors
    * Prolific vs. curated
    * Examine potential differences based on genre
* Future types
    * Educators
    * Editors
    * Graphic designers
    * Virtual assistants
    * Beta readers/street teams
    * Fans


## Deliverables



* Personas
* User stories for MVP
* Competitive analysis—will need to look at all-purpose apps similar to this as well as apps that only focus on one specific element.
* User flows
* Information architecture
* Low fidelity wireframes
* High fidelity prototypes


## Roadmap

In no particular order— 




* Analytics
    * Productivity statistics
        * Word count dynamically displayed while writing
            * Broken down by series, novel, chapter, scene
        * Most productive time periods
        * Self-editing tracker (how many words deleted during a session)
        * Daily, weekly, monthly, yearly reports
        * Fastest, slowest scene/chapters written
    * Sales sync across all channels
        * Sales, returns, market statistics
        * Comparative sale charts of all published units
        * Track impact of marketing/ad-buys
* Calendar/Time management
    * Automatically sync with calendars
        * Apple
        * Google
        * Microsoft
        * Others?
    * Time to complete estimator
        * Automatically generate due dates based on prior behavior
        * Update based on progress
            * Re-calculate due dates based on progress and draft states
            * Avoid due dates that expire and then haunt and taunt
            * Re-calculate due dates if author writes out of order
        * Visual progress tracker
    * Manual time to complete estimation
        * Manually input due dates that sync in calendar
        * Drag and drop references to series, novels, chapters, scenes
            * Visual hierarchy necessary
                * Some authors write multiple books at the same time across different series
                * Grabbed from book planner
            * Differentiate between draft states
* Formatting styles
    * Customized look of ePubs and PDFs
    * More options for ePub and PDF styles
* Collaboration tools
    * Group management
        * Rights protection user flow
            * Copyright protection for authors who may be booted out of a group or for authors who leave a group
        * Group projects (e.g., multiverse, anthologies)
        * Writing partners
    * Editing
        * Comment mode, suggestion mode for editors
        * Have conversations with editor; accept/deny edits
        * Developmental, substantive, copy/line, proofreading
        * ARCs, Beta readers
* Online hosted (ew SaaS)
    * Automatically sync with offline or self-hosted
    * Account authentication
* Social integration ( → don’t try to compete with Goodreads)
    * Follow authors
    * Create reading lists
    * Author’s bookshelf
    * Author’s social media


## Reminders & Thoughts



1. Onboarding: Avoid guided pop-up tour and focus more on surfacing relevant articles and video tutorials from the documentation
    1. Documentation
        1. Quick start guide
        2. In-depth written walk-through
        3. Short videos (with closed captioning)
            1. Links to the videos will be embedded contextually
2. Similar concept to a static page generator
3. Self-hosting—contained ecosystem that doesn’t require any technical knowledge to use... inspiration TiddlyWiki
