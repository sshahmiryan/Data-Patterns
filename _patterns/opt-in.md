---
layout: default
name: Opt-in to give consent
short-description: Notifying the user of data collection and asking them to opt-in to give consent.
lang-link: opt-in-fr.html
lang: en
status: in development
date-modified: 2021-07-15
---

<!-- IMPORTANT - Create a duplicate page for the french translation! -->

## {{ page.name }}

<section class="alert alert-info">
    <p>This pattern is currently <strong>{{ page.status }}</strong>.</p>
</section>

{{ page.short-description }}

We have a responsibility to ask users for consent when we want to collect, store, or use their data, especially personal information.
This pattern asks the user to read a summarized privacy notice and confirm that they clearly understand and freely agree to how their data will be collected and used.

### When to use this pattern

* When privacy notices (statements, terms of use, etc.) are required. For example, when signing up for a new service or storing data in cookies.
* To meet legal obligations by recording when and how consent is given, including which version of a privacy notice the user agreed to.
* When the user understands from the notice what data is collected, where it is stored, what it is used for, and for how long.
* When the user is able to opt-out, correct, or delete their data at any time.

### When not to use this pattern

* When the type of data is collected, where it is stored, what it is used for, and for how long, is unspecified or will change often.
* When the user isn't able to see or access the other data that organization collects and its purposes or uses.
* When there isn't a clear process for the user to opt-out, correct, or delete their data at any time.

### How it works

Whenever collecting a user's data, make sure that the following things are present, **easy to find, read, and use**.

* A summarized privacy statement highlighting the type(s) of data collection, storage, and use, with links to the full statement.
* A summary of the type of data being collected, describing how it will be used.
* A short description of how to "opt-out" later.
* Ensuring the user takes an affirmative action to opt-in (i.e. a checkbox is not pre-selected).

### Research and impacts

Coming soon

### Examples

#### Collecting users' demographic data for research on Canada.ca

When collecting users' demographic data for research on Canada.ca, the following are the key elements that should be included on the same page as the form collecting the data.

> **Privacy policy**
>
> Your information will not be used for any decision-making process that affects your access to Government of Canada services.
> Your personal information will not be used for any administrative purposes.
>
> Your participation is completely voluntary.
> You can withdraw your participation and personal information from our list at any time with no impact on your access to government services or benefits.
>
> Your personal information and feedback is confidential.
>
> Your information will be used by Employment and Social Development Canada for policy analysis, research, and evaluation purposes.
>
> **What we will collect**
>
> We need the following information so we can contact you:
>
> * Email address
> * Year of birth
> * Language preference
>
> You can also choose to share more information with us so we can invite you to research and testing opportunities based on your life experiences:
>
> * Province or territory
> * Gender identity
> * Indigenous identity
> * Disabilities
> * Visible Minority group
> * Income range
>
> We collect this information to ensure our research groups are diverse, and to identify trends in feedback for specific groups.
>
> [Read the full privacy policy.](https://www.canada.ca/en/transparency/privacy.html)
>
> **How to unsubscribe from research invites**
>
> If you have previously signed up to become a participant and no longer wish to be contacted for future research studies, you can [unsubscribe](#unsubscribe) yourself from the participant list and we will remove your personal information.
>
> _Put your form here._
>
> <div class="checkbox">
> <input type="checkbox" id="consent" name="consent" value="consent">
> <label for="consent" class="required"><strong>I have read, understood and agree to the above.
    I affirm that I am 18 years old, or older.
    I understand that I can withdraw from this participant pool, or any research study at any time without consequence.</strong></label>
> </div>

### Related patterns and components

* [Privacy Disclaimer (Canada.ca Design System)](https://design.canada.ca/common-design-patterns/privacy-disclaimer.html)
* [Privacy Statements Generator (Canadian Digital Service)](https://privacy-statements.cds.alpha.canada.ca/en/)

#### Recent changes

* 13/07/2021 - Started development