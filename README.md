<p align="center">
<img src="https://github.com/darrylbartlett/epicor-baq/assets/159499839/f45f8b13-c7f1-4784-932c-c197f16fcfcd" alt="epicor logo"/>
</p>

<h1>Epicor ERP - Business Activity Query Environment (BAQ)</h1>
This is a brief overview of Epicor's BAQ environment where SQL-based queries can be created to build reports.<br />

<h2>Environments and Technologies Used</h2>

- Epicor's Business Activity Query (my experience has been on version 10.2.400)
- SQL Server 2016

<h2>Operating System Used</h2>

- Windows Server 2016

<h2>List of Prerequisites</h2>

- Understanding of the relational database data to be used for building queries
- SQL knowledge
<br />

<h2>The General Tab</h2>

<p>Create a new query or open an existing query. Each query can have a Query ID and Description. Queries can be shared so they're available to other users and/or companies. Queries can be created to update the database directly from a report.</p>
<p>
<img src="https://github.com/darrylbartlett/epicor-baq/assets/159499839/f8ed546a-487d-4fd8-9fb2-42155dac4833"/>
</p>
<br />

<h2>The Query Builder > Phrase Build Tab</h2>

<p>Most of the query creation is done in the Phrase Build area inside the Query Builder. Table objects (seen on the left column) can be selected/dragged on to the grid space. Fields for the selected table can be seen in the column on the right. When more than one table is added to the grid, relationships/joins can be setup. Specific field criteria can be added. Parameters can be setup to be chosen before the query is run. Select the fields to be displayed in the final report, and create any calculated columns to be a part of the output. More than one query can be created to have a multi-query report (a query with sub-queries).</p>
<p>
<img src="https://github.com/darrylbartlett/epicor-baq/assets/159499839/46520156-8d21-4f1f-bf75-df801831fbb6"/>
</p>
<br />

<h2>The Query Builder > Display Fields Tab</h2>

<p>This page is found on the Display Fields tab inside the Query Builder. In the left column, you can see all the fields for the tables that can be added to the grid. Fields shown under the 'Display Columns' area have been chosen to show as output for the query.</p>
<p>
<img src="https://github.com/darrylbartlett/epicor-baq/assets/159499839/533c01fd-4223-47da-8c72-1ada5b92cb75"/>
</p>
<br />

<h2>Calculated Fields</h2>

<p>This screen is a selection of the Display Fields tab. It lets you create a calculated column that will be a part of the displayed fields in the final output of the query. The column data is setup like any other database field would be with a name, data type, format, and column label (or header). Calculate on different fields and values, select from a list of functions, and there are functions not shown that can also be used in a calculation.</p>
<p>
<img src="https://github.com/darrylbartlett/epicor-baq/assets/159499839/03a85f63-f23d-47bd-a3b2-d901473adbaa"/>
</p>
<br />

<h2>The Query Builder > Subquery Options Tab</h2>

<p>This page is on the Subquery Options tab inside the Query Builder. When building a report that has more than one query, you can switch between them on this screen. Only one query is displayed at a time. This screen will let you organize how the queries will run. For example, do you want a main query with a sub-query (or multiple sub-queries)? Is the data from multiple queries being combined into a single output (union query)?</p>
<p>
<img src="https://github.com/darrylbartlett/epicor-baq/assets/159499839/dc2358bb-81cf-4363-910d-b603b1ea1060"/>
</p>
<br />

<h2>The Analyze Tab</h2>

<p>This tab lets you run and review the output from the created query. Here you can verify the requested columns are displayed correctly, the retrieved data is accurate, correct values for calculated columns are showing properly, the data is sorted in the correct order, etc.</p>
<p>
<img src="https://github.com/darrylbartlett/epicor-baq/assets/159499839/84496dc7-253d-4120-b51b-caae7a6a0610"/>
</p>
<br />


