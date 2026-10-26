# StoryScope findings for editorial review

## What the study does and does not show

StoryScope studies narrative structure in short fiction. Its parallel corpus contains 10,272 prompts, each paired with one human story and stories from five particular models: Claude Sonnet 4.6, GPT-5.4, Gemini 3 Flash, DeepSeek V3.2 and Kimi K2.5. Stories average 4,753 words. The authors extracted 304 features and report 93.2% macro-F1 for human-versus-model classification from narrative features on a length-matched test subset. These are group-level correlations for this corpus, these models and this method. They do not prove authorship of an individual passage, establish universal AI rules, or guarantee detector evasion.

The paper identifies 30 unique core features: 20 AI-elevated and 13 human-elevated, with three measured variables appearing in both lists under different categorical values (dominant emotional expression, reference explicitness and subplot integration). The 304 measured variables are not 304 validated “AI signs.” Model fingerprints are source-specific distinctions, not rules about all AI writing.

Use this catalogue as a set of fiction-review questions, not a rewrite recipe. **Preserve the author’s persona, meaning and voice.** Do not add ambiguity, subplots, chronology shifts, sensory detail or a different ending merely to look “more human.” Applications to nonfiction are editorial extrapolations, not findings tested by StoryScope. SlopMonster’s numerical checker score is separate and unchanged.

The examples below are brief original illustrations, not quotations or model-output samples.

## Complete core feature catalogue

### All 20 features elevated in the study’s AI stories

“Elevated” means a higher average score or prevalence across the five model sources, not that every model story contains the feature.

| # | Feature and reported direction | Voice-preserving editorial question | Quick illustration | Source |
|---:|---|---|---|---|
| 1 | Thematic explicitness and moralizing — higher | Does an explicit lesson belong to this narrator’s persona, or repeat what the scene already conveys? | After returning the key, Mara reflects that honesty is always best. | Table 14 #1, p. 24; Table 16, p. 26 |
| 2 | Dominant emotional expression — embodied metaphors more prevalent | Is bodily imagery characteristic of this voice, or mechanically attached to every feeling? | Grief settles like a stone behind Arun’s ribs. | Table 14 #2, p. 24; Table 16, p. 26 |
| 3 | Thematic unity — higher | Does the tight thematic pattern serve the design, or flatten intentional tensions? | The clock, missed train and late apology all reinforce patience. | Table 14 #3, p. 24; Table 16, p. 26 |
| 4 | Dominant sensory modalities — olfactory more prevalent | Does the smell matter to this viewpoint and scene? | The stairwell smells of bleach and wet wool. | Table 14 #4, p. 24; Table 16, p. 26 |
| 5 | Character introduction — external description more prevalent | Would this narrator first notice appearance, or action, speech or thought? | Lena enters as a tall woman in a silver coat. | Table 14 #5, p. 24; Table 16, p. 26 |
| 6 | Setting as psychological mirror — higher | Is the environment intentionally echoing the character’s state? | Clouds close over the house as Jo’s hope fails. | Table 14 #6, p. 24; Table 16, p. 26 |
| 7 | Continuity of the main causal chain — higher | Is the clean cause-and-effect line the intended form, or has the voice lost useful digression? | She finds the letter, confronts her brother and leaves town. | Table 14 #7, p. 24; Table 16, p. 26 |
| 8 | Sensory density — higher | Which details would this persona truly register, and which merely decorate? | Cold rain, copper air and shoe squeaks fill the station. | Table 14 #8, p. 24; Table 16, p. 26 |
| 9 | Agency in resolution — protagonist choice more prevalent | Does the protagonist’s decisive act fit the story’s conception of agency? | He signs the confession, ending the family’s standoff. | Table 14 #9, p. 24; Table 16, p. 26 |
| 10 | Narratorial thematic commentary — “yes” more prevalent | Is the narrator entitled, by persona and distance, to state the theme? | The narrator adds that forgiveness is the price of change. | Table 14 #10, p. 24; Table 16, p. 26 |
| 11 | Opening spatial grounding — clearer/higher | Would this voice orient the reader immediately, or is disorientation purposeful? | At dawn in the hospital’s east wing, Nia waits. | Table 14 #11, p. 24; Table 16, p. 26 |
| 12 | Dialogue function — philosophical debate more prevalent | Do these characters plausibly debate ideas in this register? | “What is justice,” he asks, “if not memory’s debt?” | Table 14 #12, p. 24; Table 16, p. 26 |
| 13 | Spatial granularity — higher | Does this focal character need to map the setting so precisely? | The hall has three doors, two alcoves and a west window. | Table 14 #13, p. 24; Table 16, p. 26 |
| 14 | Subplot integration — no subplots more prevalent | Is the single thread deliberate, or did revision erase material the work needs? | One decision occupies the story; no secondary thread develops. | Table 14 #14, p. 24; Table 16, p. 26 |
| 15 | Moral/philosophical weighting — higher | Does the persona naturally foreground the moral problem this heavily? | Every conversation returns to whether loyalty excuses a lie. | Table 14 #15, p. 24; Table 16, p. 26 |
| 16 | Reference explicitness — implicit echoes more prevalent | Would this voice hint at the source rather than name it? | A forbidden-room motif appears without naming *Bluebeard*. | Table 14 #16, p. 24; Table 16, p. 26 |
| 17 | Environmental/ecological emphasis — higher | Is ecological attention integral to the story’s values and viewpoint? | Changes in the river shape each household’s choices. | Table 14 #17, p. 24; Table 16, p. 26 |
| 18 | Mode of resolution — internal understanding more prevalent | Is inward acceptance a true resolution in this character’s terms? | She understands why he left, though nothing external changes. | Table 14 #18, p. 24; Table 16, p. 26 |
| 19 | Pre-threat character investment — higher | Is the long calm setup proportionate to the later jeopardy? | Three domestic scenes establish the routine before danger arrives. | Table 14 #19, p. 24; Table 16, p. 26 |
| 20 | Depth of interior access — higher | Does deep explanation fit the narrative distance, or restate action and dialogue? | After refusing the offer, he privately rehearses every reason. | Table 14 #20, p. 24; Table 16, p. 26 |

