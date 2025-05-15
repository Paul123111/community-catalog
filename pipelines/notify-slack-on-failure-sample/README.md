# notify-slack-on-failure-sample pipeline

Sends an error message to Slack using postMessage API if managed pipelines fail.

## Parameters

| Name                                | Description                                                                                                                | Optional   | Default value                                             |
|-------------------------------------|----------------------------------------------------------------------------------------------------------------------------|------------|-----------------------------------------------------------|
| secretName                          | Name of secret which contains authentication token for app                                                                 | No         | -                                                         |
| secretKeyName                       | Name of key within secret which contains webhook URL                                                                       | No         | -                                                         |
| release                             | String representation of release spec                                                                                      | No         | -                                                         |
| taskGitUrl                          | The url to the git repo where the community-catalog tasks to be used are stored                                            | Yes        | https://github.com/konflux-ci/community-catalog.git       |
| taskGitRevision                     | The revision in the taskGitUrl repo to be used                                                                             | No         | -                                                         |
