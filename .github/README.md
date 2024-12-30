# Andromeda HackerBoard

[![Contributors](https://img.shields.io/github/contributors/andromedaprotocol/hackerboard)](https://github.com/andromedaprotocol/hackerboard/graphs/contributors)
[![Forks](https://img.shields.io/github/forks/andromedaprotocol/hackerboard)](https://github.com/andromedaprotocol/hackerboard/forks)
[![Stars](https://img.shields.io/github/stars/andromedaprotocol/hackerboard)](https://github.com/andromedaprotocol/hackerboard/stargazers)

Welcome to the Andromeda HackerBoard! This platform is designed to foster innovation within the Andromeda ecosystem. Here, you can contribute to tasks, earn rewards through bounties, propose new ADO ideas, bid on contracts, join our ambassador program, and participate in AI initiatives.

## Repository Structure

```
andromeda-hackerboard/
├── README.md                           # Main documentation file
├── .github/                            # GitHub specific configuration
│   ├── workflows/                      # GitHub Actions workflows
│   │   ├── leaderboard.yml             # Workflow for managing the leaderboard
│   │   └── issue-rewards.yml           # Workflow for handling issue rewards
│   └── ISSUE_TEMPLATE/                 # Templates for creating issues
│       ├── bug-report.md               # Template for bug reports
│       ├── feature-request.md          # Template for feature requests
│       ├── bounty-task.md              # Template for bounty tasks
│       ├── ado-feature-request.md      # Template for ADO feature requests
│       ├── ado-idea-proposal.md        # Template for ADO idea proposals
│       └── ado-submission.md           # Template for ADO submissions
├── categories/                         # Main categories of the HackerBoard
│   ├── hacker-board/                   # Tasks and leaderboard
│   │   ├── tasks/                      # Directory for individual task descriptions
│   │   │   └── example-task.md         # Example task file
│   │   └── leaderboard.md              # Leaderboard information
│   ├── bounties/                       # Information about bounties
│   │   ├── open-bounties.md            # List of open bounties
│   │   └── completed-bounties.md       # List of completed bounties
│   ├── ado-ideas/                      # ADO ideas section
│   │   ├── submission-guide.md         # Guide for submitting ADO ideas
│   │   └── submitted-ideas.md          # List of submitted ADO ideas
│   ├── contractor-bidding/             # Contractor bidding information
│   │   ├── how-to-bid.md               # Guide on how to bid on projects
│   │   ├── open-projects.md            # List of open projects for bidding
│   │   └── submitted-bids.md           # List of submitted bids
│   ├── ambassador-program/             # Ambassador program details
│   │   ├── program-guide.md            # Guide to the ambassador program
│   │   └── current-ambassadors.md      # List of current ambassadors
│   └── ai-initiatives/                 # AI-related initiatives
│       ├── current-projects.md         # Current AI projects
│       ├── initiative-guidelines.md    # Guidelines for AI initiatives
│       └── collaboration-opportunities.md # Opportunities for AI collaboration
```


## Categories

*   **[Hacker Board](./categories/hacker-board/)**: Participate in tasks and climb the leaderboard.
*   **[Bounties](./categories/bounties/)**: Earn rewards for solving challenges.
*   **[ADO Ideas](./categories/ado-ideas/)**: Propose and discuss innovative ADO concepts.
*   **[Contractor Bidding](./categories/contractor-bidding/)**: Bid on open development projects.
*   **[Ambassador Program](./categories/ambassador-program/)**: Learn how to become an Andromeda Protocol ambassador.
*   **[AI Initiatives](./categories/ai-initiatives/)**: Explore and contribute to AI-related projects.

## Getting Started

1. **Explore Opportunities**:
    *   Browse [open bounties](./categories/bounties/open-bounties.md).
    *   Review [AI collaboration opportunities](./categories/ai-initiatives/collaboration-opportunities.md).
    *   Check out the [Ambassador Program guide](./categories/ambassador-program/program-guide.md).

2. **Contribute**:
    *   Submit an [ADO idea](./categories/ado-ideas/submission-guide.md).
    *   Complete tasks listed in the [Hacker Board](./categories/hacker-board/).

## Contributing to the Andromeda Ecosystem

We welcome contributions! Please review our contribution guidelines before submitting pull requests (PRs) or issues.

### General Guidelines

#### Coding Standards

*   Maintain consistent indentation.
*   Use `camelCase` for variables and `PascalCase` for components.
*   Lint JavaScript code with ESLint.

#### Commit Message Format

```
[CATEGORY] Brief description of changes

Examples:
- [HackerBoard] Added lazy loading for images
- [Bounties] Updated completed bounties list
```

#### PR Review Process

*   All PRs require review and approval from at least one maintainer.
*   Use GitHub Discussions for questions and clarifications.

## Requesting, Developing, and Submitting ADOs

### Requesting a New ADO

1. Create a new issue using the [ADO Idea Request template](https://github.com/andromedaprotocol/ado-database-hackerboard/issues/new/choose).
2. Review a good example of a new ADO idea submission [here](https://github.com/andromedaprotocol/ado-database/issues/2).

**Note:** Initial submissions are reviewed by the Andromeda team, with a long-term goal of transitioning to a DAO-structured community review process.

### Requesting a New Feature for an Existing ADO

1. Create a new issue using the [ADO Feature template](https://github.com/andromedaprotocol/ado-database-hackerboard/issues/new/choose).
2. See a well-structured feature request example [here](https://github.com/andromedaprotocol/ado-database/issues/3).

**Important:** Ensure all sections of the template are completed for a valid submission.

### Submitting a Developed ADO

1. After your ADO idea is approved, develop the ADO in your own repository. We recommend starting with our [ADO Template](https://github.com/andromedaprotocol/andr-cw-template).
2. To add your ADO to the Andromeda library, create a PR in this repository.
3. Your PR should follow the [ADO Submission template](https://github.com/andromedaprotocol/ado-database-hackerboard/issues/new/choose). See a complete submission example [here](https://github.com/andromedaprotocol/ado-database/issues/4).

**Note:** Do not include the ADO codebase in the PR. Instead, provide a link to the repository where the codebase is hosted.

## Need Help?

*   Consult the documentation within each section.
*   Start a GitHub Discussion for specific questions.
*   Join our community channels for support and collaboration.

---
