## Karol Siejek

Mendix developer. I build small local tools for the people who work on Mendix
applications — testers, developers, and whoever has to answer "what can this
role actually do?"

Whatever I build follows the same rules, because it has to run on a company
machine and pass a security review without exceptions: **no npm dependencies,
no installer, no admin rights, nothing written to disk, and no outbound
connection.** What runs is what you read — no build step, no bundler.

**[MxScout](https://github.com/ksiejek/mxscout)** — a local Mendix app
explorer. Point it at a project and it shows what a given user role can really
see and do; connect it to a running dev or test app and it reads real data and
runs a microflow in your own logged-in session. Production is refused by
design. Every promise it makes is written out on its own **About & security**
page, meant to be handed to a reviewer.
