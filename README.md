#netuitive.packages.aws.elb 1.4.0

For detailed information on this package, please refer to the [online documentation](https://help.app.netuitive.com/Content/Misc/Datasources/AWS/new_aws_datasource.htm).

##Release History

###Version 1.4.0

* Updated the baseline and correlation flags for a couple of metrics.
* Updated the sparse data strategy for a couple of metrics.
* Added three new policies:
 * AWS ELB - Elevated ELB Error Rate
 * AWS ELB - Unhealthy Host Percent Above 50%
 * AWS ELB - Unhealthy Host Percent Above 75%

###Version 1.3.1

* Fixed bug with the Events widget on the Element Detail Page.
* Removed configuration details for old, obsolete metrics.

###Version 1.3.0

* Added ELB-specific element detail page.
* Changed "sum" to "avg" on summary dashboard widgets.
* Updated 2 widgets on summary dashboard that were still using obsolete metrics.

###Version 1.2.1

* Fixed two minor packaging bugs.

###Version 1.2.0

* Removed obsolete computed metrics.
* Defined units for the metrics.

###Version 1.1.0

* Added summary dashboard.

###Version 1.0.0

* Initial production release of the package for monitoring AWS Elastic Load Balancer (ELB) resources.

