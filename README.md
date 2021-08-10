Here is code verifying the computations and theorems of the manuscript

                                  "Elliptic curves with non-abelian entanglements"

                                          By Nathan Jones and Ken McMurdy
                                          
To reproduce those computations, please do the following:

First, copy the contents of the file Step1-FunctionLibrary.txt into a running MAGMA prompt.  (Step 1 inputs the library of necessary functions.)

Next, copy the contents of Step2-ScriptsForMaximalEntanglementGroups.txt into the same MAGMA prompt in batches, as indicated in the comments in the file. (Note: some of these computations are long and will require hours of machine time.)  This script outputs the four genus zero maximal non-abelian entanglement groups presented in the main theorem of the manuscript.  In particular, it crucially verifies that there are no pre-twist groups possessing a twist cover that is a maximal non-abelian entanglement group of genus zero.

Finally, copy the contents of Step3-ScriptsForMaximalNonCommutatorThickSubgroupsOfG6.txt into the same MAGMA prompt in batches, as indicated in the comments in the file. This script produces the list of subgroups mentioned in the first theorem appearing in the section "An application to counting elliptic curves over Q with maximal Galois image modulo a prescribed obstruction", and also verifies properties mentioned in the section "An infinite family of D6-entanglements".
