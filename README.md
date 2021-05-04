# Protocol Labs - Research
[![](https://img.shields.io/badge/team-research-0f41f4.svg?style=flat-square)](https://github.com/protocol/research)

> :rocket: Making Protocol Labs Protocol _Labs_.

Welcome to the main research landing and launch repo. This is a companion to the [Protocol Labs Research website](https://research.protocol.ai/), which is the primary public reference for our work.

Our mission is to pursue open, collaborative, high-impact research that pushes the boundaries of what computing can do for humanity.

#### Maintainer
 [Evan Miyazono](https://github.com/miyazono)

# What's in This Repo?

This repo contains a directory and explanation of the structure of public research at Protocol Labs.  While not all Protocol Labs research will begin in this repository under public scrutiny, most will.  In addition, only under extreme circumstances will we ever make private any progress on a project that was at any point made public.

In addition, this repo houses a complete [list of past and upcoming research seminars](https://github.com/protocol/research/blob/master/research-events/research-seminars.md) and our [code of conduct](https://github.com/protocol/research/blob/master/research-events/code-of-conduct.md) for all public research events.

This repo also contains a list of open problem statements in the issues and serves as a workplace and dicussion venue for those problems.

Subscribe to this repo if you want to be updated about new research ideas and discussions. If you want to closely follow the work of Protocol Labs Research, however, we strongly suggest also subscribing to [our official mailing list](https://protocol.us4.list-manage.com/subscribe?MERGE0=&u=09d704b0125b11d44d67d4617&id=7aa0f1150b&subscribe=) for quarterly newsletters, funding opportunity announcements (FOAs), research talk announcements, and more (customizable subscription preferences). 

If you are looking for open problems specifically to do with our Resilient Networks Lab (ResNetLab), you can find those [here](https://github.com/protocol/ResNetLab/tree/master/OPEN_PROBLEMS).

---


# How to Navigate Protocol Labs Research - What's in the Other Repos
In general, research ideas start here as responses to important questions, and then potentially develop into RFPs or their own research topic repositories.  The research repositories within IPFS and Filecoin should take on a similar structure over time.

## Unique structural repos
There are two public structural repos that contain directories, instructions, or other information needed for performing research at PL.


### [protocol/research-RFPs](https://github.com/protocol/research-RFPs)
 - contains grant information and RFPs for applicants

### [protocol/research]  **(this repo)**
 - default location of all research topics before they've reached prototype stage
 - contains index of public research
 - contains links, the list of open problem statements (in the issues)

### Project-specific Repos

- IPFS
  - [ipfs/notes](https://github.com/ipfs/notes)
- libp2p
  - [libp2p/notes](https://github.com/libp2p/notes)
- IPLD  
  - [ipld/research](https://github.com/ipld/research)
- Filecoin
  - [filecoin-project/research](https://github.com/filecoin-project/research)

## Creating an open problem statement
Open problem statements are to be created by anyone in the community as issues in this repo, and should be used to prompt and focus discussion and investigation.
The purpose of an open problem statement is twofold.  Firstly, it should convince the reader that the problem you are presenting is worth working on.  Secondly, it should provide enough background and understanding of the problem that all design decisions and requirements are comprehensively described and motivated.  Feel free to deviate from the issue template if you prefer, or answer the following questions as succinctly as possible for an easy open problem statement.

While this template was made to support the RFP program, the open problem statements themselves are purely for the benefit of the community, and there is no obligation to make an RFP for each open problem.

## Example Use Cases

### Working on a public research problem
Start with the list of problems (logbook) in the issues of this repo.  Post your thoughts on that issue and help develop potential solutions.  If the project reaches the point of prototyping solutions, propose making a repo for it and copy over the relevant items.

### Turning a problem into an RFP or bounty
Start by writing up the problem statement in Markdown or LaTeX, which should include sections motivating the problem, describing and distinguishing the ideal solution from similar existing systems, defining terms and data structures, and listing constraints.  Then create an issue for discussing the scale and importance of the problem so that a timeline and size for the bounty/grant can be determined.  If, at any point in this process, the problem grows quite large, it's possible that the problem, discussion, and problem statement can move out of [research](https://github.com/protocol/research) and into its own repo.  Otherwise, the problem statement and discussion of scale and importance should take place in one of the aforementioned two repositories.  Tag a core Protocol Labs researcher in the discussion, and if funding can be allotted, the final RFP will be posted in [research-RFPs](https://github.com/protocol/research-RFPs) and will link to the problem statement.


