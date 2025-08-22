![[An AI-powered workflow for collecting and understanding stories at scale]]

![[Abstract]]

![[015 causal mapping for evaluation/Reconstructing program theory empirically]] 

![[Causal mapping as a way to reconstruct program theory empirically]]

![[Steps in using causal mapping to gather evidence about structuretheory and contribution simultaneously]]

![[Steps in scaling the automated causal mapping workflow]] 

![[Previous work on each step]] 
![[Step 1 existing work Using an AI interviewer to gather causal information at scale]]
![[Step 2 existing work using automated causal mapping to code causal information at scale]] 

![[Step 3 existing work using causal mapping to help answer evaluation questions]]

![[Steps in the “AI-assisted causal mapping pipeline”]]

![[Results]] 

# **Discussion** 

**Question for Step 1 -** **can an AI interviewer successfully gather causal information at scale?****:** Our AI interviewer was able to conduct multiple interviews with no researcher intervention at a low cost, reproducing the results of [Chopra and Haaland (2023) and Geiecke and Jaravel (2024)](https://www.zotero.org/google-docs/?nzAgJV). The interview transcripts read quite naturally and the process seems to have been acceptable to the interviewees. 

**Question for Step 2 -** **can automated causal mapping successfully code causal information?****:** Automated coding was able to identify causal claims made by respondents. The coding was noisy, with 35% dropping at least one quality point, but with no evidence of *systematic* errors*.* This level of precision is adequate for sketching out “causal landscapes” but would not be for high-stakes evaluations without additional manual correction. The accuracy can also be substantially improved by getting the AI to revise its work, (see redacted). This procedure still involves the researchers making significant high-level decisions in the formulation of the coding instructions as well as, before analysis, in clustering similar factor labels into groups. We believe this coding approach using genAI represents a significant improvement over the more hard-coded approaches for identifying causal relationships expressed in text [(Dunietz, 2018; Dunietz et al., 2017; Rory Hooper et al., 2023;](https://www.zotero.org/google-docs/?mMCSuK) [Jiang et al., 2023; ](https://www.zotero.org/google-docs/?XePutn)[Yang et al., 2022)](https://www.zotero.org/google-docs/?ForqTu), and provides a more detailed, section-by-section coding which relies less on using AI as a black box to identify themes for initial coding [(Jalali and Akhavan, 2024)](https://www.zotero.org/google-docs/?D1sEVk) or to identify a global map [(Graham, 2023)](https://www.zotero.org/google-docs/?mZeZGN).

**Question for Step 3 -** **can automated causal mapping help answer evaluation questions?****:** An overview map was produced which included over 40% of the causal claims identified within the transcripts, using just 11 relatively broad factor labels. 

The most central factor with the highest number of citations was Economic stress, which is a plausible result, with plausible connections to other factors. 

We can use the map to identify and weigh up the evidence for contributions from and to individual factors. For example, the major contributions to Economic stress are Government policy and Covid-19, as well as “self-loops” mentioned by 46 sources, i.e. where one aspect of Economic stress was seen as causing another. 

All such results depend on the (not automated) decisions made during the clustering process: how many clusters to use, whether to intervene in labelling, etc. This situation is closely parallel to decisions facing a statistician who has to identify variables for, say, structural equation modelling [(Goertz, 2020: 136 ff)](https://www.zotero.org/google-docs/?Eu6HAG). 

Comparison of citation frequency across timepoints was able to show that some links were mentioned significantly more than others, illustrating how this kind of map could be used to explore changes in systems (or in mental models of systems) over time. 

## Caveats

### Ethics, bias and validity

This kind of AI processing is not suitable for dealing with sensitive data because information from the interviews passes to OpenAI’s servers, even though it is no longer used for training models [(OpenAI, 2024)](https://www.zotero.org/google-docs/?EbXseZ). 

[Head et al. (2023)](https://www.zotero.org/google-docs/?vHmYD8) and [Reid (2023)](https://www.zotero.org/google-docs/?mTFDnJ) raise concerns about bias and the importance of equity in AI applications for evaluation, which have led to questions about the validity of AI-generated findings [(Azzam, 2023)](https://www.zotero.org/google-docs/?AszCJK). The way the AI sees the world, the salient features it identifies, the words it uses to identify them, and its understanding of causation are certainly wrapped up in a hegemonic worldview [(Bender et al., 2021)](https://www.zotero.org/google-docs/?7Mxaw6). Those groups most likely to be disadvantaged by this worldview are approximately the same who have least say in how these technologies are developed and employed. 

AI is developing quickly: new models and techniques become available every month. However, we believe that any tools which genuinely add to knowledge should use procedures which are broken down into workflows consisting of simple individual steps so that humans can understand and check what is happening.

### Interviewing

Researchers should carefully consider whether the interview subject matter is compatible with this kind of approach. For example, the AI may miss subtle cues or struggle to provide appropriate support to respondents expressing distress [(Chopra and Haaland, 2023; Ray, 2023)](https://www.zotero.org/google-docs/?0A38Cv). We recommend that interview guidelines are tested and refined by human interviewers before being automated. No automated interview can substitute for the contextual information which a human evaluator can gain by talking directly to a respondent, ideally face-to-face and in a relevant context. 

There is likely to be a differential response rate in this kind of interview: some people are less likely to respond to an AI-driven interview than others, and this propensity may not be random.

### Causal mapping

Causal mapping is not at all suited for estimating the strength of causal effects: it can reveal the *strength of the evidence* for the influence of X on Y but this is not to be confused with the *strength of the effect* itself. There can be strong evidence for a weak link and vice-versa. 

### Autocoding

The work of the AI coder and clustering algorithms are not error-free. The coding of individual high-stakes causal links should be checked. In particular, there is a danger of accepting inaccurate results which look plausible.

This approach does not nurture substantive, large-scale theory-building of the kind expected, for example in grounded theory [(Glaser and Strauss, 1967)](https://www.zotero.org/google-docs/?FwD94y). However, it can do smaller-scale theory-building in the sense of capturing theories implicit in individuals’ responses. 

This pipeline relieves researchers of much of the work involved in coding but it is not fully autonomous. The human evaluator is responsible for applying the techniques in a trustworthy way and for drawing valid conclusions.

## Potential

**Qualitative approach:** These procedures approach the stakeholder stories as far as possible without preconceived templates, to remain open to emerging and unexpected changes in respondents’ causal landscapes. 

**Scalability and reach:** The AI’s ability to communicate in many languages presents an opportunity to reach more places and people, subject to internet access and the AI’s fluency in less common languages, and to include representative samples of populations.

The interview and coding processes are machine-driven and use zero temperature, so this approach should be mostly reproducible. Reproducibility opens the possibility of comparing results across groups, places and timepoints. 

The low cost of coding large amounts of information means that it is much easier to develop, compare and discard hypotheses and coding approaches, something which qualitative researchers have previously been understandably reluctant to do.

**Qualitative causality:** These procedures have the potential to help evaluators answer evaluation questions which are often causal in nature, like: understanding stakeholders' mental models; judging whether "their" ToC matches "ours"; investigating “how things work” for different subgroups of stakeholders; tracing impact from mentions of "our" intervention to outcomes of interest; triaging the key outcomes in stakeholders’ perspectives. 

In summary, this kind of semi-automated pipeline opens up possibilities for monitoring, evaluation and social research which were unimaginable just three years ago and are well suited to today’s challenging, complex problems like climate change and political and social polarisation. Previously, only quantitative research claimed to produce generalisable knowledge about social phenomena validly and at scale, by turning meaning into numbers. Now perhaps qualitative research will eclipse quantitative research by bypassing quantification and dealing with meaning directly, in somewhat generalisable ways. 

## Further work

We have tried to demonstrate a semi-automated workflow with which evaluators can capture stakeholders’ emergent views of the *structure* of a problem or program at the same time as capturing their beliefs about the *contributions* made to factors of interest by other factors. We have presented this approach via a proxy application but have since applied it in real-life research. Many challenges remain, from improving the behaviour of the automated interviewer through improving the accuracy of the causal coding process to dealing better with valence (for example distinguishing between “employment”, “employment issues” and “unemployment”). Perhaps most urgently needed are ways to better understand and counter how LLMs may reproduce hegemonic worldviews [(Head et al., 2023; Reid, 2023)](https://www.zotero.org/google-docs/?lWBvjV).

![[References]]



![[List of figure captions]] 
