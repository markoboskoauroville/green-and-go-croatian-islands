# HANDOVER — Green and Go Croatian Islands

Written 6.10.2026 by a Claude chat that did research only. Rewrite this file as the project moves, do not append a log to it.

---

## 0. The prompt for the next AI, in one paragraph

You are building a pitch website in Croatian for Baba (Marko Boško, Mantra Productions). He is pitching an idea to Svemir, the president of a Croatian NGO called GreenerGo. The idea is **Green and Go Croatian Islands**: renovated shipping containers, one per car-accessible Croatian island in the season, each one a charger, a storage space and an air-conditioned office from which electric scooters are rented and tracked. It is green and commercial at the same time, paid for by rental income, by scooter manufacturers who sponsor it to promote their brand, and by EU money for cutting CO2. Read this whole file, then `RESEARCH.md`, then `NANO_BANANA_PROMPTS.md`. Baba will upload images he generated with Nano Banana. Build the page with those images, in his voice, and do not invent facts about the NGO.

---

## 1. Who

**Baba.** Chosen name. Credited name Marko Boško. Video editor at Nova TV Zagreb, filmmaker, sound designer, DJ, beginner programmer, runs Mantra Productions. Croatian, deep ties to Ugljan (Kukljica). Dictates by voice, almost always on a phone. Low vision and dyslexia, so keep replies short and readable on a phone screen. Works in Croatian and English.

**Svemir.** The person the pitch is addressed to. Baba dictated the name as "Sven Mir" and "Sveimir", which is voice dictation of **Svemir**. Baba has a friend Svemir Vranko and writes to him in Croatian, informally, with "ti". It is very likely the same person. **Confirm with Baba before the name goes on the page.**

**GreenerGo.** The NGO (udruga). Baba said its information can be found on the internet. The research chat searched and **did not find it**: no website, no registry hit under "GreenerGo", "Greener Go" or "Svemir Vranko". See `RESEARCH.md` section 1. Ask Baba for the website, Instagram, OIB or exact registered name, or search the Registar udruga at registri.uprava.hr yourself. Until then, describe the NGO only in words Baba gives you.

---

## 2. The idea in Baba's own words

Dictated 6.10.2026, kept verbatim apart from obvious dictation splits. This is the source. Everything in section 3 is interpretation of it.

> "You're going now to pitch to Sven Mir, who is the president. You can start. Dear Sven Mir, I had a vision this morning for your Greener Go NGO. Everything in Croatian, normal style, speaking human. Read my manifest with styles, how to write."

> "Create a web page pitching this idea and give me a few prompts for Nano Banana. Then I will give you images to illustrate the idea. And the idea is to promote the electric transportation in Croatian islands."

> "And logistics looks like this. He is going to get few shipping containers and renew them, reorganize them to be a storage space and office for renting electric scooters on Croatian islands. And on each Croatian island which is accessible with the cars, meaning going with the ferry boat or going with the bridge, there will be one container with electric scooters in a season. And that container will rent electric scooters on Croatian Island."

> "We can call this project Croatian Island Green and Go, which is maybe name I find more interesting. Green and Go. So that will be the project name: Green and Go Croatian Islands."

> "So I'm going to send you a few images. You're going to tell me which prompts you need. Nano Banana, I will give you images and you're going to create a pitch website. This NGO, you can find its information on the internet."

> "So it's very simple. The truck is bringing this container somewhere where there is an electric plug and the scooters are charged. This container is a charger, is a storage space, is office space. It has also AC inside and people can work and rent and track people who rent the scooters to travel through Croatian islands."

> "And find, research internet in European Union, which company could sponsor this project. And it can be also sponsored by different manufacturers of electric scooters and being sponsored, and in that way they promote their own company. So it's kind of green and also it's commercial projects and also there can be donation from European Union for CO2 emission promotion. So let's run this project. Give the pitch to Svemir."

Then, in the same chat:

> "Please don't build anything now. Write a comprehensive prompt for another AI to build everything I just told you with all my words and your interpretation, and do only research. Create the repo with handover document, and I'm going to open another chat which is going to read handover document and going to read this repo called Green and Go Croatian Islands."

> "My GitHub token attached here needs to be treated as a secret. Mask its number, never send it anywhere. Just use it to create this repo."

---

## 3. Interpretation (mine, the research chat's, check with Baba where marked)

### The unit: one container
A used shipping container, renovated. It does four jobs at once: **charging station**, **storage** for the scooter fleet, **office**, and **air-conditioned workspace** for the person renting. A truck brings it to a spot with a grid connection. At the end of the season it can leave again. Plain, mobile, cheap infrastructure, which is the strength of the idea.

Sensible details to show on the page, all marked as proposals and not as decisions: a 20 ft or 40 ft container (ask Baba), solar panels on the roof as an extra, an awning or deck in front, a counter window for renting, racks and chargers inside, a sponsor panel on the outside walls.

### The network: one per island
One container per Croatian island **reachable by car**, either by bridge or by car ferry, during the tourist season. The truck rides the ferry or crosses the bridge. Islands with no car access are out of scope by Baba's own definition. `RESEARCH.md` section 4 has a starting list, to be verified.

