# PN-CI-PIPELINE

## AWS Docs

### Nested stacks


### Variables
[Working with variables](https://docs.aws.amazon.com/codepipeline/latest/userguide/actions-variables.html)

Some actions in CodePipeline generate variables.

To use variables:

- You _assign a namespace_ to an action to make the variables it produces available to a downstream action configuration. 
- You _configure the downstream action_ to consume the variables generated by the action.

You can view the details for each action execution to see the values for each output variable that was generated by the action in execution-time.

[CodeStarSourceConnection variables](https://github.com/awsdocs/aws-codepipeline-user-guide/blob/main/doc_source/reference-variables.md#codestarsourceconnection-action-output-variables)
