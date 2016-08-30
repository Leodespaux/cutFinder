cutFinder
by Leo d'Espaux <leodespaux@gmail.com>
with help from William Zhuang, Kai Li

Finds cut sites within a user-input sequence, then checks those candidates against
chromosome files discarding sequences found more than once. 
Output is a list of candidate 20mer gRNAs in your target sequence.

Details:
*For now only looks in the sense strand of input, but checks both sense and antisense on the genome.
*The program lists these sequences as it finds them. 
*Usually, we get a cut site every ~25nt.
*Note your target can be a sequence that's not originally in the genome.
