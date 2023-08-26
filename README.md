# NR PCI Calculator
online calculate: https://dustinchen26.github.io/PCI

## example
```
Ref: ETSI TS 138 211 chap 7.4.2.1 Physical-layer cell identities
PCI = 3 * N_ID1 + *N_ID2

【1】Input N_ID1, N_ID2, then Calculate PCI
N_ID1 range {0, 1, ..., 335}: 303
N_ID2 range {0, 1, 2}: 1
Calculate
PCI (N_cell_ID) = 910

【2】Input PCI, then calculate N_ID1,N_ID2
PCI (N_cell_ID): 910
Calculate
N_ID1 = 303, N_ID2 = 1
```