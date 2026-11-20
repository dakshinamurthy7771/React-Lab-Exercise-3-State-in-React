# React-Lab-Exercise-3-State-in-React
# Name: Dakshinamurthy.V
# Roll no: 2305001006
# Department: CSE
# AIM
To create a simple React application that demonstrates the use of State using the useState() Hook.
# PROGRAM
```
App.jsx
import { useState } from "react"; function App() { const [name, setName] = useState("Aravindan T"); const [newName, setNewName] = useState(""); 
return ( 
<div> 
<h1>Student Name Example</h1> 
<h2>Student Name: {name}</h2> 
<input type="text" placeholder="Enter new name" value={newName} 
onChange={(e) => setNewName(e.target.value)} 
/> 
<button onClick={() => setName(newName)}> 
Change Name 
</button> 
</div> 
);
}
export default App;
```
# OUTPUT
<img width="1024" height="403" alt="image" src="https://github.com/user-attachments/assets/eac508ea-659e-4845-b9ec-ee70dc1d51f3" />
<img width="1024" height="397" alt="image" src="https://github.com/user-attachments/assets/d2cdf152-b1b2-4699-937f-b85fd62c4039" />


# RESULT
The React application was successfully created using Props to pass employee information from the parent component to the child component. Three employee details were displayed successfully using Props and Props Destructuring.


