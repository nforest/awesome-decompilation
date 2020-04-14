# awesome-decompilation

A curated list of awesome decompilation resources and projects.

-----------------------------------------

## Contents

 * [General Overview](#general-overview)
 * [Projects](#projects)
 * [Compilers](#compilers)
 * [Program Analysis](#program-analysis)
 * [Decompilation Pipeline](#decompilation-pipeline)
   + [General](#general)
   + [Intermediate Representation](#intermediate-representation)
   + [Type Reconstruction](#type-reconstruction)
   + [Control-Flow Reconstruction](#control-flow-reconstruction)
   + [C++ Decompilation](#c++-decompilation)
   + [Identifier Recovery](#identifier-recovery) 
 * [Advanced Topics](#advanced-topics)
   + [Search-Based Decompilation](#search-based-decompilation)
   + [AI-based Decompilation](#ai-based-decompilation)
   + [Binary-Source Matching](#binary-source-matching)

-----------------------------------------

## General Overview

 * [Reverse Compilation Techniques](http://www.phatcode.net/res/228/files/decompilation_thesis.pdf)

 * [Static Single Assignment for Decompilation](https://yurichev.com/mirrors/vanEmmerik_ssa.pdf)

* [Retargetable Analysis of Machine Code](https://dspace.vutbr.cz/bitstream/handle/11012/63279/482.pdf)

 * [A Human-Centric Approach For Binary Code Decompilation](http://hss.ulb.uni-bonn.de/2018/5004/5004.pdf)

## Projects

 * [Hex-Rays](https://www.hex-rays.com/products/decompiler/)

 * [JEB](https://www.pnfsoftware.com/)

 * [fcd](https://github.com/zneak/fcd)
 
 * [radeco](https://github.com/radareorg/radeco)

 * [retdec](https://retdec.com/)

 * [smartdec](https://github.com/smartdec/smartdec)

 * [snowman](https://derevenets.com/)

 * [dcc](https://github.com/nemerle/dcc)

## Compilers

 * [Compilers: Principles, Techniques, and Tools](https://www.amazon.com/dp/0321486811)

 * [Advanced Compiler Design and Implementation](https://www.amazon.com/dp/1558603204)

## Program Analysis

 * [Principles of Program Analysis](http://www.imm.dtu.dk/~hrni/PPA/ppa.html)

 * [Data Flow Analysis: Theory and Practice](https://www.crcpress.com/Data-Flow-Analysis-Theory-and-Practice/Khedker-Sanyal-Sathe/p/book/9780849328800)

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

### Type Reconstruction

 * [DIVINE: DIscovering Variables IN Executables](https://research.cs.wisc.edu/wpis/papers/vmcai07.invited.pdf)

 * [Improved Memory-Access Analysis for x86 Executables](http://research.cs.wisc.edu/wpis/papers/cc04.pdf)
 
 * [TIE: Principled Reverse Engineering of Types in Binary Programs](https://users.ece.cmu.edu/~aavgerin/papers/tie-ndss-2011.pdf)

 * [Polymorphic Type Inference for Machine Code](https://arxiv.org/abs/1603.05495)

### Control-Flow Reconstruction

 * [No More Gotos: Decompilation Using Pattern-Independent Control-Flow Structuring and Semantics-Preserving Transformations](http://www.ndss-symposium.org/ndss2015/ndss-2015-programme/no-more-gotos-decompilation-using-pattern-independent-control-flow-structuring-and-semantics/)

 * [Helping Johnny to Analyze Malware](https://www.computer.org/csdl/proceedings/sp/2016/0824/00/0824a158.pdf)

### C++ Decompilation

 * [SmartDec: Approaching C++ Decompilation](https://www.computer.org/csdl/proceedings/wcre/2011/1948/00/06079860.pdf)

### Identifier Recovery

 * [Meaningful Variable Names for Decompiled Code: A Machine Translation Approach](https://cmustrudel.github.io/papers/icpc18decompilation.pdf)

 * [Debin: Predicting Debug Information in Stripped Binaries](https://files.sri.inf.ethz.ch/website/papers/ccs18-debin.pdf)

## Advanced Topics

### Search-Based Decompilation

 * [Evolving Exact Decompilation](https://www.cs.unm.edu/~eschulte/data/bed.pdf)

### AI-based Decompilation

 * [Using Recurrent Neural Networks for Decompilation](http://www.cs.unm.edu/~eschulte/data/katz-saner-2018-preprint.pdf)

 * [Towards Neural Decompilation (2019)](https://arxiv.org/pdf/1905.08325.pdf)

### Binary-Source Matching

* [BinPro: A Tool for Binary Source Code Provenance](https://arxiv.org/pdf/1711.00830)

* [Statistical Similarity of Binaries](http://www.cs.technion.ac.il/~yahave/papers/pldi16.pdf)

* [Similarity of Binaries through re-Optimization](http://www.cs.technion.ac.il/~yanivd/pldi17/pldi17_GitZ.pdf)

* [Scalable Graph-based Bug Search for Firmware Images](http://www.cs.ucr.edu/~heng/pubs/genius-ccs16.pdf)

* [Neural Network-based Graph Embedding for Cross-Platform Binary Code Similarity Detection](https://arxiv.org/abs/1708.06525)

* [SAFE: Self Attentive Function Embedding For Binary Similarity](https://arxiv.org/abs/1811.05296)



