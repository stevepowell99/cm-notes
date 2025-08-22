# Why do causal mapping rather than ordinary qualitative coding?

in a google doc atm https://docs.google.com/document/d/1kXrH6pdKSvVNVEsRoZCw4GlN87L7m8x65lHtWk-ZbMo/edit?tab=t.0

Causal mapping has traditionally been done manually, just like working with Nvivo, but instead of coding individual _themes_ we code _links between themes (aka causal factors)_. For example in the text “then the teacher said that the children are now much more active due to the new playground”, we would code “the new playground” as the cause, “the children are now much more active” as the effect, “the teacher” as the source and the whole sentence as the associated quote or evidence.  The coding is nowadays entirely done by AI. But human input is crucial, in particular to craft the instructions to the AI and in deciding how to cluster and label similar themes. The software automatically constructs maps and tables to answer specific questions, e.g. “what drives poverty, from the point of view of the women?”.

----------

**# Causal mapping: an unusually useful form of qualitative coding?

Our aim is to present causal QDA as a particularly useful way to make sense of text in a way which is straightforward to apply with a highly, though not completely, standardised approach.  

Our steps in doing this are: 

- We present causal QDA as an important and useful form of QDA
    
- We explain why causal coding can be easier to apply than non-causal coding. 
    
- We explain how it gives us causal maps “for free”, which can be used to answer useful questions.
    

Although the focus of this paper is not on AI assistance, we also argue that these properties make causal mapping particularly suitable for automation with AI in a way which is verifiable and avoids using the AI as a “black box”.

## What is causal mapping?

Causal mapping helps make sense of the causal claims (about "what influences what") that people make in interviews, conversations, and documents. This data is coded, combined, and displayed in the form of a causal map. Each claim adds a link to the map. These maps represent individuals' and groups' mental models: individual links and (often interlocking) longer chains of causal explanations. For every link, we can store the original sources and quotes.

  

Causal mapping has been used across multiple disciplines for over 50 years [(Ackermann et al., 2004; Axelrod, 1976; Eden, 1992; Hodgkinson et al., 2004; Laukkanen, 1994; Narayanan, 2005; Powell et al., 2024)](https://www.zotero.org/google-docs/?7MjFBb), but though some causal mapping practitioners have published guides to causal coding, it has not often been presented as (also) a stand-alone form of QDA. We tried to rectify that in [(Powell et al., 2024)](https://www.zotero.org/google-docs/?0TB0AV). This paper follows on from that explication.

## What is causal QDA?

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXf799gcLwZ-_-O6I25u5YHKKiL1E3u72B418GPJkt9X5nPD7nB443zfhJa1X6Rtb7UwKumcRvs3GYd8-P4JEeF1AggoxncG9Y6EC_LV_DhJB8zNssVGND0y-bD7kVsNl2_CsjHYOg?key=HqSC1Nnmz1P6ho1HY9VSBCMB)

