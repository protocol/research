# Protocol Labs Research
[![](https://img.shields.io/badge/team-research-0f41f4.svg?style=flat-square)](https://github.com/protocol/research)

> :rocket: Making Protocol Labs Protocol _Labs_.

Welcome to the main research landing and launch repo. This is a companion to the [Protocol Labs Research website](https://research.protocol.ai/), which is the primary public reference for our work.

Our mission is to pursue open, collaborative, high-impact research that pushes the boundaries of what computing can do for humanity.

# What's in This Repo?

📋 This repo contains a directory and explanation of the structure of public research at Protocol Labs.

🎙️ In addition, this repo houses a complete [list of past and upcoming research seminars](https://github.com/protocol/research/blob/master/research-events/research-seminars.md) and our [code of conduct](https://github.com/protocol/research/blob/master/research-events/code-of-conduct.md) for all public research events. You can suggest a topic or spreaker for our seminar series using this [issue template](https://github.com/protocol/research/blob/master/.github/ISSUE_TEMPLATE/research-seminar-suggestion.md). 

📝 This repo also contains a list of **Open Problem Statements** in the issues and serves as a workplace and dicussion venue for those problems.
Our **Research Development Labs** and **AbstractionLab** host Open Problems relevant to their research in their respective Lab repos:
-  [AbstractionLab](https://github.com/protocol/AbstractionLab)
-  🚧 CryptoComputeLab
-  🚧 CryptoEconLab
-  [CryptoNetLab](https://github.com/protocol/CryptoNetLab)
-  [ResNetLab](https://github.com/protocol/ResNetLab)


🎤 This repo also houses a [**Discussion Board**](https://github.com/protocol/research/discussions) where Open Problem statements can be formulated and refined. This  board is also the appropriate venue for discussions related to [**metaresearch**](https://research.protocol.ai/areas/metaresearch/): this includes roadmapping, knowledge management and dissemination, the history and economics of science, and the statistical validation of scientific findings,  among other topics. We plan the [**MetaRsearch Journal Club**](https://github.com/protocol/research/discussions/categories/metaresearch-journal-club) here as well. Topics that are aligned with PL Research but don't fit neatly in existing Lab repos ( e.g. AI, augmented reality, AR/VR, and brain-computer interfaces) are also appropriate for the [PL Research Discussion Board](https://github.com/protocol/research/discussions).

Subscribe to this repo if you want to be updated about new research ideas and discussions. If you want to closely follow the work of Protocol Labs Research, however, we strongly suggest also subscribing to [our official mailing list](https://protocol.us4.list-manage.com/subscribe?MERGE0=&u=09d704b0125b11d44d67d4617&id=7aa0f1150b&subscribe=) for quarterly newsletters, funding opportunity announcements (FOAs), research talk announcements, and more (customizable subscription preferences). 


---


# How to Navigate Protocol Labs Research - What's in the Other Repos
Many research ideas start here as responses to important questions, and then potentially develop into RFPs or their own research topic repositories. Other open problems are nucleated in the ResDev Lab discussion boards.

## Unique Structural Repos
There are two public structural repos that contain directories, instructions, or other information needed for performing research at PL.


### [protocol/research-grants](https://github.com/protocol/research-RFPs)
 - contains grant information and RFPs for applicants

### [protocol/research]  **(this repo)**
 - default location of all research topics before they've reached prototype stage
 - contains index of public research
 - contains links, the list of open problem statements (in the issues)

### Lab Repos
The Research Development Labs and the AbstractionLab maintain their own github repositiories and discussion boards for topics relevantto their primary research interests:

-  [AbstractionLab](https://github.com/protocol/AbstractionLab): decentralized knowledge graphs and operations on knowledge
-  🚧 CryptoComputeLab: the intersection of applied cryptography, high performance computing, and programming language design
-  🚧 CryptoEconLab: economic incentives, coordination games, and novel marketplaces
-  [CryptoNetLab](https://github.com/protocol/CryptoNetLab): public good cryptography -- creating secure building blocks for Web 3.0 protocols
-  [ResNetLab](https://github.com/protocol/ResNetLab): building resilient distributed systems

### Project-Specific Repos

- IPFS
  - [ipfs/notes](https://github.com/ipfs/notes)
- libp2p
  - [libp2p/notes](https://github.com/libp2p/notes)
- IPLD  
  - [ipld/research](https://github.com/ipld/research)
- Filecoin
  - [filecoin-project/research](https://github.com/filecoin-project/research)

## Creating an Open Problem Statement
Open problem statements are to be created by anyone in the community as issues in this repo, and should be used to prompt and focus discussion and investigation. The purpose of an open problem statement is twofold:

1. Firstly, it should convince the reader that the problem you are presenting is worth working on.  

2. Secondly, it should provide enough background and understanding of the problem that all design decisions and requirements are comprehensively described and motivated. 

Feel free to deviate from the [issue template](https://github.com/protocol/research/blob/add-metaresearch/.github/ISSUE_TEMPLATE/open-problem.md) if you prefer, or answer the following questions as succinctly as possible for an easy open problem statement.

While the [template](https://github.com/protocol/research/blob/add-metaresearch/.github/ISSUE_TEMPLATE/open-problem.md) was made to support the RFP program, the open problem statements themselves are purely for the benefit of the community, and there is no obligation to make an RFP for each open problem.

## Example Use Cases

### Working on a public research problem
Start with the list of problems (logbook) in the issues of this repo.  Post your thoughts on that issue and help develop potential solutions.  If the project reaches the point of prototyping solutions, propose making a repo for it and copy over the relevant items.

### Turning a problem into an RFP or bounty
1. Start by writing up the problem statement in Markdown or LaTeX, which should include sections motivating the problem, describing and distinguishing the ideal solution from similar existing systems, defining terms and data structures, and listing constraints. 
 
2. Then create an issue for discussing the scale and importance of the problem so that a timeline and size for the bounty/grant can be determined.  If, at any point in this process, the problem grows quite large, it's possible that the problem, discussion, and problem statement can move out of [research](https://github.com/protocol/research) and into its own repo.  Otherwise, the problem statement and discussion of scale and importance should take place in one of the aforementioned two repositories.  

3. Tag a Protocol Labs researcher in the discussion, and if funding can be allotted, the final RFP will be posted in [research-RFPs](https://github.com/protocol/research-RFPs) with a link to the problem statement.


