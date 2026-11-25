# MineBitcoinMobile

An Android Bitcoin mining client built with .NET MAUI.

> **Project ownership and releases:** This repository is owned and controlled exclusively by its founder. Only the owner decides what is merged, what is published, and when an official version is released. AI tools do not have repository ownership or release authority.

## About the project

MineBitcoinMobile is a personal project created to explore and build a configurable Bitcoin mining client for Android.

The idea came from wanting more control over the mining connection instead of being locked to a single pool or a fixed configuration. The goal is to let the user configure the Bitcoin mining connection with their own details, including:

- Mining pool
- Server and port
- Bitcoin wallet address
- Worker name
- Password

The project is focused on Bitcoin (BTC). Its guiding principles are transparency, user control, and reporting actual mining results—not fabricated hashrate, shares, or rewards.

## Download

Official Android releases will be published by the repository owner on the **[Releases page](../../releases)**.

Always download builds from an official release published by the owner. Do not treat test builds or unofficial copies as official versions.

## Project history

I started MineBitcoinMobile because I wanted to create a Bitcoin mining app for Android that gives the user control over the pool connection and mining settings.

I wanted to build the project myself, understand how the Stratum connection and mining process work, and make the app report real results instead of displaying simulated performance. I also wanted the project and its development decisions to remain under my control.

The project is developed step by step. Existing functionality should be preserved, changes should be tested, and features should not claim results that have not actually been measured.

This history will be updated as the project evolves.

## Project governance

- **Founder and sole project owner:** the repository owner.
- **Official releases:** created and published only by the owner.
- **Version decisions:** made only by the owner.
- **External contributions:** do not become official until reviewed and accepted by the owner.
- **AI assistance:** AI tools may help with research, explanations, code suggestions, and debugging, but they do not own the project or control its repository.

## Source code and permissions

This repository is public so that visitors can inspect the source code and follow the project's development. **Public visibility does not mean the project is open source or that reuse is authorized.**

Unless the owner gives prior written permission, visitors are not authorized to copy, redistribute, modify, adapt, create derivative works from, or publish builds based on this project's code. The project is distributed under the **All Rights Reserved** terms in [LICENSE](LICENSE).

GitHub may still allow users to view, clone, or fork public repository content as a platform feature. These technical capabilities do not grant copyright permission to reuse or redistribute the code. The owner alone controls this original repository and its official releases. Unofficial copies, forks, and builds are not official MineBitcoinMobile releases.

## Development assistance

The following AI assistants have been used as development tools:

- **ChatGPT (OpenAI)** — assistance with technical reasoning, code review, debugging, and documentation.
- **Claude (Anthropic)** — assistance with development and technical review.

They are credited for AI-assisted work, not as legal owners, human maintainers, or release managers. All project direction and final decisions remain with the founder.

## Technical direction

- Platform: Android
- Framework: .NET MAUI
- Language: C#
- Current scope: Bitcoin (BTC)
- Mining connection: configurable pool connection using Stratum

## Important notice

Mining performance, pool acceptance, rewards, and profitability depend on the device, pool, network, and mining difficulty. Mobile mining can generate heat and consume battery power. Use the app responsibly and monitor the device.

MineBitcoinMobile is provided as a software project. Users are responsible for their own wallet addresses, pool settings, device use, and applicable obligations.

## License

All rights reserved. See [LICENSE](LICENSE). No open-source license is granted for this project. Third-party dependencies remain subject to their respective licenses.