### All 13 features elevated in the study’s human stories

These are contrasts in the corpus, not instructions for making prose “human.” In particular, **explicit emotional labels are more common in the human stories** (29% versus 8% AI), not less common.

| # | Feature and reported direction | Voice-preserving editorial question | Quick illustration | Source |
|---:|---|---|---|---|
| 1 | Intertextual strategy types — explicit named reference more prevalent | Would this persona know and name the source? | She calls the locked room her own *Bluebeard* chamber. | Table 15 #1, p. 25; Table 16, p. 26 |
| 2 | Frequency of direct reader address — higher | Does direct address belong to the narrator’s relationship with the reader? | You know the silence that follows a bad toast. | Table 15 #2, p. 25; Table 16, p. 26 |
| 3 | Reference explicitness — balanced mix more prevalent | Is the mix of named and unstated allusion intentional? | One myth is named; another is left as an echo. | Table 15 #3, p. 25; Table 16, p. 26 |
| 4 | Depth of recontextualization after surprise — higher | Should the revelation substantially change how earlier scenes read? | The neighbor’s helpful questions become evidence of her search. | Table 15 #4, p. 25; Table 16, p. 26 |
| 5 | Dialogue-to-narration proportion — higher | Does more spoken exchange fit the scene’s pace and voices? | The quarrel unfolds in speech rather than narrated summary. | Table 15 #5, p. 25; Table 16, p. 26 |
| 6 | Fourth-wall permeability — higher | Does acknowledging the audience fit the narrator’s persona? | I will spare you the third committee meeting. | Table 15 #6, p. 25; Table 16, p. 26 |
| 7 | Subplot integration — thematically parallel more prevalent | Does the secondary thread deepen or complicate the theme? | A neighbor’s estrangement offers a second view of forgiveness. | Table 15 #7, p. 25; Table 16, p. 26 |
| 8 | Degree of chronological discontinuity — higher | Do time jumps serve memory, disclosure or voice? | A hospital scene cuts to the patient’s first day in town. | Table 15 #8, p. 25; Table 16, p. 26 |
| 9 | Location variety scope — higher | Does moving among more places enlarge the story, or dilute its chosen confinement? | The action moves from harbor to farm to courthouse. | Table 15 #9, p. 25; Table 16, p. 26 |
| 10 | Anachrony intensity — higher | Is heavier use of flashback or flashforward structurally meaningful? | Repeated memories interrupt the hearing and revise its stakes. | Table 15 #10, p. 25; Table 16, p. 26 |
| 11 | Moral polarity toward protagonist — ambivalent/mixed more prevalent | Does moral ambiguity belong to the work’s ethical stance? | Keeping the secret protects one person and harms another. | Table 15 #11, p. 25; Table 16, p. 26 |
| 12 | Dominant emotional expression — explicit labels more prevalent (29% human, 8% AI) | Would this persona name the feeling directly? | She was angry, and she wanted him to know it. | Table 15 #12, p. 25; Table 16, p. 26 |
| 13 | Nonlinear framing for delayed disclosure — higher | Does rearranging disclosure create the intended re-reading? | The consequence appears first; the cause arrives much later. | Table 15 #13, p. 25; Table 16, p. 26 |

