# Gravity RFC

Gravity RFC is a process for proposing and implementing changes in our ecosystem.

## Overview

This repository contains of the two parts:

- [Issues](https://github.com/gravity-ui/rfc/issues) (each issue is a RFC)
- [Project](https://github.com/orgs/gravity-ui/projects/1) for tracking all our RFCs

## What is the difference between RFC and project issues

We recommend creating a RFC in any of the following cases:

- Change that you're proposing affects multiple Gravity UI projects
- OR change that you're proposing is complex enough to require proper analysis and discussion (i.e. it's not simple bugfix
- OR you want to change something in Gravity ecosystem but don't know which project you proposal should be related to

## How can I create a RFC?

Just [create an issue](https://github.com/gravity-ui/rfc/issues/new) in this repository. We ask you to use template if possible: it helps you structure your proposal and helps us triage and process them faster.

## RFC lifecycle

### Stage I: triage

After creating RFC, it will be triaged by our team: we'll mark it with necessary labels and invite relevant people to the discussion – usually the maintainers of the projects affected by the proposal.

If we come to a conclusion that the proposed change is related only to a single project and not very complex in it's nature, we'll move it to the proper repository so it can be triaged and processed by that project's team.

### Stage II: discussion

Anybody can participate in the discussion and bring something to the table: we are always interested in various usecases and potential problems related to the proposal.

#### Who approves RFCs?

Usually we strive to achieve general agreement with all parties involved in the discussion, but maintainers of related projects have upper hand in these decisions. In controversial situations, special group consisting of experienced maintainers and team leaders will investigate the proposal and it’s possible solutions and will correct decision if necessary.

### Stage III: implementation

After discussion and approval, usually set of issues will be created to track required changes in related repositories. If proposal requires some assistance for implementation, we'll try to aid in finding volunteer who will be able to help with that.
