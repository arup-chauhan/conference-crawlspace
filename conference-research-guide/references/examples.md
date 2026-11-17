# Interaction examples

These examples describe behavior. Titles and technical contexts here are hypothetical and must not be reported as discovered talks.

## Starting with only an event

User: "Use this skill. List the tracks at ExampleCon 2026."

Resolve editions. Browse the official program, label the edition whose tracks you show, and ask the user to confirm or choose a different edition. Do not fabricate one universal track list or begin downloads before the scope is clear.

## Starting with only an interest

User: "I want to learn about distributed databases."

Ask a short question about their purpose or level if necessary. Find a small set of real events or supplied collections and explain why each fits. Let the user choose. Do not require them to know track names or speakers.

## Expanding beyond a track

User: "I chose the data track, but also want autoscaling, benchmarking, working-group notes, and the architecture Company X presented."

Keep the selected track and broaden the search to the stated topics. Identify plausible Company X talks and clarify ambiguity without blocking other discovery. Look up actual community groups. Separate accessible minutes, proposals, abstracts, and vendor engineering sources. Offer experiments connected to the user's workload.

## Handling missing material

User: "Summarize the slides for these three talks."

Two decks download correctly. The third link returns an authentication page. Inspect the two actual decks, record the third gap, and offer abstract/recording coverage or a supplied deck. Do not count the authentication page as a downloaded presentation or attribute abstract text to slides.

## Delegated completion

User: "Choose the strongest material and make the report."

Use known goals and state any material assumptions. Select, collect, synthesize, and deliver without asking the user to approve each talk or routine step. Keep unsupported claims and unavailable material clearly labeled.

## Animated presentation

User: "Make an animated deck from the findings."

Inspect the host's authoring capabilities. Create the requested format when supported. If no format is specified and native authoring is unavailable, explain a browser-deck fallback and proceed. Include actual animations and test them. Keep illustrative workload numbers distinct from measurements.

## New user and new host

User installs the shared skill in a different environment.

Start from their own context. No local path, account, personal system, conference edition, API key, or connector from the author's environment is required. Use available tools, keep state in the task workspace, and explain missing capabilities when they affect the result.


## Explaining talks rather than proposing research

User: “Pull in context from the relevant talks, explain it using simpler models and illustrations, and make a deck.”

Expected behavior: inventory the relevant sessions, inspect available substantive material, make source briefs, then teach the mechanisms with cited illustrations and stepwise explanations. Label supplemental documentation and unavailable recordings. Proposed benchmarks may appear after the explanations if useful to the user's broader goal.

Failure to avoid: an attractive deck of talk titles, architecture suggestions, and experiments that never explains the talks themselves.


## Optional showcase discovery

User: “Research this conference for ideas to optimize our existing data service on Kubernetes.”

Expected behavior: establish the workload and goal, discover relevant talks, and offer the separate Solutions Showcase question when the event has one. While the answer is pending, continue independent talk research. A No excludes product crawling. An explicit request to include showcase products skips a redundant question.

After a Yes, inspect official listings and available primary product materials. A sponsor's demo of an existing product is classified as an existing-product demonstration unless dated evidence establishes a launch or update. Explain which mechanism could help the user's workload and what would need benchmarking. Do not present sponsorship as proof of technical fit.

User: “Add a Solutions Showcase option to this skill.”

Expected behavior: update the reusable workflow. This is not an opt-in to execute a showcase crawl for the current conference.
