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
<th>Note</th>
</tr>
</thead>
<tbody>
<tr>
<td>-u</td>
<td>single URL to scan</td>
<td><a href="http://example.com" rel="nofollow">http://example.com</a> or <a href="http://example.com/" rel="nofollow">http://example.com/</a></td>
<td>All these example usages are interpreted in the same way</td>
</tr>
<tr>
<td>-U</td>
<td>path to list of URLs</td>
<td>./urllist.txt, ../../urllist.txt, etc.</td>
<td>Just provide the path where the file is located :)</td>
</tr>
</tbody>
</table>
  
  
