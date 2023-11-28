# mass-balance-sim
### A simple Mass Balance simulation app written in Scilab 6

![window preview](https://github.com/Danedevz/mass-balance-sim/blob/main/preview/main_window.png?raw=true)

#### Required data:
- Component's name
- Molecular weight of each component
- Number of input streams
- Number of output streams

#### What you get:
- Mass balance per component (in kmol/h and kg/h)
- Mass balance subtotal (in kmol/h and kg/h)
- Total mass balance (in kmol/h and kg/h)

#### DEMO
For given data, check if the mass balance is balanced
<table>
<thead>
  <tr>
    <th rowspan="2">Components</th>
    <th colspan="4">Input</th>
    <th>Output</th>
  </tr>
  <tr>
    <th>1</th>
    <th>2</th>
    <th>3</th>
    <th>4</th>
    <th>1</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>C6H6</td>
    <td>0</td>
    <td>68.0963</td>
    <td>0</td>
    <td>186.1648</td>
    <td>186.1648</td>
  </tr>
  <tr>
    <td>H2O</td>
    <td>0.0385</td>
    <td>0.0682</td>
    <td>0.5395</td>
    <td>0</td>
    <td>0.6462</td>
  </tr>
  <tr>
    <td>C6H4O</td>
    <td>38.4133</td>
    <td>0</td>
    <td>0</td>
    <td>20.6841</td>
    <td>20.6841</td>
  </tr>
  <tr>
    <td>AlCl3</td>
    <td>0</td>
    <td>0</td>
    <td>179.3067</td>
    <td>0</td>
    <td>179.3067</td>
  </tr>
  <tr>
    <td>C8H10O</td>
    <td>0</td>
    <td>0</td>
    <td>0</td>
    <td>0</td>
    <td>106.5059</td>
  </tr>
</tbody>
</table>

1. Fill the required data
   
   ![window preview](https://github.com/Danedevz/mass-balance-sim/blob/main/preview/main_window.png?raw=true)
   
2. Run the program by clicking "Evaluate" button. Fill the mass flow composition for each input and output stream

   **Input**\
   ![window preview](https://github.com/Danedevz/mass-balance-sim/blob/main/preview/input_window.png?raw=true)\
   **Output**\
   ![window preview](https://github.com/Danedevz/mass-balance-sim/blob/main/preview/output_window.png?raw=true)
   
3. The Status Bar will indicate if your mass balance is balanced or not. The detailed data is shown on the console window
   
   *The status bar will light green if the mass balance is balanced*\
   ![window preview](https://github.com/Danedevz/mass-balance-sim/blob/main/preview/accepted_window.png?raw=true)
   
   *Data shown on the console windows*\
   ![window preview](https://github.com/Danedevz/mass-balance-sim/blob/main/preview/kgh_result.png?raw=true)\
   ![window preview](https://github.com/Danedevz/mass-balance-sim/blob/main/preview/kmolh_result.png?raw=true)
   
4. You can reset all the user input if the result doesn't satisfy your need and start from beginning
