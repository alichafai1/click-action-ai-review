# Web scraping compliance checklist

Use this before you run a Click Action AI mission that reads a website. The goal is to finish the task without breaking the site’s rules or trying to slip past a block.

Stated value of this file: $27. It is a bonus from Click Action AI Review, sent after a receipt is checked.

This is not a guide to bypass CAPTCHAs, rotate proxies, spoof a browser fingerprint, or hide who you are. If a site puts up a wall, you stop or you log in yourself.

## Before you write the prompt

- Name the business reason. A lead list for outreach you are allowed to send is different from collecting private data you do not need.
- Decide the fields in advance. Prefer business name, public phone, website, city, and a contact-page URL.
- Do not ask the agent for personal emails that are not published, home addresses, or anything behind a login you do not have rights to use.
- Cap the job. “50 plumbers in Austin” is a task. “Every business in the state” is how runs get sloppy and sites get hammered.

## Check the site

- Read the terms of use if the site has them. If automated collection is forbidden, do not point the mission at that site.
- Look at robots.txt. If the paths you need are disallowed for automated access, do not scrape them.
- Login walls, paywalls, and CAPTCHAs are a stop sign. Click Action AI should pause. You complete the check yourself only when you are allowed to be there, then you hand the browser back. You do not look for a way around the check.
- If the site says the data is licensed, private, or for logged-in customers only, leave it.

## While the mission runs

- Watch Live Watch. If the same page reloads, the agent is stuck, or the site shows a block page, pause and stop.
- Keep the pace of a person doing research, not a flood of requests. If you need a huge list, split it into smaller missions on another day.
- Do not submit forms, create accounts, or post content unless that action is the job and you are allowed to do it.
- Do not paste passwords into a prompt. Use pause and take over, type the password yourself, and continue only on accounts you own or are authorized to use.

## After you have the file

- Delete columns you do not need. Extra personal data is a liability, not a bonus.
- Do not present a scraped list as fresher or more complete than it is. Sites change, and emails go stale.
- If you will email the people on the list, follow the email rules that apply to you, including consent and unsubscribe requirements. A CSV is not permission to spam.
- Store the file where your team already keeps client data. Do not drop it in a public folder or a shared link with no access control.

## When you are blocked

A block, a CAPTCHA loop, or an error page means the site does not want this traffic. Stop the mission.

Do not:

- Retry the same URL in a tight loop
- Ask the agent to “get past” the check
- Switch identities, proxies, or browser fingerprints to look like someone else
- Create fake accounts to see a page you were refused

Do:

- Shrink the task or pick a source that allows the collection
- Finish that part by hand
- Note the site on a “do not automate” list so the next mission skips it

## A short yes/no before you hit run

Answer yes to all of these, or do not run it.

1. I can name the business reason for this list.
2. The fields are public business information, not private data I do not need.
3. The site’s terms and robots.txt do not forbid this collection.
4. The prompt has a limit, a place, and an export.
5. I will watch the run and stop if a login, CAPTCHA, or block appears.
6. I will not try to evade that block.
7. I know what I am allowed to do with the file after I download it.
