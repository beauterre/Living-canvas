# Living Canvas
### Generative art. Human collaboration. Verifiable evolution.

Living Canvas is a collaborative art platform exploring how generative systems, collective creativity, and social consensus shape the creation and perceived value of physical art.

Each artwork begins as a mathematically generated image. People then work together to reproduce it through successive physical layers of paint. The platform documents the process, measures progress toward the target, and builds a historical record of the artwork's evolution.

The result is more than a painting. It is a physical object with a reproducible digital identity, a history of human contributions, and a record of the social and economic events surrounding it.

Living Canvas does not sell artworks or operate an internal marketplace. Buying, selling, trading, and auctioning take place independently of the platform, between participants or through external marketplaces.

The platform provides the creative protocol, collaboration infrastructure, artwork metadata, progress measurements, and historical price visualizations that allow people to explore the relationship between art, community, and economic value.

---

## 1. The Core Idea

An artwork can be understood through several overlapping dimensions:

- **Generative identity:** the mathematical process that defines the target image.
- **Physical realization:** the paint, materials, and accumulated layers of the canvas.
- **Collective authorship:** the people who contribute to its creation.
- **Algorithmic progress:** the measured relationship between the physical painting and its target.
- **Social history:** the groups, communities, and relationships formed around the work.
- **Market history:** the offers, auctions, transactions, and ownership changes associated with it.

Living Canvas brings these dimensions together in a single documented system.

The project explores a broader question:

**How much of an artwork's value comes from the image itself, how much from the people who create it, and how much from the history that develops around it?**

## 2. Generative Identity

Every artwork begins with a title chosen by a participant.

The title is converted into a deterministic seed that drives a generative image process. The generator produces a target image using mathematical rules, parameters, and a defined version of the generation algorithm.

The same title and generation configuration produce the same target.

Each artwork records the information necessary to reproduce its digital identity, including:

- Artwork title
- Seed or seed-generation method
- Generator version
- Generation parameters
- Target image or its cryptographic hash
- Canvas aspect ratio
- Creation timestamp

The image provides the technical starting point. The title provides a human point of reference, allowing meaning and interpretation to emerge through the creative process.

The generative system can use mathematical functions, procedural patterns, fractals, noise fields, and other deterministic techniques to produce aesthetically interesting images.

The aim is not simply to create random pictures. It is to create a reproducible visual identity that can be interpreted, realized, and transformed through human collaboration.

## 3. From Digital Image to Physical Canvas

The artist selects a canvas format and commits to the target image before the collaborative painting process begins.

The target remains hidden from participants during the process, encouraging them to work through instructions and shared coordination rather than simply copying a visible reference.

The canvas is built through successive layers of paint. Participants may apply color with sponges, rollers, brushes, or other defined techniques.

After each layer:

1. The physical canvas is photographed.
2. The photograph is aligned and normalized as far as the capture setup allows.
3. The system compares the observed painting with the target image.
4. The current progress score is calculated.
5. The system generates instructions for the next layer.
6. The new layer and its measurements are added to the artwork's history.

The process repeats until the collective reaches its chosen completion criteria.

The physical painting is the artwork. The digital record documents its evolution.

### Image Capture

Reliable comparisons require consistent image capture.

Where possible, the process should use:

- A fixed camera position
- Perspective correction
- Consistent lighting
- Color calibration
- Known canvas dimensions
- Reference color markers where appropriate

These measures help distinguish genuine changes in the painting from differences caused by camera position, exposure, or lighting.

## 4. Measuring Progress

Living Canvas uses image analysis to estimate how closely the physical painting corresponds to its generative target.

The measurement system may consider:

- Color distribution
- Spatial composition
- Large-scale shapes
- Regional similarity
- Layer coverage
- Image structure at multiple scales

A single similarity metric may not adequately capture artistic progress. The scoring system should therefore be versioned, documented, and designed to avoid rewarding superficial changes that increase numerical similarity without improving the overall composition.

Each recorded score represents a measurement under a particular protocol, not an objective judgment of artistic quality.

Progress is a measurable property of the painting relative to its target. Artistic merit remains open to interpretation.

## 5. Protocol Price

Living Canvas can calculate a protocol price from a published algorithm.

The calculation may combine a base value with the measured progress of the painting:

`Protocol Price = Base Value + Progress Component`

The actual formula, parameters, and version are recorded with the artwork.

The protocol price is a system-defined metric. It is not a sale offer, an independent appraisal, or a guarantee of future market value.

The distinction is fundamental:

- **Progress score** measures similarity to the target under the defined scoring protocol.
- **Protocol price** expresses the output of the platform's pricing formula.
- **Asking price** is the price a seller requests.
- **Bid price** is an amount offered by a prospective buyer.
- **Completed sale price** is the amount paid in a completed transaction.

These figures describe different things and should never be presented as interchangeable.

The algorithm measures progress according to its own rules, while buyers and sellers outside the platform determine what they are willing to pay.

## 6. Collective Creation

Living Canvas supports groups of people working together on the same artwork.

