## Genes and Proteins

Q: A scientist splices a eukaryotic promoter in front of a bacterial gene and inserts the gene in a bacterial chromosome. Would you expect the bacteria to transcribe the gene?

A: No. Bacterial RNA polymerase only recognizes bacterial promoters (the −10/−35 consensus sequences) — it can't bind a eukaryotic promoter (TATA box, etc.), and bacteria lack the eukaryotic transcription factors needed to recruit it. The gene would sit untranscribed.

Why: A promoter is only a start signal to the machinery that evolved to read it — bacterial σ factor reads −10/−35 sequences, while eukaryotic promoters require eukaryotic transcription factors to recruit Pol II. With neither present in a bacterium, the hybrid gene has no landing pad. That's why genes cloned into E. coli are always placed behind a bacterial promoter.

Source: [OpenStax Biology 2e, §15.2 Prokaryotic Transcription](https://openstax.org/books/biology-2e/pages/15-2-prokaryotic-transcription) and [§16.4 Eukaryotic Transcription Gene Regulation](https://openstax.org/books/biology-2e/pages/16-4-eukaryotic-transcription-gene-regulation)

Q: Errors in splicing are implicated in cancers and other human diseases. What kinds of mutations might lead to splicing errors? Think of different possible outcomes if splicing errors occur.

A: Mutations that break splicing fall into a few classes: (1) point mutations in the spliceosome recognition sequences — the GU at the 5′ intron end, the AG at the 3′ end, or nearby enhancer/silencer sites where splicing factors bind; (2) mutations that *create* a new (cryptic) splice site in an exon or deep in an intron; (3) mutations in the spliceosome machinery itself (snRNAs or their proteins). Possible outcomes: a recognition-site loss causes the spliceosome to skip an exon or retain an intron; a new cryptic site causes part of an intron to be kept or part of an exon to be cut out. Either way the reading frame usually shifts, producing either a frameshifted/truncated dysfunctional protein, a premature stop codon (often triggering nonsense-mediated decay of the mRNA — a total loss of the protein), or occasionally an in-frame deletion (a shorter but partly working protein). Examples: splice-site mutations in the β-globin gene cause β-thalassemia; mutations in splicing factor genes (SF3B1, SRSF2, U2AF1) drive certain blood cancers.

Why: The spliceosome finds introns only by their short sequence signals (GU … AG plus nearby enhancer/silencer sites), so single-base changes can either erase a true signal or create a false one anywhere near an exon. And because exon/intron boundaries define where triplet reading begins and ends, most boundary errors shift the frame — which is why the typical outcome is a truncated or garbled protein rather than a slightly different one.

Source: [OpenStax Biology 2e, §15.4 RNA Processing in Eukaryotes](https://openstax.org/books/biology-2e/pages/15-4-rna-processing-in-eukaryotes) (this question is the Figure 15.13 Visual Connection); outcomes: [Splicing mutations in human genetic disorders, J Appl Genet 2018](https://link.springer.com/article/10.1007/s13353-018-0444-7)

Q: Many antibiotics inhibit bacterial protein synthesis. For example, tetracycline blocks the A site on the bacterial ribosome, and chloramphenicol blocks peptidyl transfer. What specific effect would you expect each of these antibiotics to have on protein synthesis?

A: Tetracycline — tRNA binding to the ribosome: the A site is where incoming charged aminoacyl-tRNAs dock, so blocking it stops new tRNAs from entering. Chloramphenicol — growth of the protein chain: peptidyl transferase is what catalyzes the peptide bond joining each new amino acid to the chain, so blocking it halts chain elongation (tRNAs can still bind). Neither directly affects ribosome assembly.

Why: Translation is an assembly line with dedicated stations, so an inhibitor blocks exactly the step that happens at the site it binds: the A site is the only entry point for aminoacyl-tRNA (delivery), and peptidyl transferase in the large subunit is the only thing that forms peptide bonds (chain growth). Blocking delivery ≠ blocking bonding — the two symptoms distinguish the two drugs.

Source: [OpenStax Biology 2e, §15.5 Ribosomes and Protein Synthesis](https://openstax.org/books/biology-2e/pages/15-5-ribosomes-and-protein-synthesis) (this question is the Figure 15.18 Visual Connection; answer per the text's review hint: tetracycline a, chloramphenicol c)

## Chapter 15 Review Questions (OpenStax Biology 2e)

Q4: The AUC and AUA codons in mRNA both specify isoleucine. What feature of the genetic code explains this?

A: Degeneracy — multiple codons can code for the same amino acid.

Why: The code has 64 codons for 20 amino acids (plus stops), so it must be redundant — most amino acids are spelled by several synonymous codons. Synonymous codons usually differ only in the third base, the position read loosely ("wobble"), which is what lets AUC and AUA both mean isoleucine.

Q5: How many nucleotides are in 12 mRNA codons?

A: 36 — each codon is 3 nucleotides (12 × 3).

Why: The genetic code is read in consecutive, non-overlapping groups of three nucleotides — that's what "codon" means — so nucleotide count is always codons × 3.

Q6: Which event contradicts the central dogma of molecular biology?

A: Scientists using reverse transcriptase to make DNA from RNA — the dogma is DNA → RNA → protein; reverse transcription runs RNA → DNA.

Why: The central dogma claims information flows one way: DNA → RNA → protein. Reverse transcriptase (carried by retroviruses such as HIV) copies RNA back into DNA, reversing the first arrow — the classic exception that forced the dogma to be restated as a general rule with exceptions.

Q7: Which subunit of the E. coli polymerase confers specificity to transcription?

A: σ (sigma) — it recognizes the promoter; without it, the core enzyme would transcribe from random sites.

Why: The core enzyme can synthesize RNA but can't tell a gene from random DNA. σ supplies the specificity by contacting the −10/−35 promoter sequences and melting the DNA to start initiation, then drops off for elongation. Different σ factors recognize different promoter classes, letting one bacterium switch gene programs (heat shock, sporulation).

Q8: The −10 and −35 regions of prokaryotic promoters are called consensus sequences because _____.

A: They are similar (not identical) in all bacterial species — consensus = the most common version of a shared sequence.

Why: "Consensus" means agreement in the majority, not universality: align the promoters of many bacterial genes and each position has a most-common base — that idealized average is the consensus. Individual promoters approximate it rather than copy it.

Q9: Three bacteria have these promoter sequences upstream of a conserved gene — order from most to least efficient transcription initiation:

| | Species A | Species B | Species C |
| --- | --- | --- | --- |
| −10 | TAATAAT | TTTAAT | TATATT |
| −35 | TTGACA | TTGGCC | TTGAAA |

A: A > C > B. Efficiency tracks closeness to the consensus (−10 TATAAT, −35 TTGACA): A matches consensus at −35 exactly and is closest at −10; C has one mismatch in each; B has the most mismatches, so σ binds it most weakly.

Why: σ-factor binding affinity — and therefore how often initiation fires — scales with how closely a promoter matches the ideal −10 (TATAAT) and −35 (TTGACA). Count total deviations from consensus: A has one, C has two, B has three, so binding strength and transcription rate fall A > C > B.

Q10: Which feature of promoters can be found in both prokaryotes and eukaryotes?

A: The TATA box — the prokaryotic −10 region (TATAAT) is its counterpart; GC box and octamer box are eukaryotic-only, −10/−35 prokaryotic-only.

Why: Both domains need an AT-rich anchor element for their machinery, and TATA is it: the eukaryotic TATA box sits upstream of Pol II genes, and the prokaryotic −10 element is essentially the same motif (TATAAT). The other elements co-evolved with domain-specific machinery — GC/octamer boxes are read only by eukaryotic factors, the −10/−35 pair only by bacterial σ.

Q11: What transcripts will be most affected by low levels of α-amanitin?

A: pre-mRNAs — RNA polymerase II (which makes all protein-coding pre-mRNAs) is extremely sensitive; Pol I (18S/28S rRNA) is insensitive, Pol III (5S rRNA, tRNAs, snRNAs) only moderately sensitive.

Why: The three nuclear RNA polymerases are structurally different, and the mushroom toxin discriminates them by dose: Pol II stops at low levels, Pol III only at high levels, Pol I essentially never. Whatever transcript class disappears at low dose therefore identifies Pol II (pre-mRNAs) as the target.

Q12: How do enhancers and promoters differ?

A: Enhancers increase the efficiency of gene expression but aren't essential for transcription; promoter recognition is essential for transcription initiation.

Why: A promoter is where the transcription machinery physically assembles and orients to begin — no promoter recognition, no initiation at all. An enhancer is an activator docking site that contacts that machinery through DNA looping and turns the rate up or down — modulation, not an on/off switch.

Q13: Which pre-mRNA processing step is important for initiating translation?

A: The 7-methylguanosine cap — the translation initiation machinery recognizes the 5′ cap.

Why: The eukaryotic ribosome doesn't find the start codon on its own — the initiation factors that assemble it grab the 5′ cap first, and that landing pad is what lets the small subunit attach and scan to the AUG. No cap, no efficient initiation.

Q14: What processing step enhances the stability of pre-tRNAs and pre-rRNAs?

A: Methylation — a –CH₃ group is added to some bases for stability.

Why: tRNAs and rRNAs are long-lived structural workhorses, and methylating some bases shields them from RNases and stabilizes their folded structure — chemistry that extends RNA lifetime, which is the stability this question is about.

Q15: A pre-mRNA is exon 100 bp / intron 50 bp / exon 75 bp / intron 90 bp / exon 120 bp. Predicted size of the mature mRNA (excluding cap and poly-A tail)?

A: 295 bp — splicing removes the introns, leaving only the exons (100 + 75 + 120).

Why: Mature mRNA contains only what the ribosome reads: exons spliced together in order. Add the exons (100 + 75 + 120 = 295); the introns (50 + 90 = 140) never appear in mature mRNA, and cap/poly-A are excluded by the question itself.

Q16: The RNA components of ribosomes are synthesized in the _____.

A: Nucleolus — rRNA is transcribed, processed, and assembled into ribosome subunits there.

Why: The nucleolus is the ribosome factory: Pol I transcribes the 45S pre-rRNA there, it is processed into the mature rRNAs and combined with ribosomal proteins into subunits, and the subunits are exported to the cytoplasm. All ribosomal RNA except 5S is born there.

Q17: In any given species, there are at least how many types of aminoacyl tRNA synthetases?

A: 20 — at least one per amino acid (each charges its cognate tRNA).

Why: Each aminoacyl-tRNA synthetase recognizes one amino acid and all of that amino acid's tRNAs — the enzyme is what guarantees each tRNA gets charged with its correct cargo. You need at least one per amino acid: 20 amino acids → at least 20 enzymes. Degeneracy adds tRNAs, not synthetases.

Q18: A mutation makes the 60S ribosomal subunit nonfunctional in a human cell line. Predicted effect on translation?

A: The ribosome cannot catalyze peptide bond formation between the tRNAs in the A and P sites — peptidyl transferase is part of the large (60S) subunit.

Why: The two subunits divide the work: the small (40S) subunit decodes mRNA–tRNA pairing, while the large (60S) subunit carries the peptidyl transferase activity — an rRNA ribozyme that forms the peptide bond between the A- and P-site tRNAs. Knock out the large subunit and matching still happens, but no bonds form and no chain grows.

Source: [OpenStax Biology 2e, Ch. 15 Review Questions](https://openstax.org/books/biology-2e/pages/15-review-questions); answers verified against §15.1–§15.5

## Chapter 15 Critical Thinking Questions (OpenStax Biology 2e)

Q19: Imagine there were 200 commonly occurring amino acids instead of 20. What would be the shortest possible codon length?

A: 4 nucleotides — codons must provide at least 200 distinct combinations: 4³ = 64 (too few), 4⁴ = 256 (enough).

Why: A codon of length n gives 4ⁿ possible codons, and that number must be at least as large as the set of amino acids it must uniquely label. With 200 amino acids, 4³ = 64 falls short; 4⁴ = 256 is the first length that covers them all.

Q20: Discuss how degeneracy of the genetic code makes cells more robust to mutations.

A: Codons for the same amino acid usually differ only in the third (wobble) base, so a point mutation there is often silent. Chemically similar amino acids also tend to have similar codons, so even when the amino acid changes, the substitution is often conservative rather than catastrophic.

Why: The code is arranged so that point mutations are usually survivable on two levels: wobble pairing lets one tRNA read several third-base variants (silent), and chemically similar amino acids are encoded by neighboring codons (conservative missense). The redundancy is a buffer, not an accident.

Q21: A scientist sequencing mRNA identifies: CUAUGUGUCGUAACAGCCGAUGACCCG. What amino acid chain does it make?

A: Met-Cys-Arg-Asn-Ser-Arg. Find the first AUG, then read in triplets: CU | AUG UGU CGU AAC AGC CGA UGA | CCCG — translation stops at UGA (a stop codon).

Why: The reading frame is set once, at the first AUG (start = methionine), then read in non-overlapping triplets until a stop codon ends translation — everything after the stop is never translated, which is why the trailing bases drop out of the answer.

Q22: If mRNA is complementary to the DNA template strand, and the template is complementary to the nontemplate strand, why aren't mRNA and the nontemplate strand identical? Could they ever be?

A: They match at every position except that mRNA has uracil where DNA has thymine. They could never be identical — mRNA contains U (and ribose), DNA contains T (and deoxyribose); the two molecules are chemically different.

Why: Complementarity is symmetric: mRNA and the nontemplate strand are both complements of the template, so they must carry the same sequence — that's why the nontemplate strand is called the coding strand. But identical molecules are impossible: RNA carries uracil and ribose where DNA has thymine and deoxyribose, so the best they can be is same-sequence-except-T-for-U.

Q23: In your own words, describe the difference between rho-dependent and rho-independent termination in prokaryotes.

A: Rho-dependent termination needs the ρ protein: ρ tracks along the growing mRNA behind the polymerase; when the polymerase stalls at a run of G nucleotides on the template near the gene's end, ρ catches up and collides with it, releasing the mRNA from the transcription bubble. Rho-independent termination needs no protein factor — the DNA sequence itself does the job: a C–G-rich stretch makes the mRNA fold into a hairpin that stalls the polymerase, and the weak A–U pairing in the region that follows lets the mRNA detach.

Why: The two mechanisms differ in where the termination signal lives: rho-dependent termination outsources it to a protein factor (ρ, which chases down the stalled polymerase and pries the transcript loose), while rho-independent termination encodes it in the sequence itself (GC-rich hairpin + weak A–U tail that release the mRNA with no help). Trans-acting protein vs cis-acting sequence.

Q24: A fragment of bacterial DNA (template strand): 3′–TACCTATAATCTCAATTGATAGAAGCACTCTAC–5′. What mRNA would be transcribed?

A: 5′–ACUAUCUUCGUGAGAUG–3′. The −10 consensus (TATAAT) sits near the 3′ end of the fragment; counting downstream, the +1 initiation site is the T immediately following the "AAT" — so the transcribed template is TGATAGAAGCACTCTAC, and the mRNA is its complement (U for T).

Why: Promoters are located by their consensus motifs, not their position: scan the template for the −10 TATAAT, and the first transcribed base (+1) sits a few bases downstream of it — here the T after the CTCAAT spacer. From +1, mRNA is the running complement of the template (A→U, T→A, C→G, G→C), because the template is read 3′→5′ toward the fragment's 5′ end.

Q25: A cell has an RNA polymerase deficiency that prevents it from making proteins. What three observations would support that Pol I (not Pol II or III) is the culprit?

A: (1) 18S and 28S rRNAs are absent/severely reduced — Pol I makes all rRNA except 5S, so no ribosomal subunits get assembled in the nucleolus, and without ribosomes no translation happens; (2) protein-coding pre-mRNAs are transcribed at normal levels (Pol II intact); (3) tRNAs and 5S rRNA are transcribed at normal levels (Pol III intact). Normal mRNA + normal tRNA + no rRNA = Pol I.

Why: Each nuclear polymerase owns a distinct transcript class, so the missing RNA identifies the enzyme: Pol I → large rRNAs, Pol II → pre-mRNA, Pol III → tRNA/5S. Pol I failure means mRNA and tRNA keep being made but no ribosomes are assembled — translation halts even though transcription of protein-coding genes is intact, which is exactly the observed pattern.

Q26: CLL patients often harbor nonsense mutations in their spliceosome machinery. How would this change the final location and sequence of a pre-mRNA?

A: The mutation eliminates splicing, so the "mature" mRNA would retain its introns — its sequence stays complementary to the entire DNA template (exons + introns joined together). It would still receive its 5′ cap and poly-A tail, so it could still be exported to the cytoplasm for translation — where the retained introns shift the reading frame and wreck the protein.

Why: A nonsense mutation truncates the spliceosome's protein components, disabling the machine that cuts introns out, so the transcript keeps every intron and stays complementary to the full gene. Capping and polyadenylation don't depend on splicing, so the mRNA still leaves the nucleus — but intron lengths aren't multiples of three, so the retained segments scramble the reading frame.

Q27: Transcribe and translate (nontemplate strand): 5′–ATGGCCGGTTATTAAGCA–3′

A: mRNA: 5′–AUGGCCGGUUAUUAAGCA–3′ (nontemplate = mRNA sequence, T→U). Codons: AUG GCC GGU UAU UAA GCA → Met-Ala-Gly-Tyr. UAA is a stop codon, so the sixth codon is never translated.

Why: The nontemplate strand is the coding strand — it reads like the RNA with T in place of U, so transcription is just T→U substitution. Translation then reads triplets from the start codon until a stop: everything after UAA is never translated.

Q28: Explain how single nucleotide changes can have vastly different effects on protein function.

A: It depends where the change lands: a change in the third (wobble) position is often silent (degeneracy); a missense change swaps one amino acid — harmless in a noncritical spot, devastating in an active site; a nonsense change creates a premature stop codon, truncating the protein and usually destroying its function; changes to start/stop codons or splice sites restructure the entire product.

Why: A single nucleotide is one base in a triplet code and one amino acid in a chain of hundreds — its effect depends entirely on position: in the codon (third base = often silent, first/second = missense, to a stop = truncation), in the protein (active site vs noncritical region), and in signals (start/stop/splice sites restructure the whole product). Same-size change, different context, different damage.

Q29: Normal mRNA 5′–UGCCAUGGUAAUAACACAUGAGGCCUGAAC–3′ has a U inserted after UGCCAUGG. Translate both and explain why insertions can be dramatic.

A: Original: AUG GUA AUA ACA CAU GAG GCC UGA → Met-Val-Ile-Thr-His-Glu-Ala (stop at UGA). Mutated: AUG GUU AAU AAC ACA UGA → Met-Val-Asn-Asn-Thr (stop at UGA now arrives early). The inserted nucleotide is not a multiple of three, so it frameshifts the reading of every codon after it — different amino acids and a premature stop, producing a much shorter, likely nonfunctional protein.

Why: Codons are read in a frame fixed at the start codon, so inserting one nucleotide shifts every subsequent codon by one base — the same stretch of mRNA now decodes into entirely different amino acids and hits a stop earlier. Insertions/deletions are only harmless when they change the length by a multiple of three.

Source: [OpenStax Biology 2e, Ch. 15 Critical Thinking Questions](https://openstax.org/books/biology-2e/pages/15-critical-thinking-questions); answers verified against the textbook's official hints (Q21, Q24, Q26, Q27, Q29 sequence answers match the published key)
