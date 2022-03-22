# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (firstName, lastName, age){
  const person = {
    firstName: firstName,
    lastName: lastName,
    age: age,
  }

  return person
}
```

Inputs and outputs should be valid JavaScript values!

| Input | Output |
| {"Andrew", "Conklin", 27} | {firstName: "Andrew", lastName: "Conklin", age: 27, |
| {"Raja", "Catsmith", 6} | {firstName: "Raja", lastName: "Catsmith", age: 6, |
| {"Fred", "Flintstone", 103} | {firstName: "Fred", lastName: "Flintstone", age: 103, |
|       |        | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>This program takes in 3 inputted variables (firstName, lastName, age) and outputs an object (person) that has the the name:value pairs of the 3 inputted variables inside of it.   </td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
