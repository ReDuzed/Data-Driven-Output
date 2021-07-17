Provide either --help, /?, or /help for the available arguments. Note that the text file ingested currently only replaces each of its values per line of input data to read through.

### Example
Ingest file:
```html
<tr>
    <td class='cell'>
        #0
    </td>
    <td>
        <input required type='checkbox' name='#1'/>
    </td>
</tr>
```

Data file:

``Line1``

``Line2``

``etc...``

Output file:
```html
<tr>
    <td class='cell'>
        Line1
    </td>
    <td>
        <input required type='checkbox' name='Line1'/>
    </td>
</tr>
<tr>
    <td class='cell'>
        Line2
    </td>
    <td>
        <input required type='checkbox' name='Line2'/>
    </td>
</tr>
etc...```
