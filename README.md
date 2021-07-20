# Armature

Armature is an event-driven stateful actor framework for Rust.

## What does that mean?

- **Event-driven:** events are the driving for behind any change to the 
system state. Events are gathered in a queue and dispatched to the actors.
- **Stateful actor:** every actor contains a hierarchical state machine 
that processes incoming events.

See the example for how to use.