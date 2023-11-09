# awesome-decompilation

A curated list of awesome decompilation resources and projects.

-----------------------------------------

## Contents

 * [General Overview](#general-overview)
 * [Compilers](#compilers)
 * [Program Analysis](#program-analysis)
 * [Projects](#projects)
 * [Decompilation Pipeline](#decompilation-pipeline)
   + [General](#general)
   + [Intermediate Representation](#intermediate-representation)
   + [Type Reconstruction](#type-reconstruction)
   + [Control-Flow Reconstruction](#control-flow-reconstruction)
   + [C++ Decompilation](#c-decompilation)
   + [Identifier Recovery](#identifier-recovery)
 * [AI-based Decompilation](#ai-based-decompilation)
 * [Advanced Topics](#advanced-topics)
   + [Search-Based Decompilation](#search-based-decompilation)
   + [Binary-Source Matching](#binary-source-matching)

-----------------------------------------

## General Overview

 * [Reverse Compilation Techniques](http://www.phatcode.net/res/228/files/decompilation_thesis.pdf)

 * [Static Single Assignment for Decompilation](https://yurichev.com/mirrors/vanEmmerik_ssa.pdf)

 * [Retargetable Analysis of Machine Code](https://dspace.vutbr.cz/bitstream/handle/11012/63279/482.pdf)

 * [A Human-Centric Approach For Binary Code Decompilation](https://bonndoc.ulb.uni-bonn.de/xmlui/handle/20.500.11811/7517)

## Compilers

 * [Compilers: Principles, Techniques, and Tools](https://www.amazon.com/dp/0321486811)

 * [Advanced Compiler Design and Implementation](https://www.amazon.com/dp/1558603204)

## Program Analysis

 * [Principles of Program Analysis](http://www.imm.dtu.dk/~hrni/PPA/ppa.html)

 * [Data Flow Analysis: Theory and Practice](https://www.crcpress.com/Data-Flow-Analysis-Theory-and-Practice/Khedker-Sanyal-Sathe/p/book/9780849328800)

## Projects

 * [Hex-Rays](https://www.hex-rays.com/products/decompiler/)

 * [Ghidra](https://github.com/NationalSecurityAgency/ghidra/tree/master/Ghidra/Features/Decompiler)

 * [JEB](https://www.pnfsoftware.com/)

 * [retdec](https://retdec.com/)

 * [rev.ng-c](https://rev.ng/revngc-features.html)

 * [jsdec](https://github.com/rizinorg/jsdec)

 * [decomp.me](https://decomp.me)

## Decompilation Pipeline

### General

 * [Decompilers and beyond](https://www.hex-rays.com/products/ida/support/ppt/decompilers_and_beyond_white_paper.pdf)

 * [decomp](https://github.com/decomp/decomp)

### Intermediate Representation

 * [LLVM](https://llvm.org/docs/LangRef.html)

 * [VEX](https://github.com/angr/vex/blob/master/pub/libvex_ir.h)

 * [Hex-Rays microcode](http://hex-rays.com/products/ida/support/ppt/recon2018.ppt)

 * [BAP](https://github.com/BinaryAnalysisPlatform/bap)

 * [REIL](https://github.com/Cr4sh/openreil)

 * [ESIL](https://radare.gitbooks.io/radare2book/content/disassembling/esil.html)

 * [LLIL](https://docs.binary.ninja/dev/bnil-llil/index.html)
 
 * [VTIL](https://github.com/vtil-project)

### Type Reconstruction

 * [DIVINE: DIscovering Variables IN Executables](https://research.cs.wisc.edu/wpis/papers/vmcai07.invited.pdf)

 * [Improved Memory-Access Analysis for x86 Executables](http://research.cs.wisc.edu/wpis/papers/cc04.pdf)
 
 * [TIE: Principled Reverse Engineering of Types in Binary Programs](https://users.ece.cmu.edu/~aavgerin/papers/tie-ndss-2011.pdf)

 * [Polymorphic Type Inference for Machine Code](https://arxiv.org/abs/1603.05495)

### Control-Flow Reconstruction

 * [No More Gotos: Decompilation Using Pattern-Independent Control-Flow Structuring and Semantics-Preserving Transformations](http://www.ndss-symposium.org/ndss2015/ndss-2015-programme/no-more-gotos-decompilation-using-pattern-independent-control-flow-structuring-and-semantics/)

 * [Helping Johnny to Analyze Malware](https://www.computer.org/csdl/proceedings/sp/2016/0824/00/0824a158.pdf)

 * [A Comb for Decompiled C Code](https://dl.acm.org/doi/10.1145/3320269.3384766)

### C++ Decompilation

 * [SmartDec: Approaching C++ Decompilation](https://www.computer.org/csdl/proceedings/wcre/2011/1948/00/06079860.pdf)

### Identifier Recovery

 * [Meaningful Variable Names for Decompiled Code: A Machine Translation Approach](https://cmustrudel.github.io/papers/icpc18decompilation.pdf)

 * [Debin: Predicting Debug Information in Stripped Binaries](https://files.sri.inf.ethz.ch/website/papers/ccs18-debin.pdf)

 * [DIRE: Decompiled Identifier Renaming Engine](https://github.com/CMUSTRUDEL/DIRE)

## AI-based Decompilation

 * [Using Recurrent Neural Networks for Decompilation](http://www.cs.unm.edu/~eschulte/data/katz-saner-2018-preprint.pdf)

 * [Towards Neural Decompilation (2019)](https://arxiv.org/pdf/1905.08325.pdf)
 
 * [Coda: An End-to-End Neural Program Decompiler](https://proceedings.neurips.cc/paper/2019/file/093b60fd0557804c8ba0cbf1453da22f-Paper.pdf)

 * [N-Bref: a neural-based decompiler framework](https://github.com/facebookresearch/nbref)

 * [Neutron: an attention-based neural decompiler](https://link.springer.com/content/pdf/10.1186/s42400-021-00070-0.pdf)

 * [Beyond the C: Retargetable Decompilation using Neural Machine Translation](https://arxiv.org/abs/2212.08950)

## Advanced Topics

### Search-Based Decompilation

 * [Evolving Exact Decompilation](https://www.cs.unm.edu/~eschulte/data/bed.pdf)

### Binary-Source Matching

 * [BinPro: A Tool for Binary Source Code Provenance](https://arxiv.org/pdf/1711.00830)

 * [Neural Network-based Graph Embedding for Cross-Platform Binary Code Similarity Detection](https://arxiv.org/abs/1708.06525)

 * [CodeCMR: Cross-Modal Retrieval For Function-Level Binary Source Code Matching](https://keenlab.tencent.com/zh/whitepapers/neurips-2020-cameraready.pdf)




