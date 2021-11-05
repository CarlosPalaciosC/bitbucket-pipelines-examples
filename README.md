# bitbucket-pipelines-examples

### deploy-environments-in-parallel:

Problems that can be Solved:

- If you need to deploy in many environments in parallel, this is not possible in Bitbucket Pipelines (in the same execution), but you can do it in next:
  Create a pipeline execution to deploy branch master in environment 1, and
  Add a step where you can trigger another pipeline with all configurations to deploy in environment 2

- This solution is util if you need to deploy in staging and productions environment with the same merge in any branch (master branch in this example)

- Additionally:
  Adding slack notification step with the link of bitbucket pipelines to check and open URL to approve the deployment in a specific environment. ( Manual deployment of bitbucket pipelines )

  [Pipelines Executions In Bitbucket Pipelines In public Repository](https://bitbucket.org/capalacios56/deploy-environments-in-parallel/addon/pipelines/home)

  


###
