# Unit 3 Exam Study Guide — Answers & Explanations

## Genetics & Inheritance

Q: What is the difference between genotype and phenotype?

A: Genotype = the alleles an organism carries (its genetic makeup, e.g. Rr). Phenotype = the observable traits those alleles produce (e.g. round peas). Genotype determines phenotype, but you can't always read the genotype from the phenotype — a dominant phenotype (round) could be either RR or Rr.

Why: The genotype is the instruction sheet, the phenotype is the finished product. Dominance masks the distinction: Rr and RR look identical (same phenotype) but breed differently (different genotype) — which is exactly why test crosses exist.

Q: What are Mendel's three principles?

A: **Principle of Segregation** — the two alleles of a gene separate (segregate) from each other during gamete formation, so each gamete carries only one allele per gene. **Principle of Dominance** — in a heterozygote, one allele (dominant) masks the other (recessive); the dominant trait is what shows in the phenotype. **Principle of Independent Assortment** — genes for different traits sort into gametes independently of each other (a pea's seed color doesn't influence its seed shape), which is what produces the 9:3:3:1 dihybrid ratio.

Why: Each principle describes what physically happens in meiosis: homologous chromosomes (and their alleles) separate in anaphase I (segregation), one allele's product wins in the heterozygote (dominance), and different chromosome pairs align and migrate independently in metaphase I (independent assortment). The laws are Mendel's statistics; meiosis is the mechanism.

Q: What is a testcross and what is it used for?

A: A testcross crosses an individual with a dominant phenotype but unknown genotype (RR or Rr) against a homozygous recessive individual (rr). The offspring reveal the mystery genotype: all dominant offspring → the parent was RR; a 1:1 dominant:recessive ratio → the parent was Rr.

Why: The homozygous recessive partner is the trick — it can only contribute a recessive allele, so every recessive allele in the unknown parent has nowhere to hide: rr offspring are only possible if the unknown parent contributed a recessive allele, proving it was heterozygous.

Example: 
Punnet square show typical crosses

|     | y   | y   |
| --- | --- | --- |
| Y   | Yy  | Yy  |
| y   | yy  | yy  |

Q: What is the difference between homozygous and heterozygous?

A: Homozygous = both alleles at a gene are the same (RR or rr). Heterozygous = the two alleles differ (Rr). Homozygotes are true-breeding — they produce only one gamete type; heterozygotes produce two.

Why: Gametes get one allele per gene, so a homozygote has only one thing to give (RR → all R gametes) while a heterozygote gives either (Rr → half R, half r). That's why only heterozygotes produce the characteristic 3:1 and 1:1 ratios — uniform parents can't segregate anything.

Q: What is the difference between dominant and recessive?

A: A dominant allele is expressed in the phenotype even when only one copy is present (masks the other allele in a heterozygote). A recessive allele is only expressed when both copies are recessive — in a homozygote — because in a heterozygote the dominant allele hides it. Recessive alleles aren't "weaker"; they can encode perfectly functional (or dysfunctional) proteins that simply aren't seen when a dominant allele is present.

Why: Dominance describes the phenotype of the heterozygote, not the strength of the allele. One functional dominant copy (often making enough enzyme) is sufficient for the trait, so the recessive version only shows up when no dominant copy is present — "dominant" and "recessive" are statements about masking, not quality.

Q: What are the different forms of inheritance that extend simple dominance?

A: **Incomplete dominance** — the heterozygote is intermediate between the two homozygotes (red × white snapdragon → pink); neither allele fully masks the other. **Codominance** — both alleles are fully expressed in the heterozygote at the same time (AB blood type expresses both A and B antigens). **Multiple alleles** — a gene has more than two allele versions in the population (ABO blood system: A, B, O); any individual still carries only two. **Pleiotropy** — one gene affects several seemingly unrelated traits (e.g. Marfan syndrome affects height, vision, and the heart; the coat color gene in mice affects pigmentation and viability). **Epistasis** — one gene's alleles mask or modify another gene's expression (e.g. the gene for pigment deposition can hide the coat-color gene entirely, producing the 9:3:4 recessive epistasis ratio). **Blending inheritance** — the pre-Mendelian idea that parental traits mix permanently in offspring like fluids; it was disproved because blending predicts offspring are always intermediate and variation would be diluted away — discrete genes that pass intact generation after generation are what Mendel showed instead.

