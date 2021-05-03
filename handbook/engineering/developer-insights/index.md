# Developer Insights org

## Mission

Bring Sourcegraph’s insights into your codebase ([Code Intel](../code-intelligence/index.md), [Code Insights](code-insights/index.md), and [API docs](api-docs/index.md)), [extended](extensibility/index.md) with other dev tools’ information, to where developers interact with code ([sourcegraph.com](https://sourcegraph.com/search), code hosts, and IDEs)

## Teams
1. [Frontend platform](frontend-platform/index.md): the maintenance and expansion of the Sourcegraph web application. We also define and maintain the standards and tooling for how we do web development at Sourcegraph.
2. [Extensibility](extensibility/index.md): our code host and third-party integrations (including our browser extension) and our [Sourcegraph extensions](https://docs.sourcegraph.com/extensions).
3. [Code insights](code-insights/index.md): empowering data-driven decisions in engineering organizations.
4. [API docs](api-docs/index.md): making Sourcegraph the standard developer reference for public code.

## Members

<!-- Due to the markdown renderer that we use, the indentation here is sensitive. If you want to change the indentation, check that it renders correctly locally with `make serve` -->
- [Jean du Plessis](../../../company/team/index.md#jean-du-plessis-he-him) ([Director of Engineering](../roles.md#director-of-engineering))
     - [Frontend platform](../developer-insights/frontend-platform/index.md)
         - [Alicja Suska](../../../company/team/index.md#alicja-suska-she-her) ([Product Designer](../../product/roles/index.md#product-designer))
         - [Patrick Dubroy](../../../company/team/index.md#tom-ross-he-him) ([Engineering Manager](../roles.md#engineering-manager))
              - [Tom Ross](../../../company/team/index.md#tom-ross-he-him)
              - [Felipe Janer](../../../company/team/index.md#felipe-janer-he-him)
              - [Valery Bugakov](../../../company/team/index.md#valery-bugakov-he-him) (moves to Code Insights in FQ2)
     - [Extensibility](index.md)
         - [Joel Kwartler](../../../company/team/index.md#joel-kwartler-he-him) ([Product Manager](../../product/roles/index.md#product-manager)) is the acting PM for this team until we can hire a dedicated PM for it. Once that happens, Joel will focus entirely on code insights.
         - [Alicja Suska](../../../company/team/index.md#alicja-suska-she-her) ([Product Designer](../../product/roles/index.md#product-designer))
         - [Jean du Plessis](../../../company/team/index.md#jean-du-plessis-he-him) is the acting [Engineering Manager](../roles.md#engineering-manager) for this team
              - [TJ Kandala](../../../company/team/index.md#tharuntej-kandala-he-him)
              - [Murat Sutunc](../../../company/team/index.md#murat-sutunc-he-him)
     - [Code Insights](../developer-insights/code-insights/index.md)
         - [Joel Kwartler](../../../company/team/index.md#joel-kwartler-he-him) ([Product Manager](../../product/roles/index.md#product-manager))
         - [Alicja Suska](../../../company/team/index.md#alicja-suska-she-her) ([Product Designer](../../product/roles/index.md#product-designer))
         - [Felix Becker](../../../company/team/index.md#felix-becker) ([Engineering Manager](../roles.md#engineering-manager))
              - [Vova Kulikov](../../../company/team/index.md#vova-kulikov-he-him)
              - C.C. starts May 17
              - [Valery Bugakov](../../../company/team/index.md#valery-bugakov-he-him) (joins from Frontend Platform in FQ2)
     - [API docs](../developer-insights/api-docs/index.md)
         - [Jean du Plessis](../../../company/team/index.md#jean-du-plessis-he-him) is the acting [Engineering Manager](../roles.md#engineering-manager) for this workstream
              - [Stephen Gutekanst](../../../company/team/index.md#stephen-gutekanst)

## Strategy for FY22

_Updated 2020-03-08_

The strategy is currently a work in progress and can be viewed here: [Developer Insights FY22 Strategy](https://docs.google.com/document/d/18GS2Gr7SP2ICuJaOpofxiwuxU3pKBfp8eXREFLDcM30/edit)
_(Only accessible to Sourcegraph teammates until finalized.)_

## Processes

Each team is afforded the freedom to operate as best they see fit to achieve their goals.
The following processes apply to all teams in Developer Insights.

### Communication

We recognize that frequent, open communication is key to the success of every team, especially in an all-remote environment.
We default to asynchronous communication in Slack and GitHub issues over other mediums (video calls, emails, etc) as we are respectful of our teammates' time.

In addition to team specific channels, we communicate in the following org-wide channels in Slack:

[**#developer-insights-org**](https://sourcegraph.slack.com/archives/C01EM5J1NF8): Our daily standups (facilited through Geekbot) go into this channel as well as all non-work related commmunication. Random conversations, banter, jokes etc. are all welcome here.

[**#developer-insights-org-onboarding**](https://sourcegraph.slack.com/archives/C01K7TKKR09): This channel is dedicated to questions or thoughts that new teammates have while they onboard. It's a safe space to simply think out load and the goal is to identify things that we can improve and things we should make more clear in the handbook.

[**#developer-insights-org-leadership**](https://sourcegraph.slack.com/archives/C01P1TVDJR4): This channel is for the Engineering Managers, Product Managers and Product Designers to discuss higher-level matters impacting the whole org.

### Events

We have a [shared events calendar](https://calendar.google.com/calendar/u/0?cid=Y181Z2Zoa2Y5b2g1ajM4NDVwaHVtdHVkZTg0Y0Bncm91cC5jYWxlbmRhci5nb29nbGUuY29t) where the teams can add all their team specific events so everyone can easily see the events.

### Daily Slack updates

Collaborating across timezones requires regular communication to keep each other updated on our progress, and coordinate work handoff if needed. We also use this opportunity to build camaraderie between team members by sharing some non-work related aspects of our lives with each other.

We use [Geekbot](https://geekbot.com/) to facilitate all this and these updates are purely for coordination within the team (as opposed to for external stakeholders). At the start of each working day, Geekbot will ask each teammate a set of questions and the responses will be posted in the [**#developer-insights-org**] Slack channel.

All teammates are expected to be part of this channel, and should read the updates, to learn what your teammates have been working on, and check if they need your help.

### Status updates

Each Engineering Manager of the teams in the org is responsible for sending out a [status update](../engineering-management.md#status-updates) by the Monday following their team's retrospective.

### Health reports

The engineering managers are responsible for compiling a weekly health report ([see example](https://docs.google.com/spreadsheets/d/1PnRPydNYLF2Als3KpVuIYO8dXeqckp_sbowVkvkdkeE/edit)) for their team.

The report is a confidential update between the Director and the Engineering Managers and serves the following purpose:
1. Updates the director on how things are going at a high-level in the team
1. Identifies areas of concern that could lead to proactive intervention to mitigate concerns

The report is not used for judging the performance of the team or the manager, and its intention is solely to inform and trigger dialogue. Managers are not expected to provide exhaustive notes, rather high-level summaries are preferred.