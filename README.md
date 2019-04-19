# create-tracker-story-concourse-resource

Concourse resource used to create Pivotal Tracker stories. Inspired by https://github.com/cloudfoundry/runtime-ci/tree/master/tasks/create-pm-story

## out

Creates the tracker story with the following parameters:

```
- put: create-tracker-story-concourse-resource
  params:
    TRACKER_STORY_LABELS: "needs-pm"
    TRACKER_PROJECT_ID: 1382120
    TRACKER_API_TOKEN: "some-token"
    TRACKER_STORY_NAME_PREFIX: "The Triumphant Herald says: "
    TRACKER_STORY_NAME: "Build failed!"
    TRACKER_STORY_STATE: unscheduled
    TRACKER_STORY_TYPE: feature
    TRACKER_STORY_ESTIMATE: 0
```