Why: Simple dominance (one allele masks the other) is only the first pattern Mendel found. The exceptions make sense mechanistically: enzymes with partial activity give intermediate color (incomplete dominance), surface antigens are independently displayed (codominance), one gene's product can sit downstream of another's (epistasis), and one gene product used in many tissues produces many symptoms (pleiotropy). Blending fails because genes are discrete particles, not fluids — they reappear unchanged generations later.

Source: [OpenStax Biology 2e, Ch. 12](https://openstax.org/books/biology-2e/pages/12-introduction) — §12.2 (testcross, dominance), §12.3 (laws of inheritance, incomplete dominance, codominance, epistasis, pleiotropy, multiple alleles); see also [chapter-12.md](./chapter-12.md)

## DNA Structure

Q: Describe the structure of DNA.

A: Two antiparallel strands form a right-handed double helix: sugar-phosphate backbones on the outside, nitrogenous bases stacked inside like ladder rungs. Each nucleotide = a deoxyribose sugar + phosphate group + one of four bases (A, T, G, C). The strands run in opposite directions (antiparallel: one 5′→3′, the other 3′→5′) and are **complementary** — A pairs only with T, G only with C — so each strand fully specifies the other.

- **Purines vs pyrimidines:** purines (adenine, guanine) are double-ringed bases; pyrimidines (thymine, cytosine — and uracil in RNA) are single-ringed. Every base pair is one purine + one pyrimidine, which keeps the helix a constant width.
- **Complementary:** A–T (two hydrogen bonds) and G–C (three hydrogen bonds) — each strand is the mirror-in-sequence of the other, which is what lets each serve as a template.
- **Parallel vs antiparallel:** the two strands run in opposite directions (one 5′→3′, its partner 3′→5′); nucleic acid "direction" is defined by the sugar carbons the backbone connects (5′-phosphate end vs 3′-OH end).
- **How the strands are held together:** hydrogen bonds between paired bases (2 in A–T, 3 in G–C) plus hydrophobic/van der Waals stacking between the base pairs along the helix axis.

Why: Purine + pyrimidine pairing keeps every rung the same width, which is what makes the helix uniform — two purines would bulge, two pyrimidines would pinch. Complementarity plus antiparallel orientation means each strand carries the full information to rebuild its partner — the structural basis of replication, repair, and transcription. Hydrogen bonds hold the pairs together (individually weak; many of them together = stable, yet still unzippable), and base stacking provides most of the helix's physical stability.

Q: What are Chargaff's rules?

A: In double-stranded DNA from any species: the amount of adenine equals the amount of thymine (A = T), and guanine equals cytosine (G = C) — so %A = %T and %G = %C. The base *composition* itself varies from species to species (some genomes are A+T-rich, others G+C-rich), which showed DNA's sequence isn't a boring fixed repeat. Example: if a DNA sample is 27% A, it's 27% T, and the remaining 46% splits evenly — 23% G, 23% C.

Why: Chargaff measured actual base composition and found the pairing regularity that Watson and Crick's model explains: because A pairs only with T and G only with C, the counts must match in any double helix — and any sample of double-stranded DNA is a mixture of base pairs, so A always equals T. The between-species variation is what killed both the tetranucleotide (fixed repeat) hypothesis and blending, and pointed straight at base sequence as the information.

Source: [OpenStax Biology 2e, §14.2 DNA Structure and Sequencing](https://openstax.org/books/biology-2e/pages/14-2-dna-structure-and-sequencing); see also [chapter-14.md](./chapter-14.md)

## DNA Replication

Q: What is semiconservative replication?

A: Each new DNA double helix contains one original (parental) strand and one newly synthesized strand — the helix "half conserves" its old material. Each parental strand unwinds and serves as a template for building its complement, so the two daughter molecules are identical to the parent. This is what Watson–Crick complementarity predicted and what Meselson and Stahl proved with their ¹⁵N/¹⁴N density experiment.

Why: Because each strand specifies its partner exactly, splitting the helix and templating a complement is the only copying mechanism the structure allows. Meselson–Stahl confirmed it: after one round of replication all DNA was intermediate density (one heavy + one light strand per molecule) — ruling out conservative (all-old vs all-new molecules) and dispersive models.

Q: What are the roles of the enzymes of DNA replication?

A: Each enzyme has one job at the replication fork:

- **DNA helicase** — unwinds the double helix by breaking the hydrogen bonds between base pairs, creating the replication fork.
- **DNA gyrase** (a topoisomerase) — relieves the supercoiling/torsional strain that builds up ahead of the unwinding fork, by cutting, swiveling, and re-sealing the DNA.
- **DNA primase** — lays down a short RNA primer (complementary to the template) to give DNA polymerase its required starting 3′-OH.
- **DNA polymerase** — the builder: adds nucleotides to the 3′ end of a growing strand, complementary to the template (5′→3′ synthesis); in prokaryotes, DNA pol III is the main replicator, DNA pol I replaces RNA primers with DNA, and its 3′→5′ **exonuclease** activity proofreads as it goes.
- **DNA ligase** — seals the nicks between Okazaki fragments (and between replaced primers and DNA) by catalyzing the phosphodiester bond between a 3′-OH and a 5′-phosphate.
- **DNA endonuclease** — cuts a strand at an internal position; in replication/repair this is how damaged or unwanted segments are excised (e.g. nucleotide excision repair cuts out thymine dimers on both sides of the damage).
- **DNA exonuclease** — removes nucleotides from the *end* of a strand: proofreading (DNA pol backs up and clips a mispaired base) and chewing away RNA primers for replacement with DNA.

(These are the replication enzymes. Transcription and translation use different machinery: RNA polymerase synthesizes RNA from a DNA template with no primer needed, and the ribosome — an rRNA ribozyme, peptidyl transferase — catalyzes peptide bonds between amino acids.)

Why: Replication is an assembly line with one specialist per step: someone must open the helix (helicase), someone must relieve the wind-up strain (gyrase), someone must solve the cold-start problem (primase), someone builds (polymerase), someone proofreads and removes (exonuclease/Pol I), someone excises internal damage (endonuclease), and someone welds the pieces into one strand (ligase). Exam questions usually name the symptom — unjoined fragments → ligase; supercoiled stuck fork → gyrase; no starting 3′-OH → primase; persistent mismatches → exonuclease/proofreading.

Q: In which direction are nucleotides added to the growing DNA strand?

A: 5′ → 3′ — DNA polymerase can only add nucleotides to the free 3′-OH end of an existing strand. The new nucleotide's 5′-phosphate is bonded to the growing chain's 3′-OH.

Why: The polymerization chemistry is one-way: the energy for forming the phosphodiester bond comes from the incoming nucleotide's triphosphate, and the bond always forms between the chain's 3′-OH and the incoming 5′-phosphate. Chains can only grow at the 3′ end — this single constraint is what forces the lagging strand's backwards, fragment-based synthesis.

Q: What are Okazaki fragments?

A: Short stretches of newly synthesized DNA on the lagging strand, each starting with its own RNA primer. Because polymerase only synthesizes 5′→3′ and the two template strands are antiparallel, the lagging strand must be built backwards — in short pieces as the fork opens more template — which are later joined into one continuous strand (primers replaced with DNA by Pol I, nicks sealed by ligase).

Why: One strand's template runs 3′→5′ toward the fork (leading strand — copied continuously), but the other template runs the wrong way, so as helicase exposes more of it, polymerase — which cannot move 3′→5′ — must restart again and again behind the fork. The fragments are the necessary consequence of one-way synthesis on an antiparallel template.

Q: What is the role of an RNA primer?

A: The primer is a short RNA stretch (5–10 nucleotides) laid down by primase, complementary to the template, whose job is to provide the free 3′-OH that DNA polymerase requires to start adding nucleotides — polymerases cannot begin synthesis from nothing.

Why: DNA polymerase can only *extend* an existing chain — the first phosphodiester bond needs a 3′-OH to attach the incoming nucleotide's 5′-phosphate to, and a bare template offers none. RNA primase solves this cold-start problem; the RNA is temporary and is later removed and replaced with DNA.

Q: Why do eukaryotes have multiple origins of replication?

A: With genomes thousands of times larger than a bacterium's and linear chromosomes, a single origin would take far too long to copy. Multiple origins fire simultaneously along each chromosome, creating many replication forks and bubbles that expand and eventually merge — the whole genome gets copied in hours instead of weeks.

Why: Replication speed per fork is fixed by enzyme chemistry, so total time = genome size ÷ number of forks. Eukaryotes buy speed with parallelism: many origins → many forks running at once. Prokaryotes, with a small circular chromosome, get by with a single origin and two forks.

Q: What are thymine dimers?

A: A covalent linkage between two adjacent thymine bases on the same DNA strand, caused by ultraviolet (UV) light. The dimer kinks the helix, so polymerases can't read past it — replication and transcription stall. Cells repair them by nucleotide excision repair: endonucleases cut the damaged strand on both sides, the segment (with the dimer) is removed, DNA pol fills the gap, and ligase seals it.

Why: UV energy fuses the double rings of neighboring thymines into a cyclobutane dimer, bending the backbone so the template no longer fits into a polymerase. It's the classic DNA-damage example: the damage isn't a replication *error* — it's physical distortion of the template that only an excision-repair crew (cut, remove, refill, seal) can fix. This is the molecular basis of sunburn-driven skin cancer.

Source: [OpenStax Biology 2e](https://openstax.org/books/biology-2e/pages/14-3-dna-replication) — §14.3 (semiconservative model, replication machinery, telomeres), §14.4 (RNA primers, Okazaki fragments), §14.5 (proofreading, mismatch repair, nucleotide excision repair, thymine dimers); see also [chapter-14.md](./chapter-14.md)

## Transcription & Translation

Q: What is the difference between replication, transcription, and translation?

A: **Replication** — copying the entire DNA molecule before cell division (DNA → DNA). **Transcription** — copying one gene's DNA sequence into mRNA (DNA → RNA), catalyzed by RNA polymerase. **Translation** — decoding the mRNA sequence into a chain of amino acids (RNA → protein), carried out by ribosomes reading codons with tRNAs delivering the matching amino acids.

Why: The three processes are the three arrows of the central dogma, each with its own template, machine, and product: replication duplicates the whole archive, transcription photocopies one gene's instructions, and translation builds the actual working protein from that copy. Same polymer chemistry, different template molecule, enzyme, and output.

Q: What is splicing, and how does it work?

A: Splicing removes introns (noncoding sequences) from a eukaryotic pre-mRNA and joins the exons (coding sequences) together to make the mature mRNA. The spliceosome — a large complex of snRNPs (small nuclear RNAs + proteins) — recognizes the conserved sequence signals at intron boundaries (GU at the 5′ end, AG at the 3′ end), cuts the intron out as a lariat loop, and ligates the flanking exons. Purpose: without it, an mRNA would contain useless (and frame-wrecking) intron sequence. Bonus: alternative splicing lets one gene produce multiple different proteins by selecting different exon combinations.

Why: Eukaryotic genes are split — the coding information is interrupted by introns — so the raw transcript is a rough draft that must be edited before it can be read by a ribosome. Exon boundaries define where triplet codons begin and end, which is also why splicing errors are so damaging (frameshifts) and why alternative splicing is a powerful way to get many proteins from one gene.

Q: Where does each process take place?

A: **Eukaryotes:** replication — nucleus (also mitochondria/chloroplasts); transcription — nucleus; translation — cytoplasm (on free or ER-bound ribosomes). The nucleus/cytoplasm separation means eukaryotic RNA is fully processed (capped, spliced, poly-adenylated) *before* it is ever translated. **Prokaryotes:** all three happen in the cytoplasm (they have no nucleus), and transcription and translation are even coupled — translation begins on an mRNA that is still being transcribed.

Why: The physical boundary between DNA (nucleus) and ribosomes (cytoplasm) is what gives eukaryotes a processing stage — extra points of regulation and more complex transcripts — at the cost of speed. Prokaryotes trade that complexity for raw speed: no separation, no processing, no delay.

Q: What are the roles of each type of RNA?

A: **mRNA (messenger)** — carries the protein-coding information from DNA to the ribosome; its codons are read during translation. **tRNA (transfer)** — the physical adapter: one end carries a specific amino acid, the other has an anticodon that base-pairs with the matching mRNA codon, so it translates nucleotide language into amino acid language. **rRNA (ribosomal)** — structural and catalytic component of ribosomes; the large subunit's rRNA acts as peptidyl transferase, the ribozyme that actually forms peptide bonds. **snRNA (small nuclear)** — RNA components of snRNPs, which together form the spliceosome that removes introns from pre-mRNA in the nucleus. **miRNA (micro)** — small regulatory RNAs that bind complementary sequences in mRNAs and shut them down (degradation or translational inhibition) — gene regulation after transcription.

Why: Each RNA is a different worker in the same flow of information: mRNA is the message, tRNA is the translator (adapter between the two "languages"), rRNA is the factory machinery (and the catalyst), snRNA is the editing crew, and miRNA is the quality-control/regulatory layer that decides which messages get used at all.

Q: What is the difference between codons, introns, and exons?

A: **Codon** — a group of three consecutive nucleotides in *mRNA* that specifies one amino acid (or a stop signal); 64 codons cover 20 amino acids plus stop. **Exon** — a coding sequence in a eukaryotic gene; exons are spliced together and remain in the mature mRNA (and are what get translated into codons). **Intron** — a noncoding interrupting sequence in a eukaryotic gene; it is transcribed into pre-mRNA but spliced out and never translated.

Why: The three words live at different levels of the same pipeline: introns and exons are segments of the *gene/transcript* (raw material vs final cut), while codons are the three-base reading units that exist in the *mature mRNA* after splicing. Introns never contribute codons — they're removed precisely because their lengths would wreck the triplet frame.

Q: What is the central dogma of biology?

A: Information flows in one direction: DNA → RNA → protein (via the three processes replication, transcription, translation). The classic exception: retroviruses like HIV carry reverse transcriptase, which copies RNA back into DNA (RNA → DNA), forcing the dogma to be restated as a general rule with exceptions.

Why: The dogma states which molecules specify which: DNA is the archive, RNA is the working copy, protein is the functional product — and information doesn't flow backward from protein to nucleic acid. Reverse transcription is the famous arrow-reversal, which is why it's the standard exam example of a contradiction.

Q: How do eukaryotic and prokaryotic processing of genetic information differ?

A: **Prokaryotes:** transcription and translation happen in the same compartment and are coupled; mRNA is used almost immediately, with little to no processing (no cap, no splicing — bacterial genes usually have no introns; no poly-A tail). **Eukaryotes:** transcription happens in the nucleus, and the pre-mRNA must be processed before translation — a 5′ 7-methylguanosine cap (needed to initiate translation), splicing of introns by the spliceosome, and a 3′ poly-A tail (stability) — then the mature mRNA is exported to the cytoplasm for translation.

Why: The presence of a nucleus is the root difference: it separates the transcription machinery from the ribosomes, which creates an obligate processing stage between the two. That stage is extra regulation and more transcript complexity (like alternative splicing) — the price is speed. Prokaryotes skip all of it and translate even unfinished messages.

Q: What is a spliceosome, and what does it do?

A: A large complex in the eukaryotic nucleus, made of snRNPs (snRNA + protein particles), that removes introns from pre-mRNA and ligates the exons together. It recognizes the splice signals (GU at the 5′ intron end, AG at the 3′ end, plus a branch-point A), cuts the intron out as a lariat, and joins the flanking exons.

Why: Splicing is chemistry that has to happen with single-nucleotide precision — off by one base and the reading frame collapses — so it needs a dedicated machine, not just an enzyme. The snRNAs are the recognition part (they base-pair with the splice signals), the proteins provide the cutting and joining activity. Nonsense mutations in spliceosome components are found in cancers and blood disorders precisely because every mRNA depends on it.

Q: What are the three sites of a ribosome for?

A: They are the tRNA docking stations that step the message along during elongation. **A site (aminoacyl)** — where the incoming charged tRNA carrying the next amino acid binds, matched to the current mRNA codon. **P site (peptidyl)** — holds the tRNA attached to the growing polypeptide chain; the peptide bond is formed here, transferring the chain onto the A-site amino acid. **E site (exit)** — where the now-empty tRNA sits briefly before leaving the ribosome. After each peptide bond, the ribosome translocates one codon, so every tRNA moves A → P → E.

Why: Translation is an assembly line, and the three sites are its stations: delivery (A), chain-growth/bond formation (P), and release (E). Knowing the stations explains the antibiotics too — tetracycline blocks the A site (no delivery), chloramphenicol blocks peptidyl transfer at the P site (no chain growth).

Q: What is the difference between the coding strand and the template strand of DNA?

A: The **template strand** is the one RNA polymerase actually reads: the mRNA is built complementary to it, antiparallel, in the 5′→3′ direction. The **coding strand** (nontemplate) has the *same* sequence as the mRNA — except T where the mRNA has U — which is why it's called "coding." The two strands of the double helix switch roles gene by gene: either strand can be the template for a given gene.

Why: Only one strand can be read at a time (polymerase moves one way, 5′→3′), and the strand it reads becomes the mRNA's complement — the other strand is left as a lookalike of the product. The naming follows the result: "template" = what was read; "coding" = the strand whose sequence spells the codons (with T/U swapped). Practical shortcut: to get the mRNA, copy the coding strand and swap T→U.

Source: [OpenStax Biology 2e](https://openstax.org/books/biology-2e/pages/15-introduction) — §15.1 (genetic code, central dogma), §15.2 (prokaryotic transcription), §15.3 (eukaryotic transcription, coding vs template strand), §15.4 (RNA processing, splicing, spliceosome, miRNA), §15.5 (ribosomes, A/P/E sites, tRNA, rRNA); see also [chapter-15.md](./chapter-15.md)
