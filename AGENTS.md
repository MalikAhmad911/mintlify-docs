# Revenue Sol documentation

Customer-facing help center for Revenue Sol, built on [Mintlify](https://mintlify.com). Pages are MDX with YAML frontmatter; configuration and navigation live in `docs.json`. Published at docs.revenuesol.com.

## Audience

Owners and staff of home-service and local service businesses (plumbing, HVAC, electrical, roofing, cleaning, landscaping and similar). Assume no technical background.

## Content boundaries

- **Never describe how Revenue Sol is built or run.** Don't name the database, hosting, authentication, search, analytics, monitoring, email or deployment providers behind the product, and don't mention servers, internal APIs or routes, database tables, environment variables, background jobs, or how security controls are implemented.
- **Do document the services customers connect themselves**, because they have to set them up: Twilio, RingCentral, Retell, Stripe, QuickBooks, Google, Meta (Facebook, Instagram, WhatsApp), SendGrid and Zapier.
- Document only what a customer can see and do in the app, using the exact labels shown in the interface.
- Prices, plan limits and which plan includes a feature must match the current plans: Starter $99/month (1 user), Professional $199/month (up to 4 users), Growth $399/month (up to 15 users), Enterprise custom. Annual billing is 35% less. Every self-serve plan has a 14-day trial; a card is required, and there's no charge if cancelled before day 14.
- Don't invent features, results, customer stories or statistics.

## Terminology

- "Revenue Sol" (two words, both capitalized).
- "workspace" for a customer's account, "contact" for a person in Contacts, "lead" for a contact in the sales pipeline.
- "AI Employee" for the AI that replies to customers; "AI receptionist" or "Voice Agent" for the AI that answers phone calls; "Autopilot" for automatic AI replies.

## SEO

- Every page has `title` (under 60 characters where possible), `description` (140–160 characters, says what the reader will learn), and `keywords`.
- Use descriptive headings that match how people search ("Connect a Twilio number"), and link to related pages.

## Style

- Active voice and second person ("you").
- Short sentences, one idea per sentence. Sentence case for headings.
- Bold for UI labels: click **Settings**.
- Use `<Steps>` for procedures, tables for comparisons, and `<Warning>` only for things that break if missed.