## Complete fully specified AI fingerprint catalogue

Table 17 is abridged: it gives the top five fingerprints for each source, or all when fewer exist. An arrow supplies a categorical value; for a scalar or bare variable name, Table 17 reports importance and uniqueness but **not which direction** is characteristic. Section 5 supplies direction for some of those variables. The example in each row illustrates the label only; it is not evidence of direction.

| Source | Rank | Fingerprint and source-bounded direction | Quick illustration | Source |
|---|---:|---|---|---|
| Claude | 1 | Strength of event escalation — less escalation than any other source (§5) | A dispute stays low-key instead of building into crisis. | Table 17, p. 27; §5, p. 9 |
| Claude | 2 | Event-type diversity — important variable; direction not stated | A story alternates conversation, travel and discovery. | Table 17, p. 27 |
| Claude | 3 | Ending temporal scope — epilogue/flashforward | The last page jumps ahead twenty years. | Table 17, p. 27 |
| Claude | 4 | Dreams/visions as temporal distortion — no | Every time shift occurs in waking narration. | Table 17, p. 27 |
| Claude | 5 | Setting mood — uncanny/haunted | Empty rooms seem to listen after midnight. | Table 17, p. 27 |
| GPT | 1 | Role of gossip and rumor — salient | A neighbor’s rumor triggers the inquiry. | Table 17, p. 27 |
| GPT | 2 | Narrator temporal distance — distant retrospective | The narrator recalls the summer from forty years later. | Table 17, p. 27 |
| GPT | 3 | Reader-expectation strategy — subverts | The apparent rescuer is the person being rescued. | Table 17, p. 27 |
| GPT | 4 | Iterative/habitual narration — no | The narration presents one dinner, not what happened every Sunday. | Table 17, p. 27 |
| GPT | 5 | Reconciliation/forgiveness — partial/ambiguous | The sisters exchange keys but do not embrace. | Table 17, p. 27 |
| Gemini | 1 | Protagonist social trajectory — expands | A recluse ends with a widening circle of allies. | Table 17, p. 27 |
| Gemini | 2 | Balance of speech — primarily direct | The meeting is rendered mostly as quoted conversation. | Table 17, p. 27 |
| Gemini | 3 | Global narrative schema — siege/ordeal | The household endures three nights under attack. | Table 17, p. 27 |
| Gemini | 4 | Naming practice — named personal name | The stranger is introduced as Elena Márquez. | Table 17, p. 27 |
| Gemini | 5 | Global chronological structure — frequent flashbacks | The present action repeatedly returns to the old voyage. | Table 17, p. 27 |
| DeepSeek | 1 | Narrator presence/visibility — important variable; direction not stated | “I should admit that I misread the letter.” | Table 17, p. 27 |
| DeepSeek | 2 | Emotional expression — behavioral cues | He folds the receipt into smaller and smaller squares. | Table 17, p. 27 |
| DeepSeek | 3 | Plot-versus-atmosphere orientation — important variable; direction not stated | The scene’s main work is either an event turn or a sustained mood. | Table 17, p. 27 |
| DeepSeek | 4 | Backstory placement — evenly interleaved | Each present scene is paired with a short piece of the past. | Table 17, p. 27 |
| DeepSeek | 5 | Embedded storytelling scenes — important variable; direction not stated | At supper, the aunt tells the legend of the flooded church. | Table 17, p. 27 |
| Kimi | 1 | Character introduction — in-action event | Tomas arrives while climbing through the window. | Table 17, p. 27 |
| Kimi | 2 | Narrative entry frame — in medias res | The first sentence opens midway through the chase. | Table 17, p. 27 |
| Kimi | 3 | Explicit trait labeling — no | Her evasive answers imply caution without calling her cautious. | Table 17, p. 27 |

For comparison, Table 17’s five fully specified human rows are: character introduction **in dialogue** (“Mina, stop arguing” introduces her); breadth of focalization **single focal** (every scene stays with Mina); narrator-address mode **no direct address** (the narrator never says “you”); revelation pacing **back-loaded** (the decisive fact arrives near the end); and literary ambition **crossover genre** (a crime plot is treated with literary interiority). These are source-attribution fingerprints, distinct from the binary human-elevated core features above (Table 17, p. 27).

