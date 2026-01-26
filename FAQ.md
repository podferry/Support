## Frequently Asked Questions

### Synchronization

#### AntennaPod suddenly reports that synchronization has failed. What’s happening?
This usually means your trial period has expired. After the trial ends, the service restricts API access used by GPodder-compatible clients like AntennaPod, which results in authentication failures.
Your account credentials are still valid—this is why the website and dashboard remain accessible. To confirm, log in to the dashboard and check your account or subscription status. If the trial has expired, supporting PodFerry will restore synchronization. 
See also the _Trial_ section.

#### How can I sync my tablet and phone?
##### Device Name Matters
To keep your episodes in sync across all your devices (phone, tablet, etc.), make sure they all use the same AntennaPod device name. For example, if your phone's AntennaPod app is named "antennapod_sm9," choose the same name on your tablet instead of creating a new one like "antennapod_tab10."        
##### Checking Sync Status
Open the AntennaPod app on any device, Go to Settings, Select Synchronization and you'll see the latest sync status, including the date and time of the last successful sync.
##### Peek at Queue Status
You can also check your episode queue status (played vs. unplayed) using PodFerry [web player](https://www.podferry.com/dashboard/player) and see if the episodes you want are there.

_Remember_: Only episodes you've actually listened to will be synchronized. Unplayed items in your inbox or queue won't be synced across devices.

#### Why do AntennaPod and PodFerry show different episode playback statuses?
It appears that AntennaPod only tracks playback progress for episodes that were initially started within its own app. Episodes started in PodFerry might not have their playback positions recognized or updated in AntennaPod. Conversely, episodes initiated in AntennaPod resume correctly in PodFerry. Unfortunately, there might not be a solution on the PodFerry side to address this issue.

#### What apps and protocols are compatible with PodFerry?
PodFerry is compatible with gPodder.net protocol v2. It has been tested with AntennaPod, but compatibility with other gPodder clients or older protocol versions have not been verified. There are no plans to support other variations.
For desktop listening, complementary to AntennaPod mobile app, you may use the [web player](https://www.podferry.com/dashboard/player) that works in any browser.

#### Why am I unable to authenticate or access the service?
Access to the service is now limited to supporters. Accounts that were previously on the free program shall move to a 21-day trial period. Once this trial expires, synchronization authentication is disabled unless the account is upgraded.

---

### Trial

#### I was previously a free user. What changed?
To ensure a reliable service for supporters, PodFerry transitioned away from free access. Free users are temporarily granted trial access before requiring a supporter plan.

#### How long does the trial last?
The trial period lasts 21 days. After that, synchronization authentication will no longer be available without a supporter plan.

#### Will my data or account be deleted if I don’t upgrade?
No. PodFerry website access remains available, subject to usage limits. Synchronization and Gpodder client authentication are restricted.

---

### Quota

#### Why does the OPML export contain fewer subscriptions than what I see in the app?
The number of subscriptions included in the OPML export depends on your subscription tier, which may impose a quota on how many can be exported. 

#### Why is there a sync quota, even for contributors?
Contributors are not subject to a quota. Switching from trial to contributor may require a full AntennaPod sync, to force retrieval of all accessible podcasts subscriptions.

#### Why the subscription count discrepancy in PodFerry?
The settings page accurately reflects the total number of subscriptions stored and accessible by your account. The subscription count in the player might be influenced by factors like trial subscription tier, resource limitations aimed at optimizing service for all users or third party CORS policy limitations".

---

### Account

#### Why hasn't my plan changed?
Typically, after a donation, the subscription status updates within minutes.
However, if a different email was used through our third-party payment provider, manual reconciliation may be needed to link the payment with the subscription.
In most cases, this issue is resolved automatically within 48 hours without any action on your part.
If you encounter any problems, please reach out via the Support [form](https://www.podferry.com/help/requestform).

#### How can I close my account?
Account deletion is available in the settings menu.

#### How do I change my email address?
Your account email cannot be changed at the moment. You may delete your existing account and create a new one. If you're a contributing member and wish to transfer your status, please [provide](https://www.podferry.com/help/requestform) the usernames/emails for both your new and old accounts. 

#### Where is my data located?
The site operates from a European data center. 

