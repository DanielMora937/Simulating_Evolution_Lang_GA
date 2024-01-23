  In this paper, we propose the use of a genetic algorithm to simulate the
evolution of language. Our idea for implementation is inspired by Simon
Kirby and his work on ‘iterated learning’, which Kirby defines as “the process whereby an individual learns their behaviour by exposure to another
individual’s behaviour, who themselves learnt it in the same way”. Importantly, we were interested in viewing this phenomenon at a high-level.
We define a semantic space that stores a fixed number of concepts, or
meanings, represented by integers. Individuals in our population have the
capacity of encoding these concepts into their own representation within
a signal space (short strings of letters from the alphabet). Additionally,
individuals are capable of decoding signal space representations back into
semantic space integers. Individuals who successfully communicate with
others across the signal space while referring to the same meaning space
concepts are rewarded with higher fitness.

  We successfully evolve populations of ’sensical’ individuals who learn
to share a representation for 100 unique meanings. Furthermore, we expand the meaning space to 1000 and propose solutions to reduce the number of duplicate signals (a problem that intensifies as the meaning space
grows). Later, we modify this approach by applying letter-frequencies
from the English alphabet as weights to our signals. In a separate experiment, we achieve homogeneous transmitter genes for ’non-sensical’
individuals and document a disconnect between the transmitter and receptor genes within this representation. Finally, we successfully evolve
populations of ’bilingual’ individuals that are capable of communicating
with two independently-evolved populations that use different languages.
