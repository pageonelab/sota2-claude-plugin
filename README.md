# SOTA2

Find AI companies for a business workflow, build a shortlist, and check the evidence for each product. SOTA2 links to its published assessments and available sources for capabilities, integrations, customer use cases, reported compliance, and public product updates.

## Use SOTA2 in Claude

Add the plugin and enable the SOTA2 connector. The plugin uses the existing public SOTA2 connector at `https://www.sota2.com/mcp`. Claude can reuse your connection if you already have it. The connector provides read-only access to public records without a SOTA2 account or API key. [SOTA2 connector](https://claude.ai/directory/sota2-ai-solution-rankings)

- Find AI companies that answer incoming calls and book service visits for a contractor. Compare which products cover both steps and show the evidence and gaps.
- Find AI tools for replying to customer emails and website chats. Compare products and integrations, and cite the sources for each claim.
- Check Sei AI’s products, integrations, customer evidence, and reported SOC 2 status. Show the sources and flag missing details.

Rankings apply within a specific task and industry. Use the sources and limitations to check whether each candidate meets your requirements. The skill treats undisclosed facts as unknown and attributes compliance claims to their sources.

## Data handling and support

The bundle contains Markdown instructions and JSON configuration. Claude sends search terms and record identifiers to SOTA2 to retrieve relevant public data. The skill can also direct Claude to consult public vendor sources for evidence. Use public business requirements and omit confidential documents, credentials, and sensitive personal details. SOTA2 retains limited operational tool-call diagnostics for 30 days. Infrastructure logs and support correspondence follow the retention described in the privacy policy. [Privacy](https://www.sota2.com/mcp-privacy) · [Terms](https://www.sota2.com/mcp-terms) · [Setup and support](https://www.sota2.com/with-ai)

The MIT license covers the plugin instructions and configuration. The hosted SOTA2 service follows its own terms.
