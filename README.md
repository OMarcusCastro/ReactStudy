# ReactStudy

![evolucao da web](<Screenshot 2023-10-10 at 21.05.13.png>)

## componentes

- js funcao que retorna html
- arquivos jsx -> js+xml(parecido com hmtl)

```jsx
import Post from "./Post"


function App() {
 

  return (
    <Post/>
    <Post/>
    <Post/>
  )
}

export default App
```

pq da erro? tenho que ter algum elemento envolvendo

```jsx
function App() {
 

  return (
    <div>
        <Post/>
        <Post/>
        <Post/>
    </div>
  )

}

export default App

```