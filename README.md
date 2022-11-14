# Vite + React Cleanup Script for Windows Powershell
This is a Starter Cleanup Script to remove un-necessary codes and provide a Clean Boilerplate!


### COMMANDS

copy this entire script and RUN 🚀

```shell
Remove-Item ./src/assets/react.svg ;

Remove-Item ./public/vite.svg  ;

Remove-Item ./src/App.jsx;


"import { useState } from 'react'
import './App.css'

function App() {
return(
 <h1>Vite + React</h1>
)
}


export default App" | Out-File -FilePath ./src/App.jsx ;

Clear-Content  -Path ./src/index.css ;
Clear-Content  -Path ./src/app.css ;

New-Item -Path ./src/components  -ItemType Directory ;
New-Item -Path ./src/utils  -ItemType Directory
```

