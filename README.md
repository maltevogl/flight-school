# flight-school
learn to fly

## Reporting Issues and Requesting Features

Please report all issues and feature requests in [concourse/concourse](https://github.com/concourse/concourse/issues).

## Notes

after setting up concourse do
```
  fly -t ci set-pipeline -p flight-school -c ci/pipeline.yml
  ```
  
 and push new commit to git.
