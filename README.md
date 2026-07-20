# Cezary Baraniecki

**Product-minded AI builder focused on useful, inspectable user experiences.**

I turn ambiguous workflows into working products: define the user problem, prototype the interaction, connect the underlying systems, and build enough evaluation to know what is actually working. My projects emphasize human control, local-first data, and honest boundaries around model behavior.

I am especially interested in roles where product judgment, customer understanding, and hands-on AI prototyping overlap.

## Featured products

### [Product Decision Compiler](https://github.com/czzzry/product-decision-compiler) · [Interactive proof](https://czzzry.github.io/product-decision-compiler/)

**A read-only decision layer for AI-assisted software delivery.** It turns an approved product decision into a versioned contract, connects Linear and GitHub evidence to that contract, and brings only meaningful exceptions back for human review.

`product operations` · `human-in-the-loop AI` · `Python` · `Linear + GitHub`

### [WatchSignal](https://github.com/czzzry/watchsignal) · [Live showcase](https://watchsignal-web.vercel.app/showcase)

**Movie-night mediation for two people with different tastes.** WatchSignal keeps each person's preferences separate, finds compromise candidates, and explains why a recommendation should work for both people. It is a phone-first product built with Next.js, FastAPI, and SQLite.

`consumer product` · `recommendation systems` · `Next.js` · `FastAPI`

### [Threadwise](https://github.com/czzzry/threadwise)

**A teachable inbox companion that acts only within visible authority boundaries.** Threadwise classifies email, explains its decisions beside Gmail, accepts corrections in context, and previews the broader impact before changing matching messages.

The repository includes a synthetic product walkthrough, evaluation artifacts, bounded provider-write paths, and explicit safety decisions. The walkthrough does not require private email or provider credentials.

![Threadwise synthetic product walkthrough](https://raw.githubusercontent.com/czzzry/threadwise/main/docs/assets/threadwise-recruiter-story.gif)

`human-in-the-loop AI` · `browser extension` · `evaluation` · `local-first`

### [Pyrenees Selects](https://github.com/czzzry/pyrenees-selects)

**A local workflow for turning large drone-footage folders into a reviewable first cut.** It scans media, surfaces promising clips, supports rough-cut assembly, and hands the result to DaVinci Resolve while keeping source footage on the user's machine.

`creative tooling` · `video workflows` · `OpenCV` · `ffmpeg`

### [Local Scriptorium](https://github.com/czzzry/local-scriptorium)

**A reproducible retrieval study over a public-domain historical corpus.** The project compares keyword, BM25, vector, and hybrid retrieval, then documents where grounded answers succeed or fail instead of presenting RAG as a black box.

`information retrieval` · `RAG evaluation` · `BM25` · `embeddings`

## What these projects demonstrate

- **Product framing:** narrowing a broad AI idea into a specific user job and interaction loop.
- **Hands-on prototyping:** moving between interface work, APIs, data models, and local tooling.
- **Trustworthy AI behavior:** separating model judgment from deterministic permissions and irreversible actions.
- **Evidence over theater:** synthetic demos, regression tests, evaluation harnesses, and visible limitations.
- **End-to-end ownership:** documentation, product decisions, implementation, QA, and packaging.

## Working principles

1. Start with the user decision or frustration, not the model.
2. Build the smallest complete workflow that can be tested by a real person.
3. Make consequential actions explicit, inspectable, and reversible where possible.
4. Keep private source data local and publish synthetic demonstrations.
5. State what the evidence proves and what it does not.
