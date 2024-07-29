<H1> Plotline Destination </H1>

[Plotline](https://www.plotline.so/?utm_source=segmentio&utm_medium=docs&utm_campaign=partners) is a mobile adoption platform that helps product and marketing teams launch experiences like Stories, Videos, Animations, Streaks, Floating buttons and more inside the app - without taking engineering effort.

This destination is maintained by Plotline. For any issues with the destination, contact Plotline's support team at support@plotline.so.

<H2>Getting Started</H2>

1. From your workspace's [Destination catalog page](https://app.segment.com/goto-my-workspace/destinations/catalog) search for "Plotline".
2. Select and click Add Destination.
3. Select an existing Source to connect to .
4. Go to [Plotline's dashboard](app.plotline.so), navigate to "Credentials" and copy the API key.
5. Enter the API Key in the destination settings in Segment.

<H2> Supported methods </H2>
Plotline supports the following methods, as specified in the [Segment Spec](https://github.com/segmentio/segment-docs/blob/develop/docs/connections/spec).

<H3>Page</H3>
Send Page calls to ADD WHAT PAGE CALLS ARE USED FOR HERE. For example:  

```
analytics.page()
```
Segment sends Page calls to Plotline as a `pageview`.

<H3>Screen</H3>
Send Screen calls to ADD WHAT SCREEN CALLS ARE USED FOR HERE. For example:  

```
[[SEGAnalytics sharedAnalytics] screen:@"Home"];
```
Segment sends Screen calls to Plotline as a `screenview`.

<H3>Identify</H3>
Send Identify calls to ADD WHAT IDENTIFY CALLS ARE USED FOR HERE. For example:  

```
analytics.identify('userId123', {
  email: 'john.doe@example.com'
});
```
Segment sends Identify calls to Plotline as an `identify` event.

<H3>Track</H3>
Send Track calls to ADD WHAT Track CALLS ARE USED FOR HERE. For example:  

```
analytics.track('Login Button Clicked')
```
Segment sends Track calls to Plotline as a `track` event.
