# Date-A-Base Privacy Policy

**Effective date:** September 12, 2026  
**Last updated:** September 12, 2026

Date-A-Base ("Date-A-Base," "we," "our," or "us") provides a mobile application that creates suggested date itineraries based on information a user chooses to provide. This Privacy Policy explains what information the current pilot version of Date-A-Base handles, why it is used, when it is shared, and the choices available to users.

This policy applies to the Date-A-Base mobile application, its TestFlight versions, and the Date-A-Base planner API (collectively, the "Service").

## 1. Information we handle

### Planning information you provide

When you request an itinerary, the Service processes the information you enter or select, including:

- a city, neighborhood, or starting area;
- the requested date, start time, and device timezone;
- date mood or category;
- budget range;
- dietary preferences;
- previously suggested venues that should be excluded; and
- the itinerary and stop information needed when you request a replacement stop.

Please do not enter names, contact information, health details, or other sensitive personal information into free-text location fields.

### Location information

Date-A-Base does not continuously track your location. If you tap **Use my location** and grant permission, the app obtains your foreground location once to identify an approximate current area and find nearby suggestions. The app may send the resulting coordinates and area label to the Date-A-Base planner API. You may decline location permission and manually enter a city or neighborhood instead.

The current OpenAI-backed planner uses the area label as an approximate search location. If a Google Gemini/Google Maps-backed planner is enabled in a future version, the coordinates may also be supplied to Google for nearby venue search. Date-A-Base does not use background location access.

### Itinerary information stored on your device

When you activate an itinerary, the app stores that itinerary locally on your device so it remains available when the app is reopened. It may include venue names, addresses, dates and times, preferences, estimated costs, and travel information. In the current pilot, Date-A-Base does not provide cloud accounts or server-side itinerary history.

You can remove the active locally stored itinerary by ending the date in the app. Removing the app from your device also removes application data according to your device's operating-system behavior.

### Technical information

When your device communicates with the planner API, ordinary network and hosting systems may process technical information such as an IP address, request time, response status, and device or browser networking information. We use this information only as needed to operate, secure, troubleshoot, and prevent abuse of the Service. We do not currently include an advertising or third-party analytics SDK in the app.

### TestFlight information

If you participate in a TestFlight pilot, Apple may process your Apple Account information, device information, installation activity, crash information, and feedback under Apple's own terms and privacy practices. TestFlight feedback you submit may be made available to us through App Store Connect.

## 2. How we use information

We use the information described above to:

- generate, validate, display, and replace itinerary suggestions;
- find venues near the area you select;
- apply timing, budget, mood, and dietary constraints;
- preserve an activated itinerary on your device;
- operate, secure, debug, and improve the reliability of the Service;
- respond to pilot feedback and support requests; and
- comply with legal obligations and protect users, the Service, and others.

We do not sell personal information. We do not use your information for third-party advertising, cross-app tracking, or creating advertising profiles.

## 3. AI-generated recommendations and service providers

Date-A-Base sends planning information to its server-side itinerary provider to generate recommendations. The currently deployed pilot uses OpenAI's API with web search. Requests may include the selected area, date and time, timezone, mood, budget, dietary preferences, excluded venues, and relevant itinerary context. The API request is configured with `store: false`.

We use service providers only to perform functions for the Service. Current or supported providers include:

- **Amazon Web Services (AWS):** hosts the Date-A-Base planner API and processes network traffic required to operate it. See the [AWS Privacy Notice](https://aws.amazon.com/privacy/).
- **OpenAI:** generates and grounds itinerary recommendations when the OpenAI planner is enabled. See [OpenAI's Privacy Policy](https://openai.com/policies/privacy-policy/) and [OpenAI's enterprise privacy information](https://openai.com/enterprise-privacy/).
- **Apple:** distributes the iOS application and TestFlight builds and processes beta-testing information. See [Apple's Privacy Policy](https://www.apple.com/legal/privacy/).
- **Google:** provides device geocoding through the operating environment and may provide Gemini and Google Maps grounding if that planner is enabled. See [Google's Privacy Policy](https://policies.google.com/privacy).
- **Expo/EAS:** builds and supports distribution of the application. Expo does not receive itinerary requests merely because the installed app was built with EAS, but it processes developer build and distribution information. See [Expo's Privacy Policy](https://expo.dev/privacy).

These providers process information under their own terms and privacy practices. Venue websites, mapping applications, reservation providers, phone services, rideshare services, and other external destinations you choose to open are independent services governed by their own privacy policies.

## 4. Data retention and deletion

The current pilot does not maintain a Date-A-Base account database or intentionally retain a server-side itinerary history. Planning requests and results are processed to return the requested itinerary. OpenAI requests are sent with storage disabled in the API request.

Our infrastructure and service providers may retain limited technical, security, error, or abuse-prevention records according to their configurations, legal obligations, and policies. We retain such records only as long as reasonably necessary for those purposes.

Because the current pilot has no user accounts, there is no cloud account to delete. You can delete the active itinerary through the app and can remove other locally stored application data by deleting the app. To ask whether we hold information associated with a support interaction or TestFlight feedback, contact us using the method in Section 11.

Before Date-A-Base introduces accounts, cloud history, subscriptions, analytics, or server-managed notifications, this policy will be updated to describe the additional information, retention periods, and account-deletion process.

## 5. Disclosure of information

We may disclose information:

- to the service providers identified above as necessary to provide the Service;
- when required by law, legal process, or a valid governmental request;
- when reasonably necessary to investigate fraud, abuse, security incidents, or threats to safety; or
- as part of a merger, acquisition, financing, reorganization, or sale of assets, subject to appropriate notice and protections.

We do not share planning information with other Date-A-Base users unless you deliberately use your device's sharing features. Review shared content carefully because an itinerary can reveal where and when you intend to be somewhere.

## 6. Your choices

You can:

- use a manually entered city or neighborhood instead of device location;
- deny or revoke location permission in your device settings;
- avoid supplying optional dietary preferences;
- end an active date to remove its locally stored itinerary;
- choose not to open external venue or map links;
- stop using the Service and delete the app; and
- contact us about a privacy question or request.

## 7. Security

We use reasonable administrative and technical measures intended to protect information, including encrypted HTTPS transport and keeping AI-provider credentials on the server rather than in the mobile app. No method of transmission or storage is completely secure, and we cannot guarantee absolute security.

## 8. Children's privacy

Date-A-Base is intended for adults and is not directed to children under 18. We do not knowingly collect personal information from children. If you believe a child has provided personal information through the Service, contact us so we can investigate and take appropriate action.

## 9. United States operation and international transfers

The Service is operated from the United States. Information may be processed in the United States and other locations where our service providers operate. Privacy laws in those locations may differ from those in your jurisdiction.

Depending on where you live, you may have rights to request access to, correction of, or deletion of personal information, or to object to or restrict certain processing. These rights may be subject to exceptions. Contact us to submit a request. We may need to verify the request before responding.

## 10. Changes to this policy

We may update this Privacy Policy as the Service changes. We will post the revised policy and update the date above. If a change materially affects how we handle information, we will provide additional notice when reasonably appropriate.

## 11. Contact us

Questions or privacy requests may be sent to:

**Date-A-Base Privacy Contact**  
**Email:** smiley0418@gmail.com

The privacy contact email must be completed before this policy is published or submitted as the application's privacy-policy URL.
