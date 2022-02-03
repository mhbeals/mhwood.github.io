---
layout: page
title: TEI for Close Reading:
subtitle: Can It Work for History?
---

*This blog originally appeared on  March 10, 2015. It was re-posted on February 3, 2022.*

The large-scale digitisation of historical texts presents history, literary and corpus linguistics scholars with a number of intriguing opportunities. The ability to semantically parse or otherwise encode texts for computer-aided analysis allows a single researcher to discover trends and outliers within corpora far larger than that same researcher could possible examine in a lifetime, let alone a career. But what about the scholar wishing to examine a small number of sources in detail. In an age where distant reading is possible, is close reading dead? Or, at the very least, does digitisation offer nothing to scholars of the single text?

If they answer was yes, would you have come here today?

## Why Close Reading Will Never Die

Close reading is the process by which a researcher examines a text (or, arguably, any source), taking note of its literal contents, the materiality of its original or duplicate form, the paratextual information that literally surrounds or accompanies it, and the contextual information that shaped its creation, development and distribution. The usage and historical definition of a single word can lead to significant discoveries, or, at least, significant questions to pursue. Tim Hitchcock, in a recent paper to the British Library Labs Symposium, applauded the role of historians in providing in-depth, reflective analyses of the component parts of the large-scale corpora undergoing distance reading. Trends found through computer-aided techniques, he suggested, were hypotheses that could be best understood through traditional historical scholarship, through historians and computer and network scientists working hand-in-hand. Thus, the historian, with his training in close reading, should be considered a sine non qua to distant reading, rather than a predecessor or competitor. But does digitisation, particularly machine-readable transcription, offer anything to the close reader?

## Slow Down

As I mentioned in my last post, the primary service transcription, and TEI encoding, offers the intrepid historian is to get her to slow down. Transforming a source, whether printed or manuscript, into an accurate, encodable, machine-readable text will inevitably take longer than simply reading it. This is especially true for scholars for whom touch-typing remains an arcane mystery. Every tap of the space bar and every stretch to the shift key is usually accompanied by a re-orientation of the transcriber’s focal length as he moves from workspace to source and back again. Having to hold the information in the one’s short-term memory while the meaning is conveyed from page to screen likewise reinforces the need to engage with the text, rather than skim or slide over it. Kate Singer, discussing the possibilities of TEI in the close reading of poetry, likewise suggested that the process ‘effectively engages the encoder in a determinative act of reading‘.

Yet, it is not only the mechanical process of typing that facilitates this slow down. The use of attributes and tags to identify people and places, themes and arguments, forces the reader to clearly identify and explain the vague, abstract concepts that would otherwise flit in and out of her consciousness. Such demands are re-enforced by use of the @ref attribute, which allows the transcriber to cite his sources.

Could she not simply read carefully, or take notes separately on these traits as and when they are relevant? Perhaps. But perhaps we can not know what will be of relevance unless we are pushed, forced even, to consider each and every word. Have you, for example, noticed my fluctuating gender designations? If not, perhaps you should consider encoding this text.

## Get (Productively) Distracted

If we really, truly think about each word we type, and its connections to the wider world, we will almost certainly become distracted, chasing tangents long into the night.  This is, counter-intuitively, a very good thing. A few years ago, long before text encoding entered the realm of my imagination, I was reading an article and came across an allusion that I vaguely recognised, but could not place. Upon looking up its precise definition, I came across another phrase that sparked, by sheer coincidence, a long dormant neuron in the upper left-hand side of my brain, leading me to what I still believe was a solid little conference paper—indeed an article if time could ever be found to complete it. While distraction—or, rather, serendipitous cross-referencing—is usually a ‘nice to have’ rather than something that can be relied upon, encoding regularly may increase the frequency of these flashes of inspiration.

If you rely on serendipity, these references must be recorded, lest they be lost forever when inspiration flits away once more. Manual connections can be recorded through @ref attributes or tags. Yet, if you have not yet had that moment of serendipity, what can you do to hurry it on its way? Simple! Take those those and other ‘entity’ tags and collate them. Using XSLT, you can index all your sources, giving you a list of every snippet that you have tagged or . Connections you never knew you never knew will suddenly appear before you. Yes, the selection bias will be terrible, but they are connections nonetheless.

## Collaborate

Selection bias is a pesky problem, of course, and not one you can easily dismiss. When contextualising a single source, or a small collection, this is not usually damaging. Indeed, for centuries historians have relied upon mere cross-sections of human history in developing their interpretations the past. But, if you have gone to the trouble of encoding the texts, why shouldn’t you be allowed to create one of those amazing visualisations you have seen at recent conferences?

Because your data is not statistically significant, that’s why. Or, more precisely, any trends you might notice using distant reading methods would not have been robustly proved. Big data analyses rely, to some degree, on having incomprehensibly large, often very messy, sets of data. Because the data is unordered (in theory), trends develop naturally from statistical enquiry rather than from a manipulation of the source material. For example, if you have transcribed a series of articles from the Glasgow Advertiser based on their inclusion of the word ‘Indian’, your keyword histogram might, just maybe, be skewed. Over the course of many years, and many projects, selection biases will likely overlap help to cancel each other out, but the data will always be slightly dodgy.

On the other hand, collaboration between many individuals, within a single project or across many different projects, may open new avenues to the ’boutique’ researcher. While keyword lexicons will inevitably vary, other entity tags may provide helpful links between corpora. Smaller, more focused collaborations, such as the creation of an annotated volume or edited collection, may not lead to definite answers, but will certainly lead to interesting questions.

## Try It Yourself

If you would like to try TEI yourself in safe, free, and largely controlled environment, you are in luck. This year, as part of a new module on digital history, I created a seminar-length (90 minute) exercise for my first-year students. The exercise is available in full here and you are free to download, fork and adapt the exercise as you please—though I would certainly appreciate the opportunity to see (and play with) any variants made!

The aim of the exercise is not to teach TEI encoding to students. Although I find it a very useful encoding language, and an army of 115 encoders would certainly be useful for in-house projects, I do have some qualms about indentured servitude. Instead, the exercise will hopefully encourage students to slow down, get distracted (in a good way), actively cross-references their other work, and collaborate towards a common goal.
