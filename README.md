<div align="center">
  <h1>CodSoft Python GUI Exercises</h1>
  <p>Four beginner desktop utilities built during a hands-on Python practice period</p>
  <img src="https://img.shields.io/badge/status-archived-6B7280?style=flat-square" alt="Status: archived" />
  <img src="https://img.shields.io/badge/stack-Python%20%7C%20Tkinter-3776AB?style=flat-square" alt="Python Tkinter" />
</div>

> [!NOTE]
> **Archived learning project.** These are preserved Tkinter exercises from a CodSoft practice period. They are kept as early Python work and are not part of the active portfolio.

## Included exercises

- **To-do list** — desktop task-list interface with local JSON storage.
- **Calculator** — basic calculator interface.
- **Password generator** — configurable random-password generator.
- **Rock, paper, scissors** — simple desktop game.

## Skills practised

- Building desktop interfaces with Tkinter.
- Managing user input, validation, and simple local state.
- Applying basic Python control flow and randomisation in small utilities.

## Application map

~~~mermaid
flowchart LR
    A[Python and Tkinter] --> B[To-do list]
    A --> C[Calculator]
    A --> D[Password generator]
    A --> E[Rock paper scissors]
    B --> F[tasks.json local storage]
    C --> G[Display and button callbacks]
    D --> H[Length input and generated characters]
    E --> I[Random computer choice and score state]
~~~

## Source-backed exercise detail

| Exercise | What its source implements |
| --- | --- |
| To-do list | A TodoListApp class with task persistence in local tasks.json. |
| Calculator | Button-driven expression entry, clear/backspace, on-off state, and error display. |
| Password generator | User-selected length and a mix of letters, digits, and punctuation. |
| Rock, paper, scissors | Player choice, random computer choice, winner calculation, and session score reset. |

## Important exercise limitations

- The calculator evaluates the typed expression with Python eval; it is suitable only as a local learning exercise and should not accept untrusted input.
- The password generator uses Python random, not a cryptographically secure generator; do not use it for production credentials.

## Explore locally

Install Python 3, then run any preserved source file directly:

```bash
python ".\\#1 Project TO-DO-LIST"
```

The original source-file names and screenshots are intentionally preserved as submitted.
