# notify-slack-on-failure-sample pipeline

Sample Tekton pipeline that runs the "notify-slack-on-failure" task.

## Parameters

| Name                                | Description                                                                                                                | Optional   | Default value                                             |
|-------------------------------------|----------------------------------------------------------------------------------------------------------------------------|------------|-----------------------------------------------------------|
| secretName                          | Name of secret which contains authentication token for app                                                                 | No         | -                                                         |
| secretKeyName                       | Name of key within secret which contains webhook URL                                                                       | No         | -                                                         |
| RELEASE                             | String representation of Release spec                                                                                      | No         | -                                                         |
