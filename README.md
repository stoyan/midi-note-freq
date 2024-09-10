# Lookup table of MIDI numbers to note names to note frequences

Available in CSV, JSON and JavaScript

## CSV sample
```
midi,note,freq
...
21,"A0",27.50
22,"A#0/Bb0",29.14
23,"B0",30.87
24,"C1",32.70
...
```


## JSON sample
```
[
  ...
  [21, "A0", 27.50],
  [22, "A#0/Bb0", 29.14],
  [23, "B0", 30.87],
  [24, "C1", 32.70],
  ...
]
```


## JS sample
```js
const midi_note_freq = [
  ...
  [21, 'A0', 27.5],
  [22, 'A#0/Bb0', 29.14],
  [23, 'B0', 30.87],
  [24, 'C1', 32.7],
  ...
];
```

## HTML sample

```html
<table>
  <thead>
    <tr>
      <th>midi</th>
      <th>note</th>
      <th>freq</th>
    </tr>
  </thead>
  <tbody>

    ...

    <tr>
      <td>21</td>
      <td>A0</td>
      <td>27.50</td>
    </tr>
    <tr>
      <td>22</td>
      <td>A#0/Bb0</td>
      <td>29.14</td>
    </tr>
    <tr>
      <td>23</td>
      <td>B0</td>
      <td>30.87</td>
    </tr>
    <tr>
      <td>24</td>
      <td>C1</td>
      <td>32.70</td>
    </tr>
    
    ...

  </tbody>
</table>
```
