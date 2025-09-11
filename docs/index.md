# The Decompilation Wiki

<p align="center">
   <img src="/static/img/logo.png" style="width: 30%;" alt="Dec Wiki Logo"/>
</p>

The Decompilation Wiki is a collection of categorized information on all things decompilation.
From real-world applications to cutting-edge research papers, the Decompilation Wiki has it all! Join our Discord below for active community engagement. To get involved, see our [contribution guide](/contributing).
The Decompilation Wiki is still early in development, so any contribution is appreciated! 

[![Discord](https://dcbadge.vercel.app/api/server/eVySXH7ZQ8)](https://discord.gg/eVySXH7ZQ8)

## What Is Decompilation?
Interestingly, the term "decompilation" and its definition are still argued about by researchers.
However, most people agree that decompilation is the reversal of compilation. 
By that definition, **decompilation is the process of turning low-level machine code into a higher-level representation.**

In many cases, this means turning machine code, like [x86 assembly](https://en.wikipedia.org/wiki/X86_assembly_language), into source code, like [C](https://en.wikipedia.org/wiki/C_(programming_language)).
This methodology can also be applied to languages like [Java](https://en.wikipedia.org/wiki/Java_(programming_language)), which create [bytecode](https://en.wikipedia.org/wiki/Java_bytecode).
The difficulty and accuracy of decompilation can vary per language target[^1].

Decompilation has wide applications across cyber security, including:

- reverse engineering (the understanding of programs)
- vulnerability discovery (the understanding of program flaws)
- malware classification
- program repair
- [and much more...](/applications/overview/)

## Wiki Goals?
This wiki has two main goals:

1. Making decompilation knowledge more accessible to new-comers in the field
2. Categorizing research and tooling to make future decompilation progress easier

To accomplish the first goal, it is highly encouraged to link public code when adding a technique. 
Additionally, we will store tutorials for self-rolling (to a degree) your own decompiler components.

To accomplish the second goal, we will attempt to rapidly categorize new research and tools in the area.
These categorizations may not be agreed upon at first, however, we will update them as the community hits consensus. 
In this way, we can quickly attempt to taxonomize the area of decompilation while iterating on it.

## Who Made This?
The Decompilation Wiki was started by [Zion Leonahenahe Basque](https://zionbasque.com), but is sustained by the contributions of the decompilation community. Both closed and open-source developers are welcome! 

The wiki is highly inspired by the following sources:

- [Program-Transformation.org](https://www.program-transformation.org/): a wiki on program transformations, including some decompilation.
- [CTF Wiki](https://ctf-wiki.org/): a wiki for Capture the Flag, inspiring this layout and design.
- ["30 Years into Scientific Binary Decompilation"](https://www.youtube.com/watch?v=XasallkPQIA), Dr. Ruoyu (Fish) Wang: a source of information on decompilers.

Additionally, the wiki is due in large part to the support and advisement of Zion's PhD committee: [Dr. Ruoyu (Fish) Wang](https://ruoyuwang.me/), [Dr. Yan Shoshitaishvili](http://yancomm.net/), [Dr. Adam Doupé](https://adamdoupe.com/), and [Dr. Christina Cifuentes](https://labs.oracle.com/pls/apex/f?p=labs:bio:0:21). 

## Decompilation Paper List
Across this wiki you will find many papers cited from across the scientific community. 
For easy accessibiliy, you can find all cited papers here: [Comprehensive Decompilation List](https://docs.google.com/spreadsheets/d/13QUqON6cwNADk-2E1hwiKxXeCd0ESXUmkA9_dweCESM/edit?usp=sharing).

[^1]: Yakdan, Khaled, et al. ["Helping johnny to analyze malware: A usability-optimized decompiler and malware analysis user study."](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7546501&casa_token=Pl69lA763yoAAAAA:0rH6AIEbiBhbUGGaSvJvhaYeFEaWPnIifVHceQTGkd_k4NQK6EDH_zcytY-I-W6OE5oHbdU) 2016 IEEE Symposium on Security and Privacy (SP). IEEE, 2016.
