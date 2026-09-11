# Sense Privacy Notice

**The practical version:** We ask for your email only when you ask to hear from us. We do not sell data, target ads, set cookies for tracking, load tracking scripts, or train shared models on your information. Running a website and delivering email still requires limited processing; this notice explains it rather than pretending no information ever moves.

## 1. Who is responsible and what this notice covers

Sense Inc. is responsible for the launch website and launch-update list. Contact [hello@sense.inc](mailto:hello@sense.inc) for access, correction, deletion, complaints, and privacy questions. The business mailing address is in section 11. This notice covers the teaser and its first-party signup service, not a claim that unreleased applications already use a particular architecture.

Before a new app, payment flow, managed account, or hosted AI feature collects additional information, Sense will publish a versioned feature-specific notice describing its actual processing. Accepting consumer terms or this notice is not blanket consent for future features. The durable restrictions in section 2 of the applicable Sense agreement apply throughout.

## 2. What the launch service processes

**Visiting the page:** the hosting system necessarily receives a network address, requested resource, and basic protocol information to deliver the page. The signup application does not keep page-view histories, analytics identifiers, request-body logs, access logs, or persistent browser identifiers. Sense disables provider analytics, access logging, session-affinity cookies, cookie-setting bot challenges, and automatic tracking integrations in this service. Necessary upstream network processing is not a claim of complete anonymity.

**Requesting updates:** we store the email address you enter, whether you affirmatively agreed to the displayed Consumer Terms and requested launch updates, the exact displayed document source commits/hashes and consent wording, request and confirmation times, and subscription status. The form does not request a name, employer, location, phone number, date of birth, or demographic information. An age checkbox confirms adulthood without collecting your birth date. Email-code confirmation also creates a Sense identity in Amazon Cognito, identified by its issuing pool and immutable subject identifier. This is intended to preserve your identity for possible later access through a Sense Theca cell. It does not enroll you in a paid service, grant product access, or accept a future product agreement for you. We do not add an address to the active mailing list until its owner confirms.

**Abuse prevention:** the service uses short-lived keyed hashes derived from the source network address and entered email to limit repeated submissions. These are pseudonymous personal information while retained, not anonymous analytics. They are not used to follow you between visits or services. Raw network addresses are not stored in the signup database. Confirmation and unsubscribe capabilities use cryptographic tokens; token values are credentials, not advertising identifiers.

**Delivery failures and spam complaints:** Amazon SES forwards permanent-bounce and complaint notifications through Amazon SNS to the signup service. It processes the affected address to create a keyed suppression hash, a failure/complaint reason, and a timestamp so it can stop requesting codes for that address. These events concern delivery safety, not whether you read a message or followed a link. The application does not store the raw notifications or record them in its logs, and it does not configure open or click events.

**Writing to us:** we receive what you include in a support or privacy message and the email routing information needed to reply. Avoid sending sensitive information that is not necessary. An operator's email system may retain that correspondence under the limits below; it must not use it for advertising or model training.

## 3. Why we use it

We use the submitted address and explicit confirmation to send requested Sense launch news and invitations, maintain accurate subscription choices, and stop messages when you withdraw. We use minimal consent records to show what you actually requested, and short-lived rate limits to reduce abuse. We use permanent-delivery-failure and spam-complaint suppression records to prevent further unwanted or undeliverable messages. We use correspondence to resolve your request and comply with applicable law. We do not combine these records into behavioral profiles, infer interests, score visitors, or use them as a training dataset.

Where a law requires a specified processing basis, requested launch marketing relies on your consent; proportionate security and recordkeeping rely on legitimate interests where that basis is available; legal duties rely on the relevant legal obligation. We must assess any additional local requirements before actively offering services in a new jurisdiction. This wording is not a claim that every international compliance step has been completed.

## 4. Who receives information

Sense personnel with a need to operate the list or answer a request may access limited records. The configured hosting/database environment and email delivery provider process information strictly to deliver the service, under purpose-limited obligations. The named providers, their functions, and processing regions are listed in section 11. An email provider receives an address and message content to deliver mail, not permission to profile recipients.

