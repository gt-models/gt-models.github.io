---
layout: home
title: HOME
description: In this website, we provide a number of additional resources to complement the paper submitted to `ISMIR 2024`
permalink: /
subtitle: 
---

# **ISMIR 2024 Submission - Supplementary Material**
---

In this website, we provide a number of additional resources to complement the paper submitted to `ISMIR 2024`.


<br>

#### **Recordings of Real-Time System**
---

<br>

##### **_Anon Performance with the System_**

The following two excerpts are from the live performance using the system. 
As mentioned in the paper, the system was developed in collaboration with ANON, 
for a series of recuring live performances.

> **Note**  
> The organizers of the concert have recorded the entire performance, and will release the videos to the public soon. 
> we will link the full video here. 

The following video is a snippet of the recording made by the organizers.

<video width="300" height="200" controls>
  <source src="/assets/video/vid2_pro_camera.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

<br>

The following video is a short phone recording. As mentioned above, the full video with good audio quality will be made available.

<video width="300" height="200" controls>
  <source src="/assets/video/a.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>


<br>


<br>

##### **_System Demo_**

> **Note**
> The demos here are prepared by the authors of the paper.

The following video shows the system in action. The interface shown here is slightly different from the one shared in this website.
However, the underlying system is the same. To download the latest plugin, please visit the [VST Plugins](/resources/source_code_and_vst_plugins/) page.

In this recording, we use an arpegiating bassline played is looped and fed into the system (bottom-right corner). In the meantime, 
a live performance on the synthesizer (top-right) is also fed into the system. The system generates the drums in real-time, which
are then synthesized using a drum synthesizer (left).


<video width="300" height="200" controls>
  <source src="/assets/video/VCV_VST_Keyboard_LowRes.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

<br>
<br>

[**Click Here for More Recordings**](/generated_examples/jam_session_recordings){: .btn}

[//]: # (Setup:)

[//]: # ()
[//]: # (- An arpegiating bassline played back using an ableton stock plugin)

[//]: # (- An Arturia Polybrute synthesizer played live. )

[//]: # (- `GrooveTransformer`receiving MIDI grooves from both the arpegiated basseline and the live performance on the synthesizer)

[//]: # ()
[//]: # (Drum Synthesis:)

[//]: # ()
[//]: # (- [Cardinal]&#40;https://github.com/DISTRHO/Cardinal&#41; Virtual Eurorack Environment)

[//]: # (- Cardinal receives the generated drums, strips the gats and velocities to trigger the modules)

[//]: # (- Triggers used to activate voices while velocities are used either as VCA gains and/or synthesis parameters. )

[//]: # (- While 9 voices are generated, some voices were grouped together)

[//]: # (- Typical Kick and Snare &#40;with velocity controled VCAs&#41; were used for kick and snares)

[//]: # (- A single FM Operator was used for all hats &#40;closed and open&#41;. The decay of the envelop was controlled by the type of trigger)

[//]: # (- For Rides and Toms, two separate Mutable Instrument Plait modules were used.)






<br>

#### **Quick Links**
---




- Listen to the generated samples:
  - [Test set reconstructed generations]({{site.baseurl}}/generated_examples/reconstructed_samples/)
  - [Random generations]({{site.baseurl}}/generated_examples/random_samples/)
  - [Interpolation samples]({{site.baseurl}}/generated_examples/interpolated_samples/)
  
  <br>
  
- Resources to download, access and explore the trained models: 
  - [Trained Models: Access weights, source code, and API]({{site.baseurl}}/resources/trained_models/)
  - [UMAP analysis: Visualize the latent space]({{site.baseurl}}/further_analysis/umap/)
  - [Colab Notebooks: Quickly interact with models]({{site.baseurl}}/resources/colab_notebooks/) to quickly interact with the models
  - [VST Plugins: Deployed in real-time system]({{site.baseurl}}/resources/source_code_and_vst_plugins/)
  - [Genre Classifier: Access weights, source code, and API]({{site.baseurl}}/further_analysis/genre_classifier_model/)

[//]: # (- Further analysis)

[//]: # (  - [Feature analysis]&#40;{{site.baseurl}}/further_analysis/feature_analysis/&#41;)

  