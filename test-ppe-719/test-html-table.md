# test

The <strong>@Me</strong> macro expands to the full name of the current user in any work item search. The <strong>@Me</strong> macro is especially useful for creating a search that you can share with other users, and it can simplify your work by reducing the number of characters you must type to specify your own user name. For a description of all macros, see [Query fields, operators, and macros, Query macros or variables](test-new-line.md). 

<table width="100%">
<tbody valign="top">
<tr>
<th width="50%">Filter for</th>
<th width="50%">Type the following string</th>
</tr>
<tr>
<td>Currently assigned to you
</td>
<td>
<code>A=<xref href="ax" data-throw-if-not-resolved="False" data-raw-source="@ax"></xref></code>
</td>
</tr>

<tr>
<td>Created by you
</td>
<td>
<code>C=<xref href="ax" data-throw-if-not-resolved="False" data-raw-source="@ax"></xref></code> 
</td>
</tr>


<tr>
<td>Resolved yesterday
</td>
<td>
<code>&quot;Resolved Date&amp;quot;=<xref href="ax" data-throw-if-not-resolved="False" data-raw-source="@ax"></xref></code> 
</td>
</tr>

<tr>
<td>Modified 7 days ago
</td>
<td>
<code>System.ChangedDate=<xref href="ax" data-throw-if-not-resolved="False" data-raw-source="@ax"></xref></code>
</td>
</tr>

<tr>
<td>
Created yesterday under the Phone Saver team
</td>
<td>
&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;<code>Created Date <em> = </em> <xref href="ax" data-throw-if-not-resolved="False" data-raw-source="@ax"></xref></code><br/><code>And <em> Area Path </em> = _ FabrikamFiber\Phone Saver</code><br/>
</td>
</tr>

</tbody>
</table>  


## test another

<table>
<tbody>
  
<tr><th>table header</th></tr>

<tr><td>table data</td></tr>

</tbody>
</table>

## test another 1

<table>
<tbody>

<tr><th>table header</th></tr>
<tr><td><xref href="@a"></xref></td></tr>

</tbody>
</table>
