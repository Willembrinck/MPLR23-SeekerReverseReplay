## Anonymization
Access to the complete implementation code would break anonymity.
This also implies that the experiments cannot be replicated without breaking anonymity.
For the review process, we offer instead extracts of code explicitly referenced in the paper and the raw results of the experiments.
The masked text will be replaced by the actual one after the review process.


## Undoing Writing Operations 

All the code related to undoing writing operations is in the class: `SkSelectiveExecutionRestorer` (file included in the repository)

## Experiments Raw Data


## Instructions to Replicate Experiments

Installing Seeker: Prototype Scriptable Time-Traveling Queryable Debugger.

1. Download Pharo, and create a new Pharo 11 image.
2. Open a Playground and execute the following code to install the debugger.

```Smalltalk
Metacello new
    baseline: 'Seeker';
    repository: 'github://maxwills/SeekerDebugger:mplr';
    load.
```

## Related Resources
SeekerDebugger is an ongoing project.
The official repository with the latest features and fixes is available at https://github.com/maxwills/SeekerDebugger
