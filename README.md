# Event Storming

## Resources

1. Sticky notes (a lot of them, with different colours)
2. Pens  
3. A lot of horizontal space (or a paper roll)
4. Facilitator
5. Domain Experts
6. Stackeholders
7. Intorduction about the problem the scoping session needs to solve

## Terminology

1. The `Event` is something that happens within the domain that we are scoping.
2. The `Definition` should resolve the terminology is not consistent/confussed during the event storming session.
3. The `Concern` in case there is some issue raised about an `Event` or some information that could have an impact on the scoping session. Also, with concern it would be best to define the priority/importance of the concern, so later it can help with planning and prioritization.
4. The `Command` is usually paired with an `Event`. They represent action/interaction/decission that leads to the event that `Command` is paired with.
5. The `External system` is something that our domain depends on, but it has no control over it. This also can represent an internal system but it is not part of the domain of the scoping session.

## Conventions

1. The `Event` usually are represented using orange colour.
2. Pasttense verbs to desctibe the events, to ensure that timeline is consistant.
3. In case `Events` need to happen at the same time, they are stacked vertically.
4. Define a timeline for the events.
5. Stick to the Domain language, so all people are on the same page and understand what is being talked about.
6. In case of confussion/different opinions/terminologies define `Definition` to guide the session further. This is usually in same row as the `Event` it describes but above of it.
7. If the concern/issue/risk is raised about particular `Event`, then an `Concern` should be added with some prioritization.
8. Encourage questions to resolve the assumptions during the scoping sessions.
9. The `Commands` are usually represented by using a blue sticky notes.
10. The `Command` that is carried out by the `User` is usually paired with the `User Role` on the command itself.
11. The `Command` that is triggered by the system, doesn't have the role associated with it.
12. The `Command` should be desciptive to provide details on what needs to happen to cause the `Event`.
13. The `External system` is usually represented by pink colour.
14. Use markers/lines to show the interaction between domain being scoped and the `External system`.

## Example of timeline

