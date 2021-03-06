# Contentful Operations Repository
This repo is maintained by Contentful Operations Team at Topcoder. For questions and answers contact [@kkartunov](https://github.com/kkartunov) and/or [@hokienick](https://github.com/hokienick).

## Useful references
- [Environment Setup: Contentful Challenges](https://www.topcoder.com/thrive/articles/Environment%20Setup:%20Contentful%20Challenges)
- [Community App](https://github.com/topcoder-platform/community-app)
- [Contentful CMS Docs](https://github.com/topcoder-platform/community-app/blob/develop/docs/contentful/index.md)
- [Content Delivery API Reference](https://www.contentful.com/developers/docs/references/content-delivery-api/)

## How to work with git tickets

The basic flow for handling a ticket is as follows:

1. Assign the ticket to yourself, change the label to "tcx_Assigned", remove the "tcx_OpenForPickup" label.  Please only assign tickets to yourself when you are ready to work on it.  I don't want tickets assigned to someone and then not have them work on a ticket for 36 hours.  The goal here is a quick turnaround for the client.  If you can't work on a ticket immediately, leave it for someone else.

1. Complete the ticket and create a merge request within __36 hours__.  Please ensure your merge request can be merged automatically and that it's against the latest commit in Git when you create it.

1. Change the label on the ticket to "tcx_ReadyForReview"

After seeing a ticket marked as "tcx_ReadyForReview", the copilot will review that ticket, usually within 24 hours.

Note that you are expected to keep your changes in-sync with Git - make sure to do a pull before you push changes to make sure there aren't any merge issues.

#### Accepted fix

If a fix is accepted, a payment ticket will be created on the Topcoder platform within 5-10 minutes of the issue being closed.  You should see the payment in your PACTs within 24 hours.

#### Rejected fix

If a fix is rejected, a comment, and possibly a screenshot, will be added to the ticket explaining why the fix was rejected.  The status will be changed to "tcx_Feedback".

**If a fix is rejected, that ticket is your priority.  You should not assign yourself any more tickets until you complete the required additional fixes!**

## Payment amounts

Each ticket in GitLab has a dollar value.  That is the amount you will be paid when the ticket is completed, merged, and verified by the copilot.  Note that there is still a 30 day waiting period as the payment will be treated as a regular TopCoder challenge payment.

## Important Rules:

- You can assign any unassigned issue to yourself with an "Open for pick up" label (first come first serve)

- You can only assign **ONE AT A TIME**. The nature of it being assigned will indicate it is not available to anyone else.

- You will fix the ticket by committing changes to the master branch.

- After marking a ticket "tcx_ReadyForReview" you are eligible to accept another. You do _NOT_ need to wait for the copilot to validate your fix.

- You can do as many tickets as you want, as long as you follow the rules above.

- If an assigned task is not done in 36 hours, you will need to explain why it is not completed as a comment on the ticket.

- You can ask questions directly on the GitLab ticket.

#### ANYONE NOT FOLLOWING THE RULES ABOVE WILL BE WARNED AND POTENTIALLY LOSE THEIR GITLAB ACCESS!
