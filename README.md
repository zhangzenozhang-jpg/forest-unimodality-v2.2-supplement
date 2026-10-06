# Unimodality of Forest Independence Polynomials

Supplementary materials for manuscript version 2.2 by **Wei Li, Kevin Vallier, and Tong Zhang**.

The files preserve the computational evidence accompanying the manuscript. Section 7 of the paper describes the finite checks and their role in the proof; Section 8 describes the Lean formalization. The manuscript is provisional, and its account of human and AI contributions appears in Section 9.

`supplementary_data.zip` contains the `bundle/` directory: proof data, certificates, producer programs, and independent checkers and replay results for the earlier computational families. It also retains historical material, including the earlier F7 coverings above mean 50, which the current proof does not use. The archive contains programs as well as data.

`supplementary_code.zip` contains the `supplementary_code/` directory: the F9/F10 fiber-inequality checkers, their data and recorded outputs, and the data and checker for counting the F6 boxes used in the proof. `twin_v2.2_data.txt` records the parameters and locations of the supplementary data for version 2.2.

To inspect or reproduce a computation, download the two archives and the text file together, and extract both archives into the same working directory. Preserve the complete `bundle/` and `supplementary_code/` directory trees, file names, and empty files; individual scripts refer to these paths. Read `bundle/README.txt` for the family-to-directory map and `supplementary_code/README.txt` for the F9/F10 prerequisites, run order, and mapping from output to statements. The latter archive also includes `ROUNDING_CORRECTIONS_20261006.txt`. Historical version labels inside the preserved archives describe their original provenance; the current proof's use of those materials is specified in Section 7 of the manuscript.

`SHA256SUMS.txt` in this release checks the three downloadable assets. After extraction, `bundle/MANIFEST.sha256` and `supplementary_code/SHA256SUMS.txt` check their respective directory contents. Resolve each internal manifest's paths relative to the directory containing that manifest. The files named `SHA256SUMS_v1.txt` and `SHA256SUMS_v4.txt` are historical records, not manifests of the current code package.

The public Lean development is fixed at commit [`d174e4b6f8963abb349995606783200879aae74e`](https://github.com/selfreferencing/erdos993-forest-unimodality-lean/tree/d174e4b6f8963abb349995606783200879aae74e). Its README and build files describe the Lean workflow. The final theorem is in `Erdos993Lean/Analytic/V22/Final.lean`, and the axiom-audit source is `Audit/AxiomsV22.lean`.
