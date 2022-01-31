# merge_feature_branch
Merge source branch into feature branch and push. Create PR if conflicts

inputs:
  token:
    description: 'the GitHub PAT used to create PRs and perform commits'
    type: string
    required: true
  emailAddress:
    description: 'the email address used to login to GitHub and send email notifications'
    type: string
    required: true
  emailPassword:
    description: 'the password used to login to your mail server'
    type: string
    required: true
  featureBranch:
    description: 'featureBranch: The name of the branch to update'
    type: string
    required: true
  gitHubUsername:
    description: 'the username to display on the PR and commits'
    type: string
    required: true
    default: 'Auto Merge Triage'
  sourceBranch:
    description: 'sourceBranch: The name of the branch ahead of featureBranch'
    type: string
    required: true
    default: 'develop'
  toEmailAddress:
    description: 'the email address to send notifications to'
    type: string
    required: true
