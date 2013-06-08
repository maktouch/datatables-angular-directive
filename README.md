datatables-angular-directive
============================

An AJAX oriented Datatables for Angular. Simple markup!


## Demo

I really suggest you look at the source.
[Demo on my website](http://maktouch.net/github/maktouch/datatables-ajax-angular/examples.html)

## Quick start

```html
<!-- include jQuery, Angular and Datatatables here -->

<script type="text/javascript" src="angular.datatables.js"></script>

<script type="text/javascript">
		var app = angular.module('exampleapp', ['datatablesDirectives']);
</script>

<table datatable sAjaxSource="data.json" sAjaxDataProp="result" class="table table-striped table-bordered">
  <thead>
		<tr>
			<th data-mdata="id" data-sclass="highlight-red">ID</th>
			<th data-mdata="name">Name</th>
			<th data-mdata="about.text" data-bvisible="false">About me</th>
			<th data-mdata="phone">Phone</th>
			<th data-mdata="email">Email</th>
			<th data-mdata="age">Age</th>
		</tr>
	</thead>
	<tbody></tbody>
</table>
```


## Docs 

It's pretty straightforward to use if you know datatables. Here is the link to [datatable's documentation](http://datatables.net/usage/).

