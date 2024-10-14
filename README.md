This repo includes links relevant to Mixed Boolean-Arithmetic (MBA) obfuscation. PRs are welcome. 

Note that some resources here are not *strictly* related to MBA, though all are relevant in some way.

## Papers

- **[Information Hiding in Software with Mixed Boolean-Arithmetic Transforms](https://link.springer.com/chapter/10.1007/978-3-540-77535-5_5)**
- **[Obfuscation with Mixed Boolean-Arithmetic Expressions : reconstruction, analysis and simplification tools](https://theses.hal.science/tel-01623849/document)**
- **[Analysis and applications of orthogonal approaches to simplify Mixed Boolean-Arithmetic expressions](https://arnaugamez.com/assets/theses/msc.pdf)**
- **[Code deobfuscation by program synthesis-aided simplification of Mixed Boolean-Arithmetic expressions](https://arnaugamez.com/assets/theses/bsc.pdf)**
- **[Boosting SMT solver performance on mixed-bitwise-arithmetic expressions](https://dl.acm.org/doi/abs/10.1145/3453483.3454068)**
- **[MBA-Blast: Unveiling and Simplifying Mixed Boolean-Arithmetic Obfuscation](https://www.usenix.org/conference/usenixsecurity21/presentation/liu-binbin)**
- **[An In-Place Simplification on Mixed Boolean-Arithmetic Expressions](https://doi.org/10.1155/2022/7307139)**
- **[Software Obfuscation with Non-Linear Mixed Boolean-Arithmetic Expressions](https://par.nsf.gov/servlets/purl/10318183)**
- **[NeuReduce: Reducing Mixed Boolean-Arithmetic Expressions by Recurrent Neural Network](https://www.semanticscholar.org/paper/NeuReduce%3A-Reducing-Mixed-Boolean-Arithmetic-by-Feng-Liu/958da5461cc6e1169e93990350493aeb8cb57e60)**
- **[Efficient Deobfuscation of Linear Mixed Boolean-Arithmetic Expressions](https://arxiv.org/abs/2209.06335)**
- **[Simplifying Mixed Boolean-Arithmetic Obfuscation by Program Synthesis and Term Rewriting](https://dl.acm.org/doi/pdf/10.1145/3576915.3623186)**
- **[Simplification of General Mixed Boolean-Arithmetic Expressions: GAMBA](https://arxiv.org/abs/2305.06763)**
- **[Deobfuscation of Semi-Linear Mixed Boolean-Arithmetic Expressions](https://arxiv.org/abs/2406.10016)**
- **[Mixed Boolean-Arithmetic (MBA) Obfuscation Using Permutation Polynomials on Modular Lipschitz Integers](https://ieeexplore.ieee.org/abstract/document/10667325)**
- **[On simplifying expressions with mixed Boolean-arithmetic](https://www.mathnet.ru/php/archive.phtml?wshow=paper&jrnid=mais&paperid=795&option_lang=eng)**
- **[Binary Permutation Polynomial Inversion and Application to Obfuscation Techniques](https://dl.acm.org/doi/10.1145/2995306.2995310)**
- **[Quadratic time algorithm for inversion of binary permutation polynomials](https://hal.science/hal-01981320/document)**
- **[Efficient Normalized Reduction and Generation of Equivalent Multivariate Binary Polynomials](https://www.ndss-symposium.org/wp-content/uploads/bar2024-14-paper.pdf)**
- **[Bypassing Malware Obfuscation with Dynamic Synthesis](https://inria.hal.science/hal-01378662/document)**
- **[Search-Based Local Black-Box Deobfuscation: Understand, Improve and Mitigate](https://dl.acm.org/doi/10.1145/3460120.3485250)**
- **[Syntia: Synthesizing the Semantics of Obfuscated Code](https://www.usenix.org/system/files/conference/usenixsecurity17/sec17-blazytko.pdf)**
- **[Arybo: Manipulation, Canonicalization and Identification of Mixed Boolean-Arithmetic Symbolic Expressions](https://dl.acm.org/doi/pdf/10.1145/3576915.3623186)**
- **[Loki: Hardening Code Obfuscation Against Automated Attacks](https://www.usenix.org/system/files/sec22-schloegel.pdf)**
- **[QSynth – A Program Synthesis based approach for Binary Code Deobfuscation](https://www.ndss-symposium.org/wp-content/uploads/2020/04/bar2020-23009-paper.pdf)**
- **[On polynomial functions (mod m)](https://www.sciencedirect.com/science/article/pii/0022314X74900316?via%3Dihub)**
- **[Polynomial functions (modm)](https://link.springer.com/article/10.1007/BF01950276)**
- **[Permutation Polynomials Modulo 2^w](https://www.sciencedirect.com/science/article/pii/S107157970090282X?via%3Dihub)**
- **[Gröbner Bases for Boolean Function Minimization](https://ceur-ws.org/Vol-3455/short4.pdf)**

## Implementations

### Simplification:
- **[SiMBA: Efficient Deobfuscation of Linear Mixed Boolean-Arithmetic Expressions](https://github.com/DenuvoSoftwareSolutions/SiMBA)**
- **[SiMBA++: Port of SiMBA to C/C++](https://github.com/pgarba/SiMBA-)**
- **[GAMBA: Simplification of General Mixed Boolean-Arithmetic Expressions](https://github.com/DenuvoSoftwareSolutions/GAMBA)**
- **[Oracle Syntehsis Meets Equality Saturation](https://github.com/fvrmatteo/oracle-synthesis-meets-equality-saturation)**
- **[MSiMBA: Deobfuscation of Semi-Linear Mixed Boolean-Arithmetic Expressions](https://github.com/mazeworks-security/MSiMBA)**
- **[Simplifier: Efficient general mixed boolean-arithmetic (MBA) simplifier](https://github.com/mazeworks-security/Simplifier)**
- **[MBA-Blast: Tool for simplification of MBA expressions](https://github.com/softsec-unh/MBA-Blast)**
- **[MBA-Solver: Boosting SMT solver performance on mixed-bitwise-arithmetic expressions](https://github.com/softsec-unh/MBA-Solver)**
- **[Arybo: Manipulation, canonicalization and identification of mixed boolean-arithmetic symbolic expressions](https://github.com/quarkslab/arybo)**
- **[msynth: Code deobfuscation framework to simplify Mixed Boolean-Arithmetic (MBA) expressions](https://github.com/mrphrazer/msynth)**
- **[QSynth: Greybox Synthesizer geared for deobfuscation of assembly instructions](https://github.com/quarkslab/qsynthesis)**
- **[gooMBA: Hex-Rays Decompiler plugin to simplify Mixed Boolean-Arithmetic (MBA) expressions](https://github.com/HexRaysSA/goomba)**
- **[Syntia: Program synthesis based deobfuscation framework](https://github.com/RUB-SysSec/syntia)**
- **[Tigress Deobfuscation - Documentation of several Tigress obfuscation passes and an attempt to simplify Mixed Boolean-Arithmetic (MBA) expressions](https://github.com/adutilleul/tigress-deobfuscation)**
- **[M3: An Efficient Deobfuscation of Mixed Boolean Arithmetic (MBA) Expressions Using Dynamic Analysis](https://github.com/letonchanh/M3)**

### Boolean manipulation and minimization:
- **[Gröbner Bases for Boolean Function Minimization](https://github.com/cispa/Microarchitectural-Hash-Function-Recovery/tree/main/minimizer)**
- **[Espresso heuristic logic minimizer](https://github.com/Gigantua/Espresso)**
- **[Kitty: C++ boolean truth table library](https://github.com/msoeken/kitty)**
- **[Combining DNF minimization, ANF minimization, and up to 4-variable precomputed truth tables](https://github.com/mazeworks-security/Simplifier/tree/master/Mba.Simplifier/Minimization)**
- **[DenseQMC: A bit-slice implementation of the Quine-McCluskey algorithm](https://github.com/hellman/Quine-McCluskey)**
- **[boolean_expression: a small Rust crate for Boolean expressions and BDDs](https://github.com/cfallin/boolean_expression)**

### Construction:
- **[MBA-Obfuscator: Tool for generating Non-linear Mixed Boolean-Arithmetic Expressions](https://github.com/nhpcc502/MBA-Obfuscator)**
- **[Mba: Mixed Boolean-Arithmetic](https://github.com/plzin/mba)**
- **[Pocket: Mixed Boolean Arithmetic Expression Obfuscator](https://github.com/seekbytes/pocket)**
- **[MBA-Generator: Generator for Mixed-Boolean-Arithmetic expressions.](https://github.com/generic-placeholder-name/MBA-Generator)**
- **[Mutaben: Simple mixed-boolean-arithmetic (MBA) generator witten in python](https://github.com/z1ko/mutaben)**
- **[Mixed-boolean-transform: Mixed boolean arithmetic x+y transform](https://github.com/sant024/mixed-boolean-transform)**

## Blog Posts
- **[Mixed Boolean-Arithmetic](https://plzin.github.io/posts/mba)**
- **[Improving MBA Deobfuscation using Equality Saturation](https://secret.club/2022/08/08/eqsat-oracle-synthesis.html)**
- **[What theoretical tools are needed to simplify MBA expressions?](https://blog.quarkslab.com/what-theoretical-tools-are-needed-to-simplify-mba-expressions.html)**
- **[Introduction to Pocket: obfuscator for Mixed Boolean Arithmetic expressions](https://nicolo.dev/en/blog/introduction-pocket-obfuscator/)**
- **[Practical MBA Deobfuscation with msynth](https://synthesis.to/2021/11/11/practical_mba_deobfuscation.html)**

# Miscellaneous items (only tangentially relevant to MBA)
- **[ægraphs: Acyclic E-graphs for Efficient Optimization in a Production Compiler](https://pldi23.sigplan.org/details/egraphs-2023-papers/2/-graphs-Acyclic-E-graphs-for-Efficient-Optimization-in-a-Production-Compiler)**
- **[Optir: Compiler optimizer for arbitrary control flow based on equality saturation](https://github.com/jameysharp/optir)**
- **[Z3 adventures and fast Boolean matching](https://jamey.thesharps.us/2021/09/05/z3-boolean-matching/)**
- **[Fast Boolean Matching Based on NPN Classification](https://people.eecs.berkeley.edu/~alanmi/publications/2013/icfpt13_npn.pdf)**
- **[SAT-Based Algorithms for Logic Minimization](https://www.cs.cmu.edu/~emc/papers/Conference%20Papers/SAT-Based%20Algorithms%20for%20Logic%20Minimization.pdf)**
- **[Cranelift's Instruction Selector DSL, ISLE: Term-Rewriting Made Practical
](https://cfallin.org/blog/2023/01/20/cranelift-isle/)**