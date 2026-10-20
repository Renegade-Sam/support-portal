# Developer handoff notes

## What I delivered
I have created a Northstar Customer Support Portal with HTML and CSS. The page displays an email, support hours, and a short FAQ explaning how to check order status by signing in.

## How I verified the page
- Confirmed that the page title is visible.
- Verified that the support email address is displayed and linked in html code.
- Checked that support hours include Central Time.
- Confirmed that customers are asked to include their order number.
- Verified that the FAQ explains how to find order status.
- Checked that the page remains readable in a narrow browser window.
- Confirmed that the CSS styling is linked to the html page.

## Remote change I received
The README was updated on GitHub to document the support escalation process. It states that unresolved billing requests should be escalated to the billing team after one business day. 
I used `git pull --ff-only origin main` to receive the remote change and update my local repository.

## Git workflow explanation
The git commit command saves changes to the local git repository only and doesn't automatically push them to github. The hit push command actually uploads the local commits 
to remote repository, and the git pull --ff-only command retrieves remote changes and updates the local brach when done with fast forward. These commands help keep local and remote
repository synchronized.