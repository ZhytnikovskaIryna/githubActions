# githubActions
Develop workflow which:
 - use push trigger
 - use env var for artifact name
 - contains one job with three steps
     - action/checkout
     - print env var in console
     - action/upload-artifact
