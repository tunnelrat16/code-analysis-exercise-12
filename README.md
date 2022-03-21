# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (currentColor){
  if (currentColor === "green"){
    nextColor = "yellow"
  } else if (currentColor === "yellow"){
    nextColor = 'red'
  } else if (currentColor === "red"){
    nextColor = 'green'
  }

  return nextColor
}
```

| Input    | Output      |
| -----    | ------      |
|  green   |  "yellow"   | 
|  blue    |  undefined  | 
|  red     |  'green'    | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>If the inputs are either green, yellow or red, they will return yellow, red, or green in the output respectively. 
    If anything else is entered there will not be a color to output and it will be undefined</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
