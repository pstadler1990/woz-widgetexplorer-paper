---
layout: default
title: "Fake it and Let Them Make it: Combining WoZ and RP Tools for a Holistic Co-Design of CUIs"
---


<center><h2>Fake it and Let Them Make it</h2></center>

<h3><center>Combining Wizard-of-Oz and Rapid Prototyping Tools<br />for a Holistic Co-Design of Conversational User Interfaces</center></h3>



<div style="float: left">
<center>
Patrick Stadler<br />
<small>firstname.lastname@dfki.de</small><br />
<small>German Research Center for Artificial Intelligence (DFKI)</small><br />
<small>Berlin, Germany</small>
</center>
</div>
<div style="float: right">
<center>
Vanshika Bawa<br />
<small>firstname.lastname@dfki.de</small><br />
<small>German Research Center for Artificial Intelligence (DFKI)</small><br />
<small>Berlin, Germany</small>
</center>
</div>


<div style="clear: both"></div>


<br />
<br />
Accompanying web page with additional information and supplements for the Mensch und Computer 2023[^1] short paper: "Fake it and Let Them Make it: Combining Wizard-of-Oz and Rapid Prototyping Tools for a Holistic Co-Design of Conversational User Interfaces" by Patrick Stadler[^2] and Vanshika Bawa[^3], German Research Center for Artificial Intelligence (DFKI)[^4]. 2023, Berlin, Germany.

<br />


## Abstract

**Developing and evaluating chatbots can be a costly and resource-intensive endeavor, often only addressing the preferences of final stakeholders at the very late stage. This paper presents an innovative approach that leverages chatbot simulations within a co-design framework to involve users early on. The proposed methodology aims to enable comprehensive evaluation of chatbot aspects without the need for users to download an app. The integration of a Wizard-of-Oz (WoZ) tool with WidgetExplorer, our proposed chatbot prototyping and evaluation tool, is introduced as a platform for rapid prototyping and user-centered evaluation. This iterative process facilitates contextual conversations, reflection, and dynamic adjustments to the dialog flow and its appearance. Furthermore, the paper presents the incorporation of visual UI components using AdaptiveCards Designer. Using this approach could lead to improving efficiency, inclusivity, and transparency in chatbot design and evaluation.**



## Paper

The paper can be found in the ACM Digital Library.

<a href="https://doi.org/10.1145/3603555.3608549" target="_blank"><img src="paper_preview.png" title="Link to Paper (ACM)" alt="Paper" width="306"></a>

<p><em>Click the image above to open the paper (ACM Digital Library)</em></p>



## Our Holistic Approach

<center><img src="header.png" title="Holistic Approach" alt="Holistic Approach consists of three steps: Conversation, Export, Replay and Modify" style="max-width: 800px" /></center>

Our approach to a more accessible human-centered approach is a two-step process: first, scenarios not yet implemented in the dialog system are role-played with the subjects using a wizard-of-oz approach. In a second step, the resulting dialog data is now imported into our rapid prototyping platform WidgetExplorer, where, together with the researchers, the users can then replay the dialogs, reflect, and make changes to the dialogs at any time. It is also possible to use the AdaptiveCards Designer[^5] at the
same time to create possible visualizations in the form of small widgets together with the subjects and test them in WidgetExplorer. This allows users not only to design the dialogs themselves, but also to evaluate possible design elements.



## Wizard Of Oz

We use our Wizard of Oz platform as a straightforward way to conduct natural language dialogues with users and potential stakeholders. This also allows for a realistic discussion, in which one person takes the role of the user, while the other person can act out the responses of themselves, or a chatbot, depending on the desired scenario. Usually non-experts, i.e., users, talk to a researcher via the WoZ setup, but it is also imaginable to substitute the researcher for another non-expert, allowing for a true dialog along some prepared tasks. Another advantage of the WoZ approach lies in the fact that the resulting data is already available in digital form and can therefore be easily processed in a next step.

<figure>
<img src="woz.png" title="Wizard of Oz interface" alt="Paper" width="600">
<figcaption>Screenshot of our Wizard of Oz tool. We use this tool to collect dialog data by conversations with actual users of the application respectively from the domain.</figcaption>
</figure>


