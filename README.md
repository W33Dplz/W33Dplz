# Socle Twin

Socle Twin is an ontology-first digital twin of a small company, designed around three pieces: a typed graph of the company's entities, a structured knowledge base of its rules and procedures, and one MCP gateway through which any AI agent can query both.

- Ingestion connectors are designed to hold read-only credentials, and the typology is closed per company.
- Claude is meant to do the extraction, the typing and the entity matching, with people validating what matters.
- The gateway is specified as read-only by default. A write will exist only as a proposed action that a person approves.

Status: we have built parts of this by hand with Claude on client engagements and prototypes. Nothing runs end to end at a client yet. A plug-and-play platform is the goal for 2027.

- Architecture: [getsocle.com/architecture](https://getsocle.com/architecture)
- The same content with the diagrams as files: [W33Dplz/socle-twin](https://github.com/W33Dplz/socle-twin)
- Website: [getsocle.com](https://getsocle.com)

Socle Twin is a project of Derivatives Academy (BCE 0804.022.310), Lasne, Belgium. Contact: info@getsocle.com
