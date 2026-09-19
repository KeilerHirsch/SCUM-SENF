# SCUM-SENF

**SCUM Server Event & Notification Framework**

Open-source monitoring, events, alerts and operational tooling for SCUM servers. Built for server owners who prefer telemetry over guessing.

## Scope

SCUM-SENF is intended to provide a small, transparent operational layer around a SCUM server, including:

- server and service health monitoring
- event and alert handling
- crash and restart chronology
- CPU, RAM, storage and network telemetry
- backup verification
- Discord notifications
- API and bot integration
- later adapters for additional operational tooling

The project is deliberately starting small. Architecture and implementation will be added only where they solve an actual server-operations problem.

## Philosophy

- Prefer telemetry over guessing.
- Prefer deterministic signals over vague dashboards.
- Keep Discord as the cockpit, not the database.
- Preserve useful operational history.
- Keep the system understandable enough that server owners can fork, inspect and modify it.

Community forks, adapters and contributions are welcome.

## Status

Early foundation / pre-implementation.

No production-ready release exists yet.

## License

Licensed under the **European Union Public Licence (EUPL) v1.2**.

See [LICENSE](LICENSE).

## Disclaimer

SCUM-SENF is an unofficial community project. It is not affiliated with, endorsed by, or sponsored by Gamepires, Jagex, or any other developer or publisher associated with SCUM.

SCUM and related names, marks and assets belong to their respective owners.
