---
layout: about
title: About
permalink: /
subtitle: # <a href='#'>Affiliations</a>. Address. Contacts. Moto. Etc.

profile:
  align: right
  image: rozplokhas_prof_photo_2.jpg
  image_circular: false # crops the image to make it circular
  address:

news: false  # includes a list of news items
latest_posts: false  # includes a list of the newest posts
selected_papers: false # compact list below instead of full bibliography entries
social: false  # includes social icons at the bottom of the page
---

I am a postdoctoral researcher in the [Theory and Logic group](https://www.logic.at/) at TU Wien, working on the FWF project ENCORE (Exploring Conditional Logics via Proof Theory), led by [Prof. Agata Ciabattoni](https://www.logic.at/staff/agata/). I completed my PhD at TU Wien under her supervision in the MSCA COFUND doctoral programme [LogiCS@TUWien](https://www.vcla.at/msca/programme/), focused on logical methods in Computer Science.

My research develops proof-theoretic and model-theoretic methods for logics used in knowledge representation and normative reasoning, particularly conditional and non-monotonic logics. I use these methods to uncover connections between different logical formalisms, investigate their computational complexity, and design automated reasoning procedures.

<h2 class="selected-publications-heading">Selected publications</h2>

<style>
.selected-publications-heading { margin-top: 3rem; }
.selected-work { margin: 0 0 1.5rem; }
.selected-work .title { font-weight: 600; }
.selected-work .authors, .selected-work .venue, .selected-work .award { line-height: 1.35; }
.selected-work .authors { color: var(--global-text-color-light, #777); }
.selected-work .venue { color: var(--global-text-color, #111); }
.selected-work .award { color: #198754; font-weight: 700; }
.selected-work .actions { margin-top: .3rem; }
.selected-work .actions a, .selected-work .actions button {
  display: inline-block; padding: .12rem .45rem; margin-right: .3rem;
  border: 1px solid currentColor; border-radius: 2px;
  font-size: .75rem; line-height: 1.3; text-decoration: none;
  color: var(--global-text-color, #111); background: transparent;
}
.selected-work .actions button { cursor: pointer; }
.selected-work .abstract-panel[hidden] { display: none; }
.selected-work .abstract-panel {
  border: 1px dashed var(--global-text-color-light, #777);
  padding: .65rem .8rem; margin-top: .55rem; line-height: 1.5;
}
</style>

<div class="selected-work">
  <div class="title">Streamlining Input/Output Logics with Sequent Calculi</div>
  <div class="authors">Agata Ciabattoni and Dmitry Rozplokhas</div>
  <div class="venue">20th International Conference on Principles of Knowledge Representation and Reasoning (KR 2023)</div>
  <div class="award">🏆 Ray Reiter Best Paper Prize</div>
  <div class="actions"><button type="button" class="abstract-trigger" aria-controls="abstract-streamlining-io" aria-expanded="false">Abstract</button><a href="{{ '/assets/pdf/KR_2023.pdf' | relative_url }}">PDF</a></div>
  <div class="abstract-panel" id="abstract-streamlining-io" hidden>Input/Output (I/O) logic is a general framework for reasoning about conditional norms and/or causal relations. We streamline Bochman’s causal I/O logics via proof-search-oriented sequent calculi. Our calculi establish a natural syntactic link between the derivability in these logics and in the original I/O logics. As a consequence of our results, we obtain new, simple semantics for all these logics, complexity bounds, embeddings into normal modal logics, and efficient deduction methods. Our work encompasses many scattered results and provides uniform solutions to various unresolved problems.</div>
</div>

<div class="selected-work">
  <div class="title">GL-Based Calculi for PCL and Its Deontic Cousin</div>
  <div class="authors">Agata Ciabattoni, Dmitry Rozplokhas, and Matteo Tesi</div>
  <div class="venue">19th European Conference on Logics in Artificial Intelligence (JELIA 2025)</div>
  <div class="award">🏆 Best Student Paper and Runner-up Best Paper Awards </div>
  <div class="actions"><button type="button" class="abstract-trigger" aria-controls="abstract-gl-based-pcl" aria-expanded="false">Abstract</button><a href="{{ '/assets/pdf/JELIA_2025.pdf' | relative_url }}">PDF</a></div>
  <div class="abstract-panel" id="abstract-gl-based-pcl" hidden>We introduce a natural sequent calculus for preferential conditional logic PCL via embeddings into provability logic GL, achieving optimal complexity and enabling countermodel extraction. Extending the method to PCL with reflexivity and absoluteness – corresponding to Åqvist’s deontic system F with cautious monotony – we employ hypersequents to capture the S5 modality; the resulting calculus subsumes the known calculi for the weaker systems E and F within Åqvist family.</div>
</div>

<div class="selected-work">
  <div class="title">From Explicit Allowances to Defeasible Deontic Operators: A Modal View</div>
  <div class="authors">Agata Ciabattoni, Josephine Dik, Emiliano Lorini, Dominik Pichler, and Dmitry Rozplokhas</div>
  <div class="venue">26th International Conference on Principles and Practice of Multi-Agent Systems (PRIMA 2025)</div>
  <div class="award">🏆 Martin Purvis Student Best Paper Award</div>
  <div class="actions"><button type="button" class="abstract-trigger" aria-controls="abstract-permission-bases" aria-expanded="false">Abstract</button><a href="{{ '/assets/pdf/PRIMA_2025.pdf' | relative_url }}">PDF</a></div>
  <div class="abstract-panel" id="abstract-permission-bases" hidden>Preference-based deontic logics provide a foundation for normative reasoning but fail to distinguish between explicit allowances - specified by a designer - and implicit ones derived by inference. This distinction is crucial in systems where agents may act only if (explicitly or implicitly) permitted. In this paper, we formalize this inference by grounding the preference ordering over possible worlds in a permission base, i.e., a set of explicit allowances, and derive implicit permissions, as well as defeasible prohibitions and obligations. Our framework provides solutions to key deontic paradoxes and is a conservative extension of Åqvist’s dyadic deontic system F extended with cautious monotony. We illustrate the approach with a case study involving robotic agents operating under normative constraints and provide complexity results together with a QBF-based decision procedure to support automated reasoning.</div>
</div>

<div class="selected-work">
  <div class="title">LEGO-Like Small Model Constructions for Åqvist’s Logics</div>
  <div class="authors">Dmitry Rozplokhas</div>
  <div class="venue">15th International Conference on Advances in Modal Logic (AiML 2024)</div>
  <div class="actions"><button type="button" class="abstract-trigger" aria-controls="abstract-lego-models" aria-expanded="false">Abstract</button><a href="{{ '/assets/pdf/AiML_2024.pdf' | relative_url }}">PDF</a></div>
  <div class="abstract-panel" id="abstract-lego-models" hidden>Åqvist's logics (E, F, F+(CM), and G) are among the best-known systems in the long tradition of preference-based approaches for modeling conditional obligation. While the general semantics of preference models align well with philosophical intuitions, more constructive characterizations are needed to assess computational complexity and facilitate automated deduction. Existing small model constructions from conditional logics (due to Friedman and Halpern) are applicable only to F+(CM) and G, while recently developed proof-theoretic characterizations leave unresolved the exact complexity of theoremhood in logic F. In this paper, we introduce alternative small model constructions assembled from elementary building blocks, applicable uniformly to all four Åqvist's logics. Our constructions propose alternative semantical characterizations and imply co-NP-completeness of theoremhood. Furthermore, they can be naturally encoded in classical propositional logic for automated deduction.</div>
</div>


<script>
document.querySelectorAll('.selected-work .abstract-trigger').forEach((button) => {
  button.addEventListener('click', () => {
    const panel = document.getElementById(button.getAttribute('aria-controls'));
    panel.hidden = !panel.hidden;
    button.setAttribute('aria-expanded', String(!panel.hidden));
  });
});
</script>
