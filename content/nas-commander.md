+++
title = "NAS Commander — Privacy Policy"
appName = "NAS Commander"
logo = "nas"
pageTitle = "Privacy Policy"
metaDescription = "Privacy policy for NAS Commander, an iOS app for administering Synology NAS devices. No analytics, no tracking, no servers."
tagline = "Synology NAS administration for iOS. No analytics, no tracking, no servers of ours — your data stays on your device and your NAS."
footerNote = "Synology NAS administration for iOS"
lastUpdated = "8 July 2026"

[[navLinks]]
  name = "Privacy Policy"
  url = "#privacy"

[[navLinks]]
  name = "Contact"
  url = "#contact"

[[navLinks]]
  name = "Silo - Work Photos"
  url = "/"
+++

<section id="privacy">
<h2>Privacy Policy</h2>
<p class="meta">Effective date: 8 July 2026</p>

<p>NAS Commander is developed and published by Justin Bloom ("we," "us"). This policy explains what information NAS Commander handles and — more importantly — what it does not.</p>

<p class="lede">The short version: we collect nothing. NAS Commander has no analytics, no tracking, no advertising, no third-party SDKs, and no servers of our own. Your data stays on your device and your NAS.</p>

<h3>Information we collect</h3>
<p>None. We do not collect, receive, store, sell, or share any personal information. We have no servers, no databases, and no analytics infrastructure. We cannot see your NAS, your credentials, your usage, or your identity.</p>

<h3>Information stored on your device</h3>
<p>NAS Commander stores the following only on your device, solely so the app can function:</p>
<ul>
<li><strong>Server profiles</strong> — display names, addresses, ports, and QuickConnect IDs you enter, stored in the app's local database.</li>
<li><strong>Credentials</strong> — your NAS username is stored locally; your password is stored exclusively in the iOS Keychain, Apple's encrypted credential store. Passwords never leave your device except to authenticate directly with your own NAS over an encrypted connection.</li>
<li><strong>Certificate pins</strong> — a cryptographic fingerprint (SHA-256) of your NAS's certificate, captured on first connection and used to protect later connections from tampering.</li>
<li><strong>Trusted-device tokens</strong> — issued by your NAS after two-factor authentication so you are not prompted for a code on every login.</li>
</ul>
<p>Deleting a server profile deletes its stored credentials and pins. Deleting the app deletes everything.</p>

<h3>Where your data goes</h3>
<p>NAS Commander communicates with exactly two parties:</p>
<ol>
<li><strong>Your own NAS.</strong> Credentials and management commands travel directly from your device to your NAS over HTTPS. We are never in the middle.</li>
<li><strong>Synology's QuickConnect service</strong> — only if you use a QuickConnect ID. To locate your NAS, the app sends your QuickConnect ID to Synology's resolution servers (for example, quickconnect.to), exactly as Synology's own applications do. If no direct route to your NAS is reachable, your connection may pass through Synology's relay infrastructure, encrypted end to end. This service is operated by Synology Inc. and governed by Synology's own privacy policy. If you connect only by direct address, no QuickConnect communication occurs at all.</li>
</ol>
<p>That is the complete list. The app contacts no other services, ever.</p>

<h3>Analytics and crash reports</h3>
<p>NAS Commander contains no analytics or crash-reporting frameworks. If you have opted in to sharing diagnostics with app developers in your iOS settings, Apple may provide us with anonymized crash reports through the standard App Store mechanism. These contain no personal information and no information about your NAS.</p>

<h3>Purchases</h3>
<p>Your purchase of NAS Commander is processed entirely by Apple through the App Store. We never see your payment information.</p>

<h3>Children's privacy</h3>
<p>NAS Commander is a utility for managing network hardware and is not directed at children. Since we collect no information from anyone, we collect no information from children.</p>

<h3>Changes to this policy</h3>
<p>If a future version of NAS Commander changes what information the app handles — for example, an optional push-notification service — this policy will be updated before that version ships, and the change will be described in the App Store release notes. The effective date above always reflects the current revision.</p>
</section>

<hr class="divider">

<section id="contact">
<h2>Contact</h2>

<div class="callout">
<p><strong>Questions about this policy or the app?</strong> Email <a href="mailto:blmjstn@proton.me">blmjstn@proton.me</a>. Please include your device model, iOS version, and DSM version so we can help faster.</p>
</div>

<p class="disclaimer">NAS Commander is an independent third-party application and is not affiliated with, endorsed by, or sponsored by Synology Inc. Synology, DiskStation, DSM, and QuickConnect are trademarks of Synology Inc.</p>
</section>
