# root-wtf
A collection of "wtf" moment in CERN Root code

## TH1
1. Bins are indexed from 1 to n because numero 0 is undeflow bin and n+1 is the overflow bin
2. Function GetBin(x) returns fucking x
3. GetBinContent has 3 implementations and are ALL THE SAME