Some forms of causal mapping may involve constructing maps directly, for example in participatory fashion with a group of people. In this paper we don’t cover that method. Here, we do causal mapping by coding causal claims within text, what we call "causal QDA".  So this is a less participatory approach. This task is similar to other forms of qualitative data analysis (QDA). However, non-causal QDA is designed to capture concepts in general, whereas in causal QDA we code (claimed) causal links between causal factors: things, events, phenomena, changes: anything which can affect or influence, or be affected or influenced by, something else. Using non-causal QDA we can create post-hoc causal links between independent concepts as in the figure above, version 2. Or we can create the causal link as a monolithic concept as in version 1. But then the word “cause” does not really do anything: we can’t automatically deduce anything from it. In causal QDA, the primary act of coding is to highlight a specific quote from within a statement and identify the causal claim made by simultaneously identifying a pair of causal factors: a "cause" and an "effect". In causal QDA, we only code causal claims. The causal factors only exist as one or other end of a causal link and have no meaning except in their role as either end of a causal link. The coding Floods happened → Crops destroyed IS a causal link, and a set of such links can be immediately visualised as a network or map using suitable software – even [Excel](https://causalmap.notion.site/Coding-with-Excel-f5d2ea5542004d28882f67613bef1850). In causal coding, the result of each act of coding is a pair of factors (an ordered pair, because B → C is not the same as C → B). It is the factors which are the atomic units, which form the codebook, even though the factors only make sense as part of causal links. 

  

## An emergent-reproducible spectrum in QDA?

Before we get to the logic of causal QDA, let’s present what we might call an emergent/reproducible spectrum within QDA more generally. We will then place causal QDA on this spectrum.

In emergent forms of QDA:

- The design is not pre-determined but emerges: Yvonna Lincoln & Egon Guba (1985): there is no clear distinction between the method and the output. As Braun and Clarke describe in thematic analysis, an inductive approach “is grounded in the qualitative data itself, enabling researchers to identify patterns and derive key themes without the constraints of pre-existing categories”​ xx
    
- Analysis is interpretative rather than systematic. The product is interpretive text, not a structured model. It’s usually a report, paper, a narrative synthesis of themes.
    
- Answers are mediated by the author. You need the author (or a reader-analyst) to interpret the analysis and answer your questions.
    
- It’s not machine-readable. You can’t automate reasoning over it or extract structured inferences without re-coding it.
    

- More interested in a general theory a la Glaser and Strauss [(1967)](https://www.zotero.org/google-docs/?broken=5JrRzk).
    

Reproducible designs on the other hand tend to propose:

- Pre-registration of questions and methods.
    
- More emphasis on a top-down or deductive deconstruction of high-level questions into simpler tasks.
    
- A greater chance of being able to reproduce similar results with similar inputs.
    
- More interested in a case-specific summary as in Mayring [(1991)](https://www.zotero.org/google-docs/?broken=Glvgcf) rather than a global theory. 
    

We do not claim that any form of QDA is truly reproducible; we use reproducible as a name for an idealised pole of a spectrum opposite the other pole, “emergent”.

Every form of QDA involves at least to some extent breaking down hard, high-level questions into simpler tasks which are at least somewhat more traceable and verifiable than the original questions. In more "emergent" traditions we might start with the vaguest of research questions and refine the questions and the methodology as part of the process,"making up the rules as we go along". The positionality of the researcher is central[(Copestake et al., 2019)](https://www.zotero.org/google-docs/?5vszGn). In more reproducible approaches, the balance is more heavily algorithmic and the outputs are closer to being machine-readable answers to pre-determined, even pre-registered, questions, though the researcher still has to make crucial decisions at various points (“human in the loop”). 

Reproducible QDA at least partially encodes claims in a structured, somewhat machine-readable form. It supports decentralized interpretation: once the output exists, anyone can inspect, trace, and reason over it without needing to consult the author.

  

Like Patton we affirm a “paradigm of choices” – balancing flexibility with appropriate methodological structure for the situation​ xx[scholar.lib.vt.edu](https://scholar.lib.vt.edu/ejournals/JTE/v9n1/hoepfl.html#:~:text=complex%20and%20dynamic%20quality%20of,example%2C%20Russek%20and%20Weinberg) Each application involves some balance between these two extremes, on various subdimensions, where we might characterise the disputes between Glaser and Strauss & Corbyn as about the introduction of at least a degree of pre-structured methods, a smidgen of reproducibility.

  

Spoiler: Causal QDA lies at the latter, reproducible, end of this spectrum. 

## The logic of QDA: you’ve done your analysis, now what?

The result of qualitative data analysis can be understood as, at least, some kind of qualitative theory or model at least of the sources’ beliefs, with at least some possibility of generalising beyond them. But it can be hard to know what to do with the results of an emergent qualitative text analysis. There is no clear decision procedure: we can ask the author, and the answer is: some explanation, i.e. more text. In more reproducible approaches we do get some more structured outputs such as tables of frequencies. Some authors such as Mayring see these kinds of outputs as an important analysis result. QDA software is often used to capture and structure and even make inferences with these kinds of outputs. 

In the logic of (non-causal) reproducible QDA, we can do things like this:

- - count occurrences of concepts, and use ordinary arithmetic to report eg which of two concepts was more common
    
- - count co-occurrences of two concepts, and construct measures like association between concepts, and more generally combine and query occurrences with boolean logic
    
- - create case/code matrices
    
- - report relationships between sources and concepts, for example to compare codings of one concept for different genders
    
- - reason about concepts, for example to deduce that an occurrence of "lion" is also an occurrence of "mammal", either relying on our implicit understanding of the concepts or through the explicit declaration of a parent-child relationship. 
    

  

Of course frequency statistics are notoriously unstable, because they depend on our decisions about granularity and chunking. If I have a codebook which has 100 different codes for cats and only 1 code for dogs, we may conclude that dogs were mentioned in the text more often than any other animal-concept even if cat-concepts were mentioned more often in combination.  This is one reason why reasoning with these kinds of outputs can never be merely automated. There always has to be a “human in the loop”. Nevertheless the point is that we can understand the output of QDA coding as some proportion of "more text", which itself needs to be interpreted by humans, and a complementary proportion of machine-readable, structured output which can be used to ask and answer questions (Which are the overarching themes? How much does climate anxiety come up as a theme? Who mentions it most?) at least somewhat independently of human guidance. 

  

QDA logic can also be extended beyond the simple logic of frequencies and occurrences to apply (special kinds of) codes which have additional explicit rules associated with them, such as code weighting (as for example in MaxQDA). This means we can for example apply codes like “somewhat happy” or ‘very unhappy’ which enable us to say that the expression of happiness in one case is stronger than the other, or (if we also allow coding for time) that happiness increases or decreases over time. These extra deductions we can make come free with the (implicit or explicit) underlying ordinal logic of comparison of intensity.

  

### QDA without coding

Coding does not have to be central to qualitative data analysis [(Morgan, 2025; Nguyen-Trung & Nguyen, 2025)](https://www.zotero.org/google-docs/?kIV7Qv). …

  

## What are the advantages of causal over non-causal QDA?

### The additional logic of causal QDA lets us ask and answer additional questions

  

In the ontology of causal QDA, we have factors, which are something like concepts, and also links, which are ordered pairs of factors. We can immediately make use of all of the frequency/occurrence logic mentioned above for both factors and links, e.g. to report which was the most commonly mentioned causal factor and/or which was the most commonly mentioned causal link. The same caveats about granularity and frequency apply (here and also in the following section).

  

But that is just the start of it. In addition, any set of links can also be understood as a network. We don't need to do any extra work, we can simply display and query the network using any suitable algorithm or software. There is a whole wealth of [causal-belief logic](https://www.causalmap.app/resources/open-source-cm-functions/) we can (tentatively) apply here to ask and answer practical questions.

  

Causal coding allows us to make free use of the logic of causal mapping to do causal-belief analysis: to ask and answer questions and make deductions. 

##### We can ask questions about the causal map overall:

- Leveraging our ability to count the frequency with which particular links are mentioned, we can, with caveats, interpret the frequency with which a link is mentioned as the strength of the evidence for that link. 
    
- - which factors are causally central or causally peripheral? 
    
- - which factors appear most often at (or near) the end of causal chains, and which appear at (or near) the beginning?: which factors appear proportionately more often as outcomes than as drivers?
    

  

##### We can ask questions anchored to specific factors

For example, 

- we can ask about all the immediate causes or effects of a particular factor or set of factors, 
    
- or we can ask about both causes and effects, to produce the local neighbourhood or "ego network" xx.
    

##### Most interestingly we can ask about chains anchored to specific factors. 

A fundamental, emergent property of networks is (with caveats) transitivity: being able to ask questions not just about links but about chains. 

- All the questions mentioned above about links we can also apply to arbitrary chains. So for example we can ask how often a particular chain is mentioned, or mentioned by women.
    
- We can list all of the factors downstream of a particular factor of interest. Here, there is a lot to be said about transitivity (when and where we can, from B → C and C → D, conclude B → D). 
    
- For example if the same source who claims Floods happened → Crops destroyed, in the same context also says that Crops destroyed led to going hungry, we can deduce that perhaps this person attributes going hungry indirectly to the floods.
    
- Likewise, we can list all the factors upstream of a particular factor (or set of factors)
    
- Likewise, we can list all the factors between an origin factor (or set of factors) and a target factor (or set of factors), again optionally up to a certain length of chain, which Bougon called xx. In terms of program evaluation, we can think of this as all the causal chains from one or more interventions of interest to one or more outcomes of interest.
    
- All the logic which we can apply to the whole network can be applied to arbitrary chains or subnetworks. For example we can ask how robust overall is the network of evidence for the influence of X on Y? (for which we have proposed the maximum flow / minimum cut algorithm). 
    

  

Causal mapping also gives us some additional, optional tools (like [hierarchical causal coding](https://guide.causalmap.app/hierarchical-coding/) and [opposites coding](https://guide.causalmap.app/opposites/) and coding links with hashtagsxx) for organising its elements in a way which will help answer additional practical questions, which we will however not cover here.

  

### Coding the strength of a link, and why we don’t do that

Many or most causal mapping approaches, including Causal Loop Diagrams, also code the perceived strength of a causal link. This means that the factors become variables which can take values between, say, low and high or positive and negative, and we can make a much broader range of inferences using some form of numerical modelling. This can be seen as the extreme reproducible end of our spectrum and borders on quantitative approaches. 

However we do not go so far: our causal factors are closer to being propositions rather than variables and we do not jump to code, say, poverty as negative wealth, or unemployment as obviously just the opposite of employment.

  

Generally all forms of causal mapping have been less interested in finding general rules but only in modelling a more or less specific case or set of cases. But causal mapping has been used for causal meta-analysis, for example of sets of existing evaluation reports (see Powell (2020) for an example).

  

### Why a more restricted, causal, ontology helps cut to the chase in asking and answering useful questions

  

The result of causal QDA is not just a report or an essay, but a network, a map, already structured to answer questions about causal beliefs. Many practical, real-world questions are at least partly causal in nature: what leads to what? why does Z happen? what might happen if X? what are the dominant explanations for Y?. Causal mapping gives us a causal vocabulary which provides some semi-standard ways not only to ask but also to answer those kinds of causal questions (e.g. what is the collected evidence for a causal path from X to Y?.  For which pathway is there most evidence? According to the women only?)

We should stress that even here, we very much need a human in the loop, for instance in order to:

- Pay attention to problems of chunking (where do phenomena begin and end) and granularity (how big are the chunks) 
    
- The transitivity trap
    
- While we can be guided by relative frequencies of links, we always consider the specific (combined) evidence for each link, for example when some evidence might be weak or valid only for a specific context
    

  

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXfJ2Nw_YsKTnRxJWflVGeqCRb7QweXvNnTrYk5N3771gjLkj_dv8zQticbUY2_ly-uCt9mkypy9LKUSeBnQu5JAKexX2cyJoimOH6QzFGu-XEvAU7zwFiXbWNBuTg0N9cBYaJzynw?key=HqSC1Nnmz1P6ho1HY9VSBCMB)

### A more restricted, causal, ontology simplifies the construction and development of a codebook

"What are the causal factors, the cause and the effect, at each end of this causal claim" … is a very challenging question, but it is a whole ballgame less challenging, less open, than "what themes/concepts are mentioned here". This fact makes it much easier to get started on and complete our coding, whether we are going to code deductively (from an established codebook) or inductively (developing the codebook iteratively). It is particularly easy when working inductively and using in-vivo labels close to the original text: we simply have to identify each and every causal claim in the text, and for each one, identify the cause and the effect – the “causal factors”. (Using in-vivo labels means we then need another way to consolidate the resulting large number of factor labels.) Inter-rater agreement in causal coding is good [(Buzogany et al., 2024; McCardle-Keurentjes et al., 2018)](https://www.zotero.org/google-docs/?tRWcaj). This means that we can reduce most of causal coding to a series of low-level tasks: code each and every causal link.

### Inter-rater agreement for causal coding is high, making it suitable for automation with AI

The fact that causal coding can be largely reduced to a series of low-level tasks makes it very suitable for automation with AI. High [precision and recall scores](https://drive.google.com/file/d/1-1SjT7B86BFn0sR9hRgjXCWnMDYWXh8T/view?usp=sharing) can be achieved. (Consolidating a large number of in-vivo labels can be accomplished mostly automatically with [clustering of text embeddings](https://docs.google.com/document/d/1d7J-aTOPnkOH1AQ2DsWZLFjlgaRxk8VG/edit).)

The AI is used only as a tireless, low-level but incredibly fast assistant with the instruction to code each and every causal claim in the text. This is radically different from the kind of AI-supported “black box” coding which essentially treats the AI as a trusted co-coder who is asked to make, or help make, high-level decisions such as "what are the main themes in this text?" or even “What is the overarching causal network in this text?”. 

The accuracy (precision and recall) of AI-supported causal coding is not perfect, but it is improving all the time. Creating, implementing and monitoring the coding protocol remains an essential task ("human in the loop") but we claim that AI-supported causal coding comes closer than other approaches to providing an almost out-of-the-box way to make sense of texts at scale.

## But, causation?

There are many caveats about causation, as outlined in Powell et al. 

Critical realist about actual processes, and realist about causation itself.

  

## Limitations

Causal coding uses a restricted ontology will certainly reduce the potential scope of the final report or model, but perhaps not as much as we might expect. It cannot answer all questions about a text! It will fail to code claims or statements which contain material which never influences anything else or is influenced by anything else. 

It is also not suited to constructing broader theories with wider applicability in the sense of [(Glaser & Strauss, 1967)](https://www.zotero.org/google-docs/?jGl1ck). 

We have not used causal coding explicitly to search for latent as opposed to explicit material, ibid, [(Braun & Clarke, 2006)](https://www.zotero.org/google-docs/?WH7AaX). Perhaps it will prove possible but we know of no examples from the wider causal mapping literature where this has been tried.

The causal coding procedures we have outlined here represent a single-pass, non-iterative approach. Of course this can be expanded to include the more iterative approach essential to most QDA approaches, with varying levels of human oversight. For example we can quickly and cheaply experiment with different coding rules, compare the results, modify the rules and iterate again. This ability to experiment with, compare and iterate potentially hundreds of coding rules and algorithms is a real strength of (semi-)automated coding.

Vulnerable to limited attention: if we really process only one section at a time, we will be unable to notice cross-references or places where one section qualifies another, as pointed out by Udo Kelle (1997) xx. This may not be a fundamental limitation of machine-led approaches if we arbitrarily expand the surrounding context, increasing the attention or context window, but at present this is slow and expensive. See A 2023 study by Rezaee et al. compared topic modeling (LDA) vs human qualitative coding of tweets, finding that automated methods reliably find dominant themes but miss subtle frames that human interpretive coding can catch.

## What Causal Map Ltd provides

A wider overview of causal mapping as applied in disciplines from ecology to organisation science is presented in [(Powell et al., 2024)](https://www.zotero.org/google-docs/?tAaTp5) and in this [Zotero library](https://www.zotero.org/groups/2858107/causal-mapping/library). 

We provide a web app [Causal Map](http://causalmap.app) which is specifically designed for (mostly human-powered) causal QDA and has been used in [academic and practical applications](http://causalmap.app/resources). Colleagues at BathSDR and others have applied (human-powered) causal coding in over 100 evaluation projects using the Qualitative Impact Protocol [(Copestake et al., 2019)](https://www.zotero.org/google-docs/?broken=cnk8gl), mostly in the field of international development, more recently using the Causal Map app. 

Here is a broader list of [causal mapping software](https://en.wikipedia.org/wiki/List_of_causal_mapping_software). 

Finally, we also provide dedicated software for AI-powered causal QDA, details on request.**
