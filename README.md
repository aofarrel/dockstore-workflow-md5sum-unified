To demonstrate the checker workflow proposal

## CWL 

```
cwltool checker_workflow_wrapping_workflow.cwl md5sum.json
cwltool checker_workflow_wrapping_tool.cwl md5sum.json
```

Extend either one depending on whether you are wrapping a tool or a workflow

## WDL
```
java -jar ~/.dockstore/libraries/cromwell-29.jar run --inputs md5sum.wdl.json checker.wdl
```
