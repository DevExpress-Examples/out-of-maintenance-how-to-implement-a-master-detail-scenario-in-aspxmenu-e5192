<!-- default file list -->
*Files to look at*:

* [MyDataSource.cs](./CS/WebSite/App_Code/MyDataSource.cs) (VB: [MyDataSource.vb](./VB/WebSite/App_Code/MyDataSource.vb))
* [MyHierarchicalCollection.cs](./CS/WebSite/App_Code/MyHierarchicalCollection.cs) (VB: [MyHierarchicalCollection.vb](./VB/WebSite/App_Code/MyHierarchicalCollection.vb))
* [MyHierarchicalView.cs](./CS/WebSite/App_Code/MyHierarchicalView.cs) (VB: [MyHierarchicalView.vb](./VB/WebSite/App_Code/MyHierarchicalView.vb))
* [MyHierarchyData.cs](./CS/WebSite/App_Code/MyHierarchyData.cs) (VB: [MyHierarchyData.vb](./VB/WebSite/App_Code/MyHierarchyData.vb))
* [Default.aspx](./CS/WebSite/Default.aspx) (VB: [Default.aspx](./VB/WebSite/Default.aspx))
* [Default.aspx.cs](./CS/WebSite/Default.aspx.cs) (VB: [Default.aspx](./VB/WebSite/Default.aspx))
<!-- default file list end -->
# How to implement a master-detail scenario in ASPxMenu


<p>This example demonstrates how to implement a master-detail scenario using <strong>ASPxMenu</strong>.<br />
Root elements will show <strong>Categories</strong> from the <strong>Northwind</strong> database, and child ones will show <strong>Products</strong> belonging to those categories.<br />
To achieve the goal we'll use custom implementation of the <strong>IHierarchicalDataSource </strong>interface as an <strong>ASPxMenu</strong>'s datasource<strong> </strong>and <strong>LinqToSql</strong><strong> </strong><strong>DataContext </strong>to fill it with items.<br />
For more details, please see the example.</p><p>See also another way to bind <strong>ASPxMenu</strong> to a database:<br />
<a href="https://www.devexpress.com/Support/Center/p/E49">ASPxMenu - How to bind a control to a database</a><u><br />
</u></p>

<br/>


