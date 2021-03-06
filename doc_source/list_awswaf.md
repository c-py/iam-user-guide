# Actions, Resources, and Condition Keys for AWS WAF<a name="list_awswaf"></a>

AWS WAF \(service prefix: `waf`\) provides the following service\-specific resources, actions, and condition context keys for use in IAM permission policies\.

References:
+ Learn how to [configure this service](https://docs.aws.amazon.com/waf/latest/developerguide/)\.
+ View a [list of the API operations available for this service](https://docs.aws.amazon.com/waf/latest/APIReference/)\.
+ Learn how to protect this service and its resources by [using IAM](https://docs.aws.amazon.com/waf/latest/developerguide/waf-auth-and-access-control.html) permission policies\.

**Topics**
+ [Actions Defined by AWS WAF](#awswaf-actions-as-permissions)
+ [Resources Defined by WAF](#awswaf-resources-for-iam-policies)
+ [Condition Keys for AWS WAF](#awswaf-policy-keys)

## Actions Defined by AWS WAF<a name="awswaf-actions-as-permissions"></a>

You can specify the following actions in the `Action` element of an IAM policy statement\. By using policies, you define the permissions for anyone performing an operation in AWS\. When you use an action in a policy, you usually allow or deny access to the API operation or CLI command with the same name\. However, in some cases, a single action controls access to more than one operation\. Alternatively, some operations require several different actions\. For details about the columns in the following table, see [The Actions Table](reference_policies_actions-resources-contextkeys.md#actions_table)\.


****  
[\[See the AWS documentation website for more details\]](http://docs.aws.amazon.com/IAM/latest/UserGuide/list_awswaf.html)

## Resources Defined by WAF<a name="awswaf-resources-for-iam-policies"></a>

The following resource types are defined by this service and can be used in the `Resource` element of IAM permission policy statements\. Each action in the [Actions table](#awswaf-actions-as-permissions) identifies the resource types that can be specified with that action\. A resource type can also define which condition keys you can include in a policy\. These keys are displayed in the last column of the table\. For details about the columns in the following table, see [The Resource Types Table](reference_policies_actions-resources-contextkeys.md#resources_table)\.


****  

| Resource Types | ARN | Condition Keys | 
| --- | --- | --- | 
|   [ bytematchset ](https://docs.aws.amazon.com/waf/latest/APIReference/API_ByteMatchSet.html)  |  arn:$\{Partition\}:waf::$\{Account\}:bytematchset/$\{Id\}  |  | 
|   [ ipset ](https://docs.aws.amazon.com/waf/latest/APIReference/API_IPSet.html)  |  arn:$\{Partition\}:waf::$\{Account\}:ipset/$\{Id\}  |  | 
|   [ ratebasedrule ](https://docs.aws.amazon.com/waf/latest/APIReference/API_RateBasedRule.html)  |  arn:$\{Partition\}:waf::$\{Account\}:ratebasedrule/$\{Id\}  |  | 
|   [ rule ](https://docs.aws.amazon.com/waf/latest/APIReference/API_Rule.html)  |  arn:$\{Partition\}:waf::$\{Account\}:rule/$\{Id\}  |  | 
|   [ sizeconstraintset ](https://docs.aws.amazon.com/waf/latest/APIReference/API_SizeConstraintSet.html)  |  arn:$\{Partition\}:waf::$\{Account\}:sizeconstraintset/$\{Id\}  |  | 
|   [ sqlinjectionmatchset ](https://docs.aws.amazon.com/waf/latest/APIReference/API_SqlInjectionMatchSet.html)  |  arn:$\{Partition\}:waf::$\{Account\}:sqlinjectionmatchset/$\{Id\}  |  | 
|   [ webacl ](https://docs.aws.amazon.com/waf/latest/APIReference/API_WebACL.html)  |  arn:$\{Partition\}:waf::$\{Account\}:webacl/$\{Id\}  |  | 
|   [ xssmatchset ](https://docs.aws.amazon.com/waf/latest/APIReference/API_XssMatchSet.html)  |  arn:$\{Partition\}:waf::$\{Account\}:xssmatchset/$\{Id\}  |  | 
|   [ regexmatchset ](https://docs.aws.amazon.com/waf/latest/APIReference/API_RegexMatchSet.html)  |  arn:$\{Partition\}:waf::$\{Account\}:regexmatch/$\{Id\}  |  | 
|   [ regexpatternset ](https://docs.aws.amazon.com/waf/latest/APIReference/API_RegexPatternSet.html)  |  arn:$\{Partition\}:waf::$\{Account\}:regexpatternset/$\{Id\}  |  | 
|   [ geomatchset ](https://docs.aws.amazon.com/waf/latest/APIReference/API_GeoMatchSet.html)  |  arn:$\{Partition\}:waf::$\{Account\}:geomatchset/$\{Id\}  |  | 
|   [ rulegroup ](https://docs.aws.amazon.com/waf/latest/APIReference/API_RuleGroup.html)  |  arn:$\{Partition\}:waf::$\{Account\}:rulegroup/$\{Id\}  |  | 

## Condition Keys for AWS WAF<a name="awswaf-policy-keys"></a>

WAF has no service\-specific context keys that can be used in the `Condition` element of policy statements\. For the list of the global context keys that are available to all services, see [Available Keys for Conditions](reference_policies_condition-keys.html#AvailableKeys) in the *IAM Policy Reference*\.