Participants can organize into collectives, coordinate early layers, share responsibilities, and develop their own creative methods.

A group might agree on the first six layers, divide tasks between members, or establish a shared approach to completing a canvas.

The platform records contributions and collaboration without requiring every artistic decision to be made by an algorithm.

Groups can develop their own identities, working methods, and reputations. Members can also build portfolios showing their participation in different works.

The platform provides the coordination infrastructure; the collective determines how it uses that infrastructure.

### Collective Ownership and Participation

Depending on the arrangements chosen by participants, a group may coordinate the creation of a painting before deciding who will own it or how it will be transferred.

The platform can document contributions, agreements, and ownership information where participants choose to provide them.

Participation in the creation of a work does not automatically establish legal ownership. Ownership and transfer arrangements remain subject to the agreements and applicable laws governing the participants.

## 7. External Trading and Auctions

Living Canvas does not operate an internal shop and does not sell artworks on behalf of participants.

Participants remain free to arrange sales, purchases, exchanges, or auctions independently, whether directly with one another or through external marketplaces.

They may use bulletin boards or other external channels to advertise works and communicate offers. Artwork identifiers and provenance records help connect those activities to the corresponding canvas.

Auctions can provide a mechanism for price discovery when participants choose to use them. The platform does not need to conduct the auction or guarantee its outcome.

This separation is intentional:

- The platform defines and documents the artwork.
- Participants determine how they organize and collaborate.
- Buyers and sellers make their own economic decisions.
- External markets determine whether a work attracts demand and at what price.

The platform does not need to incentivize trading to study the effects of trading.

### Bulletin Boards

External bulletin boards can allow participants to announce that a work is available, state an asking price, invite offers, or propose a trade.

A bulletin-board listing is not itself a transaction. Listings may be withdrawn, offers may be rejected, and asking prices may differ substantially from eventual sale prices.

Where market events are added to an artwork's history, their status should be made explicit.

### Auctions

An external auction can produce a sequence of bids and, potentially, a completed sale.

Useful auction metadata includes:

- Opening price
- Auction start and end times
- Recorded bids
- Winning bid
- Whether the sale was completed
- Final transaction price, if verified
- Relevant fees and disclosed relationships

A winning bid should not automatically be treated as a completed sale. The record should distinguish between an auction outcome and a transaction that actually occurred.

## 8. Price History and Investment Discovery

Each artwork has a time-versus-euro price-history graph.

The horizontal axis represents time. The vertical axis represents price in euros.

The graph helps visitors explore how the recorded prices associated with a painting have changed throughout its history and identify works they may find interesting as potential investments.

The purpose is to make the economic history of each artwork easy to inspect and compare.

### Price Data

Depending on the available records, a graph may include:

- Protocol prices calculated by the Living Canvas algorithm
- Recorded asking prices
- Auction bids and winning bids
- Completed sale prices
- Relevant ownership and transaction events

These values should be visually and semantically distinguished.

For example, the graph might show the protocol price as one series, asking prices as separate markers, bids as auction events, and completed sales as prominent transaction points.

The graph should not connect unrelated values in a way that implies they represent a continuous series of actual market transactions.

### Discovering Interesting Works

Visitors can compare paintings by examining their price histories alongside their:

- Generative identity
- Physical progress
- Completion status
- Contributors
- Collective history
- Ownership and provenance
- Recorded market activity

A work may attract attention because of its visual qualities, its collective history, its completion progress, its recorded transactions, or the combination of these factors.

A visitor might look for works with a long history, a particular contributor group, a high completion score, or a pattern of completed sales.

Living Canvas provides the information needed to investigate those characteristics. It does not need to recommend that a visitor buy a particular work.

### Interpreting Price Changes

A rising price history can be interesting, but it does not by itself establish independent demand, liquidity, or future appreciation.

Different kinds of price changes have different meanings:

- A rising protocol price may reflect increasing measured progress.
- A rising asking price reflects a seller's changing expectations.
- Higher bids may indicate increased willingness to pay among auction participants.
- Higher completed sale prices show that particular transactions occurred at those prices, subject to verification.

A small number of transactions may not represent a broad market. Prices may also be affected by scarcity, social relationships, coordinated activity, or differences between individual works.

Historical prices are evidence of recorded events, not guarantees of future returns.

### Comparing Works

Price-history graphs can help visitors compare the histories of multiple paintings.

Comparisons are most meaningful when users can distinguish between:

- Algorithmic prices and actual market transactions
- Asking prices and completed sales
- Recent events and older records
- Verified data and participant-reported information
- Different artwork versions and scoring protocols

The objective is to support informed exploration rather than manufacture a single misleading impression of value.

## 9. Market History as Provenance

An artwork's history does not necessarily end when the painting is complete.

Offers, auctions, ownership changes, and completed transactions can become part of its wider provenance, alongside its physical and generative history.

Where reliable records are available, an artwork's metadata may include:

- Listing and asking prices
- Offers and their outcomes
- Auction rules and opening prices
- Recorded bids and winning bids
- Whether a transaction was completed
- Reported or verified sale prices
- Ownership transfers
- Transaction timestamps
- Relevant disclosures about buyer-seller relationships
- The artwork's progress score and protocol price at the time of a recorded event

