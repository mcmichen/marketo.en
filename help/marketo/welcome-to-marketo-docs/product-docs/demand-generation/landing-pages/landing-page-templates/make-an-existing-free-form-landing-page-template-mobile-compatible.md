---
unique-page-id: 5472348
description: Make an Existing Free-form Landing Page Template Mobile Compatible - Marketo Docs - Product Documentation
title: Make an Existing Free-form Landing Page Template Mobile Compatible
---

# Make an Existing Free-form Landing Page Template Mobile Compatible {#make-an-existing-free-form-landing-page-template-mobile-compatible}

Make an Existing Free-form Landing Page Template Mobile Compatible - Marketo Docs - Product Documentation

>[!NOTE]
>
>Landing pages templates that were created before the [January 2015 release](../../../../../welcome-to-marketo-docs/release-notes/2015/release-notes-january-2015.md)need to be upgraded to be mobile compatible.

This can be done in two places, the `Template Editor` and the `Landing Page Editor`.  

#### Upgrade from the Template Editor {#makeanexistingfree-formlandingpagetemplatemobilecompatible-upgradefromthetemplateeditor}

##### 1. Go to the Design Studio. {#makeanexistingfree-formlandingpagetemplatemobilecompatible-gotothedesignstudio.}

![](assets/designstudio-1.png)

##### 2. Select Templates. {#makeanexistingfree-formlandingpagetemplatemobilecompatible-selecttemplates.}

![](assets/image2015-1-22-20-3a20-3a2.png)

##### 3. Select a template where Mobile Compatible is No. {#makeanexistingfree-formlandingpagetemplatemobilecompatible-selectatemplatewheremobilecompatibleisno.}

![](assets/image2015-1-22-20-3a22-3a24.png)

##### 4. Click Edit Draft. {#makeanexistingfree-formlandingpagetemplatemobilecompatible-clickeditdraft.}

![](assets/image2015-1-22-20-3a25-3a36.png)

##### 5. Click Make Mobile Compatible. {#makeanexistingfree-formlandingpagetemplatemobilecompatible-clickmakemobilecompatible.}

![](assets/image2015-1-22-20-3a30-3a33.png)

##### 6. Click Upgrade. {#makeanexistingfree-formlandingpagetemplatemobilecompatible-clickupgrade.}

![](assets/image2015-1-22-20-3a32-3a45.png)

Your landing page template is now mobile compatible!

>[!NOTE]
>
>Upgrading should be harmless, but make sure to check pages for any discrepancies. Upgrading will create drafts of any landing pages using that template.

`If you make any changes to the template, Click Template Actions and select Validate Mobile Compatibility.`   
![](assets/image2015-1-22-20-3a36-3a43.png)  

#### What Makes a Template Mobile Compatible? {#makeanexistingfree-formlandingpagetemplatemobilecompatible-whatmakesatemplatemobilecompatible?}

Great questions! Your template must have have the following tags:
`<pre class="syntaxhighlighter-pre" data-theme="Confluence">Must have <!DOCTYPE HTML>Must have a <HEAD> elementMust have a <TITLE> in the <HEAD> elementMust have <META CHARSET="UTF-8"> within the <HEAD> elementMust have a <BODY> element that contains one (and only one) <DIV class="mktoContent"></DIV></pre>` If everything looks good, you'll see this message.

![](assets/image2015-1-22-20-3a41-3a31.png)

If something is wrong, an error message will display, click repair to fix the issue and repeat the validation process.

![](assets/image2015-1-22-20-3a43-3a20.png)

#### Upgrading a Template from the Free-form Landing Page Editor {#makeanexistingfree-formlandingpagetemplatemobilecompatible-upgradingatemplatefromthefree-formlandingpageeditor}

When you're editing a landing page and you click on the mobile tab, you'll sometimes notice the template has not been upgraded. Fear not! You can upgrade it right there.

##### 1. Click the Mobile tab. {#makeanexistingfree-formlandingpagetemplatemobilecompatible-clickthemobiletab.}

![](assets/image2015-1-22-20-3a48-3a19.png)

##### 2. Click the check box and click Activate. {#makeanexistingfree-formlandingpagetemplatemobilecompatible-clickthecheckboxandclickactivate.}

![](assets/image2015-1-22-20-3a49-3a34.png)

>[!NOTE]
>
>Activating the mobile version of a template will create drafts of any landing pages that use it.

Awesome! You can now [customize the mobile view](../../../../../welcome-to-marketo-docs/product-docs/demand-generation/landing-pages/free-form-landing-pages/customize-mobile-view-for-your-free-form-landing-page.md) of all your landing pages that use this template.

>[!NOTE]
>
>**Related Articles**
>
>* [Customize Mobile View for Your Free-Form Landing Page](../../../../../welcome-to-marketo-docs/product-docs/demand-generation/landing-pages/free-form-landing-pages/customize-mobile-view-for-your-free-form-landing-page.md)
>
