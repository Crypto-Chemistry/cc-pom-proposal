# Kujira Community Funding proposal for Crypto Chemistry Price Oracle Monitor

## Introduction
With the introduction of Price Oracles in v0.5.0 and proposal 27, Kujira validators now need to monitor their price oracles to prevent slashing. A common tool that many validators run is Tenderduty by block pane, which is a major source of inspiration for the CC-POM. The CC team takes a Linux like mindset of "Each program does one thing and does it well".

We believe that a tool dedicated to monitoring price oracle uptime is necessary for validators in the Kujira ecosystem. As such, we are proposing a new tool Crypto Chemistry's Price Oracle Monitor (CC-POM), dedicated to the monitoring and alerting of price oracles.

## What is CC-POM?
CC-POM is a monitoring and alerting tool that provides validators with status updates and timely alerts of critical conditions of their price oracles. It will integrate with Discord and Pagerduty to start. 

## Roadmap
In the first release CC-POM will have both Discord and Pagerduty alerting capabilities. 

After an initial release and feedback from validators is received, additional features will be considered for implementation, including:
- Modifiable alert levels and frequency
    - eg. 100 misses triggers a Discord alert while 500 triggers a PagerDuty incident
- Fallback LCD endpoints
- Customizable alert formatting
- Slack, OpsGenie, and Telegram integrations

![CC-POM Discord Alert](img/discord_alert.png)

## Core Values
- Always open-source: We believe that any community funded development should be entirely transparent and open-source, with permissive licenses for anyone to expand on.
- Continued Support: We will maintain this tool as long as we are active in the Kujira ecosystem.
- Reliability: As an alerting and monitoring tool, reliability is critical to the success and useful of the tool.

## Our Proposal
$5,000 for the initial development, testing, and support of CC-POM.

The breakdown of the estimated hours spent as part of this proposal is below.
- Initial Development: 20 hours
- Additional Feature Development: 60 hours
- Testing and Documentation: 20 hours

- Average Hourly Rate: $50 USD

## Fund Allocation
If the proposal passes, the funds will be handled as follows:

- 50% of the $KUJI will be sold to alxUSDC via FIN
- 25% of the $KUJI will be staked to the Crypto Chemistry validator
- 25% of the $KUJI will be staked with other validators that we feel provide useful support, documentation, and tools to validators within the Kujira ecosystem.
    NOTE: How do we want to decide this. Will we have a framework/set of guidelines?

## About Crypto Chemistry
Insert Note about us here

### Technical Credentials
The development of this tool will be done primarily by Relyte, Crypto Chemistry's node operator. Relyte has experience working as both a DevOps Engineer and Securty Engineer within the SaaS and Defense industries. He has shown a willingnes and capability to provide tools to the community. Recently he has released another monitoring tool that will help Kujira validators receive alerts regardnig their price oracle wallet balances in the case that they are critically low: https://github.com/Crypto-Chemistry/walletmon


Crypto Chemistry Github: https://github.com/Crypto-Chemistry/

Relyte Github: https://github.com/Relyte
