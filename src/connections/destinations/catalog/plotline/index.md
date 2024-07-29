<H1> Plotline Destination </H1>

Plotline{:target="_plotline.so”} is a mobile adoption platform that helps product and marketing teams launch experiences like Stories, Videos, Animations, Streaks, Floating buttons and more inside the app - without taking engineering effort.

This destination is maintained by Plotline. For any issues with the destination, contact Plotline's support team at support@plotline.so.

<H2>Getting Started</H2>

1. From your workspace's Destination catalog page{:target="_blank”} search for "Plotline".
2. Select and click Add Destination.
3. Select an existing Source to connect to .
4. Go to the dashboard{:target="_blank"}, find and copy the API key.
5. Enter the API Key in the destination settings in Segment.

<H2> Supported methods </H2>
Plotline supports the following methods, as specified in the Segment Spec.

Page
Send Page calls to ADD WHAT PAGE CALLS ARE USED FOR HERE. For example:

analytics.page()
Segment sends Page calls to YOURINTEGRATION as a pageview.

Screen
Send Screen calls to ADD WHAT SCREEN CALLS ARE USED FOR HERE. For example:

[[SEGAnalytics sharedAnalytics] screen:@"Home"];
Segment sends Screen calls to YOURINTEGRATION as a screenview.

Identify
Send Identify calls to ADD WHAT IDENTIFY CALLS ARE USED FOR HERE. For example:

analytics.identify('userId123', {
  email: 'john.doe@example.com'
});
Segment sends Identify calls to YOURINTEGRATION as an identify event.

Track
Send Track calls to ADD WHAT Track CALLS ARE USED FOR HERE. For example:

analytics.track('Login Button Clicked')
Segment sends Track calls to YOURINTEGRATION as a track event.

(delete after reading) Congratulations! 🎉 You’ve finished the documentation for your Segment integration. If there’s any additional information or nuance which did not fit in the above template and that you want to share with our mutual customers, feel free to include these as a separate section for us to review. If not, you may now submit this doc to our team via your designated Slack Channel and we’ll respond with updates when we publish it and your integration!
