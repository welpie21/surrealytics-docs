# Design

Surrealytics is gonna be build on the dioxus framework for rust. We can implement an embedded SurrealDB into the application which holds authentication and details that the webapp 
can use to represent / interact with the data. Without the need of splitting things up we can keep the logic in one place.

![Alt Text](surrealytics-design.svg)