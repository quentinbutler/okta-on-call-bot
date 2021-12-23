# On-Call Bot For Slack

## Before you get started / prerequisites

Before you get started, you will need:

- Access to an Okta tenant with Okta Workflows enabled for your org

- Slack 

- PagerDuty

## Problem

Checking the PagerDuty on-call schedule and updating a Slack topic with the individual on-call can be an inconvenience. 

## Solution

This tool updates Slack with the scheduled on-call user from PagerDuty. A use-case scenario would be in a channel dedicated to p0 support. 

## Resources

https://api.slack.com/methods/conversations.setTopic

https://developer.pagerduty.com/api-reference/b3A6Mjc0ODE2Mw-list-all-of-the-on-calls
