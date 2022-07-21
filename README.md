# Protocol Labs Research
[![](https://img.shields.io/badge/team-research-0f41f4.svg?style=flat-square)](https://github.com/protocol/research)

> :rocket: Making Protocol Labs Protocol _Labs_.

Welcome to the main research landing and launch repo. This is a companion to the [Protocol Labs Research website](https://research.protocol.ai/), which is the primary public reference for our work.

Our mission is to pursue open, collaborative, high-impact research that pushes the boundaries of what computing can do for humanity.

# What's in This Repo?

📋 This repo contains a directory and explanation of the structure of public research at Protocol Labs.

🎙️ In addition, this repo houses a complete [list of past and upcoming research seminars](https://github.com/protocol/research/blob/master/research-events/research-seminars.md) and our [code of conduct](https://github.com/protocol/research/blob/master/research-events/code-of-conduct.md) for all public research events.

📝 This repo also contains a list of  [**Open Problem Statements** ](#open-problems) generated by PL Researchers and intended to stimulate discussion and research project development.

We welcome open problems from the community, and suggest using either the appropriate [Filecoin Slack channel](filecoinproject.slack.com) or in the [✴️  Lodestar Discord server ](https://discord.gg/lodestar-network-goods) to start a discussion. You can read more about Open Problem statements [below](#open-problems).

Subscribe to this repo if you want to be updated about new research ideas and discussions. If you want to closely follow the work of Protocol Labs Research, however, we strongly suggest also subscribing to [our official mailing list](https://protocol.us4.list-manage.com/subscribe?MERGE0=&u=09d704b0125b11d44d67d4617&id=7aa0f1150b&subscribe=) for quarterly newsletters, funding opportunity announcements (FOAs), research talk announcements, and more (customizable subscription preferences). You may also want to [follow us on Twitter](https://twitter.com/ProtoResearch).

---

# How to Navigate Protocol Labs Research 
Many research ideas start here as responses to important questions, and then potentially develop into RFPs or their own research topic repositories. Other open problems are nucleated in the [Filecoin Slack](filecoinproject.slack.com) or the [✴️  Lodestar Discord server ](https://discord.gg/lodestar-network-goods)


## Unique Structural Repos
There are two public structural repos that contain directories, instructions, or other information needed for performing research at PL:

### [protocol/research-grants](https://github.com/protocol/research-RFPs)
 - contains grant information and RFPs for applicants
 - you may also want to check out our [grant portal](https://grants.protocol.ai/)

### [protocol/research]  **(this repo)**
 - default location of all research topics before they've reached prototype stage
 - contains index of public research
 - contains links, the list of open problem statements (in the issues)

### Project-Specific Repos

- IPFS
  - [ipfs/notes](https://github.com/ipfs/notes)
- libp2p
  - [libp2p/notes](https://github.com/libp2p/notes)
- IPLD  
  - [ipld/research](https://github.com/ipld/research)
- Filecoin
  - [filecoin-project/research](https://github.com/filecoin-project/research)

## Getting in touch with PL Researchers

Several labs within PL Research maintain their own github repositiories  for topics relevant to their primary research interests:

- [ConsensusLab](https://github.com/protocol/ConsensusLab): consensus and blockchain scalability
- [CryptoEconLab](https://github.com/protocol/CryptoEconLab): research on economic incentives, coordination games, and novel marketplaces
- [CryptoNetLab](https://github.com/protocol/CryptoNetLab): public good cryptography -- creating secure building blocks for Web 3.0 protocols

Additionally, many research teams and projects maintain public Notion pages where they share their current  research activities:

-  🧮  [CryptoNetLab](https://www.notion.so/Cryptonet-81fd8bb1043643a38472335d73692339)
-  ⚖️ [CryptoEconLab](https://www.notion.so/CryptoEconLab-2bd339628c95447b8a9f7df3e8cf8798)
-  🤝  [ConsensusLab](https://www.notion.so/ConsensusLab-13dfe290f57c438eb03a3db52dbbb43c)
-  🎣  [Retrieval Markets](https://www.notion.so/Retrieval-Markets-765a9388b86646f38f7a03ee90c9c6c4)
-  🐟 [Compute Over Data](https://www.notion.so/Compute-Over-Data-25fa366465ed4ddf81027498efb4a405)
-  ⏱️ [Probelab](https://www.notion.so/pl-strflt/ProbeLab-Protocol-Benchmarking-Optimization-a63238fd1b184d6f8fea4bb38d975208)

And for faster-paced conversations, you can reach **CryptoEconLab**, **ConsensusLab**, the **Retrieval Markets** team, and **Bacalhau (CoD)** on the public [Filecoin Slack](filecoinproject.slack.com).

The **Network Goods** 🧧 📈  team, which includes researchers working on incentive and funding mechanisms for the creation and maintenance of public goods, maintains a public Discord server (called ✴️ [Lodestar](https://discord.gg/lodestar-network-goods)) where we discuss
-  *metaresearch* -- the science of accelerating science
- scientific toolbuilding
- incentive & mechanism design
- leveraging Web3 tools for public goods funding
- areas relevant to PL research (cryptography, distributed systems, consensus, cryptoeconomics)
- and many other topics (urban planning! tools for thought! federated learning!)

We also plan the [Journal Club](https://docs.google.com/spreadsheets/d/1A-rwJ2L0D7ujKiaKa8QqrKIUSMB5vdVLcKtVyOAguwU/edit?usp=sharing) and [Research Saloon](https://docs.google.com/spreadsheets/d/1lQXA8GjlCCeOg84SqY_kOaMv5fzxFcHM2UuWMAXp2tA/edit?usp=sharing) in the ✴️ Lodestar server. 


## Open Problems

### Private Retrieval 

We are looking for research and development of interactive private communication mechanisms.

Today, mixnet-like systems are the only mechanism with any sizable deployment for low-latency privacy. Their design has limits on achievable latencies, or must trade latency for compromises in their threat model. Some nascent alternative approaches to mixnets have been considered in academia, but none have been able to demonstrate at-scale real-world use. We are excited to develop work that can be applied in the contexts of libp2p, IPFS, and Filecoin.

Works we are interested in funding include those which:

-   Explore new mechanisms for private communication (e.g. with cryptographic, information theoretic, or statistical basis)
-   Relax the traditional ‘web’ assumptions of a single origin to engage with the possibilities of pre-distributed CDN or content-addressed data.
-   Prototype the use of novel network-layer privacy technologies in real systems.
    
A selection of research works that we would have been excited to fund if we were running this program a decade ago include:

-   [Express: Lowering the Cost of Metadata-hiding Communication with Cryptographic Privacy - Usenix Security 2021](https://www.usenix.org/conference/usenixsecurity21/presentation/eskandarian) 
-   [Karaoke: Distributed Private Messaging Immune to Passive Traffic Analysis - OSDI 2018](https://www.usenix.org/conference/osdi18/presentation/lazar)
-   [PIR-Tor: Scalable Anonymous Communication Using Private Information Retrieval](https://www.usenix.org/conference/usenix-security-11/pir-tor-scalable-anonymous-communication-using-private-information)
-   [Oblivious DNS: Practical Privacy for DNS Queries](https://petsymposium.org/2019/files/papers/issue2/popets-2019-0028.pdf)
-   [CryptDB: processing queries on an encrypted database](https://dl.acm.org/doi/abs/10.1145/2330667.2330691)

### Research groups' open problems

Our **Research Labs** host open problems relevant to their research in their respective repos:
- 🤝  [ConsensusLab](https://github.com/protocol/ConsensusLab)
- ⚖️  [CryptoEconLab](https://github.com/protocol/CryptoEconLab)
- 🧮  [CryptoNetLab](https://github.com/protocol/CryptoNetLab)
