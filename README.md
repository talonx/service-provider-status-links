## Service Provider Status URLs
A list of URLs to the RSS feeds and status pages of various service providers

### Key
Direct Notifications -> Does the status page have a way to send direct notifications (email, text, etc) ?

Twitter for Status -> Some services have a dedicated Twitter only for status updates. I've left out Twitter accounts that are inactive.

### Public Clouds, CDNs, Hosting
| Service               | Status Page                                     | RSS Feed                                                                                    | Direct Notifications | Twitter for Status               |
|-----------------------|-------------------------------------------------|---------------------------------------------------------------------------------------------|----------------------|----------------------------------|
| Rackspace Cloud       | https://rackspace.service-now.com/system_status | https://rss.status.rackspace.com/snow/statusfeed                                            |
| Oracle Cloud          | https://ocistatus.oraclecloud.com/              | https://ocistatus.oraclecloud.com/api/v2/incident-summary.rss                               |
| Netlify               | https://www.netlifystatus.com/                  | https://www.netlifystatus.com/history.atom, https://www.netlifystatus.com/history.rss       | Yes                  |
| Microsoft Azure       | https://azure.status.microsoft/en-us/status     | https://azure.status.microsoft/en-us/status/feed/                                           | Yes                  |
| Linode                | https://status.linode.com/                      | https://status.linode.com/history.atom, https://status.linode.com/history.rss               | Yes                  |
| Google Cloud Platform | https://status.cloud.google.com/                | https://status.cloud.google.com/en/feed.atom                                                |                      |
| Digital Ocean         | https://status.digitalocean.com/                | https://status.digitalocean.com/history.atom, https://status.digitalocean.com/history.rss   | Yes                  | https://twitter.com/dostatus     |
| AWS                   | https://health.aws.amazon.com/health/status     | Overall - http://status.aws.amazon.com/rss/all.rss, Status page has individual feeds too.   |                      |                                  |
| Alibaba Cloud         | https://status.alibabacloud.com/                |                                                                                             |                      |                                  |
| IBM Cloud             | https://cloud.ibm.com/status                    | https://cloud.ibm.com/status/api/notifications/feed.rss                                     |                      |
| Salesforce            | https://status.salesforce.com/                  |                                                                                             |                      |                                  |
| Akamai                | https://www.akamaistatus.com/                   | https://www.akamaistatus.com/history.atom, https://www.akamaistatus.com/history.rss         | Yes                  |                                  |
| Fastly                | https://www.fastlystatus.com/                   | https://www.fastlystatus.com/rss/                                                           | Yes                  |                                  |
| Cloudflare            | https://www.cloudflarestatus.com/               | https://www.cloudflarestatus.com/history.atom, https://www.cloudflarestatus.com/history.rss |                      |                                  |
| Heroku                | https://status.heroku.com/                      |                                                                                             | Yes                  | https://twitter.com/herokustatus |
|                       |                                                 |                                                                                             |                      |                                  |

### Monitoring and Alerting
| Service                                                  | Status Page                                | RSS Feed                                                                                                      | Direct Notifications | Twitter for Status |
|----------------------------------------------------------|--------------------------------------------|---------------------------------------------------------------------------------------------------------------|----------------------|--------------------|
| DataDog (US1) - other regions are linked from this page. | https://status.datadoghq.com/              | https://status.datadoghq.com/history.atom, https://status.datadoghq.com/history.rss                           | Yes                  |                    |
| DataDog Integrations                                     | https://datadogintegrations.statuspage.io/ | https://datadogintegrations.statuspage.io/history.atom, https://datadogintegrations.statuspage.io/history.rss | Yes                  |                    |
| Uptime Robot                                             | https://status.uptimerobot.com/            |                                                                                                               | Yes                  |                    |



