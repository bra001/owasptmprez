<!-- .slide: data-background-image="content/images/OWASP_Full_Logo_R_White.png" data-background-size="20%" data-background-position="right 2% top 2%"-->

# OWASP Stavanger 
## Chapter Meetup 
# #1

---

## Agenda

❓ What  
💡 Why  
📅 When  
🔧 How

---

## What is threat modeling?

> Threat modeling is analyzing representations of a system to highlight concerns about security and privacy characteristics.

-[Threat Modeling Manifesto](https://www.threatmodelingmanifesto.org/)<!-- .element: style="font-size:0.8em"-->

---

## Why
<div><!-- .element: style="font-size:0.75em"-->

- Detect design and implementation issues <!-- .element: class="fragment" data-fragment-index="1" -->
- Efficient investment of resources, appropriately prioritize security tasks <!-- .element: class="fragment" data-fragment-index="2" -->
  - Based on business requirements (Goals)
  - Driven by risk
  - Identify where building a control is unnecessary, based on acceptable risk
- Provide evidence that security and privacy is built into our designs <!-- .element: class="fragment" data-fragment-index="3" -->
- Cultivate a collective understanding of the system among team members <!-- .element: class="fragment" data-fragment-index="4" -->
  - Raise awareness and educate about security and privacy importance
- Implement a consistent approach to security <!-- .element: class="fragment" data-fragment-index="5" -->

</div>

---

### When to threat model?

<div style="display: grid;grid-column-gap: 1%; grid-auto-columns: 60% 50%;">

<div  style="grid-area: 1 / 1"><!-- .element: style="font-size:0.8em"-->

<hr>

- Ideally, we begin threat modeling for a system during the early stages of the SDLC <!-- .element: class="fragment" data-fragment-index="1" -->
- It’s important that the SDLC itself is subject of threat modelling! <!-- .element: class="fragment" data-fragment-index="2" -->
- Consistency is key – it should be an ongoing effort, not just a single event <!-- .element: class="fragment" data-fragment-index="3" -->


</div>

<div  style="grid-area: 1 / 2"><img src="content/images/devops.png" width="100%" height="auto" display="block" margin-left="auto" margin-right="auto">
</div>

</div>

<hr>

<div><!-- .element: style="font-size:0.75em"-->

🧀 Like using a compass during a hike, frequent threat modeling helps you stay on the right path towards your security goals. <!-- .element: class="fragment" data-fragment-index="4" -->

</div>

---

### What are we working on?

<div style="display: grid;grid-column-gap: 1%; grid-auto-columns: 60% 50%;">

<div  style="grid-area: 1 / 1"><!-- .element: style="font-size:0.8em"-->

<hr>

- Creating the representation of the system  <!-- .element: class="fragment" data-fragment-index="1" -->
  - Clarify ideas
  - Scoping
  - Share knowledge
  - Serve as reference
- Can use whatever <!-- .element: class="fragment" data-fragment-index="2" -->
- (ex) DFD (Data Flow Diagrams) <!-- .element: class="fragment" data-fragment-index="3" -->
  - Threats often follow data
  - Simple, easy to learn and sketch
  - Tool agnostic


</div>


<div  style="grid-area: 1 / 2"> <!-- .element: class="fragment" data-fragment-index="3" -->
DFD components
<img src="content/images/dfd.png" width="100%" height="auto" display="block" margin-left="auto" margin-right="auto"> 

</div>

</div>

---

## What can go wrong?

<div><!-- .element: style="font-size:0.75em"-->

- Track concerns/assumptions as you go <!-- .element: class="fragment" data-fragment-index="1" -->
  - Will serve as input for the next phase
- There are frameworks and tools you can lean on during this process: <!-- .element: class="fragment" data-fragment-index="2" -->
  - STRIDE/STRIPED, LINDDUN
  - Mitre Att&ck
  - Threat libraries
  - Threagile, pytm
  - Brainstorming
- Recommended practice: <!-- .element: class="fragment" data-fragment-index="3" -->
  - Appoint a note taker
  - Create a team strategy for how to document, what to document, where to store
  - Experiment and iterate

</div>

---

## What are we going to do about it?

- Addressing the threats
  - Decide on a strategy (mitigate, eliminate, accept, transfer)
- Good idea to indicate severity to help with prioritizations
- Check/verify assumptions

---

## Did we do a good enough job

<div><!-- .element: style="font-size:0.75em"-->

- Do regular Threat Modeling retrospectives <!-- .element: class="fragment" data-fragment-index="1" -->
  - Consider integrating them into regular team retros
- Potential questions for reflection <!-- .element: class="fragment" data-fragment-index="2" -->
  - Are we finding any issues?
  - Are we closing the issues we find?
  - Are there any incidents caused by our mitigations?
  - Are we as a team happy with our way of doing threat modeling?
  - Do we need to adjust our efforts one way or another?
  - Should we try out any experiments?

</div>