### Named but incompletely specified fingerprint variables

Table 17 names the following additional variables parenthetically but omits their rank, SHAP value, uniqueness ratio, categorical value and direction. They must not by themselves be converted into claims that a source has “more,” “less,” “high” or “low” of the feature. Section 5 independently makes some broader observations about closure and endings, listed later; the paper does not explicitly map those prose observations to these encoded variables. Examples illustrate only what the label might denote.

| Source | Named variable only | Quick illustration of the label | Source |
|---|---|---|---|
| Human | Visibility of withholding | The narrator signals that a fact is being held back. | Table 17, p. 27 |
| Human | Atmospheric techniques | Fog, sound and pacing sustain unease. | Table 17, p. 27 |
| Human | Subplot density | Several secondary story lines accompany the main one. | Table 17, p. 27 |
| Human | Naming | A character is named, titled or left unnamed. | Table 17, p. 27 |
| Human | Twist placement | A reversal occurs at the midpoint or near the end. | Table 17, p. 27 |
| Claude | Event density | Many or few discrete events occur per span. | Table 17, p. 27 |
| Claude | Conflict modality | Conflict is physical, social, internal or another type. | Table 17, p. 27 |
| Claude | Relationship trajectory | A bond strengthens, weakens or changes form. | Table 17, p. 27 |
| Claude | Heteroglossia | Several socially distinct voices coexist. | Table 17, p. 27 |
| Claude | Closure | The ending settles or leaves open major questions. | Table 17, p. 27 |
| GPT | Community salience | A neighborhood matters to the central action. | Table 17, p. 27 |
| GPT | Social emphasis | The narration attends to alliances and status. | Table 17, p. 27 |
| GPT | Reader competence | The text assumes the reader can infer an unstated link. | Table 17, p. 27 |
| GPT | Individualization | A minor figure receives a distinguishing habit. | Table 17, p. 27 |
| GPT | Psychological depth | Motives are explored across competing impulses. | Table 17, p. 27 |
| Gemini | Secondary-character density | Many or few secondary characters occupy the story. | Table 17, p. 27 |
| Gemini | Batch introduction | Several characters arrive in one passage. | Table 17, p. 27 |
| Gemini | Authority stance | The narrator sounds certain or qualified about events. | Table 17, p. 27 |
| Gemini | Setting mood | The setting is coded as welcoming, bleak or uncanny. | Table 17, p. 27 |
| Gemini | Community | A collective participates in the outcome. | Table 17, p. 27 |
| Gemini | Closure | The ending closes or preserves narrative questions. | Table 17, p. 27 |
| DeepSeek | Seasons/cyclical time | Annual floods frame the story’s recurrence. | Table 17, p. 27 |

The ellipses in Table 17 indicate still more unnamed fingerprint variables. The appendix says the counts are Human 32, Claude 26, GPT 11, Gemini 11, DeepSeek 7 and Kimi 3, which sum to 90, while the methods text says the procedure yields 75 fingerprint features. The paper does not reconcile that discrepancy. This guide therefore reports all 23 fully specified AI rows and all additionally named variables, but does not invent the omitted list.

## Directional observations in Section 5

These observations describe distributions or experimental results, not individual-text diagnoses. The quick examples are analogies or miniature story illustrations, not paper quotations.

