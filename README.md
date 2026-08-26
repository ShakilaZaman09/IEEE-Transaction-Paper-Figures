# Data and Source Reports for Cross-Chain Atomic Swap Figures

Supporting material for the figures in *A State-Machine Protocol for Atomic
Cross-Chain Swaps between Ethereum and Bitcoin*.

Each panel of the paper's introductory figure is backed by two documents: the
figure itself, and a report giving the underlying data table, the sources for
every number, and the method used to combine them.

| Panel | Figure | Data and sources |
|-------|--------|------------------|
| (a) Global blockchain market, 2020–2030 | [graph_a](graph_a_blockchain_market.pdf) | [report_a](report_a_blockchain_market.pdf) |
| (b) Top-15 cryptocurrencies by market capitalisation | [graph_b](graph_b_crypto_market_cap.pdf) | [report_b](report_b_crypto_market_cap.pdf) |
| (c) Cross-chain bridge hack losses, 2020–2025 | [graph_c](graph_c_bridge_hack_losses.pdf) | [report_c](report_c_bridge_hack_losses.pdf) |
| (d) Blockchain heterogeneity across nine Layer-1 chains | [graph_d](graph_d_blockchain_heterogeneity.pdf) | [report_d](report_d_blockchain_heterogeneity.pdf) |
| (e) Cross-chain research output by category, 2018–2025 | [graph_e](graph_e_research_trends.pdf) | [report_e](report_e_research_trends.pdf) |

Each report lists its sources with clickable links, so every figure in the paper
can be traced back to the published data it came from.

## A note on the bridge-loss trend in panel (c)

Annual losses peak at $1.88B in 2022 and decline thereafter. That decline tracks
falling bridge liquidity and the absence of a single catastrophic incident, not a
change in the underlying trust model: most production bridges still settle on
attestations from an external committee, and a single committee compromise still
drains the contract.

## Fonts

All PDFs embed TrueType fonts (`pdf.fonttype = 42`). Matplotlib's default Type 3
fonts are rejected by IEEE PDF eXpress and fail to render in browser-based PDF
viewers, including GitHub's.
