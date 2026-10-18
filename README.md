# RemoteCareerHub — free starter website

This is a single-file, responsive remote-jobs website prototype. It requests job listings from the public Himalayas Remote Jobs API in the visitor's browser and links visitors to the original application listing.

## Files
- `index.html` — complete website, styles, and JavaScript.
- `README.md` — this setup guide.

## Run locally
1. Extract the ZIP file.
2. Open `index.html` in a modern browser with an internet connection.
3. If live listings do not load from a local file, upload it to a web host and test there. Browser/API access can vary.

## API and attribution
- API docs: https://himalayas.app/docs/remote-jobs-api
- API endpoint used: `https://himalayas.app/jobs/api/search`
- The site visibly credits Himalayas and links back to `https://himalayas.app`, as required by the provider's published guidance.
- API listings refresh on the provider's schedule. This starter requests fresh results when a visitor opens the site; it does not create a separate daily database sync.
- API terms can change. Review them before launch and confirm your intended use is allowed.

## Important before public launch
1. Replace `hello@example.com` with a real contact address.
2. Add complete About, Privacy Policy, and Terms pages. The starter includes reminders/placeholders only.
3. Test live data, application links, mobile layout, and current API terms.
4. Do not imply that every job is available to every US resident. Read each listing's country/location restrictions.
5. Do not add AdSense until you have meaningful original content and comply with Google's policies.
6. This is a static front end. It has no employer login, job submission backend, admin dashboard, or server-side scheduled import.
7. Job listing API access can fail because of network, rate limits, CORS, or provider changes. The site shows a retry message if that happens.

## Zero-cost hosting
You can try a free static hosting provider. Check the host's current terms, especially if you plan to monetize the site or operate it as a commercial job board. A static host does not provide a database or backend by itself.