The record should distinguish clearly between an asking price, an offer, a winning bid, and a completed sale.

It should also identify whether information is independently verified, supported by documentation, or reported by a participant.

Corrections should be recorded transparently rather than silently overwriting previous events. Privacy-sensitive information should be handled separately from public provenance.

A recorded sale establishes that a transaction occurred when adequately verified. It does not automatically establish independent demand, a fair market price, or a reliable prediction of future value.

### Provenance as Part of the Artwork

The artwork's history can become part of its perceived meaning.

A painting may be associated with the people who created it, the groups that supported it, the places it has been, and the transactions through which it has changed hands.

Living Canvas documents this history without assuming that every event increases the artwork's artistic or economic value.

The record is intended to preserve context, not prescribe interpretation.

## 10. The Social Life of Value

Living Canvas is also an experiment in how value emerges from collective behavior.

A group may believe that its work deserves greater recognition. Members may choose to buy, sell, exchange, or collect one another's paintings. These decisions can influence how later participants perceive the artwork and its history.

Such behavior does not require the platform to direct or reward it. It can emerge from the incentives and relationships of the participants themselves.

The resulting feedback loop is worth examining:

1. A collective creates an artwork.
2. Participants assign meaning and significance to it.
3. Trading activity produces a history of prices and ownership.
4. That history influences how others perceive the work.
5. New participants make decisions based partly on the accumulated history.

This process can generate genuine community, shared conviction, and cultural significance. It can also produce misleading signals when coordinated activity is mistaken for independent market demand.

A transaction between two people can be genuine without demonstrating that a wider market shares their valuation. A recorded price is evidence of a particular exchange, not proof of universal desirability.

Living Canvas treats this tension as part of the subject it explores, rather than assuming that a recorded price is an objective measure of artistic worth.

The platform's responsibility is to describe its own measurements accurately and to distinguish documented facts from interpretation.

## 11. Membership and Sustainability

Living Canvas is designed around membership and participation rather than direct artwork sales.

A subscription model can support the infrastructure needed for:

- Generative image creation
- Artwork registration and provenance
- Collaboration tools
- Image processing and progress measurement
- Group management
- Member portfolios
- Artwork history and verification
- Price-history graphs
- Community features

Additional features may be introduced as the project develops.

Any future revenue from optional services should be clearly separated from artwork valuations and external transactions.

Membership should support the platform without making trading volume or rising prices a requirement for participation.

## 12. Transparency and Verification

Trust depends on distinguishing what the system knows from what it merely records.

Living Canvas should aim to make its technical and historical claims reproducible wherever practical.

Core principles include:

- Versioned generation and scoring algorithms
- Reproducible target images
- Timestamped layer records
- Traceable progress measurements
- Explicit protocol-price calculations
- Clear distinctions between reported and verified market events
- Transparent ownership and provenance updates
- Accurate historical price graphs
- Privacy-conscious treatment of participant information

The platform should not present protocol prices as independent valuations or market histories as proof of future demand.

Where price records are incomplete, the interface should make that limitation visible. Where a transaction cannot be verified, it should not be presented as independently verified.

The platform's purpose is to preserve a useful record of the artwork and the events surrounding it.

## 13. Technical Roadmap

### Phase 1 — Generative Engine

- Deterministic seed generation
- Title-based artwork creation
- Generator versioning
- Target image storage and identification
- Canvas aspect-ratio support

### Phase 2 — Physical Painting Workflow

- Canvas registration
- Camera-based image capture
- Perspective and color correction
- Layer documentation
- Initial progress-scoring system
- Instructions for successive painting stages

### Phase 3 — Collaborative Platform

- User accounts and portfolios
- Groups and shared artworks
- Layer contribution records
- Artwork completion workflow
- Member profiles and collaboration history

### Phase 4 — Provenance and Protocol Pricing

- Published protocol-price formula
- Versioned progress calculations
- Timestamped artwork histories
- Exportable artwork metadata
- Auditable event records
- Artwork identifiers

### Phase 5 — Price History and External Market Data

- Time-versus-euro price-history graphs
- Separate visualization of protocol prices, asking prices, bids, and completed sales
- Historical transaction records
- Import or submission of market-history data
- Verification and disclosure labels
- Price-history comparisons between artworks
- Links to external listings and marketplaces

The platform can remain independent of the external marketplaces where participants choose to trade.

## 14. Guiding Principle

Living Canvas begins with a simple proposition:

**An image can be generated by mathematics, realized through collective human effort, and given a social history through the people who gather around it.**

The resulting artwork exists simultaneously as an image, a physical object, a collaborative achievement, and a record of human decisions.

Its progress can be measured. Its creation can be documented. Its market history can be preserved and visualized.

People can explore its history, compare it with other works, and decide for themselves whether it interests them artistically, socially, or economically.

Living Canvas does not need to decide what art is worth.

It creates a framework in which the creation, measurement, ownership, and social life of art can be observed.
