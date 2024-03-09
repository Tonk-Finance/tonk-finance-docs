# Safety Score

### What is Safety Score?

In the context of Tonk Finance vaults, the Safety Score is a numerical representation designed to quantify the risk associated with investing in a specific vault. This score starts at a baseline of 100, with deductions applied for each risk factor identified in the vault's underlying assets, strategies, or the platforms they operate on. The purpose of the Safety Score is to provide investors with a clearer understanding of the potential risks before making investment decisions.

The deductions from the Safety Score are based on various criteria categorized into Asset Risks, Market Cap, Liquidity, and Platform Risks. Each category encompasses several subcategories with specific conditions that might affect the vault's risk profile. The final Safety Score is calculated by starting at 100 and subtracting points for each applicable risk, thereby offering a straightforward metric to gauge the relative safety or riskiness of an investment within the Tonk Finance ecosystem.

### Categories and Deductions

1. **Asset Risks**
   * **Impermanent Loss (IL)**
     * **Very Low or Zero Projected IL**: Ideal for single asset vaults or stablecoin pairs with minimal expected IL.
     * **Low Projected IL**: Applies to vaults with some risk of IL, particularly with common liquidity pairs.
     * **High Projected IL**: For vaults with significant IL risk, typically involving governance tokens or less correlated pairs.
2. **Market Cap (MCAP)**
   * **Large Market Cap**: Signifies a low-risk asset with high market cap and low volatility.
   * **Medium Market Cap**: Indicates a medium-risk asset with medium market cap and volatility.
   * **Small Market Cap**: Points to a high-risk asset with small market cap and high volatility.
   * **Micro Market Cap**: Represents an extremely volatile and risky asset with very small market cap.
3. **Liquidity**
   * **High Trade Liquidity**: Denotes assets with high liquidity, facilitating easier trades.
   * **Low Trade Liquidity**: Indicates assets with lower liquidity, potentially leading to higher slippage during trades.
4. **Platform Risks**
   * **Reputation**
     * **Established Platform**: For platforms with a known track record, implying lower risk.
     * **New Platform**: Applies to newer platforms with little track record, indicating higher risk.
   * **Security**
     * **No Audit**: For platforms that have not undergone any third-party audits, suggesting higher risk.
     * **Audit**: Indicates platforms that have been audited by reputable third parties, mitigating some risks.

### Utilizing the Safety Score

The Safety Score is a tool for investors to assess and compare the risk levels of different vaults within Tonk Finance. By quantifying risk in this manner, investors can make more informed decisions aligned with their risk tolerance and investment objectives. It's important for investors to consider not just the Safety Score but also to understand the specific risk attributes contributing to that score, as this can provide deeper insights into the nature of the risks involved.
