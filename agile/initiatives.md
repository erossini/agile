# Initiatives

Initiatives is a collection of epics that drive towards a common goal. The product roadmap is expressed and visualized as a set of initiatives, plotted along in a timeline. In many cases, an initiative combines epic from multiple teams to achieve a much broader, bigger goal.

They have a structure design. So, initiative houses epic and the completion of those epics head to the completion of the initiative.

So, while an epic is something you might completed in a month or a quarter, initiatives are often completed in multiple quarters.

```mermaid
flowchart TD
    B["Initialive"]
    B-->C["Epic 1"]
    B-->D["Epic 2"]
    B-->E["Epic 3"]
    C-->S1["User Story/Task 1"]
    C-->S2["User Story/Task 2"]
    S2-->US1["Subtask 1"]
    D-->S3["User Story/Task 1"]
    S3-->US2["Subtask 1"]
    S3-->US3["Subtask 2"]
    E-->F["Feature 1"]
    F-->S4["User Story/Task 1"]
    E-->S5["User Story/Task 2"]
    E-->S6["User Story/Task 3"]
    S4-->US4["Subtask 1"]
    S4-->US5["Subtask 2"]
```

So, you can see the hierarchy in the diagram. Initiatives are broken down into [epic](../agile/epic.md) and epic are brokwn down into a [user stories](../agile/user-story.md) or **task**.

>[!NOTE]
> - Initiatives are collections of epics that drive toward a common goal
> - The product roadmap is expressed and visualized as a set of initiatives plotted along a timeline
> - Completion of epics will lead to the completion of the initiative