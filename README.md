# PagerDuty Q-SYS Integration

## Support:
THIS IS A BETA RELEASE! IT WILL NOT BE SUPPORTED BY QSC SUPPORT IF YOU CALL THEM!
IT COULD BE PULLED OFF THE REPO AT ANYTIME IF THE BETA STATUS IS REMOVED!

## Solution Type: 
Integration Concept

## Overview: 
This repo contains a PagerDuty Incidents Manager Integration. The goal is to allow for custom incidents to be created within Q-SYS and sent to PagerDuty. The controls can be placed on an UCI to allow for users to submit incidents based on their experience. 

To view the underlying code, go to pager_duty.lua. To view the demo design go to pager_duty.qsys.

Click here for instructions on setting up your integration within PagerDuty: https://support.pagerduty.com/docs/services-and-integrations

## How to Contribute
If you plan on contributing to this project, keep in mind that changing the LUA file will not change the Q-SYS Design code, so please open and make changes within the .qsys file. The LUA file is here for viewing only.

## Setup:
1. In pager_duty.qsys locate the "Setup" container. 
2. Enter a room name for the incidents. Can be anything you'd like. The room name will be added to the beginning of all incidents. 
3. Enter the email address associated with your PagerDuty integration.
4. Enter the Service ID that you received from PagerDuty when you setup the integration. (https://support.pagerduty.com/docs/services-and-integrations)
5. Enter the API key for your integration. 

- Room Name Example: 
  - > Conference Room

- Service ID Example: 
  - > PQGF9N

- API Key Example: 
  - > Token token=u+asbsdfu293529352


## License Type
MIT
