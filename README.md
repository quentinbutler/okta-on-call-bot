# okta-pagerduty-slack-oncall-bot


## Before you get started / prerequisites
Before you get started, you will need:

Access to an Okta tenant with Okta Workflows enabled for your org

Slack Business+

PagerDuty

## Problem

Checking the PagerDuty on-call schedule and updating a Slack topic with the individual on-call can be an inconvenience. 

## Solution

This tool updates Slack with the schedule on-call user from PagerDuty. This can be benefical for channels dedicated to p0 support. 

## Resources

https://api.slack.com/methods/conversations.setTopic

https://developer.pagerduty.com/api-reference/b3A6Mjc0ODE2Mw-list-all-of-the-on-calls
