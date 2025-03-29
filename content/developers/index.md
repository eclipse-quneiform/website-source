---
title: "Developers"
date: 2025-03-08
hide_page_title: true
hide_sidebar: true
hide_breadcrumb: false
show_featured_story: false
show_featured_footer: false
---

{{< hero-image image="carousel/marc-olivier-jodoin-NqOInJ-ttqM-unsplash.jpg" label="Developers" >}}

### Features for Developers

*Eclipse Quneiform*&reg; provides numerous tools for analyzing your project at every stage of internationalization.
At the initial stage, *Quneiform* will analyze your source code to uncover various problems.
This can include issues such as function misuse, strings not exposed for translation, etc.

At the next stage of i18n, resource catalogs can be analyzed to find issues with the translatable content.
Issues here can include confusing messages, concatenated string, and strings that probably shouldn’t be in the resources.

Once your resource catalogs are ready, *Quneiform* can pseudo-translate them for integration testing.
During pseudo-translation testing, display issues, missing content, and even program instability can be uncovered.
By performing these tests, your product will be l10n ready before translator hand-off, saving both time and money.

{{< left-image-card
    lightbox-id="source-code-img" lightbox-caption="Source code options"
    headline="Source code analysis" content="Detect bad practices that can lead to truncated content, display issues, and program crashes."
    image="../images/main-window.png" >}}

{{< left-image-card
    lightbox-id="modern-img" lightbox-caption="Modernize options"
    headline="Modernize your application"
    content="Find and upgrade legacy issues in your code base and resources, such as the use of TCHAR functions or half-width Kanas."
    image="../images/main-window.png" >}}

{{< left-image-card
    lightbox-id="resource-img" lightbox-caption="Resource options"
    headline="Proactive resource analysis" content="Detect resources not available for translation, confusing messages, and l10n-unfriendly strings prior to translator hand-off."
    image="../images/options-dialog-source.png" >}}

{{< left-image-card
    lightbox-id="pseudo-img" lightbox-caption="Pseudo-translation options"
    headline="Pseudo-translation testing" content="Pseudo-translate resources to perform integration testing before translation even begins. Numerous options are available for pseudo-translations, such as:<ul><li>multiple replacement character sets to choose from</li><li>string length widening</li><li>unique IDs prefixing</li><li>surrounding brackets</li></ul>"
    image="../images/options-dialog-resources.png" >}}