## WidgetExplorer

WidgetExplorer is a rapid prototyping platform for design evaluations of CUIs and chatbots. In addition to different UI components, so-called widgets, variants of dialogs can also be evaluated, e.g., which wording suits better for a certain use case or how different avatars affect the user acceptance. The option to display multiple variants next to each other opens new possibilities for usability evaluation. WidgetExplorer generates simulated and scripted conversations, no LLM or NLU pipeline or whatsoever is included nor required. User interaction is still possible in a limited way, for instance by allowing to wait for clicks on buttons or other widgets, or simulated text inputs.

<figure>
<img src="we_muc_we.png" title="WidgetExplorer" alt="Our tool WidgetExplorer showing a  side by side comparison of three variants" width="600">
<figcaption>WidgetExplorer is a rapid-prototyping and evaluation tool for chatbots allowing for a side-by-side comparison of up to three variants of conversations, widgets, or other aspects of a chatbot dialog</figcaption>
</figure>
<figure>
<img src="we_muc_1.png" title="WidgetExplorer Backend" alt="The visual editor backend for WidgetExplorer" width="600">
<figcaption>WidgetExplorer also features a visual backend to create experiments and sub-experiments, sketch dialogs and widgets, and try and evaluate these experiments (together with users)</figcaption>
</figure>

The visual backend allows for creating and managing projects (experiments) and sub-experiments, and the actual implementation of these experiments using a drag-and-drop approach. Different variants can be added quickly. 

Variants can be anything. From different wordings in a conversation, to different variants of widgets where you want your users or participants to decide.

<figure>
<img src="persistent_menu.png" title="WidgetExplorer Experiment Persistent Menu" alt="A WidgetExplorer experiment where we tested two variants of the persistent menu widget" width="600">
<figcaption>A WidgetExplorer experiment where we tested two variants of the persistent menu widget</figcaption>
</figure>

The following actions are currently supported in WidgetExplorer:

- `send_message`
- `await_timer`
- `await_user`
- `await_dialog`
- `show_widget`
- `show_dialog`
- `simulate_click`
- `simulate_user_input`



## Download and Open Source Disclaimer

We plan to release all components to the public as open source. However, we cannot provide the download yet, as there is still a lot to prepare. Please feel free to return to this page for further details. If you still think that our tools could help with your own research, please don't hesitate to contact us and we will find a way.



## Citation

<p style="margin: 10px; padding: 10px; background: #edf0f7">
Patrick Stadler and Vanshika Bawa. 2023. Fake it and Let Them Make it: Combining Wizard-of-Oz and Rapid Prototyping Tools for a Holistic Co-Design of Conversational User Interfaces. In Mensch und Computer 2023 (MuC ’23), September 03–06, 2023, Rapperswil, Switzerland. ACM, New York, NY, USA, 5 pages. https://doi.org/10.1145/3603555.3608549
</p>


## Contact Information

<center>
<img src="DFKI_Logo_e_schrift.jpg" alt="DFKI Logo" width="300" /> <br />
<p>German Research Center for Artificial Intelligence (DFKI), Berlin, Germany.<br />
Website: <a href="https://www.dfki.de/web/ueber-uns/standorte-kontakt/berlin" target="_blank">https://www.dfki.de/web/ueber-uns/standorte-kontakt/berlin</a></p>
</center>



<br style="margin-top: 20px; margin-bottom: 5px;" />

<hr />

[^1]: [https://muc2023.mensch-und-computer.de/](https://muc2023.mensch-und-computer.de/)
[^2]: [https://orcid.org/0000-0002-5224-1522](https://orcid.org/0000-0002-5224-1522)
[^3]: [https://orcid.org/0009-0008-9585-8902](https://orcid.org/0009-0008-9585-8902)
[^4]: [https://www.dfki.de/en/web/research/research-departments/cognitive-assistants](https://www.dfki.de/en/web/research/research-departments/cognitive-assistants)
[^5]: [https://adaptivecards.io/designer/](https://adaptivecards.io/designer/)