### The vehicle: open question, ask Baba once
Croatian has two words. **Električni skuter** is a seated moped. **Električni romobil** is a standing kick scooter. For travelling across an island on open roads between villages, the seated e-moped is the realistic vehicle, and Croatian road rules restrict kick scooters on open roads. Baba said "electric scooters ... to travel through Croatian islands", so the working assumption is **e-mopeds (električni skuteri)**, with kick scooters as a possible second fleet for short trips in town. Ask him which, in one line, before writing the page copy.

### Tracking
"Track people who rent the scooters" means fleet GPS tracking and a rental log, run from the container office. On the page frame it as safety and fleet management. Mention once that it is done in line with GDPR, without making it a section.

### The money: three legs
1. **Commercial:** rental income in the season.
2. **Sponsors:** scooter manufacturers supply or discount fleets and get their brand on the containers and the scooters across the islands. Other partners possible, see `RESEARCH.md` section 3.
3. **Public money:** EU and Croatian funds for CO2 reduction and clean mobility, see `RESEARCH.md` section 2.

Baba's own summary of the spirit: green and commercial at the same time.

### The name
**Green and Go Croatian Islands.** Short form Green and Go. Keep the English name as the brand even though the page is in Croatian. Do not translate it into Croatian unless Baba asks.

---

## 4. What to build (only after Baba says go)

1. **A single pitch web page in Croatian**, addressed to Svemir, opening the way Baba opened: *Dragi Svemire, jutros sam imao viziju za tvoju udrugu GreenerGo.* (Confirm the name, see section 1.)
2. Sections, as plain prose blocks with Baba's images between them, roughly in this order: the vision, the container and what it does, the network across the islands, how a day works (truck, plug, charge, rent, ride), who pays and why it pays (rental, sponsors, EU), first steps, and a warm close that takes pressure off Svemir.
3. Images: Baba's Nano Banana images, uploaded to the next chat. Use them in the order of the prompts file. If an image is missing, leave a clean placeholder and say which prompt it was meant for.
4. Self-contained single HTML file, works on a phone first, large readable type (Baba has low vision), light and dark mode.
5. Delivery: two options, ask Baba once which. (a) Push the HTML into this repo and deploy the way his DJ Mantra page is deployed (GitHub repo plus Cloudflare Pages, like djmantra.pages.dev). (b) Publish as a claude.ai artifact link. Do not push anything public without his yes, this repo is private.
6. A short WhatsApp message to Svemir with the link, in Croatian, MARKO style.

---

## 5. Writing rules, from MANTRA_MANIFEST `modules/writing-styles.md`

The page is Baba writing to his friend, so it is in the **MARKO** style. Read the module itself in `markoboskoauroville/MANTRA_MANIFEST/modules/writing-styles.md` before writing. The short version:

No dashes of any kind in the prose. No emoji. No exclamation marks. No bullet points in the message or the letter part. No bold inside sentences. No "X, not Y" framing. No colon that sets up a reveal. No tidy three-part rhythms. Plain everyday Croatian words, "ti" form to Svemir. Say what he will do, then what he wants. Give the reason inside the sentence. Concrete things: the container, the truck, the plug, the ferry, the scooter. English is allowed where it is natural, like the name Green and Go. Short paragraphs. End by giving Svemir the exit and then restating what Baba actually wants.

Read every draft back for dashes before delivering it. This has failed before.

The check: would Baba say this out loud to Svemir? Is there a sentence doing nothing? Does it end by taking pressure off?

Section headings on a web page are fine. Inside the text, the rules above hold.

---

## 6. Design

The manifest design language is amber on near-black. For a green island project, a palette of sea blue, pine green and warm stone white fits better. Propose it to Baba in one line and let him reverse it in one word. Phone first, generous type size, high contrast.

---

## 7. Open questions for Baba (ask them together, short, at the start of the next chat)

1. Is "Sven Mir" Svemir Vranko, and is it "ti"?
2. GreenerGo: website, Instagram, OIB or exact registered name?
3. Seated e-mopeds, kick scooters, or both?
4. Container size, 20 ft or 40 ft, and how many in year one?
5. Delivery: Cloudflare Pages like djmantra, or a claude.ai artifact link?

---

## 8. What was NOT done or verified

Nothing was built. GreenerGo was not found online. The island list is from general knowledge and must be checked against current Jadrolinija car ferry lines and bridges. Croatian rules for e-mopeds and kick scooters on island roads were not checked against the current law. Sponsor companies in `RESEARCH.md` section 3 are candidates, none has been contacted or checked for a sponsorship programme.

---

## 9. Secrets

Follow `MANTRA_MANIFEST/modules/secrets.md`. The GitHub token arrives as an attached file in `/mnt/user-data/uploads/`. Extract it by shape into a vault (`/home/claude/.secret/gh_token`, folder chmod 700, file chmod 600). Never print the file, never print the token, never redact by pattern. Use it only through an Authorization header read from the vault. Never put it in a git remote URL, never in `.git/config`, never in any file in this repo. Before every push, scan the files for token shapes. If the uploads folder is empty, say the token is gone and ask Baba to attach it again.

---

## 10. Working rules

One chat, one subject. Update this file after each step, not at the end. Verify every push against the remote. Report with the link. Short replies, Baba is on a phone.
