One Does Simply (ODS)

"One does not simply do complex things, but One Does Simply do simple things."

What is ODS?

One Does Simply (ODS) is an open-source project dedicated to a simple truth: simple applications can and should be defined simply. ODS provides a clear, concise specification for defining simple, data-driven applications using a JSON file.
This specification can then be rendered by any compatible Framework, giving citizen developers the power to create useful applications without getting bogged down by the complexities of UI/UX design, proprietary ecosystems, or vendor lock-in.

The ODS Philosophy: Simple for the Builder

The word "simply" in ODS refers to the experience of the person building the app — the citizen developer. The spec should be easy to write, easy to understand, and easy to hand to someone else. That's the contract.

What happens behind the scenes is a different story. Frameworks are free — and encouraged — to be as sophisticated as they need to be. A builder who writes `"type": "date"` in a form field shouldn't have to think about date pickers, localization, or storage formats. The framework handles all of that. A builder who adds a `"list"` component shouldn't have to worry about pagination, empty states, or responsive layout. The framework takes care of it.

This is the core design principle: **complexity is the framework's job, simplicity is the builder's experience.** The more the framework can do automatically, the simpler the spec stays — and the more capable citizen developers become without needing to learn more. A powerful framework paired with a simple spec is not a contradiction; it's the whole point.

The Problem

Many low-code and no-code platforms fail for a few key reasons:
 * They try to do too much. They start simple but quickly add overwhelming complexity.
 * They expect users to be designers. Good UI/UX is incredibly difficult, yet most platforms leave it to the user.
 * They create lock-in. Moving an application out of a proprietary ecosystem often means starting over from scratch.
 * They trap your data. Data is often held in expensive, proprietary data stores that are difficult to access or migrate.

Recently, many citizen developers are trying to build apps by "vibe coding" with AI. This creates another set of problems:
 * AI agents build things the citizen developer may not understand
 * AI agents build things that may not be safe
 * AI agents build things using technologies that simply may not be conducive to citizen development
Simply put, vibe coding lacks guardrails.

The ODS Solution

ODS solves these problems by separating concerns into a clear, three-part ecosystem:
 * The Specification: A simple, open-source JSON schema that defines the structure and logic of an application. It's the universal blueprint. The spec stays deliberately simple — it describes *what* the app does, not *how* to render it. This is what keeps building accessible.
 * Frameworks: Real-time renderers for the ODS specification. A framework handles the complex parts — UI/UX, security, data management, accessibility, and platform adaptation — so the citizen developer never has to. The framework is where sophistication lives: smart defaults, polished interactions, and professional-quality output, all driven by a spec the builder can read in five minutes. Frameworks also provide an "off-ramp" code-generation feature that generates professional source code, ensuring you are never locked in.
 * The Build Helper: A conversational AI tool that guides users through the process of creating an ODS JSON file, turning their ideas into a well-structured application definition. It's like vibe coding but with guardrails — the AI can only produce valid ODS specs, so the result is always safe, understandable, and portable.

Getting Started

(This section will be updated once the first reference framework is complete.)
To get a feel for the ODS specification, check out the example specs in this directory — from a simple customer feedback app to a to-do list with data updates.

Contributing

We are excited to build a community around this project. Please read our CONTRIBUTING.md to learn how you can get involved.

Code of Conduct

This project and everyone participating in it is governed by the ODS CODE_OF_CONDUCT.md. By participating, you are expected to uphold this code.