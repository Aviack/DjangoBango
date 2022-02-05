<h1>DJANGO</h1>

![image](https://user-images.githubusercontent.com/91685640/152633355-523f6351-2b11-451f-bb11-ca8bb6eb1c2b.png)


<h1>Note</h1>
<h2>You need to have shodan Api key and type shodan init <your-api-key> to activate your account</h2>

<h1>Description</h1>
DjangoBango find the django debug mode enabled server with the help of shodan 
Here you provide list of domain you want to search for 
domain list should be in specific format --> www.google.com[Invalid] || google[valid]

<h1>Usage</h1>

<table>
<thead>
<tr>
<th>Argument</th>
<th>Description</th>
<th>Examples</th>
</tr>
</thead>
<tbody>
<tr>
<td>-d</td>
<td>provide path to the wordlist</td>
<td>'C:\\Users\\AVADH\\Desktop\\Automation\\domain.txt'</td>
</tr>
<tr>
<td>-s</td>
<td>Provide Shodan API key</td>
<td>TnJ92ZwOblwDxxxxxxxxx</td>
</tr>
</tbody>
</table>
  
  
<h2>Usage1</h2><h4>python DjangoBango.py  -d  'C:\\Users\\AVADH\\Desktop\\Automation\\domain.txt'  -s  "TnJ92ZwOblwDbq7jbrRUxxxxxxxxx"</h4>
