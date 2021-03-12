# Orb Project Template

Execute ACCELQ CI Jobs from CircleCI

# Sample input template

steps:
    - accelq-ci:
        url: << parameters.url >>
        tenant: << parameters.tenant >>
        project-name: << parameters.project-name >>
        job-id: << parameters.job-id >>
        user: << parameters.user >>
        password: << parameters.password >>
        agent-name: << parameters.agent-name >>
        runparams: << parameters.runparams >>