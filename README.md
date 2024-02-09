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

<h2>The Query Builder Tab</h2>

<p>Most of the query creation is done in this area. Table objects (seen on the left column) can be selected/dragged on to the grid space. Fields for the selected table can be seen in the column on the right. When more than one table is added to the grid, relationships/joins can be setup. Specific field criteria can be added. Parameters can be setup to be chosen before the query is run. Select the fields to be displayed in the final report, and create any calculated columns to be a part of the output. More than one query can be created to have a multi-query report (a query with sub-queries).</p>
<p>
<img src="https://github.com/darrylbartlett/epicor-baq/assets/159499839/f8ed546a-487d-4fd8-9fb2-42155dac4833"/>
</p>
<br />

<h2>The Query Builder > Display Fields Tab</h2>

<p>This page is found on the Display Fields tab inside the Query Builder. In the left column, you can see all the fields for the tables that have been added to the grid. Fields shown under the 'Display Columns' area have been chosen to show as output for the query.</p>
<p>
<img src="https://github.com/darrylbartlett/epicor-baq/assets/159499839/533c01fd-4223-47da-8c72-1ada5b92cb75"/>
</p>
<br />
