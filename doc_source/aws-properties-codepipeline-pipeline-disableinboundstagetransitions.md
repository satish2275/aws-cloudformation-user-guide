# CodePipeline Pipeline DisableInboundStageTransitions<a name="aws-properties-codepipeline-pipeline-disableinboundstagetransitions"></a>

`DisableInboundStageTransitions` is a property of the [AWS::CodePipeline::Pipeline](aws-resource-codepipeline-pipeline.md) resource that specifies which CodePipeline stage to disable transitions to\.

## Syntax<a name="w13ab1c21c10c81c17c37b5"></a>

### JSON<a name="aws-properties-codepipeline-pipeline-disableinboundstagetransitions-syntax.json"></a>

```
{
  "[Reason](#cfn-codepipeline-pipeline-disableinboundstagetransitions-reason)" : String,
  "[StageName](#cfn-codepipeline-pipeline-disableinboundstagetransitions-stagename)" : String
}
```

### YAML<a name="aws-properties-codepipeline-pipeline-disableinboundstagetransitions-syntax.yaml"></a>

```
[Reason](#cfn-codepipeline-pipeline-disableinboundstagetransitions-reason): String
[StageName](#cfn-codepipeline-pipeline-disableinboundstagetransitions-stagename): String
```

## Properties<a name="w13ab1c21c10c81c17c37b7"></a>

`Reason`  <a name="cfn-codepipeline-pipeline-disableinboundstagetransitions-reason"></a>
An explanation of why the transition between two stages of a pipeline was disabled\.  
*Required*: Yes  
*Type*: String

`StageName`  <a name="cfn-codepipeline-pipeline-disableinboundstagetransitions-stagename"></a>
The name of the stage to which transitions are disabled\.  
*Required*: Yes  
*Type*: String