---
layout: post
title: The van't Hoff equation and single molecule kinetics
category: [blog]
---

Jacobus Henricus van’t Hoff spent his career studying the velocity of chemical reactions. He did this in the second half of the 19th century,  a time when applying mathematical methods to study chemical systems was considered highly novel, atomic theory was still mere speculation, and no one had yet applied thermodynamics to chemical systems. In his quest to understand the factors that influenced reaction rates he encountered reactions whose rates differed from his theoretical predictions. One of these reactions was the apparently trimolecular reaction between hydrogen peroxide and hydrogen iodide

H2O2 + 2 HI → 2 H2O + I2.

While it was clear from the stoichiometry, or the relative proportions of the two reactants, that this equation described the overall reaction, the reaction itself appeared to follow the kinetics of a second order reaction. Van’t Hoff proposed that the formation of iodine must not occur in a single trimolecular step, but instead in two sequential bimolecular steps

H2O2 + HI → HIO + H2O,

HIO +  HI → H2O + I2

This explanation was revolutionary. For the first time in the history of chemistry had someone deduced the composition of a reaction by starting from the study of its kinetics. Van’t Hoff suggested, in the language of collision theory, that truly trimolecular reactions are rare simply because collisions between three particles in solution are statistically exceedingly rare. His work popularized the very idea of molecularity, and the notion that chemical reactions are to be understood as resulting from physical collisions between the right molecular species. The molecular complex that arises from such a collision is short-lived, and the complex is rapidly converted into one or more products. With the introduction of molecularity, chemists now had a symbolic language that described atoms and the structure of molecules instead of one that described fixed proportions of weights and volumes.
With the newly acquired ability to relate the composition of a reaction to its rate, the prospects were bright for chemists trying to understand inorganic and simple organic reactions. 

Fast forward another century, enter biomacromolecules, and things didn’t seem that rosy anymore. Macromolecules are behemoths. They contain several thousand-fold more atoms than the systems van’t Hoff was interested in, and while they react with other molecules in all the same ways as their smaller cousins, their non-covalent interactions are inarguably more complex. Molecular biology and biophysics were born in the 1940s as new methods evolved to studying these molecules, but a lot of the language used to describe kinetics was inherited from 19th century chemistry.  

As applied to biomolecules, the idea of a reaction becomes overloaded to the point of meaninglessness. Does the formation of a transient molecular complex constitute a reaction? What about a conformational change in a protein? The notion of stoichiometry falls apart: the formation of a product in enzyme-catalyzed reactions is no longer contingent on reactants being consumed. Valency loses its central significance, in both the sense of electronic valence and valence of interaction. For molecular complexes, the valence of interaction can be dynamically modulated. The glycolytic enzyme pyruvate kinase can either exist as a dimer or a tetramer depending on the stage of cell cycle. Even more dramatically the interaction valence need not indicate binding or “occupancy” at all. The 3’UTR of the HMGA2 mRNA possesses 7 binding sites for the microRNA let-7a. These seven sites don’t have to be simultaneously bound, and may never be completely occupied in vivo, in order for translation and mRNA stability to be modulated. Without broadly applicable definitions of valence or stoichiometry, we are forced to abandon the linear notion of a reaction and the binary of reactants and products in the case of all but the smallest nucleic acids and peptides and resort to the biologist’s jargon of regulation and a continuum of regulatory states. Doing so lifts the study of multitude of states between a denatured protein on the one hand and any given tertiary structure on the other, between a single, isolated protein subunit on the one and a multi-component holoenzyme on the other, between naked DNA strands on the one and chromatin on the other out of the purview of the chemist of the 19th century and into that of the molecular biophysicist.

Jargon notwithstanding, van’t Hoff’s work remains relevant in the study of these monster molecules. The van’t Hoff equation describes how the rate of a chemical reaction is determined by a single variable, temperature. But this isn’t restricted to any narrow definition of “reaction,” and the formalism is equally applicable to any process that varies exponentially with temperature and is subject to an activation threshold. Indeed, the entirety of chemical kinetics and rate laws are remarkably powerful first approximations despite being defined for chemical reactions in dilute solutions. So while the original notions of reactant and product are rendered incoherent in the complexity of macromolecular structural changes and association/dissociation processes, the kinetics of formation of any arbitrarily assigned molecular “state” can be studied using the van’t Hoff equation. This is particularly convenient because it allows single-molecule biophysicists to focus on defining and studying the kinetics of formation of molecular states, while using a framework that has origins in the highly intuition-driven collision and transition state theories. 

So van’t Hoff was right. Chemical reaction kinetics are important to study and can tell you pretty cool things. They can clarify why apparently trimolecular reactions are really just bimolecular ones. Or they can reveal how co-transcriptional translation in bacteria are regulated by riboswitches. The moral of the story is there’s more to the van’t Hoff equation than meets the eye. 

k = A e(-Ea/RT)

## **Related reading:**

Petr Ptáček, Tomáš Opravil and František Šoukal (July 18th 2018). A Brief Introduction to the History of Chemical Kinetics, Introducing the Effective Mass of Activated Complex and the Discussion on the Wave Function of this Instanton, Petr Ptáček, Tomáš Opravil and František Šoukal, IntechOpen, DOI: 10.5772/intechopen.78704. Available from: https://www.intechopen.com/books/introducing-the-effective-mass-of-activated-complex-and-the-discussion-on-the-wave-function-of-this-instanton/a-brief-introduction-to-the-history-of-chemical-kinetics

Keith Laidler (1985). Chemical kinetics and the origins of physical chemistry. https://link.springer.com/content/pdf/10.1007%2FBF00327865.pdf


