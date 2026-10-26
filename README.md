# SebastianEPalma.github.io

Developer website and `app-ads.txt` for my Android apps.

Live URLs:

- https://sebastianepalma.github.io/
- https://sebastianepalma.github.io/app-ads.txt

## AdMob publisher

```text
google.com, pub-5976547092526104, DIRECT, f08c47fec0942fa0
```

`app-ads.txt` authorizes the AdMob **publisher account**, not a single app. Every app in this AdMob account is covered by this one line.

## Adding orbit flash later

- If **orbit flash uses the same AdMob account** (`pub-5976547092526104`): no change is needed. The existing line already covers it.
- If **orbit flash uses a different AdMob account**: append its line below the current one:

```text
google.com, pub-XXXXXXXXXXXXXXXX, DIRECT, f08c47fec0942fa0
```

Keep the file at the repository root. Do not move it into a subfolder: AdMob looks for `https://sebastianepalma.github.io/app-ads.txt`.

## Play Console

Set the developer website in the store listing contact details to:

```text
https://sebastianepalma.github.io/
```

Then, in AdMob, open **Apps → app-ads.txt** and use **Check for updates**. Verification can take up to 24 hours.
