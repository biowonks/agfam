# Agfam

The Agfam database is a focused collection of signal transduction-specific protein families, each of which is represented by hidden Markov models (HMMs). Although the primary focus of Agfam is Chemotaxis signal transduction, it is also useful for one and two-component signal transduction studies.

## Usage

These HMM models are intended for use with the HMMER3 package. To search for matches using HMMER3, first "hmmpress" agfam.hmm.

## Release 2.0

This release includes all HMMs from version 1 and the following models. CheA and MCP classes are retrieved from [Kristen and Zhulin 2010] [1] and [Alexander and Zhulin 2007] [2] respectively.

* **chea-F1** F1 system-specific CheA
* **chea-F2** F2 system-specific CheA
* **chea-F3** F3 system-specific CheA
* **chea-F4** F4 system-specific CheA
* **chea-F5** F5 system-specific CheA
* **chea-F6** F6 system-specific CheA
* **chea-F7** F7 system-specific CheA
* **chea-F8** F8 system-specific CheA
* **chea-F9** F9 system-specific CheA
* **chea-F10** F10 system-specific CheA
* **chea-F11** F11 system-specific CheA
* **chea-F12** F12 system-specific CheA
* **chea-F13** F13 system-specific CheA
* **chea-F14** F14 system-specific CheA
* **chea-F15** F15 system-specific CheA
* **chea-F16** F16 system-specific CheA
* **chea-F17** F17 system-specific CheA
* **chea-ACF** ACF system-specific CheA
* **chea-Tfp** TFP system-specific CheA
* **chea-Uncat** Uncategorized CheA
* **MCP-24H** 24-heptad MCPsignal
* **MCP-28H** 28-heptad MCPsignal
* **MCP-34H** 34-heptad MCPsignal
* **MCP-36H** 36-heptad MCPsignal
* **MCP-38H** 38-heptad MCPsignal
* **MCP-40H** 40-heptad MCPsignal
* **MCP-42H** 42-heptad MCPsignal
* **MCP-44H** 44-heptad MCPsignal
* **MCP-48H** 48-heptad MCPsignal
* **MCP-52H** 52-heptad MCPsignal
* **MCP-58H** 58-heptad MCPsignal
* **MCP-64H** 64-heptad MCPsignal


## Release 1.0

* **4HB_MCP** The Methyl-accepting protein version of Four helix bundle
* **HK_CA** Histidine kinase type I general class
 * **HK_CA:1** Histidine kinase type I evolutionary distinct group
 * **HK_CA:2** Histidine kinase type I evolutionary distinct group
 * **HK_CA:3** Histidine kinase type I evolutionary distinct group
 * **HK_CA:5** Histidine kinase type I evolutionary distinct group
 * **HK_CA:6** Histidine kinase type I evolutionary distinct group
 * **HK_CA:7** Histidine kinase type I evolutionary distinct group
 * **HK_CA:8** Histidine kinase type I evolutionary distinct group
 * **HK_CA:9** Histidine kinase type I evolutionary distinct group
 * **HK_CA:10** Histidine kinase type I evolutionary distinct group
 * **HK_CA:11** Histidine kinase type I evolutionary distinct group
 * **HK_CA:12** Histidine kinase type I evolutionary distinct group
 * **HK_CA:13** Histidine kinase type I evolutionary distinct group
 * **HK_CA:14** Histidine kinase type I evolutionary distinct group
 * **HK_CA:15** Histidine kinase type I evolutionary distinct group
 * **HK_CA:16** Histidine kinase type I evolutionary distinct group
 * **HK_CA:17** Histidine kinase type I evolutionary distinct group
 * **HK_CA:18** Histidine kinase type I evolutionary distinct group
 * **HK_CA:19** Histidine kinase type I evolutionary distinct group
 * **HK_CA:20** Histidine kinase type I evolutionary distinct group
 * **HK_CA:21** Histidine kinase type I evolutionary distinct group
 * **HK_CA:22** Histidine kinase type I evolutionary distinct group
 * **HK_CA:23** Histidine kinase type I evolutionary distinct group
* **HK_CA:Che** Histidine kinase type II - CheA
* **RR** Response regulator


## References
* Alexander, Roger P., and Igor B. Zhulin. "Evolutionary genomics reveals conserved structural determinants of signaling and adaptation in microbial chemoreceptors." Proceedings of the National Academy of Sciences 104.8 (2007): 2885-2890.
* Wuichet, Kristin, and Igor B. Zhulin. "Origins and diversification of a complex signal transduction system in prokaryotes." Science Signaling 3.128 (2010): ra50.

[1]: http://www.ncbi.nlm.nih.gov/pubmed/20587806 "Kristen and Zhulin"
[2]: http://www.pnas.org/content/104/8/2885.long "Alexander and Zhulin"