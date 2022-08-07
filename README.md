# useSaveToLocalStorage

```bash
npm i usesavetolocalstorage
```

Usage:

```js
// Using setup for storing on localstorage
const initial = {current: {}, todos: []}
const db = createDb('db', initial)

export default function App() {
	const [data, setData] = useData(db.data)
	useSaveToLocalStorage(db, data)
	// ...
```

[See in action in this repository](https://github.com/sahilrajput03/warikoo-time-manager/tree/main)


Thanks for visting.
