# Living Canvas

**Generative art. Human collaboration. Verifiable evolution.**

Living Canvas is a collaborative art platform where a mathematical image becomes a physical painting through successive human contributions.

An artist chooses a title. A deterministic algorithm generates a unique image. Participants then build a physical version of that image, one layer at a time, guided by an adaptive algorithm that measures progress toward the hidden target.

Each contribution becomes part of the artwork's history. Progress is measurable, the rules are transparent, and anyone can join the creative process.

## The concept

What if people could collectively create a painting without knowing exactly what the final image would look like?

Living Canvas combines three elements:

* **Generative art:** mathematical patterns created from a title and reproducible algorithm.
* **Human participation:** people choose colors and physically apply successive layers.
* **Algorithmic guidance:** each new layer is determined by the actual state of the painting and its distance from the target.

The artwork is both a physical object and a record of its own creation.

## How it works

### 1. Choose a title

An artist enters a title for a new painting.

The title is used to generate a deterministic seed. A generative algorithm uses that seed, together with its version and parameters, to produce a mathematical image.

The artist previews the result and selects a canvas aspect ratio.

### 2. Commit the target

Before painting begins, the system records the selected target image and its generation metadata.

The target remains hidden from participants if the project calls for a surprise reveal.

The target cannot be silently changed after the painting starts.

### 3. Start the physical painting

The first participant prepares a canvas with the selected aspect ratio.

The system generates instructions for the first layer, including a color, region, coverage, and application technique.

The participant applies the paint using a sponge or another supported tool.

### 4. Photograph and measure

After each layer, the participant photographs the canvas.

The system corrects for perspective and lighting where possible, compares the current canvas with the target, and calculates a progress score.

The algorithm uses the observed result rather than assuming the participant followed the instructions perfectly.

### 5. Generate the next layer

The system adapts its instructions to the current state of the painting.

Each new contribution moves the physical artwork toward its target while preserving the unpredictable variations introduced by human hands.

### 6. Reveal the result

After the chosen number of layers, the target image can be revealed alongside the completed painting.

The original target, intermediate photographs, instructions, and contributor history document how the final work emerged.

## The pricing mechanism

Each stage can receive a protocol price calculated from a published formula.

For example:

```
protocol_price = base_price + progress_multiplier * progress_score
```

A production implementation would use a defined scoring method and pricing schedule, potentially accounting for regional accuracy, measurement uncertainty, and the remaining difference between the canvas and the target.

The formula is fixed in advance and can be independently reproduced.

Three concepts must remain distinct:

* **Progress score:** how closely the canvas matches the target under the published measurement method.
* **Protocol price:** the price calculated under the project's rules.
* **Market price:** what an actual buyer is willing to pay.

A higher progress score can produce a higher protocol price, but it does not guarantee a higher resale price or a financial return.

## Generative identity

The title gives each artwork its human identity. The committed target provides its technical reference.

Each artwork should record:

* Title.
* Generator name and version.
* Seed-generation method.
* Canvas aspect ratio.
* Generation parameters.
* Target image hash.
* Date the target was committed.

A cryptographic hash does not generate the image itself. It helps verify that the selected target has not changed.

The generator must be deterministic: identical inputs and the same algorithm version should produce the same target.

## Human meaning

The algorithm creates mathematical structure, but people give the image meaning.

A title such as "Electric Garden" might evoke flowers, circuitry, neural networks, or an imaginary landscape. Different people can interpret the same pattern differently.

The first artist establishes an intention. Subsequent participants contribute their own choices, creating a physical record of collective interpretation.

The final painting is the result of the relationship between mathematical structure and human participation.

## Groups and collaboration

Members can join groups organized around shared interests, artistic styles, or specific projects.

Groups can:

* Start new paintings.
* Coordinate early contributions.
* Invite additional participants.
* Document collective authorship.
* Share and transfer eligible artworks.
* Build portfolios and reputations.

The first six layers of a painting, for example, could be coordinated by a founding group before the project opens to a wider community.

Early members have more opportunities to establish projects, build reputations, and shape the platform's culture. These opportunities do not guarantee financial appreciation.

Ownership rules must clearly distinguish between the physical canvas, the completed artwork, and any separately defined shares or stages.

## Marketplace

Members can buy and sell eligible artworks through the platform.

An artwork listing can display:

* Title and generated preview.
* Current canvas photograph.
* Target image identifier.
* Progress score.
* Protocol price.
* Contribution history.
* Ownership and transfer history.
* Actual completed sale prices.

Auctions may be used to discover market demand.

Transactions between related members must be represented accurately. Internal transactions can document an artwork's history, but they should not be presented as independent market validation when they are not.

The protocol price is a feature of the artwork's rules, not proof of its independent market value.

## Subscription model

Living Canvas is designed around recurring membership.

Potential subscription features include:

* Creating and previewing generated images.
* Starting and managing paintings.
* Joining groups and coordinating contributions.
* Tracking progress and provenance.
* Accessing marketplace tools.
* Using advanced generation and analysis features.

Additional revenue could come from transaction fees, premium features, and gallery partnerships.

The subscription funds the platform and its community rather than relying entirely on the resale of artworks.

## Transparency and verification

The system should make its rules and records inspectable.

Core principles:

* The target is committed before painting begins.
* The generation algorithm is versioned.
* The progress-scoring method is published.
* Each layer is documented.
* Protocol prices are reproducible.
* Actual sale prices are distinguished from calculated prices.
* Ownership and transfer rules are explicit.
* Financial appreciation is never guaranteed.

Anyone should be able to photograph a canvas and compare it with the target using the published procedure. Exact results may vary because of lighting, camera calibration, paint opacity, gloss, and other physical factors. The system should disclose those limitations and define acceptable measurement tolerances.

## Technical roadmap

### Phase 1: Generative engine

* Implement deterministic image generation.
* Support titles, seeds, parameters, and aspect ratios.
* Build a preview interface.
* Commit target images and metadata.

### Phase 2: Physical painting prototype

* Define a constrained color palette.
* Generate initial layer instructions.
* Test sponge-based application.
* Document each layer photographically.

### Phase 3: Progress measurement

* Implement perspective correction.
* Calibrate color measurements.
* Compare canvas photographs with target images.
* Calculate progress scores.
* Test robustness against lighting and application variation.

### Phase 4: Adaptive guidance

* Generate instructions from the current canvas state.
* Test how layer opacity affects image recovery.
* Evaluate different scoring and correction strategies.
* Develop the protocol pricing formula.

### Phase 5: Community

* Add member profiles.
* Create groups and projects.
* Record contributions and ownership.
* Introduce subscription features.

### Phase 6: Marketplace

* Add listings and completed transaction records.
* Support eligible transfers and auctions.
* Distinguish protocol prices from actual sale prices.
* Test the platform with independent collectors.

## Guiding principle

Living Canvas turns painting into a collaborative, measurable process.

A title starts the artwork. Mathematics defines its destination. Human hands determine its path. An algorithm guides its evolution. A community gives it history.

**The goal is not simply to generate an image. It is to build a system in which people collectively bring an image into existence.**