### Communication and Collaboration
| Service              | Status Page                                                                           | RSS Feed                                                                            | Direct Notifications | Twitter for Status                |
|----------------------|---------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------|----------------------|-----------------------------------|
| Microsoft Office 365 | https://portal.office.com/servicestatus, alternatively, https://status.office365.com/ |                                                                                     |                      | https://twitter.com/MSFT365Status |
| Slack                | https://status.slack.com/                                                             | https://status.slack.com/feed/atom, https://status.slack.com/feed/rss               |                      |                                   |
| Zoom                 | https://status.zoom.us/                                                               | https://status.zoom.us/history.atom, https://status.zoom.us/history.rss             | Yes                  |                                   |
| Atlassian            | https://status.atlassian.com/                                                         | https://status.atlassian.com/history.atom, https://status.atlassian.com/history.rss |                      |                                   |
| Dropbox              | https://status.dropbox.com/                                                           | https://status.dropbox.com/history.atom, https://status.dropbox.com/history.rss     | Yes                  |                                   |
| Google Workspace     | https://www.google.com/appsstatus/dashboard/                                          | https://www.google.com/appsstatus/dashboard/en-IN/feed.atom                         |                      |                                   |
| Zoho                 | https://status.zoho.com/                                                              | https://status.zoho.com/rss                                                         | Yes                  |                                   |

### Dev Tools
| Service                    | Status Page                     | RSS Feed                                                                                | Direct Notifications | Twitter for Status                 |
|----------------------------|---------------------------------|-----------------------------------------------------------------------------------------|----------------------|------------------------------------|
| GitHub                     | https://www.githubstatus.com/   | https://www.githubstatus.com/history.atom, https://www.githubstatus.com/history.rss     |                      | https://twitter.com/githubstatus   |
| GitLab                     | https://status.gitlab.com/      | https://status.gitlab.com/pages/5b36dc6502d06804c08349f7/rss                            | Yes                  | https://twitter.com/gitlabstatus   |
| Maven                      | https://status.maven.org/       | https://status.maven.org/history.atom, https://status.maven.org/history.rss             | Yes                  | https://twitter.com/sonatype_ops   |
| Quay.io Container Registry | https://status.quay.io/         | https://status.quay.io/history.atom, https://status.quay.io/history.rss                 | Yes                  |                                    |
| Docker Hub                 | https://www.dockerstatus.com/   | https://www.dockerstatus.com/pages/533c6539221ae15e3f000031/rss                         | Yes                  |                                    |
| Kraken CI                  | https://status.kraken.com/      | https://status.kraken.com/history.atom, https://status.kraken.com/history.rss           | Yes                  |                                    |
| Travis CI                  | https://www.traviscistatus.com/ | https://www.traviscistatus.com/history.atom, https://www.traviscistatus.com/history.rss | Yes                  | https://twitter.com/traviscistatus |
| Circle CI                  | https://status.circleci.com/    | https://status.circleci.com/history.atom, https://status.circleci.com/history.rss       | Yes                  | https://twitter.com/CircleCIstatus |
| Codefresh                  | https://status.codefresh.io/    | https://status.codefresh.io/history.atom, https://status.codefresh.io/history.rss       | Yes                  |                                    |


### Other
| Service                  | Status Page                                      | RSS Feed                                                                            | Direct Notifications | Twitter for Status                  |
|--------------------------|--------------------------------------------------|-------------------------------------------------------------------------------------|----------------------|-------------------------------------|
| Apple Developer Platform | https://developer.apple.com/system-status/       |                                                                                     |                      |                                     |
| Meta                     | https://metastatus.com/                          |                                                                                     |                      |                                     |
| MailChimp                | https://status.mailchimp.com/                    |                                                                                     | Yes                  | https://twitter.com/MailchimpStatus |
| Stripe                   | https://status.stripe.com/                       | https://www.stripestatus.com/history.atom, https://www.stripestatus.com/history.rss | Yes                  | https://twitter.com/stripestatus    |
| ZenDesk                  | https://status.zendesk.com/                      |                                                                                     | Yes                  |                                     |
| PayPal                   | https://www.paypal-status.com/product/production | https://www.paypal-status.com/feed/rss                                              | Yes                  |                                     |
| OpenAI                   | https://status.openai.com/                       | https://status.openai.com/history.atom, https://status.openai.com/history.rss       | Yes                  |                                     |
| Okta                     | https://status.okta.com/                         | https://feeds.feedburner.com/OktaTrustRSS                                           |                      |                                     |
| HubSpot                  | https://status.hubspot.com/                      | https://status.hubspot.com/history.atom, https://status.hubspot.com/history.rss     |                      |                                     |