| Observation | Quick illustration | Source |
|---|---|---|
| Six-way attribution from 257 narrative features reached 68.4% macro-F1, above the 16.7% chance baseline but below narrative-plus-style at 77.3%. | Structural choices help separate six source labels, but adding surface style helps more. | §5, p. 8 |
| Narrative features outperformed style-only by 8.0 macro-F1 points; core plus fingerprints outperformed core only by 16.8 points. Raw-text baselines were much stronger (at least 99.5%). | Source-specific structure adds signal, while raw wording remains highly diagnostic in this experiment. | §5, p. 8 |
| Human was most separable (93.0% F1 with style, 88.5% without), then Claude and GPT; DeepSeek, Gemini and Kimi formed the more confused cluster. | A DeepSeek-like story is more readily confused with Gemini than a human story is with Claude. | §5, pp. 8–9 |
| AI sources overlapped one another and were separated from the human region; all six most-confused pairs were AI-to-AI. Mean human-to-AI centroid distance was 1.6× mean AI-to-AI distance, and even the closest human/AI pair was farther apart than the most distant AI/AI pair. | Two model stories may share a nearby feature profile even when both sit farther from the human center. | §5, p. 9 |
| Human stories were more dispersed: mean distance from their centroid was 22% greater than the average AI radius, and median local-neighbor radius was 1.13× larger. | Human stories occupy a wider range of structural combinations in this corpus. | §5, p. 9 |
| Human stories were rarer by the paper’s neighbor-distance measure: mean percentile 0.71 versus 0.49; 24.7% versus 7.1% occupied the top-10% rarity tail, and 3.0% versus 0.6% the top 1%. Within prompt-matched sets, the human story was rarest 57.8% of the time. | An unusual combination might pair a cramped setting, many time jumps and an unresolved side plot. | §5, p. 9 |
| Claude had the most distinctive AI profile and the least event-intensity escalation. | A disagreement remains restrained rather than becoming a showdown. | §5, p. 9 |
| Claude’s narrative voice was the most uniform. | The narrator maintains the same measured register through domestic, comic and dangerous scenes. | §5, p. 9 |
| Claude more often took a reverent/continuist approach to literary tradition (62% versus 39–56% for other sources). | A mythic quest extends familiar conventions instead of overturning them. | §5, p. 9 |
| Claude favored epilogues, avoided dream sequences and favored quiet over “avalanche” endings. | Years later, the protagonist calmly plants a tree rather than resolving several crises at once. | §5, p. 9 |
| GPT used gossip/rumor as a plot mechanism more often (64% versus 44–55%). | A whispered affair sets the investigation in motion. | §5, p. 9 |
| GPT tended toward reflections on events years or decades earlier. | An old teacher narrates the strike from retirement. | §5, p. 9 |
| GPT used ensemble-heavy social networks at levels matching the human stories. | Six relatives’ alliances matter to the inheritance dispute. | §5, p. 9 |
| GPT subverted expectations more than the other AI sources (41% versus 27–36%) and left reconciliations ambiguous. | The expected villain helps, while the final handshake may be strategic. | §5, p. 9 |
| DeepSeek front-loaded crucial context that other sources left until later. | The opening immediately explains who owns the disputed house. | §5, p. 9 |
| Gemini produced the tidiest endings. | The culprit, inheritance and relationship are all settled before the last line. | §5, p. 9 |
| Gemini produced extended denouements. | Three aftermath scenes follow the climax. | §5, p. 9 |
| Gemini produced the bleakest settings; 88% were tagged bleak and oppressive. | Ash, locked gates and failing lights dominate the town. | §5, p. 9 |
| Kimi had the fewest fingerprints and lowest attribution F1, occupying the generic center of the AI distribution without a distinctive narrative choice in this analysis. | Its feature mix resembles several neighboring model profiles rather than one sharply isolated pattern. | §5, p. 9 |

## Surface cues, editing experiment and limits

- Section 1 cites prior work reporting overused em dashes and words such as “delve” and “tapestry” as surface cues. Quick examples: “The answer—unexpectedly—was below”; “we delve into the archive”; “a tapestry of memory.” StoryScope does not newly validate these as universal indicators (§1, p. 2).
- Section 4.2 says the earlier LAMP framework identifies seven surface-artifact categories, but StoryScope names only three examples: cliché (“a deafening silence”), redundant exposition (“He left the room; he was no longer inside”) and purple prose (“The empurpled heavens wept jeweled sorrow”). Do not invent the other four from this paper (§4.2, p. 8).
- On 278 Gemini-generated stories, the narrative classifier scored **95.5% macro-F1 on the original unedited stories and 93.9% after LAMP editing**, a 1.6-point drop. This tests whether narrative classification survives one surface-editing setup; it does not make those surface artifacts new StoryScope signs (§4.2, p. 8).
- Human and model distributions overlap substantially. Model attribution is notably weaker than human-versus-AI classification, and DeepSeek/Gemini/Kimi are especially confusable. Treat every item as a review prompt, never a verdict (§5, pp. 8–9).

## Source

Russell, Jenna, Rishanth Rajendhran, Chau Minh Pham, Mohit Iyyer and John Wieting. “StoryScope: Investigating Idiosyncrasies in AI Fiction.” COLM 2026; arXiv:2604.03136v6, 10 August 2026. [Paper (PDF)](https://jenna-russell.github.io/assets/pdf/storyscope.pdf) · [arXiv record](https://arxiv.org/abs/2604.03136). The paper is released under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/).
