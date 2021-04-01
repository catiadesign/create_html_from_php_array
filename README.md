# Create HTML from PHP Array
With this function you can create Html very easy from an PHP Array.<br/>
<li>Sample, Easy & Efficient searching.</li>
<li>User friendly - pass parameters and get started</li>

# Usage

## How to use:

Assign `keyword to search` to varible `$search_keyword`
```php
$search_keyword = "keyword";                            // search Keyword
```

Enter `table names` & their repective `column names` in an associative array `$table_ass_array` to search the `given keyword`.
```php

$table_ass_array = array( 
			'TABLE NAME 1' => array( 			// TABLENAME 1 to search in
						'COLUMNNAME_A',			// Column Name A to search in
						'COLUMNNAME_B'			// Column Name B to search in
						),
			'TABLE NAME 2' => array(			// TABLENAME 2 to search in
						'COLUMNNAME_A',			// Column Name A to search in
						'COLUMNNAME_B'			// Column Name B to search in
						)
			);
```

Call this awesome function `php_search_all_database("Keyword to search", "Table name array")` as below
```php
php_search_all_database($search_keyword, $table_ass_array);       // call this Awesomme function
```
