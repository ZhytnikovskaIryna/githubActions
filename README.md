# githubActions
Tasks implemented in the current repo

1. Develop workflow:
 - use push trigger
 - use env var for artifact name
 - contains one job with three steps
     - action/checkout
     - print env var in console
     - action/upload-artifact
       
2. Develop workflow with 2 jobs
  Job1:
     - checkout repo
     - runs node Hello.js
  Job2:
      -depends on job 1
      -checkout repo
      -download artifacts
      
