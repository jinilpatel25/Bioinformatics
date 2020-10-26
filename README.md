A DNA molecule or strand is a sequence of molecular units called bases or nucleotides (these are synonyms). There are four types, denoted A (adenine), C (cytosine), G (guanine), 
and T (thymine). Each strand of the familiar double-helix human DNA molecule contains about 3 billion of these nucleotides. There are two strands of DNA in the double helix,
and each is a complementary copy of the other: an "A" on one strand is always paired with a "T" on the other, and a "C" is always paired with a "G". Sometimes we call these base
pairs. Since reconstructing the base sequence of one strand is trivial if we have the sequence of the other, we really only need to study one strand to understand what a 
particular section of DNA does.

In our genetic code, three nucleotides (i.e., three "letters") of DNA form a codon and specify a single amino acid. There are 20 common types of amino acids. A protein molecule
is nothing more than a long strand of amino acids. The amino acids determine the shape of the protein and, consequently, its function in the cell which makes it. DNA does not
wear out quickly, compared with proteins. This makes DNA well suited for data storage in the cell. DNA is essentially a biological data structure.

A gene is a (usually long) sequence of codons and thus specifies a sequence of amino acids (a protein). Our genetic code is a fixed-length code: there are exactly three nucleotides
in the code word (codon) for every amino acid. Why do you think the genetic code uses three DNA units per codon, rather than one or two units per codon? How many codons would
there be if there were two units per codon? Why not four or more units per codon?

Each entry in the Table 2.1 below lists a codon — three capital letters representing DNA nucleotides — and an amino acid or the word "stop". For example, TCT speci?es the amino
acid serine. The stop codons, TAA, TAG, and TGA, tell the cell's translational machinery that the end of a gene has been reached. Notice that more than one codon can specify the
same amino acid, and thus more than one DNA sequence can specify the same protein. For example, the protein fragment methionine-isoleucine-phenelalanine-aspartic acid-glycine is
coded by ATGATCTTTGACGGG and also by ATGATTTTTGATGGT.

Table 2.1 The genetic code.
TTT phenylalanine	TCT serine	TAT tyrosine	TGT cysteine
TTC phenylalanine	TCC serine	TAC tyrosine	TGC cysteine
TTA leucine	TCA serine	TAA stop	TGA stop
TTG leucine	TCG serine	TAG stop	TGG tryptophan
CTT leucine	CCT proline	CAT histidine	CGT arginine
CTC leucine	CCC proline	CAC histidine	CGC arginine
CTA leucine	CCA proline	CAA glutamine	CGA arginine
CTG leucine	CCG proline	CAG glutamine	CGG arginine
ATT isoleucine	ACT threonine	AAT asparagine	AGT serine
ATC isoleucine	ACC threonine	AAC asparagine	AGC serine
ATA isoleucine	ACA threonine	AAA lysine	AGA arginine
ATG methionine	ACG threonine	AAG lysine	AGG arginine
GTT valine	GCT alanine	GAT aspartic acid	GGT glycine
GTC valine	GCC alanine	GAC aspartic acid	GGC glycine
GTA valine	GCA alanine	GAA glutamic acid	GGA glycine
GTG valine	GCG alanine	GAG glutamic acid	GGG glycine

Now suppose we have a portion of DNA and we wish to find out which proteins it encodes. Since we don't know whether or not we have the beginning of the DNA sequence, and since
we very likely have a piece from somewhere in the middle, we don't know where to start reading. Which base pair is the first base pair? Which end do we start reading from? 
Does the fragment begin correctly at a codon boundary, or does it begin with the last one or two units of a disected codon? As you may imagine, it is important to choose where 
to start our translation and where to stop (we already know where to stop because of the "stop codes", TAA, TAG and TGA).

Sequencing the genome is a good example of the enormous impact of computer science in bioinformatics. The human genome would still be a mystery without: computer algorithms for 
searching and sorting; sophisticated storage and retrieval strategies; information visualization tools; and clusters of high-performance computing machines. The publication of 
the first draft of the human genome in 2001 was a pivotal moment in biology. For example, we previously estimated that the human genome contained approximately 100,000 genes;
this number was revised down to 20,000 - 25,000. Additionally, interspersed between and even within some genes is a great deal of DNA which does not seem to specify any protein.
Scientists are still learning about its purpose.
