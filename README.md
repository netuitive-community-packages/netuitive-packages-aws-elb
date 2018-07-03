# netuitive.packages.aws.elb

For detailed information on this package, please refer to the [online documentation](https://help.netuitive.com/Content/Integrations/aws.htm).

## Release History

### Version 1.7.1

* Adjusted build to use metricly-cli for validation
* Applied ReplaceWithZero sparseDataStrategy for healthyhostcount and unhealthyhostcount metrics

### Version 1.7.0

* Updated element details dashboard layout
* Updated summary dashboard for new widget configs

### Version 1.6.1

* Minor typo fix in AWS ELB - Elevated Backend Error Rate (Low Volume) policy description
* Readme formatting

### Version 1.6.0

* Updated gridstack dashboard layouts

### Version 1.5.0

* Added four new computed metrics:
 * netuitive.aws.elb.httpcodeelb4xxerrorpercent
 * netuitive.aws.elb.httpcodeelb5xxerrorpercent
 * netuitive.aws.elb.httpcodebackend4xxerrorpercent
 * netuitive.aws.elb.httpcodebackend5xxerrorpercent
* Added sparse data strategy of "replace with zero" for the request count metric.

### Version 1.4.2

* Changed the Unhealthy Host Percent policies to be disabled by default, as they can be noisy for some customers.

### Version 1.4.1

* Fixed a bug with policies that had a Warning version and a Critical version; whenever the Critical version fired, the Warning was firing at the same time.
* Updated package compatibility configuration.

### Version 1.4.0

* Updated the baseline and correlation flags for a couple of metrics.
* Updated the sparse data strategy for a couple of metrics.
* Added three new policies:
 * AWS ELB - Elevated ELB Error Rate
 * AWS ELB - Unhealthy Host Percent Above 50%
 * AWS ELB - Unhealthy Host Percent Above 75%

### Version 1.3.1

* Fixed bug with the Events widget on the Element Detail Page.
* Removed configuration details for old, obsolete metrics.

### Version 1.3.0

* Added ELB-specific element detail page.
* Changed "sum" to "avg" on summary dashboard widgets.
* Updated 2 widgets on summary dashboard that were still using obsolete metrics.

### Version 1.2.1

* Fixed two minor packaging bugs.

### Version 1.2.0

* Removed obsolete computed metrics.
* Defined units for the metrics.

### Version 1.1.0

* Added summary dashboard.

### Version 1.0.0

* Initial production release of the package for monitoring AWS Elastic Load Balancer (ELB) resources.
