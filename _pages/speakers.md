---
layout: splash
permalink: /speakers/
toc: true
toc_label: "My Table of Contents"
toc_icon: "gear"
---

{% include toc %}

### Robin Cooper (Gothenburg University)
**How to play games with types**

Inspired by [Heather Burnett’s and E. Allyn Smith’s course at ESSLLI 2017](https://www.irit.fr/esslli2017/courses/6) I have been thinking about how the kind of game theory they present could be connected to work on TTR, a type theory with records, and Ginzburg’s KOS.  Here are some points I will consider, as of yet programatically, but I hope we can discuss the viability of this as a research programme at the workshop.

1. Recasting GT in TTR.  They both talk about types (of action) and when GT talks about possible worlds it’s really what TTR would call types of situations. (The same holds of the use of the term “possible worlds” in probability theory).  I will sketch an example of how it might look.
2.  But what might doing (1) add to a linguistic theory?   KOS/TTR might provide a framework for dealing with issues like choosing which games to play, misunderstandings between two agents about what game is being played or accommodating a game on the basis of another agent’s behaviour.  There is a notion of game in the paper I am circulating (more detail in the [partialbook draft](https://sites.google.com/site/typetheorywithrecords/drafts)) and also in Breitholtz’s work on enthymemes and topoi in [her thesis](https://gupea.ub.gu.se/handle/2077/36005) and book in preparation.  Ginzburg’s work on genre and conversation types is related.  The games in this literature are very simple from the perspective of GT (basically you have a string type for a string of events on the gameboard and you traverse it trying to realize the types).  We have nothing to say about how you would make choices in a non-deterministic game, but GT would add that.  I think it could be extremely productive to embed game theory in a theory of dialogue — one even begins to imagine metagames, games you play about concerning which game to play…  We can perhaps supply a way of connecting GT to dialogue and grammar in a formal setting.
3. We could view this as making a connection between games and a general theory of action along the lines of the paper I am circulating.  The assumption seems to be that you compute utility and then perform the action that has highest utility for you.  But you could think of other strategies:  e.g. cooperative (make the move that has the highest utility irrespective of player), altruistic (maximize the utility of the other player).  If you think of games as assigning utilities to event types at a given state of play (perhaps exploiting techniques from our work on [probabilistic TTR](http://csli-lilt.stanford.edu/ojs/index.php/LiLT/article/view/52)) you could have a superordinate theory of action which would tell you what you might do depending on which strategy you are using.

Literature: 
1. Cooper, Robin (2014) How to do things with types, in Joint Proceedings of the Second Workshop on Natural Language and Computer Science (NLCS 2014) & 1st International Workshop on Natural Language Services for Reasoners (NLSR 2014), July 17-18, 2014 Vienna, Austria, ed. by Valeria de Paiva, Walther Neuper, Pedro Quaresma, Christian Retoré, Lawrence S. Moss and Jordi Saludes, Center for Informatics and Systems of the University of Coimbra,
pp. 149--158

### Heather Burnett (LLF, Paris-Diderot)
**Identity construction in dialogue: A game-theoretic approach**

I give a brief overview of social meaning and identity construction through language and argue that identity construction considerations play an important role in both the use and interpretation of individual linguistic expressions, and in the construction and understanding of larger dialogues. I present a Bayesian game theoretic model of identity construction with single expressions and discuss prospects for the extension of this model to full dialogues.

### Nicholas Asher  (IRIT, Toulouse) 

(TBA)                                                                                                                       

### Ye Tian (LLF, Paris-Diderot & Amazon)
**Um, what’s the word: Filled Pauses and Self-addressed Questions; Disfluency in German, French and Chinese dialogues**

(TBA)


### Julian Hough (Bielefeld University)
**Deep Learning Approaches to Incremental Disfluency Detection**

Despite being marginalized by mainstream linguistic research, we claim that disfluency is a core part of dialogue content. We support this claim from a computational modelling perspective, by showing how repairs and edit terms are amenable to modelling by statistical sequence models, in line with current automatic approaches to other linguistic phenomena. From the work on the DUEL project, we present the joint task of incremental disfluency detection and utterance segmentation on dialogue data, and a simple deep learning system which performs it on transcripts and speech recognition results. We show how the constraints of the two tasks interact. Our joint-task system outperforms the equivalent individual task systems, provides competitive results and is suitable for future use in conversation agents in the psychiatric domain.

### Andrzej Wisniewski (Adam Mickiewicz University, Poznan)
**Question dependencies in view of erotetic logic**

Erotetic logic, like any other logic, can play at most a subsidiary role in dialogue modelling. Nevertheless, erotetic logic as a whole provides (somewhat diverse) accounts of interrogative entailment and other semantic relations between questions as well as between questions and declaratives. My aim is to present some recent developments in erotetic logic which, potentially, provide a more fine-grained account of semantic dependencies between questions occurring in dialogues.

Literature:
* Andrzej Wiśniewski, Semantics of questions, in: S. Lappin, Ch. Fox (eds.), The Handbook of Contemporary Semantic Theory – second edition, Wiley-Blackwell 2015, pp. 273-313. (Mainly sections 2.3, 5.5, and 6).
* Andrzej Wiśniewski, Generalized entailments, Logic and Logical Philosophy 26, 2017, pp. 321-356. (Mainly section 5). 

### David Traum (ICT, USC)
**Multi-floor dialogue and hybrid requests**

Dialogue is sensitive to many aspects of context, including the roles that participants fill in activities and organizations, their relationships, and co-temporal activities they are involved with, including other conversations. I will discuss cases where not only are more than two participants involved in dialogue, but where there are separate dialogue “floors” that are active at the same time, particularly those that involve some of the same participants, and which are connected by having the same purpose (which I term multi-floor dialogue). I will present examples from a  human-robot wizard of Oz corpus. I will also examine some kinds dialogue acts that appear in this corpus and might be analyzed as hybrids between requests and other types of action with different effects. One is “translation” requests, that involve someone other than the addressee performing the requested action (in this case, involving a translation from one floor to another). I will also look at what I call “request-no-questions” that fall in between yes-no-questions and indirect requests, sharing some properties of each.

### David Schlangen (Bielefeld University)
**Dialogical Learning and Maintenance of a Lexicon for Situated Interaction**

(TBA)

### Chiara Mazzocconi (LLF, Paris-Diderot)
**What’s your laughter doing there?**

Laughter is extremely frequent in our daily interactions occurring in the most different contexts. Especially in adulthood, it is crucial in managing interactions, its form and distribution are to some extent regular and it is deeply intertwined with linguistic productions serving highly sophisticated pragmatic and socio-cognitive functions. The work I will present attempts to tackle the problem of laughter functions classification, still unresolved after decades of academic investigation. We propose  a taxonomy where form, context, relation to the laughable and linguistic material, as well as intentions reasoning are taken into account in order to determine its semantics and pragmatic functions. We propose viewing laughter as akin to a gestural event anaphora, that is, a vocal signal that searches in the context for an event (the laughable) which is to be highlighted, commented about or modified. We put forward the existence of a basic meaning of laughter that when aligned with rich contextual reasoning, and when integrated with linguistic import can generate a wide range of functions. The taxonomy of laughter functions proposed is grounded in a semantic and pragmatic analysis of corpus data and proved to be reliably applicable by naive coders.

### Andy Lücking (Frankfurt University)
**From exemplification, through alignment to association: Aspects of iconic gesture meaning**

If iconic co-speech gestures contribute to the semantics of dialogue, then there is a way of getting from hand-and-arm movements to meanings. The talk provides such a semantic model based on the notion of exemplification. It is spelled out within a Type Theory with Records and thereby linked to a dynamic update semantics. Furthermore, based on observations on pairs of such iconic gestures and their affiliated verbal expressions, the notion of multimodal ensembles is introduced and operationalized as an extension of the interactive alignment model. Since the performance of a co-speech gesture and its relation to verbal expressions is often very sketchy and vague, in ongoing work an associative interface based on conceptual spaces is tested. The conceptual framework and first results, as available, are presented. 

### Judith Holler (MPI, Nijmegen)
**Multimodal language use and comprehension in social interaction: the body is part of the package**

My talk will address the issue of whether the information we convey with our bodies (esp with hands, head and face) should be considered core components of the messages that interlocutors convey and comprehend. I will reflect on this issue primarily from a psycholinguistic perspective, drawing on both experimental and corpus data. Specifically, I will address the link between bodily signals and communicative intentions, their relevance in semantic message production and comprehension, and their role in in situ language processing and conversational turn-taking.

### Ian Cross (Cambridge University)
**Music, speech and the relational dimension of interaction**

We tend to understand music as formed of autonomous works with aesthetic value that can be explored and analysed in terms of its textual identities: as scores, and perhaps, as recordings.  This provides a narrow and partial view of music, even more reduced than that which is afforded on language by a focus on the complexities of syntactic and semantic properties. In this paper I shall argue that music—and language—are fundamentally interactive media; that they constitute culturally-particularised components of an underlying human communicative toolkit, differentiable primarily by function; and that they overlap significantly in the resources on which they draw in real-time interactive communication.  I shall contend that we should think of music as foregrounding relational aspects of communication and as tending to elicit affiliative frames for interaction.  I shall show that in communicative contexts that are relational, affiliative, yet apparently linguistic, conversational interaction tends to display features that we can think of as musical, and will argue that these features are used pragmatically to sustain mutual affiliation in real-time interaction.
 
Relevant prior reading: Cross, I. (2013). "Does not compute"? Music as real-time communicative interaction. AI & Society, 28(4), 415-430

### Jonathan Ginzburg (LLF, Paris-Diderot)
**Gesture, Emotion and Interaction**

Certain classes of gestures, most prominently facial gestures, are sometimes understood referentially, sometimes in terms of emotions. This point applies also to musical content, where although its understanding in terms of emotional content is widespread, there is increasing evidence for the existence of referential content, on which arguably emotional content supervenes. I will consider how to integrate the semantic contribution of certain gestures to a theory of dialogue, attempting along the way to explain the limits of what they can express. In particular, I will offer some initial proposals about how to integrate mood (in the sense of `medium term feeling') into information states and the appraisal process into utterance processing.
