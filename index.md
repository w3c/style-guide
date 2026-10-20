---
title: W3C Style Guide
lang: en
toc: true
stylesheets: 'assets/css/example.css'
note:
  id: beta-note
  title: Style Guide beta version
  content: >-
    This style guide is in beta and is being reviewed and refined. For more
    information, see the [W3C Style Guide ReadMe](https://github.com/w3c/style-guide).
    To suggest improvements or report issues, please
    [create an issue on GitHub](https://github.com/w3c/style-guide/issues).
---

## About this style guide

**Editors:** Tamsin Ewing, W3C; Coralie Mercier, W3C. 
Initial draft: 28 July 2026

This style guide is written for W3C authors and editors. It promotes readability, consistency, and easier translation across all W3C content, including standards-related materials, educational resources, organizational communications, and website content.

This is a living document. For the list of substantive changes, see the Changelog [Link coming].

The guidance is written for **US English**. Translators should follow the conventions of their target language.

Following this guide helps:

- make content easier to read and understand for people with a wide range of English language proficiency
- support translators by using clear, consistent language
- improve consistency across W3C publications
- reduce editorial corrections and reports of avoidable issues

Keep in mind that W3C content serves a global audience and is often used as authoritative reference material. Prioritize clarity, simplicity, and long-term readability. Much of what we publish becomes part of the permanent web record under the [W3C Persistence Policy](https://www.w3.org/policies/uri-persistence/).

To provide feedback on this style guide, please [comment on existing issues or raise a new issue on GitHub](https://github.com/w3c/style-guide/issues/new?template=custom-form.md).

## Structure and presentation

### Structure

#### Logical flow and order

- Present what readers need to know or do first, followed by supporting details and background.
- Make connections between sections clear. For example, use wording that shows how one section builds on, contrasts with, or illustrates another.

#### Using structural elements

- **Headings:**
  - Use headings and subheadings to group related ideas.
  - Write concise, unique headings that clearly describe the content beneath them.
  - Front-load headings with relevant keywords to aid readability.
- **Sentences:**
  - Write simple sentences.
  - Stick to one idea per sentence.
  - Keep the subject and verb close together.
  - Use [punctuation](#punctuation) that helps readers understand how ideas relate to one another.
  - If a sentence becomes complex with more than one dependent clause, consider dividing it into two grammatically complete sentences.

- **Paragraphs:**
  - Keep paragraphs short.
  - Stick to one topic per paragraph.
  - Make sure the paragraph content fits the topic of the heading it sits under.
- **Lists:**
  - Use lists for steps, options, and related items.

### Formatting

#### Bold

Use bold sparingly to highlight important or urgent information, such as names, dates, deadlines, or key actionable points.

Avoid bolding text in whole paragraphs or sections.

#### Italics

Use italics for <b>words or phrases from other languages</b> that are not commonly used in English. For guidance on identifying changes in language and using appropriate HTML markup, see [Using <code>b</code> and <code>i</code> elements](https://www.w3.org/International/questions/qa-b-and-i-tags). 

{% include example.html content="The Japanese aesthetic of <i lang=\"ja-Latn\">wabi-sabi</i> values simplicity." %}

Use italics sparingly to <b>emphasize</b> a word or phrase if it helps make the meaning clearer, especially to show differences between ideas. For guidance on using appropriate HTML markup, see [HTML5: 4.6.2 The em element](https://www.w3.org/TR/2011/WD-html5-author-20110809/the-em-element.html).

{% include example.html content="This policy applies to *new* staff, not existing staff." %}

Avoid italicizing text in whole paragraphs and sections.

## Tone, language and words

### Tone

- Authoritative and factual
- Clear and straightforward
- Inclusive and respectful

### Language

#### Write in plain language

Plain language uses clear wording, structure and design. It helps readers easily:

- **find** information
- **understand** it
- **use** it to complete tasks

##### Techniques for writing in plain language

###### Abbreviations

Provide the full term with the abbreviation on first use. See [Expanding abbreviations](#expanding-abbreviations).

###### Contractions

Use simple positive contractions in informative (non-normative) writing.

{% include example.html label="Examples"
  use="it’s, that's, you’re,  we’ve, they’ll, let's" %}

Positive contractions make text feel more conversational and friendly, and help readers absorb information faster.

Avoid negative contractions in all writing.

{% include example.html label="Examples"
  use="cannot, do not, will not"
  avoid="can’t, don’t, won’t" %}
  
Negative contractions can cause some readers to overlook the apostrophe and interpret a statement as positive.  

###### Personal pronouns

Use “you” and “your” to address the reader.

Use “we” when speaking for an organization (like W3C), but only when it’s clear who “we” refers to.

###### Structure

Break up information into smaller sections to make it easier to read. See [Using structural elements](#using-structural-elements).

###### Verbs

Do not turn actions into nouns. Use verbs instead.

{% include example.html label="Example 1"
  use="We analyzed the results."
  avoid="We conducted an analysis of the results." %}

{% include example.html label="Example 2"
  use="They investigated the issue."
  avoid="They carried out an investigation into the issue." %}

###### Voice

Write in the active voice; that is, the subject performs the action.

Avoid the passive voice where possible.

{% include example.html label="Example"
  use="We’ll provide updated information here when it’s available."
  avoid="Additional information will be provided here when it's available." %}

###### Words

- Use everyday, familiar words.
- Avoid jargon and metaphors.
- Explain specialist terms on first use.
- Remove unnecessary words.

{% include example.html label="Example of unnecessary words"
  use="Write link text that describes where the link goes."
  avoid="**Try to** write link text **so** that **it** **clearly** describes where the link goes." %}

#### Write for a global audience

W3C content is read and translated around the world.

- Use examples that reflect a variety of cultures and regions.
- Avoid culture-specific references.
- Choose internationally understood terms, such as “postal code” instead of “ZIP code”, and “given name” instead of “first name” (and [do not assume everyone has a first and last name, or that a family name comes last](https://www.w3.org/International/questions/qa-personal-names.en.html)).
- Use internationally recognized formats for [dates](#dates), [times](#global-audience), [currencies](#currencies), [measurements](#measurements), [large numbers](#billion), and [phone numbers](#phone-numbers) to avoid ambiguity.

#### Write inclusively

##### Age-inclusive language

Only state or request someone’s age when it’s strictly relevant.

{% include example.html label="Example"
  use="Older people"
  avoid="Older users, old people, the elderly, seniors" %}

##### Disability language

Use respectful, accurate language when referring to disability.

For examples of disability-specific terms, and terminology to avoid, see the [W3C word list](#w3c-word-list).

###### People-first and identity-first language

Use people-first language on first reference, then use a mix of people-first and identity-first language.

People-first language puts the person before the disability.

{% capture body %}
- people with disabilities
- people who are blind
{% endcapture %}
{% include example.html label="Example" content=body %}

Identity-first language puts the disability before the person.

{% capture body %}
- disabled people
- blind people
{% endcapture %}
{% include example.html label="Example" content=body %}


##### Gender-inclusive language

Use gender-neutral language, where possible.

Avoid making assumptions about gender.

{% include example.html label="Example"
  use="“chair”"
  avoid="“chairman”" %}

###### Pronouns: Gender inclusivity and translation considerations

Use pronouns that are **inclusive** and **easy to translate** for W3C's global audience.

**Use a plural noun instead of “he/she” or “his/her”:**

“He/she” and “his/her” unnecessarily limit gender to binary choices.

Use a **plural noun** with “they” or “their”.

Where possible, avoid “he/she” and “his/her”.

{% include example.html label="Example: Using the noun “developer”"
  use="**Developers** should test **their** code before release."
  avoid="A developer should test **his** or **her** code before release." %}

**Repeat the noun instead of using singular “they”:**

Singular “they” can be:

- hard to translate in some languages
- hard to understand for some people
- considered grammatically incorrect by some people

Repeat the noun.

Where possible, avoid singular “they”.

{% include example.html label="Example"
  use="If an author can avoid jargon, **the author** should do so."
  avoid="If an author can avoid jargon, **they** should do so." %}

**Exceptions:** 

Use:

- personal pronouns that real people use for themselves
- pronouns assigned to named personas

##### Race-inclusive language

Terms to avoid and possible alternatives:

- master — use a more precise alternative such as “main”, “primary”, “original”, “source”, or “authoritative”
- whitelist — use “allowlist”
- blacklist — use “denylist”

### Spelling

Use US English.

To check spelling, use the [Merriam-Webster dictionary](https://www.merriam-webster.com/).

### W3C key terms

For correct usage and spelling of key terms, see the [W3C word list](#w3c-word-list).

## Style for different content types (A–⁠Z)

### Abbreviations

#### Expanding abbreviations

Spell out an abbreviation the first time you use it on a page. Put the short form in parentheses afterwards. After that, you can just use the abbreviation.

{% capture body %}
- First use: World Wide Web Consortium (W3C)
- Later use: W3C
{% endcapture %}
{% include example.html label="Example" content=body %}

There are a few ways you can do this. See [techniques for expanding abbreviations](https://www.w3.org/WAI/WCAG22/Techniques/general/G102#related).

**Exception:** If a term is widely known by its abbreviation, you do not need to spell it out.

{% capture body %}
ARIA, CAPTCHA, GIF, HTML, PDF, WiFi
{% endcapture %}
{% include example.html label="Examples" content=body %}

#### Re-expanding abbreviations

**Independent sections:** In sections that may be read independently of the main text, spell out the abbreviation again, followed by the abbreviation in parentheses.

**Change of context:** If an abbreviation could have multiple meanings and the context changes, provide the full meaning to clarify which meaning is intended.

#### Capitalization in expanded terms

Use **title case** for proper names.

{% capture body %}
- Web Content Accessibility Guidelines (WCAG)
- Framework for Accessible Specification of Technologies (FAST) Task Force
{% endcapture %}
{% include example.html label="Examples" content=body %}

Use **lowercase** for common nouns.

{% capture body %}
- real-time communication (RTC)
- augmentative and alternative communication (AAC)
{% endcapture %}
{% include example.html label="Examples" content=body %}

#### Plural acronyms

Form the plural of an acronym by adding a lowercase “s”. Do not use an uppercase “S” or an apostrophe.

{% capture body %}
- Use: PDFs
- Avoid: PDFS, PDF’s
{% endcapture %}
{% include example.html label="Example" content=body %}

#### Abbreviations to avoid

- etc.: Where the text might be used within a legal context, use “**including, but not limited to,**” to introduce a non-exhaustive list of examples.
- e.g.: Use “**for example**”.
- i.e.: Use “**that is**” or “**in other words**”.
- vs.: Use “**versus**”, “**compared with**”, or “**in contrast to**”.

**Exception:**

If space is limited (for example, in a table cell), you may use abbreviations carefully.

Include a comma if it would normally follow the full phrase. 

{% include example.html label="Examples"
  use="“e.g.,” and “i.e.,”"
  avoid="“e.g.” and “i.e.”" %}

### Currencies

Use ISO 4217 currency codes and place the code after the amount.

{% include example.html content="100 USD" %}

**Note:** This guidance is for English-language text. Currency conventions may differ in other languages.

Read more on the <abbr title="International Organization for Standardization">ISO</abbr> website: [ISO 4217 — Currency codes](https://www.iso.org/iso-4217-currency-codes.html).

### Dates

Use the international format to reduce ambiguity for a global audience.

Put the day first using digits, followed by the month written out as a word. **Note:** This is a specific, intentional departure from US practice.

{% include example.html content="1 August 2026 (instead of 8/1/2026)" %}

Do not use letter suffixes after the day.

{% include example.html content="30 April (instead of 30th April)" %}

If numbers only are required, such as in a form, use YYYY-MM-DD.

{% include example.html content="2025-10-21" %}

#### Relative dates and times

Use a specific date, including the year, where appropriate, so the information still makes sense over time.

Avoid relative dates and times, such as tomorrow, last week, or next Thursday, unless the content will be updated promptly.

{% include example.html content="The deadline to complete the course is Friday, 27 November 2026." %}

**Exceptions:** Blog posts and other dated content can use relative dates because readers expect them to reflect when they were published.

### Headings

#### Correct heading hierarchy

Nest headings properly. For example, `<h1>` should not be followed by `<h3>` or lower.

See also the guidance on [how to write good headings](#using-structural-elements).

#### Capitalization in headings

Use sentence case for headings `<h1>` to `<h6>`.

**Exceptions:**

- Capitalize any terms in the heading that are proper names.
- Use title case for the title of a complete, fixed, authoritative work. For details, see [Title case versus sentence case — Naming new documents](#naming-new-documents)

#### Punctuation in headings

Use no punctuation at the end of headings, unless a question mark is required.

### Labels

Use sentence case for labels in user interface elements. Avoid title case. This includes:

- buttons
- links
- menu items
- form labels
- tabs
- navigation items

Capitalize only the first word and any proper names.

{% include example.html label="Examples"
  use="\"Create account\", \"Reset password\"."
  avoid="\"Create Account\", \"Reset Password\"." %}

### Links

#### Link text

Link text should describe the destination.

To write link text for a link that takes the user to a page titled “Our mission”:
{% include example.html label="Example"
  use="“Our mission”"
  avoid="“Click here”, “Learn more”, “Read more”" %}

On a given page, do not use the same link text for links that go to different destinations.

#### In-line links

Place links at the end of sentences, if possible. This helps readers understand the complete thought before deciding whether to follow the link.

{% include example.html label="Example"
  use="For more information, see [Discover W3C groups](https://www.w3.org/groups/)."
  avoid="See [Discover W3C groups](https://www.w3.org/groups/) for more information." %}

#### Links to definitions

When linking to a definition or glossary entry, link only the first occurrence of the term in each distinct section.

Avoid linking every occurrence of the same term within a paragraph or section. Repeated links create visual clutter and make content harder to scan.

#### Links to email addresses

##### Individual email addresses

Use the person's **name** as the link text rather than the email address.

This helps protect the email address from spam.

{% include example.html content="For more information, email [Jane Smith](mailto:jane.smith@example.org)" %}

##### Shared email addresses

Use the **email address** as the link text rather than the name of the group or team.

This helps people identify the destination before activating the link and makes it easier to copy or note the address.

{% include example.html content="For more information, email [support@example.org](mailto:support@example.org)" %}

#### Links to non-HTML documents

Include the **file format** so the user knows what to expect.

{% include example.html label="Example"
  use="To download the full report, see Annual Report 2025 (PDF)."
  avoid="To download the full report, see Annual Report 2025." %}

#### Links to non-public documents

When linking to non-public content, indicate that access is restricted. Use a label such as:

- Password protected
- Member only
- Restricted
- Internal
- Login required

{% include example.html content="Meeting minutes (Password protected)" %}


#### Punctuation in links

Add a full stop after the linked text if it ends a sentence. Do not include the full stop as part of the link.

{% include example.html label="Example"
  use="See [How to join W3C](https://www.w3.org/membership/join/)."
  avoid="See [How to join W3C.](https://www.w3.org/membership/join/)" %}

**Exception:** Never add a full stop after a raw URL.

### Lists

#### Parallel structure

Use the same grammatical structure for each item in a list. For example, if one item starts with a noun, start all the items with a noun.

Avoid mixing different structures in the same list.

{% capture use %}
- Research the audience.
- Design the content.
- Conduct usability testing.
{% endcapture %}

{% capture avoid %}
- Research the audience.
- Content design.
- Testing with users.
{% endcapture %}

{% include example.html label="Example"
  use=use
  avoid=avoid %}

#### Long list items

When some items in a list consist of several sentences, consider if the list structure is particularly useful for conveying the information. If not, use regular paragraphs instead of a list.

#### Capitalization and punctuation in lists

##### Text that introduces a list

End with a **colon**.

{% capture body %}
Web accessibility means that people can:

- perceive, understand, navigate, and interact with the web
- contribute to the web
{% endcapture %}
{% include example.html label="Example" content=body %}

##### List items complete the introductory phrase or sentence in the body text

Treat all the items in the list as a grammatical part of the introductory phrase or sentence.

Start with a **lowercase** letter, even if the list is a numbered list.

End each item with **no punctuation**.

{% capture body %}
To give your day structure, use the 1-3-5 Rule and focus on:

- one big task
- three medium tasks
- five small tasks

To prepare for a productive day:

1. wake up early
2. review goals
3. prioritize the most important tasks
{% endcapture %}
{% include example.html label="Examples" content=body %}

##### List items are complete sentences

**Capitalize** the first letter.

End with a **full stop** or a **question mark**.

{% capture body %}
- In spring I mulch the roses.
- In summer I grow vegetables.
- In autumn I sow and repair the lawn.
{% endcapture %}
{% include example.html label="Example" content=body %}

##### List items are fragments or not complete sentences

Begin each item with a **lowercase** letter (unless the first word is normally capitalized, such as a proper noun).

End each item with **no punctuation**.

{% capture body %}
Shopping list:

- bread
- milk
- eggs

Your application must include the following documents:

- a full résumé
- three letters of recommendation
- two forms of identification
{% endcapture %}
{% include example.html label="Examples" content=body %}

##### List items that are a mix of complete sentences and fragments

If you must mix sentences and fragments, start with a capital letter and end with a full stop or question mark for all items.

### Measurements

When writing for a global audience, provide both metric and imperial units.

{% capture body %}
- The hotel is 6.2 miles (10 km) from the airport.
- The package weighs 22 lb (10 kg).
- The temperature is 68°F (20°C)
{% endcapture %}
{% include example.html label="Examples" content=body %}

### Numbers

#### When to write as digits

##### Ages, measurements, percentages, and ratios

Always use a **digit**.

{% capture body %}
- She is 5 years old.
- They run 3 miles every day.
- He is 6 feet tall.
- We drink 2 liters of water a day.
- I bought 4 pounds of tomatoes.
{% endcapture %}
{% include example.html label="Examples" content=body %}

#### Digits versus words

##### Numbers showing quantity or order

**Numbers up to nine:** Use words.

{% capture body %}
- He invited nine friends.
- She came first.
- It was the ninth time this happened.
{% endcapture %}
{% include example.html label="Examples" content=body %}

**Numbers 10 and above:** Use digits.

{% capture body %}
- They bought 10 plants.
- I was 12th in the queue.
{% endcapture %}
{% include example.html label="Examples" content=body %}

**Exceptions:**

Use words for very large, rounded numbers.

{% capture body %}
1 million, 2.2 billion, 3.5 trillion
{% endcapture %}
{% include example.html label="Examples" content=body %}

For more exceptions, see [Ages, measurements, percentages, and ratios](#ages-measurements-percentages-and-ratios).

**Numbers billion and above**

When using billion and larger-number terms, their meaning can vary between languages and numbering conventions. For example, depending on the numbering convention, one billion can mean one thousand million or one million million.

Always clarify billion and larger-number terms in words.

{% capture body %}
1 billion (one thousand million)
{% endcapture %}
{% include example.html label="Example" content=body %}

##### Start of a sentence

When starting a sentence with a digit, use words or reword.

{% capture use %}
- Ten of the 25 participants had issues completing the task.
- Of the 25 participants, 10 had issues completing the task.
{% endcapture %}
{% include example.html label="Example"
  use=use
  avoid="10 of the 25 participants had issues completing the task." %}

##### Related numbers

With *related* numbers, where one number is usually written in digits and the other not, use **digits** for both.

{% include example.html content="We bought 1 bag containing 500 seeds." %}

##### Adjacent numbers

With *adjacent* numbers that express different categories of numbers, use a **mixture of words and digits**.

{% include example.html content="The cook needs twelve 2-pound bags of flour." %}

##### Phone numbers

Include the country calling code and, where applicable, the area code.

{% include example.html label="Example"
  use="+1 212 555 1234"
  avoid="(212) 555-1234" %}

#### Punctuation in numbers

Use commas as thousands separators in numbers that express a quantity.

{% capture body %}
More than 1,000 users participated in the study.
{% endcapture %}
{% include example.html label="Example" content=body %}

Do not use thousand separators in numbers that identify or label something, such as a year, address, page number, code line number, or issue number.

{% capture body %}
- year 2026
- page 1234
{% endcapture %}
{% include example.html label="Examples" content=body %}

Use a period as the decimal separator.

{% capture body %}
The account balance is 1,000,500.50 USD.
{% endcapture %}
{% include example.html label="Example" content=body %}

### Symbols

Except where there is a lack of space (for example, in a table or chart), use words for the following symbols:

- **Ampersand:**
  - &: Use “**and**” instead.
- **Number sign:**
  - #: Use “**number**” or a suitable noun instead.

{% capture body %}
- Number 3 is correct.
- Statement 2 is true.
{% endcapture %}
{% include example.html label="Examples" content=body %}

### Times

Use the 24-hour clock.

#### Global audience

**One-time events:** Give the time in UTC (Coordinated Universal Time).

{% include example.html content="10:00 UTC" %}

**Recurring events:** Give the time in UTC *unless* the event needs to remain at a fixed local time where daylight saving time applies. In that case, use the local time and explicitly identify the time zone. The equivalent UTC time changes when daylight saving time starts or ends.

{% include example.html content="Every Tuesday at 10:00 Casablanca time (Africa/Casablanca)." %}

#### Local audience

For an audience in a particular location, use the local time zone.

{% include example.html content="15:00 CEST" %}

#### Time ranges

For time ranges **in a sentence**, do not use an en dash. Use words instead, such as “from … to” or “between … and”.

{% capture body %}
- The meeting is from 09:00 to 10:30.
- They agreed to meet between 13:00 and 15:00.
{% endcapture %}
{% include example.html label="Examples" content=body %}

### Titles

#### Published documents

When referring to the title of a published document, follow the title exactly as it appears and preserve its capitalization, whether it uses title case or sentence case.

If the title uses sentence case and is not linked, enclose it in double quotation marks to distinguish it from the surrounding text.

#### Naming new documents

##### Title case

Use **title case** for the title of a complete, fixed, authoritative work, such as a specification, standard, or policy.

These documents typically have the following characteristics:

- complete works
- formally published and version-controlled
- authoritative, citable documents

{% capture body %}
- Web Content Accessibility Guidelines (WCAG)
- W3C Process Document
- War and Peace
- The Chicago Manual of Style
{% endcapture %}
{% include example.html label="Examples" content=body %}

**Note:** When using title case, keep titles as short as practical to improve readability.

##### Sentence case

Use **sentence case** for the title of any document that is ***not*** a complete, fixed, authoritative  work, unless the title includes a proper name.

These documents typically have the following characteristics:

- form part of a larger work, such as a chapter, module, or technique
- describe the information people can find in the document

{% capture body %}
- Contact us
- Register for TPAC 2026
- Accessibility requirements for media players
- ARIA1: Using the `aria-describedby` property to provide a descriptive label for user interface controls (one technique within the Techniques for WCAG 2.2 collection)
{% endcapture %}
{% include example.html label="Examples" content=body %}

See related guidance on [Capitalization in headings](#capitalization-in-headings).

## Grammar

### Capitalization

#### Abbreviations

See [Capitalization in abbreviations](#capitalization-in-expanded-terms).

#### All caps

Avoid using all capital letters for words (except acronyms).

#### Glossaries

Use lowercase for glossary terms (except for proper names).

{% capture body %}
browser
: A web client that allows a human to read information on the web

information space
: The abstract concept of everything accessible using networks: the web

W3C Recommendation
: A technical specification that has been endorsed by W3C and its members — similar to what other standards organizations would call a "standard"
{% endcapture %}
{% include example.html label="Examples" content=body %}

#### Headings

See [Capitalization in headings](#capitalization-in-headings).

#### Lists

See [Capitalization and punctuation in lists](#capitalization-and-punctuation-in-lists).

#### Official names versus common terms

Capitalize terms when they form part of an official name.

Use the full official name where practical to reduce ambiguity.

Use lowercase for common terms.

When you remove part of an official name, it's no longer an official name and becomes a common term.

| Example official name | Common term |
| ------- | ------ |
| W3C Advisory Committee | advisory committee |
| W3C Code of Conduct | code of conduct |
| WAI Interest Group | interest group |
| W3C Member | member |
| W3C Participant | participant |
| W3C Patent Policy | patent policy |
| W3C Process Document | process document |
| W3C Recommendation | recommendation |
| W3C Staff Contact | staff contact |
| W3C Statement | statement |
| COGA Task Force | task force |
| ARIA Working Group | working group |
| W3C Workshop | workshop |

##### Shortening official names

After using the full official name on first reference, you can omit part of the name and retain capitalization if the shortened name remains unambiguous.

If the shortened name could refer to more than one type of entity, use the full official name.

{% capture body %}
- “W3C Advisory Committee” can be shortened to “Advisory Committee” because W3C has only one advisory committee.
- “W3C Member” should not be shortened to “Member” because W3C has members of different bodies, including the W3C Board of Directors, the Technical Architecture Group, and various committees.
{% endcapture %}
{% include example.html label="Examples" content=body %}

##### Plural forms

When you pluralize an official name, it usually becomes a common term. 

Use lowercase for common terms.

{% capture body %}
- The organization joined as a **W3C Member** to work with us.
- Organizations of all sizes and all types are **W3C members**.
- We have published a new **W3C Recommendation**.
- We have published several **W3C recommendations**.
- WCAG 2.2 includes **Success Criterion 2.5.8 Target Size (Minimum)**.
- WCAG 2.2 contains 86 **success criteria.**
- The **Accessibility Guidelines Working Group** is discussing the issue.
- There are currently 47 open **working groups**.
{% endcapture %}
{% include example.html label="Examples" content=body %}

### Punctuation

Punctuation helps to separate ideas, signal relationships between ideas or emphasize ideas.

Each punctuation type has a different purpose.

#### Brackets

##### Parentheses

Known as "round brackets" in some areas.

Use parentheses sparingly within a simple sentence in the following scenarios:

**Scenario 1:** Provide the abbreviation for a term

{% include example.html content="Internet of Things (IoT)" %}

**Scenario 2:** Clarify something in a short aside

{% include example.html content="Captions (called “subtitles” in some areas) provide content to people who are deaf and hard-of-hearing." %}

**Scenario 3:** Signal an optional plural

{% include example.html content="Test(s)" %}

##### Square brackets

Use square brackets in quotations to show you have altered or added something to the original quoted material.

**Scenario 1:** Insert an explanation in a direct quotation

{% include example.html content="The council approved the project after reviewing the trial results [from an earlier study]." %}

**Scenario 2:** Indicate something that’s been incorrectly written in a direct quotation

{% include example.html content="The letter states, “The committee beleives [sic] the proposal will succeed." %}

**Scenario 3:** Add some text within a direct quotation in order to clarify something

{% include example.html content="The report says the system must be updated because “it [the software] is outdated." %}

**Scenario 4:** Modify a direct quotation so that it fits grammatically within the surrounding text

{% include example.html content="The policy explains that “[t]he system must be reviewed every year." %}

#### Colons and semicolons

##### Colons

Use a colon to introduce the main idea(s). It gives the sense of “as follows.”

**In paragraph text:**

- A complete sentence must precede a colon.
- Use **lowercase** for the word following a colon.

{% include example.html content="They had one goal: to finish the marathon." %}

**In titles or labels:**

- A colon may separate a category label from a title or description.
- Use **uppercase** for the word following a colon.

{% capture body %}
- Group Note: Use of Large Language Models in standards work
- Chapter 3: Accessible forms
- Figure 2: User journey
- Contact us: Email support@example.com.
{% endcapture %}
{% include example.html label="Examples" content=body %}

##### Semicolons

Use a semicolon in the following scenarios:

**Scenario 1:**  Use a semicolon to combine two related ideas in a simple sentence. The text before and the text after the semicolon should both be grammatically complete sentences.

{% capture body %}
- The rule is simple; applying it consistently is harder.
- The first draft focused on accuracy; the second focused on readability.
{% endcapture %}
{% include example.html label="Examples" content=body %}

**Scenario 2:** Use a semicolon to break up complex lists in a sentence or bulleted item that contains internal commas.

{% include example.html content="The conference has attendees from Seattle, Washington; New Delhi, India; and Nairobi, Kenya." %}

#### Commas

In a phrase listing three or more items, place a comma before the final conjunction (this is commonly referred to as an "Oxford comma").

{% include example.html content="I bought apples, oranges, and bananas." %}

#### Dashes and hyphens

##### Em dash (—) {#em-dash}

Put a space before and after an em dash.

The part after the dash does not have to be a complete sentence.

Use an em dash to add clarification, explanation, or emphasis after a complete clause.

**Scenario 1:** Add clarification

{% include example.html content="WCAG 3 will have a different structure, different conformance model, and broader scope — see WCAG 3 Introduction." %}

**Scenario 2:** Add explanation

{% include example.html content="The letter states, “Write in the active voice — that is, the subject performs the action." %}

**Scenario 3:** Add emphasis

{% include example.html content="Our mission is to make the web work — for everyone." %}

**Note:** If combining related ideas with an em dash makes a sentence long or complicated, it is usually better to split it into two sentences.

###### Em dashes in list items

Use an em dash in a list item to separate a short term or phrase from its explanation or a clarification.

{% capture body %}
Common roles include:

- **author** — writes the content
- **editor** — reviews the content before publication
- **translator** — translates the content into another language
{% endcapture %}
{% include example.html label="Example" content=body %}

##### En dash (–) {#en-dash}

Use an en dash to indicate a range in numbers, such as in dates, pages, and sports results.

Do not add a space before and after an en dash.

{% capture body %}
- The years 1990–2000 were transformative.
- Read pages 10–15.
- They won 106–76.
{% endcapture %}
{% include example.html label="Examples" content=body %}

##### Hyphen (-)

Use a hyphen to join compound adjectives.

{% capture body %}
- peer-to-peer connection
- well-known technique
{% endcapture %}
{% include example.html label="Examples" content=body %}

**Note:** Be aware that a hyphen can change the meaning of a phrase:

- “small-business owner” versus “small business owner” (an owner of a small business or a business owner who is small?)
- “little-used car” versus “little used car” (a car that has been used very little, or a used car that is small?)

Do *not* hyphenate:

- an adverb that ends in “ly”
- an adverb that follows a noun

{% capture body %}
- They are two **closely related** concepts.
- The technique is **well known**.
{% endcapture %}
{% include example.html label="Examples" content=body %}

Use a hanging hyphen when two compound adjectives modify the same noun.

{% include example.html content="The pre**-** and post**-**deployment stages are equally important." %}

For guidance on terms we no longer hyphenate and now write as one word, see the [W3C word list](#w3c-word-list).

#### Ellipsis (...)

Add a space before and after an ellipsis.

Use an ellipsis to show:

- missing words
- a pause
- something left unsaid

{% include example.html content="I was wondering … but it’s probably not important." %}

#### Headings

See [Punctuation in headings](#punctuation-in-headings).

#### Links

See [Punctuation in links](#punctuation-in-links).

#### Lists

See [Punctuation in lists](#capitalization-and-punctuation-in-lists).

#### Numbers

See [Punctuation in numbers](#punctuation-in-numbers).

#### Quotation marks

##### Double quotation marks

Use double quotation marks to reference a term.

{% include example.html content="This accessibility requirement is sometimes called “sufficient color contrast”; however, the technical term is “luminosity contrast.”" %}

##### Single quotation marks

Use single quotation marks for a quotation inside a quotation.

**Note:** With nested quotes, the full stop remains inside both the single and double quotation marks.

{% include example.html content="Maria said, ”The reviewer described the proposal as 'well structured and easy to follow.'”" %}

##### Scare quotes

Avoid using quotes in a way that could be taken to suggest irony or in a non-standard way. For more information, see [Scare quotes](https://en.wikipedia.org/wiki/Scare_quotes).

#### Slashes

##### Forward slash

Generally, use a forward slash only in dates, fractions, and URLs.

Avoid using a forward slash as a substitute for words whenever possible.

For two things that have a close relationship, use words like “and” or “or” instead.

**Scenario 1:** Equal relationship

{% include example.html label="Example"
  use="The project examines cause-**and**-effect relationships."
  avoid="The project examines cause/effect relationships." %}

**Scenario 2:** Either or both

{% include example.html label="Example"
  use="Add a potato, **or** an onion, **or both**."
  avoid="Add a potato and/or an onion." %}

**Scenario 3:** Alternative

{% include example.html label="Example"
  use="If **or** when I have a dog, I’ll need a fenced yard."
  avoid="If/when I have a dog, I’ll need a fenced yard." %}

**Exception:** You may use a forward slash to show an alternative if it's clearer than using words.

{% include example.html label="Example"
  use="In inclusive writing, avoid gender pronouns (she/her, he/his)."
  avoid="In inclusive writing, avoid gender pronouns (she or her or he or his)." %}

### That versus which

**That:** Introduces essential information needed to understand the sentence.

{% include example.html content="The time is essential to identify specific meetings: “The meeting that starts at 10:00 is online. The other meetings are in-person.”" %}

**Which:** Introduces extra information that is not essential.

{% include example.html content="The time is not essential: “The meeting, which starts at 10:00, is online.”" %}

### Verb agreement with collective nouns

Use a singular verb with collective nouns when referring to the group as a single entity.

{% include example.html label="Example 1"
  use="The working group has published a draft."
  avoid="The working group have published a draft." %}
  
{% include example.html label="Example 2"
  use="Web Content Accessibility Guidelines (WCAG) is published by W3C."
  avoid="Web Content Accessibility Guidelines (WCAG) are published by W3C." %}

**Exceptions:**

Use a plural verb if members act independently.

{% include example.html content="The staff have handed in their separate reports." %}

The collective noun, “people“, always takes a plural verb.

{% include example.html content="The people are waiting." %}

## W3C word list

This alphabetical list provides guidance on how to write terms commonly used in W3C work, as well as on words and phrases to avoid or use only in specific contexts.

accessible
: Use **"accessible"** only when referring to accessibility for people with disabilities, or to places that disabled people can easily reach or enter. Do not use it to mean "convenient", "available", or "easy to use". For example, avoid: “The gardens are accessible to the public.” Instead, use: “The gardens are open to the public.”

abort <span class="tag">Avoid</span>
: Use **"cancel"**.

anti-alias
: Hyphenate.

ASCII
: Use all caps.

autistic
: Use “autistic people”, not “people with autism”.

back end, back-end
: Use **"back end"** as a noun: “Data is processed by the back end.” Use **back-end** as an adjective: “We rely on a back-end server.” See [Hyphen](#hyphen--).

base64
: Lowercase and write as one word.

Bézier
: Capitalize and include the accent on the first "e".

blacklist <span class="tag">Avoid</span>
: Use **"denylist"**. See [Race-inclusive language](#race-inclusive-language).

braille
: Lowercase, unless referring to Louis Braille.

built-in
: Hyphenate when used as an adjective or noun. Do not hyphenate when "built" is a verb. See [Hyphen](#hyphen--).

checkbox
: Write as one word.

click (versus select)
: Use **"click"** when instructing a user to activate an interactive element, such as a button or link. For example, avoid “Select the Submit button.” Instead use: “Click the Submit button.”

color blind
: When referring to people, use “people who cannot distinguish between certain colors (often called ‘color blindness’).” When referring to the medical condition, use **"color vision deficiency"**. See [Disability language](#disability-language).

color space
: Write as two words.

data
: Treat as singular. Write “The data is transferred,” not “The data are transferred.” See [Verb agreement with collective nouns](#verb-agreement-with-collective-nouns).

dingbat
: Write as one word.

DTDs
: Do not use an apostrophe. See [Plural acronyms](#plural-acronyms).

ECMAScript
: Write as one word and capitalize the "S".

email
: Write as one word. Do not hyphenate.

end user
: Write as two words.

et al.
: Do not place a full stop after "et".

filename
: Write as one word.

for instance <span class="tag">Avoid</span>
: Use **"for example"**. See [Words](#words) in plain language.

front end, front-end
: Use **front end** as a noun. Use **front-end** as an adjective. See [Hyphen](#hyphen--).

full stop (.)
: Use **full stop** as the formal name.

grandfather <span class="tag">Avoid</span>
: When referring to existing code, systems, or practices that continue under earlier requirements, use "**legacy**", "**exempt**", or another precise alternative. The metaphorical use originates from discriminatory US voting laws. See [Race-inclusive language](#race-inclusive-language).

hand-eye coordination
: Use **"hand-eye coordination"**, not "eye-hand coordination".

hard-coded
: Hyphenate.

hash (#)
: Also called a **number sign**. Usually avoid "pound sign", "crosshatch", and "octothorpe".

header
: Use **header** for table headers and HTTP headers.

heading
: Use **heading** for headings marked up with `<h1>` through `<h6>`.

hearing-impaired, hearing impairment
: When referring to people, use **"deaf"** with a lowercase "d", unless a person or community prefers another term. See [Disability language](#disability-language).

homepage, home page
: One word preferred, both allowed.

hostname
: Write as one word.

HTTP/1.0, HTTP/3
: Use the slash when referring to the protocol name. Omit it only where established usage in running text requires a different form.

internet
: Lowercase.

italics
: Use the plural form.

its, it’s
: Use **"its"** as the possessive form. Use **"it’s"** as the contraction of "it is" or "it has". For example, “It’s a dog wagging its tail. It’s happy to see its owner.”

Java
: Capitalize the "J".

JavaScript
: Capitalize the "J" and the "S".

Level 1, Level 2, Level 3
: Capitalize **"Level"** when referring to a level in a W3C technical report.

line feed
: Write as two words.

log in, login
: Use **"log in"** as a verb. Use **"login"** as a noun or adjective.

loss
: When referring to disabilities, avoid as a general description that includes congenital conditions. You can use it when describing a change, such as “As we age, we may experience hearing loss.” See [Disability language](#disability-language).

lowercase
: Write as one word.

markup
: Write as one word. Do not hyphenate.

master
: Use "master" when referring to expertise or mastering a skill. Where possible, avoid "master" when another word more precisely describes the intended meaning. For example, avoid "master branch", "master switch" (use **main** instead); "master copy", "master spreadsheet" (use **original**, **source**, or **authoritative**, depending on the meaning); "master bedroom" (use **primary** instead); "the dog's master" (use **owner** instead). For related guidance, see [Race-inclusive language](#race-inclusive-language).

metadata
: Write as one word. Do not hyphenate.

million
: Do not abbreviate within a sentence. Use a capital **"M"** for "mega" only with care and where the meaning is clear.

MIME type
: Prefer **"Internet media type"**. If using **"MIME type"**, write it as two words and use all caps for **"MIME"**.

mouse click
: Write as two words. Check whether you mean a mouse click specifically or any form of activation, including a finger tap or key press.

mouse pad
: Write as two words.

namespace
: Lowercase, unless referring to the "Namespaces in XML" specification by name.

number sign (#)
: Also called a **hash**. Usually avoid "pound sign", "crosshatch", and "octothorpe".

nobody
: Write as one word.

no one
: Write as two words.

offline
: Write as one word. Do not hyphenate.

online
: Write as one word. Do not hyphenate.

onscreen
: Write as one word when used as an adjective.

pathname
: Write as one word.

PDF
: Use all caps. It does not need to be expanded on first use. See similar exceptions in [Expanding abbreviations](#expanding-abbreviations).

persons <span class="tag">Avoid</span>
: Use **"people"**.

please
: Usually omit in informational content and instructions when it's an unnecessary word. See [Words](#words).

plug-in
: Hyphenate.

read-only
: Hyphenate.

real-time communication
: Lowercase, including when used with the acronym: **real-time communication (RTC)**. Capitalize only when part of a proper name.

refer to
: Use **"see"** where possible. See [Words](#words).

ruby
: Lowercase for the typographic convention. Capitalize for the Ruby programming language.

sanity <span class="tag">Avoid</span>
: In phrases such as "sanity check", use a more precise term, such as **"coherence"**, **"confidence check"**, or **"validation"**. See [Disability language](#disability-language).

schema
: Lowercase, unless part of a proper name.

schemas
: Prefer **"schemas"** to "schemata".

select (versus click)
: Use **"select"** when choosing from a set of options. For example, “Select an option from the dropdown menu.”

semicolon
: Write as one word.

slave <span class="tag">Avoid</span>
: Use a context-specific alternative, such as **"replica"**. See [Race-inclusive language](#race-inclusive-language).

speech recognition
: Use for technology that converts spoken words into text for speech-to-text transcription, virtual assistants, and other speech user interfaces.

standalone, stand-alone
: One word preferred, both allowed.

style sheet
: Write as two words, except in the official name, Extensible Stylesheet Language.

subset
: Write as one word. Do not hyphenate.

superset
: Write as one word. Do not hyphenate.

timestamp
: Write as one word.

time zone
: Write as two words.

touchscreen
: Write as one word.

uppercase
: Write as one word.

URI reference
: Usually write **"URI reference"**, not "URI Reference" or "URI-Reference".

URIs
: Do not use an apostrophe. See [Plural acronyms](#plural-acronyms).

usable
: Use **"usable"**, not "useable".

user agent
: Lowercase, unless part of a proper name.

user interface
: Lowercase, unless part of a proper name.

visually impaired
: When referring to people, use **"blind"** or a more specific term that reflects the person or group being described. See [Disability language](#disability-language).

voice recognition
: Use for technology that identifies who is speaking by analyzing vocal characteristics, such as voice biometrics used for authentication.

W3C
: Use "W3C", not "**the** W3C". For example, "There are more than 50 staff at W3C". But it's okay to say "the World Wide Web Consortium".

W3C Note
: Use **"W3C Note"**, not "W3C NOTE".

web
: Lowercase, except when referring to the invention, as in “Sir Tim Berners-Lee invented the Web,” or when it is part of a proper name, such as "World Wide Web Consortium" or a job title such as “Senior Web Developer.”

web page
: Write as two words.

webmaster
: Write as one word.

website
: Write as one word.

white space
: Write as two words when used as a noun.

whitelist <span class="tag">Avoid</span>
: Use **"allowlist"**. See [Race-inclusive language](#race-inclusive-language).

World Wide Web
: Write as three words. Do not hyphenate.

worldwide
: Write as one word.

zeros
: Use **"zeros"**, not "zeroes".

## Acknowledgments

Thank you to Tamsin Ewing, W3C Senior Accessibility Content Specialist, and Coralie Mercier, W3C Director of Marketing and Communications, who authored this guide in July 2026.

We are also grateful to contributors who have improved the guidance [List to be added as part of the GitHub issue triage and disposition]
