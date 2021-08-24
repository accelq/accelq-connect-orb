# Orb Project Template

Execute ACCELQ CI Jobs from CircleCI

## Sample input template
<pre>
steps:
    - accelq-ci:
        url: << parameters.url >>
        userId: << parameters.userId >>
        apiKey: << parameters.apiKey >>
        tenantCode: << parameters.tenantCode >>
        jobId: << parameters.jobId >>
        runparams: << parameters.runparams >>
        proxyHost: << parameters.proxyHost >>
        proxyPort: << parameters.proxyPort >>
        agentName: << parameters.agentName >>
</pre>

You can get ACCELQ CircleCI orb from here https://circleci.com/developer/orbs/orb/accelq/accelq-connect
