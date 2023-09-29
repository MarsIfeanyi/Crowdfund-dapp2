Pull the repository. continuing from where we stopped tonight. The tasks below are to be completed and submitted before 10am tomorrow

After proposing a campaign, close the "create campaign" modal

inside the fetchAllCampaigns function in the useAllCampaigns hook, modify the function such that you can get all the contributors for each campaign.

In the same file, we defined a useEffect in which we're listening for the ProposeCampaign event, at the moment, the handler is only logging the event parameters, modify the handler, such that you can get all the info about the campaign and add it to the array of the campaigns so the page updates in real time when someone creates a campaign.

in the campaign page render all the contributors.

Bonus
Listen to ContributeEth event, so that the campaign page is updated (without refreshing) when someone contribute to a campaign
