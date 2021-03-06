# AWS::CodeGuruProfiler::ProfilingGroup<a name="aws-resource-codeguruprofiler-profilinggroup"></a>

Creates a profiling group\.

## Syntax<a name="aws-resource-codeguruprofiler-profilinggroup-syntax"></a>

To declare this entity in your AWS CloudFormation template, use the following syntax:

### JSON<a name="aws-resource-codeguruprofiler-profilinggroup-syntax.json"></a>

```
{
  "Type" : "AWS::CodeGuruProfiler::ProfilingGroup",
  "Properties" : {
      "[ProfilingGroupName](#cfn-codeguruprofiler-profilinggroup-profilinggroupname)" : String
    }
}
```

### YAML<a name="aws-resource-codeguruprofiler-profilinggroup-syntax.yaml"></a>

```
Type: AWS::CodeGuruProfiler::ProfilingGroup
Properties: 
  [ProfilingGroupName](#cfn-codeguruprofiler-profilinggroup-profilinggroupname): String
```

## Properties<a name="aws-resource-codeguruprofiler-profilinggroup-properties"></a>

`ProfilingGroupName`  <a name="cfn-codeguruprofiler-profilinggroup-profilinggroupname"></a>
The name of the profiling group\.  
*Required*: Yes  
*Type*: String  
*Update requires*: [Replacement](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-replacement)

## Return Values<a name="aws-resource-codeguruprofiler-profilinggroup-return-values"></a>

### Ref<a name="aws-resource-codeguruprofiler-profilinggroup-return-values-ref"></a>

When you pass the logical ID of this resource to the intrinsic `Ref` function, `Ref` returns the name of the profiling group\.

For more information about using the `Ref` function, see [Ref](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/intrinsic-function-reference-ref.html)\.

### Fn::GetAtt<a name="aws-resource-codeguruprofiler-profilinggroup-return-values-fn--getatt"></a>

The `Fn::GetAtt` intrinsic function returns a value for a specified attribute of this type\. The following are the available attributes and sample return values\.

For more information about using the `Fn::GetAtt` intrinsic function, see [Fn::GetAtt](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/intrinsic-function-reference-getatt.html)\.

#### <a name="aws-resource-codeguruprofiler-profilinggroup-return-values-fn--getatt-fn--getatt"></a>

`Arn`  <a name="Arn-fn::getatt"></a>
The full Amazon Resource Name \(ARN\) for that profiling group\.