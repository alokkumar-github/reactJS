https://github.com/sudheerj/awesome-javascript-technologies
https://github.com/sudheerj/javascript-interview-questions
https://github.com/sudheerj?tab=repositories
https://github.com/sudheerj/reactjs-interview-questions#what-is-react

Q. What are two-way data binding and one-way data flow, and how are they different?
A. Two way data binding means that UI fields are bound to model data dynamically such that when a UI field changes, the model data changes with it and vice-versa.

One way data flow means that the model is the single source of truth.
Changes in the UI trigger messages that signal user intent to the model (or “store” in React). Only the model has the access to change the app’s state.

The effect is that data always flows in a single direction, which makes it easier to understand.

One way data flows are deterministic, whereas two-way binding can cause side-effects which are harder to follow and understand.

Good to hear:

React is the new canonical example of one-way data flow, so mentions of React are a good signal. Cycle.js is another popular implementation of uni-directional data flow.
Angular is a popular framework which uses two-way binding.

https://itnext.io/the-absolute-easiest-way-to-debug-node-js-with-vscode-2e02ef5b1bad
