Props are a way to send data from one [[React Components|component]]  to another in [[React]]
`<Leaderboard characters={characters} />`

Props are often destructured to easily refer to their component parts in a file without having to begin with the prop name. 

React Props can lead to **Prop Drilling** when a component deep in chain needs a value from a top component. There is a tool called Context API to avoid Prop Drilling


