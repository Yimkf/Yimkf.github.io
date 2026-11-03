---
layout: academic
title: "EMS Hand Prop"
collection: research
permalink: /research/2024-04-EMS Hand Prop
---

<p class="project-deck">EMS Hand Prop: Leveraging the Loss of Sense of Agency Caused by Electrical Muscle Stimulation to Make Hands Serve Better as Virtual Objects</p>

**Jianhui Yan**, Jiesi Zhang, Haoqiang Hua, Wenxuan Wu, Hongnan Lin, Qiwei Xiong, Jianxiu Jin, Lin Shu

*International Journal of Human–Computer Studies, Volume 208 (2026), Article 103715*

[Read the paper ↗](https://doi.org/10.1016/j.ijhcs.2025.103715)

<figure class="project-figure"><a href="{{ '/assets/images/publications/ems-hand-prop-figure-1.webp' | relative_url | uri_escape }}" aria-label="View Figure 1 at full resolution"><img src="{{ '/assets/images/publications/ems-hand-prop-figure-1.webp' | relative_url | uri_escape }}" alt="Figure 1: EMS Hand Prop interaction concept, electrode placement, gesture recognition, and interaction pipeline" width="1023" height="742"></a><figcaption>Figure 1. EMS actuates the non-dominant hand into virtual-object poses; a data glove recognizes the gestures, while the dominant hand interacts with the resulting hand-formed objects.</figcaption></figure>

## Overview

EMS Hand Prop explores how a reduced sense of agency—the feeling of controlling one’s own actions—can help a hand feel more like a virtual object. Instead of treating this effect of electrical muscle stimulation as a drawback, the system uses it to support immersive hand-as-prop interaction in VR.

## How it works

1. Electrical muscle stimulation actuates fingers of the non-dominant hand into poses associated with eight virtual objects.
2. A motion-capture glove and a one-dimensional convolutional neural network recognize the hand gesture and retrieve its corresponding virtual object.
3. The dominant hand touches and manipulates the stimulated hand, combining visual feedback with self-haptic contact.

## Evaluation & findings

Two user studies with 12 participants compared EMS Hand Prop with non-EMS conditions in object-retrieval and object-interaction tasks. Quantitative and qualitative feedback indicated stronger perceptual transformation of the hand into a virtual object and greater immersion in hand-as-prop interactions.

## Takeaway

A loss of perceived control can become a useful design resource when the interaction calls for the hand to behave like an object.

## My contributions

- Developed the concept of leveraging EMS-induced loss of agency for hand-as-prop interactions.
- Designed an anatomically guided electrode layout for finger actuation.
- Integrated EMS actuation, gesture recognition, and VR interaction.

## Publication

**Jianhui Yan**, Jiesi Zhang, Haoqiang Hua, Wenxuan Wu, Hongnan Lin, Qiwei Xiong, Jianxiu Jin, Lin Shu. **EMS Hand Prop: Leveraging the Loss of Sense of Agency Caused by Electrical Muscle Stimulation to Make Hands Serve Better as Virtual Objects**. International Journal of Human–Computer Studies, Volume 208 (2026), Article 103715. [DOI: 10.1016/j.ijhcs.2025.103715](https://doi.org/10.1016/j.ijhcs.2025.103715).
