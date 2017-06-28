---
title: 1st Underhanded Solidity Coding Contest
---
# 1st Underhanded Solidity Coding Contest

The Underhanded Solidity Coding Contest is a contest to write harmless looking Solidity code that conceals a hidden purpose. A good USCC entry looks like a clearly and straightforwardly written smart contract, but contains well disguised vulnerabilities that ensure its actual operation differs significantly from what the reader would expect. The USCC is inspired by the similar [Underhanded C Coding Contest](http://www.underhanded-c.org/).

# Theme

The theme for the first contest is "ICOs".

You are the lead developer of a groundbreaking new product, Merdetoken (MDT). Investor demand has been heavy, and soon you plan to announce an initial distribution of coins to the eager public.

Unfortunately, investors are getting more demanding, asking projects for assurances such as payout contracts that release funds over time and require the approval of investors, and smaller caps with better pricing mechanisms. All of this significantly impacts your master plan to take in a hundred million dollars in token sales and then retire to a nice island, saddling your intern with the task of actually writing something - eventually.

But you will not be deterred. Being well versed in solidity and sneakiness both, you're confident you can come up with a tokensale contract that will pass the most careful audit, but still allow you to quickly retire to your tropical paradise with your ill-gotten gains.

# Brief

Entrants must write a contract that in some way relates to ICOs - such as an ERC20 token contract, a contract for selling tokens, or one that conditionally pays funds out to project creators - with some critical vulnerability that can be exploited to enrich the project creators. Examples might include:

 - A crowdsale contract that allows certain participants to get more tokens than they ought to.
 - A disbursement contract that lets the project creators withdraw all the funds at once.
 - A token contract that allows stealthy creation of additional tokens.

# Rules and Scoring

 - Submissions that are shorter and cleaner will be scored higher than those that are lengthy and complicated. It's easy to hide a vulnerability in complex and poorly written code; far harder to hide it in clean and simple code.
 - Bugs are worth more points if, once discovered, they can be plausibly dismissed as coder error.
 - An error that arises from users misinterpreting code (such as confusing scoping, misleading variable names, etc) is just as valuable as one that exploits the language or the EVM itself. The goal is simply to pass inspection by a human.
 - Remember to consider plausibility. Code that drops down to inline assembly without any clear reason why will look immediately suspicious, no matter how cleverly written the assembly-level flaw is.

# Submission guidelines and deadline

Email submissions to underhanded-submissions@solidity.cc. Entries should consist of a ZIP file containing a README describing your submission and how it works (spoilers included), and one or more Solidity files. Please do not include identifying information in the ZIP file; entries will be sent to judges anonymously.

 - July 1, 2017: Submissions open
 - July 31, 2017: Submissions close
 - September 1, 2017 or before: Winners announced

# Judges

Judging this first contest are:

 - Christian Reitwiessner, Solidity lead developer
 - Raine Revere
 - Reto Trinkler, Melonport CTO
 - Matthew Di Ferrente, Security engineer & code auditor

Judges are presented with anonymised submissions, and provide scores and commentary. The scores across all judges will be aggregated to determine the final score of each entry.

# Prizes

The Ethereum Foundation has generously contributed a first prize of a ticket to DevCon 3 in Cancun, and a speaking slot for the winner to present their entry.

The judges may, at their discretion, nominate any number of additional 'honorable mentions' for examination and approbation on the website.

Anyone wishing to offer additional prizes, or with questions about the contest, should email underhanded@solidity.cc.