Sense will not sell, rent, license, exchange for value, or monetize information or derived information, including aggregated or de-identified information; it will not share information for cross-context behavioral advertising or allow service providers to use it for their own advertising or training. Narrow legally required disclosures and genuine business continuity transfers follow the restrictions in the applicable terms, including successor obligations and legally permitted notice. A subscriber list will not be sold as a standalone asset.

## 5. Cookies, tracking, and outside links

This site sets and reads no HTTP cookies, including essential/session cookies. It uses no analytics SDK, advertising code, third-party font request, embedded video service, tracking pixel, session replay, or fingerprinting. Theme selection exists only in page memory and resets with a new page; it is not stored in your browser. The signup does not use CAPTCHA vendors or social sign-in. We do not substitute local-storage identifiers for cookies.

We do not track activity across websites, so our practices already meet the no-sale/no-sharing/no-targeting outcome requested by Global Privacy Control or Do Not Track; enabling or disabling those signals does not cause us to begin tracking. We do not disclose cross-site browsing activity to other parties.

Legal pages request current canonical text through a first-party Sense endpoint. Sense's server resolves the configured repository's current `main` text and exact source commit; your browser does not contact GitHub merely to read the page. A GitHub source/history link, like any external link, opens only when you choose it; that independent service receives your connection and may have its own cookies and policies. We do not automatically embed GitHub, email-provider interfaces, or other outside sites. An independent destination is not a cookie exception for Sense's own pages.

## 6. Retention and deletion

Email-code requests are usable for at most 30 minutes. Codes and authentication challenges may expire sooner; resending does not extend the overall request window. Expired request data and pseudonymous rate-limit records are excluded from use immediately and removed by scheduled cleanup and database expiry controls. Physical deletion is asynchronous, not a promise that storage bytes disappear at the exact expiration second. Unconfirmed Cognito identities are queued for deletion after 7 days. Delivery-failure and complaint suppression hashes, reasons, and timestamps expire at most three years after the latest relevant notification. The original email address is not stored in those suppression entries; pseudonymization is not anonymization.

Active launch subscriptions, their exact consent records, and teaser-only confirmed identities are retained for at most 24 months after the latest independently confirmed signup. A confirmation-code request by itself cannot extend active consent. When you unsubscribe, launch messages stop immediately; a minimal account identity, your current preference, and the consent record remain for the remainder of that period so the preference can be honored and your identity preserved for possible future access. Unsubscribing is not account deletion. You can separately request account deletion through the contact in section 11. At expiry or account deletion, the teaser removes its account and consent information and can retain only a keyed email hash and suppression date for up to 3 years to prevent unwanted messages. A new, independently verified choice is necessary to resume messages.

A later Theca service may adopt a confirmed identity only after the applicable onboarding, notices, and agreement requirements have been completed. The adoption must be explicitly recorded; the teaser must not silently extend a signup's lifetime or treat email verification as acceptance of a new product. An adopted product identity is then governed by that service's disclosed retention rules, while launch-message preferences remain independently revocable. An operator retaining an AWS resource during deployment teardown does not extend these periods; stopping scheduled cleanup requires a replacement cleanup procedure or timely export and deletion.

The application does not keep request access logs, raw network addresses, email contents, or submitted codes in its logs. Short-lived keyed rate-limit identifiers are used only for security. Minimal runtime error logs expire after 7 days in the supplied deployment. Backups and raw delivery-event logging are not enabled by that deployment; any later backup or logging arrangement must be disclosed and given a limited retention before activation. Infrastructure providers still perform the processing needed to deliver and secure their services; provider-controlled operational records and their applicable retention must be reviewed before live collection. The browser keeps confirmation state only in memory.

Support and privacy correspondence is retained for up to 12 months after closure unless a documented legal obligation or genuine dispute requires a limited hold. Records subject to such a hold are isolated, limited to the relevant purpose, and deleted when the obligation ends. Sense must verify scheduled cleanup, provider settings, and restored-data suppression before live operation.

