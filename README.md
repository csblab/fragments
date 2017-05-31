# Small Libraries of Protein Fragments Accurately Model Native Protein Structures
**Authors:** Rachel Kolodny, Patrice Koehl, Leonidas Guibas and Michael Levitt

Supplementary data to
> [Kolodny R, Koehl P, Guibas L, Levitt M., *Small libraries of protein fragments model native protein structures accurately.* **J Mol Biol.** 2002 Oct 18;323(2):297-307](https://www.ncbi.nlm.nih.gov/pubmed/12381322)


| Fragment Length | Library Size | Complexity [States/Residue]<sup>A</sup> | Average<sup>B</sup> Local cRMSD (&#8491;) | Average<sup>B</sup> Global cRMSD (&#8491;) | Data File | Angle Data File |
|:---------------:|:------------:|:---------------------------------------:|:-----------------------------------------:|:------------------------------------------:| --------- | --------------- |
| 4 | 4   | 4     | 0.39 | 2.23 | [lib_4_z_4.txt](data/lib_4_z_4.txt)     | |
| 4 | 6   | 6     | 0.35 | 1.64 | [lib_6_z_4.txt](data/lib_6_z_4.txt)     | |
| 4 | 7   | 7     | 0.33 | 1.48 | [lib_7_z_4.txt](data/lib_7_z_4.txt)     | |
| 4 | 8   | 8     | 0.32 | 1.39 | [lib_8_z_4.txt](data/lib_8_z_4.txt)     | |
| 4 | 10  | 10    | 0.30 | 1.12 | [lib_10_z_4.txt](data/lib_10_z_4.txt)   | |
| 4 | 12  | 12    | 0.28 | 1.01 | [lib_12_z_4.txt](data/lib_12_z_4.txt)   | |
| 4 | 14  | 14    | 0.26 | 0.92 | [lib_14_z_4.txt](data/lib_14_z_4.txt)   | |
| 5 | 10  | 3.16  | 0.57 | 2.57 | [lib_10_z_5.txt](data/lib_10_z_5.txt)   | |
| 5 | 20  | 4.47  | 0.47 | 1.85 | [lib_20_z_5.txt](data/lib_20_z_5.txt)   | [lib_20_z_5.ang](data/lib_20_z_5.ang)   |
| 5 | 30  | 5.48  | 0.43 | 1.59 | [lib_30_z_5.txt](data/lib_30_z_5.txt)   | |
| 5 | 40  | 6.32  | 0.40 | 1.41 | [lib_40_z_5.txt](data/lib_40_z_5.txt)   | [lib_40_z_5.ang](data/lib_40_z_5.ang)   |
| 5 | 50  | 7.07  | 0.39 | 1.28 | [lib_50_z_5.txt](data/lib_50_z_5.txt)   | |
| 5 | 60  | 7.75  | 0.37 | 1.20 | [lib_60_z_5.txt](data/lib_60_z_5.txt)   | |
| 5 | 80  | 8.94  | 0.35 | 1.06 | [lib_80_z_5.txt](data/lib_80_z_5.txt)   | [lib_80_z_5.ang](data/lib_80_z_5.ang)   |
| 5 | 100 | 10    | 0.34 | 0.99 | [lib_100_z_5.txt](data/lib_100_z_5.txt) | [lib_100_z_5.ang](data/lib_100_z_5.ang) |
| 5 | 150 | 12.25 | 0.31 | 0.86 | [lib_150_z_5.txt](data/lib_150_z_5.txt) | |
| 5 | 225 | 15    | 0.29 | 0.76 | [lib_225_z_5.txt](data/lib_225_z_5.txt) | |
| 6 | 40  | 3.42  | 0.65 | 2.30 | [lib_40_z_6.txt](data/lib_40_z_6.txt)   | |
| 6 | 60  | 3.91  | 0.59 | 2.02 | [lib_60_z_6.txt](data/lib_60_z_6.txt)   | |
| 6 | 70  | 4.12  | 0.58 | 1.92 | [lib_70_z_6.txt](data/lib_70_z_6.txt)   | |
| 6 | 80  | 4.31  | 0.56 | 1.87 | [lib_80_z_6.txt](data/lib_80_z_6.txt)   | |
| 6 | 100 | 4.64  | 0.54 | 1.72 | [lib_100_z_6.txt](data/lib_100_z_6.txt) | |
| 6 | 200 | 5.85  | 0.48 | 1.41 | [lib_200_z_6.txt](data/lib_200_z_6.txt) | |
| 6 | 300 | 6.69  | 0.45 | 1.26 | [lib_300_z_6.txt](data/lib_300_z_6.txt) | |
| 7 | 50  | 2.66  | 0.85 | 2.89 | [lib_50_z_7.txt](data/lib_50_z_7.txt)   | |
| 7 | 100 | 3.16  | 0.76 | 2.41 | [lib_100_z_7.txt](data/lib_100_z_7.txt) | |
| 7 | 150 | 3.50  | 0.72 | 2.16 | [lib_150_z_7.txt](data/lib_150_z_7.txt) | |
| 7 | 200 | 3.76  | 0.68 | 2.04 | [lib_200_z_7.txt](data/lib_200_z_7.txt) | |
| 7 | 250 | 3.98  | 0.66 | 1.91 | [lib_250_z_7.txt](data/lib_250_z_7.txt) | |

<sup>A</sup> The complexity, or the average number of states per residue, of a fragments library is *|L|<sup>1/(f-3)</sup>* where *|L|* is the library size and *f* is the length of the fragments in the library.

<sup>B</sup> The average is taken over the approximations of the test set proteins.
