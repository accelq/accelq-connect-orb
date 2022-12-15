# Orb Project Template

Sample Template to execute ACCELQ CI Jobs from CircleCI

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
        stepFailureThreshold: << parameters.stepFailureThreshold >>
</pre>

You can get ACCELQ CircleCI orb from here https://circleci.com/developer/orbs/orb/accelq/accelq-connect