## 7. Your choices and rights

You can unsubscribe through a direct link in any update without logging in, answering questions, or paying. It takes effect immediately in the signup system. A message already handed off for delivery may still arrive; it does not reactivate your subscription. You can also contact [hello@sense.inc](mailto:hello@sense.inc) to request access, a portable copy, correction, deletion, restriction or objection where applicable, or to raise a concern. We offer access, correction, and deletion as a company policy even where a particular statutory threshold does not apply.

We acknowledge privacy requests within 10 business days and aim to complete them within 30 days, subject to a shorter legal deadline or a legally permitted extension explained to you. We verify requests proportionately, normally through the relevant email address; we do not routinely require government identification. Authorized representatives may act with appropriate proof of authority. We explain a refusal and available review or appeal; contact the same address for internal review. You may complain to the relevant privacy regulator or seek a remedy available under law, without retaliation.

California residents retain applicable rights to know, access, correct, delete, limit qualifying uses of sensitive information, opt out of covered sale/sharing, and avoid discriminatory treatment. Other jurisdictions may provide additional rights. We do not claim that the CCPA or every other privacy statute automatically applies to Sense; these voluntary protections do not reduce any law that does apply. We do not sell/share data or use sensitive information for targeted advertising, so no paid opt-out or data-sale setting is needed to obtain those outcomes.

## 8. Security and international processing

Access is restricted to authorized operators, and live traffic must use HTTPS. Confirmation and unsubscribe links are sensitive capabilities: do not share them. The static page is delivered from private Amazon S3 storage through CloudFront. The signup service uses Cognito for identity and code delivery, a narrowly scoped Lambda function reached through API Gateway, and an encrypted DynamoDB table for consent and preferences. Client secrets remain server-side; the browser receives no account access or refresh tokens. Account-continuity and recovery procedures must be verified before launch. There is no promise of zero risk.

Processing regions are listed in the published provider schedule. If international transfers require a particular safeguard, Sense must establish it before those transfers begin and explain how to obtain relevant information. We do not infer a lawful transfer mechanism from the fact that a provider offers one.

## 9. Children

The launch list is for adults aged 18 or older. We do not knowingly solicit children's information. Tell us if a child has submitted information so we can remove it. Future child-directed products require their own appropriate notices, consent, and safeguards before launch.

## 10. Public change history

The canonical `POLICY.md` on the official Sense privacy repository's `main` branch is the current published notice. Git history preserves prior text, and Sense records the exact source commit and document hash when consent is collected. Material changes receive direct advance notice to affected people, ordinarily at least 30 days, and new consent when required before a new optional purpose begins. A GitHub edit alone does not provide that notice or consent. The durable no-sale, no-targeting, no-cookie and no-shared-training commitments cannot be undone for existing data by a quiet update, a business sale, or an integration agreement.

## 11. Published provider and contact schedule

**Responsible company:** Sense Inc.
**Private contact:** [hello@sense.inc](mailto:hello@sense.inc).
**Business mailing address:** 3857 Birch St #198, Newport Beach, CA 92660.
**Hosting/database provider and role:** Amazon Web Services: S3 and CloudFront for the static site; API Gateway and Lambda for signup actions; Cognito for identity; DynamoDB for consent and preferences.
**Account/data region:** US-EAST-1. CloudFront is an edge-delivery service; it is not a claim that all network processing stays in that region.
**Email delivery provider and role:** Amazon SES, delivering requested verification codes through Cognito.
**Delivery-safety provider and role:** Amazon SNS, transporting permanent-bounce and complaint notifications from SES to the signup function in the deployment region; no open/click analytics.
**SES region and provider-controlled retention:** US-EAST-1.
**Backup and delivery-log retention:** No customer-configured backups or raw delivery-event logging in the supplied stack.
**Publication/effective dates:** 09/11/26.
**Canonical notice and history:** [sense-gh/privacy](https://github.com/sense-gh/privacy).
